FontAwesome-for-iOS
===================

FontAwesome fixed to have correct (at least much better) vertical alignment in iOS UILabel

In iOS the UILabel's vertical alignment tends to work well only for the built-in fonts.
As soon as you use a custom font, it will most likely not be rendered centered on the label.
The same applies to all kinds of UIControls etc. that have UILabel as a part of them (UIButton e.g.).

The solution is given by Andy Yardley in an article here: dyyardley.com/2012/04/24/custom-ios-fonts-and-how-to-fix-the-vertical-position-problem/

Basically, the fonts have values for "ascender" and "descender" that are not working out nicely for iOS's rendering.

I followed his instructions and pinpointed some values (probably not _the_ best, but sufficiently good) to achieve a font file that lets iOS render the UILabel correctly vertically aligned. Yay!

<img src="https://github.com/leberwurstsaft/FontAwesome-for-iOS/blob/master/before_after.png?raw=true">

Thanks to Dave @ twitter for FontAwesome!

##FontAwesome License
Version 2.0 of the Font Awesome font, CSS, and LESS files are licensed under CC BY 3.0:
http://creativecommons.org/licenses/by/3.0/
A mention of 'Font Awesome - http://fortawesome.github.com/Font-Awesome'
in human-readable source code is considered acceptable attribution (most common on the
web). If human readable source code is not available to the end user, a mention in an 'About' 
or 'Credits' screen is considered acceptable (most common in desktop or mobile software).