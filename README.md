# Telekinesis-meta
This is a metapackage pulling down *ALL* components of Telekinesis, excluding voice translations.

Those are in Telekinesis-sample-voices which can be fetched with:
- make download

You should probably use this this:
- git clone --recurse-submodules  https://github.com/PripyatAutomations/Telekinesis-meta

But If you forgot --recurse-submodules:
- git submodule init; git submodule pull

Then chose your language,etc in config.mk LANG:
- joe config.mk

Either build your voices (requires AWS or google cloud account):
 make voices
*OR*
- make fetch-voices

If successfully download all needed things, install dependencies:
- make dep


If success, install
- make install

Set up appropriate startup script (rc.local or whatever) and enjoy!


Expect bugs as this is an early public release of the mess i use internally ;)
I'll try to test things as best as possible on other machines, but please do
report all bugs/suggestions/feature requests via github or IRC!

 ~ rustyaxe 
