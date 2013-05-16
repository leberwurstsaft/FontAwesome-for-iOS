FontAwesome-for-iOS
===================

**Now Updated to FontAwesome ~~3.0~~ 3.1.1** (see differences and all new icons at http://htmlpreview.github.com/?https://github.com/leberwurstsaft/BButton/blob/master/FontAwesomeIcons.html)

FontAwesome fixed to have correct (at least much better) vertical alignment in iOS UILabel

In iOS the UILabel's vertical alignment tends to work well only for the built-in fonts.
As soon as you use a custom font, it will most likely not be rendered centered on the label.
The same applies to all kinds of UIControls etc. that have UILabel as a part of them (UIButton e.g.).

The solution is given by Andy Yardley in an article here: http://www.andyyardley.com/2012/04/24/custom-ios-fonts-and-how-to-fix-the-vertical-position-problem/

Basically, the fonts have values for "ascender" and "descender" that are not working out nicely for iOS's rendering.

I followed his instructions and pinpointed some values (probably not _the_ best, but sufficiently good) to achieve a font file that lets iOS render the UILabel correctly vertically aligned. Yay!

<img src="https://github.com/leberwurstsaft/FontAwesome-for-iOS/blob/master/before_after.png?raw=true">

Thanks you for FontAwesome, Dave!

##Used in these projects##
https://github.com/mattlawer/BButton

https://github.com/alexdrone/ios-fontawesome


##FontAwesome License
The Font Awesome font is licensed under the SIL OFL 1.1:
http://scripts.sil.org/OFL

Attribution is no longer required as of Font Awesome 3.0, but much appreciated:

Font Awesome by Dave Gandy - http://fontawesome.io
