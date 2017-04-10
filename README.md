Lesson export
===========

This plugin adds the ability to export Moodle lessons as epub documents.
Many thanks to Davo Smith for developing the original base-code this plugin was ported from.

Usage
=====

Once the plugin is installed, you can visit a lesson, then click on the new 'Export as epub' link that appears
in the activity administration block (with javascript enabled, similar links are inserted on the top-right corner of the page).

Settings
========

There are many globally configurable options for exporting documents from a lesson including;

## Settings
- Strict mode - Throw exceptions on content errors
- Cover photo banner colour
- Custom CSS

Customising
===========

If you want to add your organisation's logo to the front page of the exported lesson, please replace the file
local/lessonexportepub/pix/logo.png with your logo. Do not alter the file dimensions, it must remain 514 by 182 pixels.

Customise the following language strings, to alter the embedded export information:
'printed' - set the description on the front page 'This doucment was downloaded on [date]'

(see https://docs.moodle.org/en/Language_customization for more details)

Disclaimer
=======

This repository has been modified, from the wikiexport plugin, with the sole intention of exporting Lesson modules. It is provided as-is and is open to pull
requests or issues. It was developed by Adam King for use at [SHEilds Health & Safety](http://sheilds.org/). Any development going forwards will be to abstract
the plugin to match many use-cases. There is a [pdfonly](https://github.com/adam-p-king/moodle_lessonexport_pdf/tree/pdfonly) branch for those who do not want
to use EPUB at all as PDF has standard protection implemented; using EPUB alongisde PDF would compromise that.
