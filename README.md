# Telekinesis-meta
This is a metapackage pulling down *ALL* components of Telekinesis, excluding voice translations.

Those are in Telekinesis-sample-voices which can be fetched with 'make download'

You should probably down this, chose your language in config.mk LANG

Then run:
	make download


If successfully download all needed things, install dependencies:
	make dep


If success, install
	make install

Set up appropriate startup script (rc.local or whatever) and enjoy!
