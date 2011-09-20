# SCEditor v1.2.3
Copyright (C) 2011, Sam Clarke (http://www.samclarke.com)

For more invormation visit: http://www.samclarke.com/2011/07/sceditor/

If you find any bugs please let me know by either leaving a comment at
http://www.samclarke.com/2011/07/sceditor/ or contacting me at
http://www.samclarke.com/contact


# Usage

Include the JQuery and SCEditor JavaScript then you can simpley do:

	$(document).ready(function() {
		$("textarea").sceditor();
	});

or for BBCode WYSIWYG:

	$(document).ready(function() {
		$("textarea:last").sceditorBBCodePlugin();
	});



# Options

**toolbar** *string*
Comma seperated list of commans. Groups should be split by a bar (|) charecter

**style** *string*
Stylesheet to style the WYSIWYG document

**fonts** *string*
Comma seperated list of fonts

**colors** *string*
Comma seperated list of HEX colours. Use the bar charecter (|) to signify a new colum. If set to null a list of colours will be automatically generated

**emoticons** *map*
Map in the following format:

	emoticons:
	{
		dropdown:
		{
			":)": "emoticons/smile.png",
			":angel:": "emoticons/angel.png"
		},
		more: {
			":alien:": "emoticons/alien.png",
			":blink:": "emoticons/blink.png"
		}
	},

**width** *int*
Width of the editor in px. If set to null the width will be set to that of the textarea it is replacing.

**height** *int*
Height of the editor in px. If set to null the height will be set to that of the textarea it is replacing.

**resizeEnabled** *bool*
If to allow the editor to be resized. Defaults to true

**resizeMinWidth** *int*
Min resize to width in px. Set to null for half textarea width or -1 for unlimited.

**resizeMinHeight** *int*
Min resize to height in px. Set to null for half textarea height or -1 for unlimited.

**resizeMaxHeight** *int*
Max resize to height in px. Set to null for double textarea height or -1 for unlimited.

**resizeMaxWidth** *int*
Max resize to width in px. Set to null for double textarea width or -1 for unlimited.

**getHtmlHandler** *function*

**getTextHandler** *function*


# License

SCEditor is dual licensed under the MIT and GPL licenses:
http://www.opensource.org/licenses/mit-license.php
http://www.gnu.org/licenses/gpl.html

If you use SCEditor a link back would be nice but it's not requird.


# Donate

If you would like to make a donation you can via PayPal here:
https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=AVJSF5NEETYYG

# Credits

**Nomicons: The Full Monty Emoticons by:**
Oscar Gruno, aka Nominell v. 2.0 -> oscargruno@mac.com
Andy Fedosjeenko, aka Nightwolf -> bobo@animevanguard.com

**Icons by:**
Mark James (http://www.famfamfam.com/lab/icons/silk/)
Licensed under the Creative Commons CC-BY license (http://creativecommons.org/licenses/by/3.0/)
