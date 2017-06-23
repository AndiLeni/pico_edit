Pico edit - An admin interface for Pico CMS
===========================================

A small Back-end for Pico CMS.

Install
-------

1. Clone the Github repo into your 'plugins' directory (so you get a 'pico_edit' subdirectory) OR extract the zip into your 'plugins' directory (and rename the new directory to 'pico_edit')
2. Open the Pico config.php file and insert your sha1 hashed password
3. Visit http://www.yoursite.com/pico_edit and login

If pages editing doesn't work check file/dir permissions of 'content' folder.

About
-----

Pico Edit provides a back-end interface to edit Pico pages.

Features:

* Simple and clean interface, optimized for small screens like smartphones, tablets, etc.

* Page create/edit/delete

* Markdown preview

* Edit 404 page (aka "page not found")

* Edit Pico options

Options (Pico "config/config.php"):

	$config['pico_edit_404'] = true;
	$config['pico_edit_options'] = false;			// Disallow options editing
	$config['pico_edit_default_author'] = 'Me';		// Default author for new pages




Editing Pico options
--------------------

To override a string option simply write a line with: `theme = default`

To override a boolean option use: `my_option ! true`

Other types of options are not supported.


History
-------
* This version is a fork of [pico_edit](https://github.com/blocknotes/pico_edit). It contains several UI improvements and is mobile friendly.

* [pico_edit](https://github.com/blocknotes/pico_edit) is a fork + modifications of [Peeked](https://github.com/coofercat/peeked). It contains minor improvements and some new feature like ability to edit 404 page and Pico options.

* Peeked is a fork + modifications of the [Pico Editor](https://github.com/gilbitron/Pico-Editor-Plugin), written by [Gilbert Pellegrom](https://github.com/gilbitron). It contains a few bug fixes and some functional changes, most particularly the addition of some Git capabilities.
