# Introduction #

When the number of entries in the What's New section on the main home page gets too long, copy the older ones here and delete them from the main home page.

### October 12th, 2009: New Release ###

Yowsers! It's another release of SVG Web, this time code named Beholder:

![http://codinginparadise.org/images/beholder.jpg](http://codinginparadise.org/images/beholder.jpg)

According to the classic D&D Monster Manual, the Beholder is an "aggressive and avaricious spherical monster that is most frequently found underground." In other words, you don't want to bump into this guy in a back alley.

This release, roughly about 1 month of work, has contributions from many users and developers. We've knocked out a bunch of bugs and features. The full release list:

  * [Issue 327](https://code.google.com/p/svgweb/issues/detail?id=327) : Patching currentTranslate in causes error in Wikipedia Pan and Zoom tool
  * [Issue 326](https://code.google.com/p/svgweb/issues/detail?id=326) : Update config.html tool to test for SVG MIME type
  * [Issue 316](https://code.google.com/p/svgweb/issues/detail?id=316) : Background SVG is not being re-drawn on secondary pages for some browsers
  * [Issue 307](https://code.google.com/p/svgweb/issues/detail?id=307) : Window resize handler can sometimes throw exceptions on IE if Flash not ready
  * [Issue 308](https://code.google.com/p/svgweb/issues/detail?id=308) : Implement currentTranslate and currentScale and have it be a fast path
  * [Issue 312](https://code.google.com/p/svgweb/issues/detail?id=312) : For Shelley Powers: Odd error when using within XHTML document: works with Firefox, does not work with any other browser
  * [Issue 176](https://code.google.com/p/svgweb/issues/detail?id=176): Document Makefile dependencies
  * [Issue 233](https://code.google.com/p/svgweb/issues/detail?id=233) : (regression) inconsistent size, spacing, flow of rendering
  * [Issue 304](https://code.google.com/p/svgweb/issues/detail?id=304) : tspan-tag ignore s coordinates of upper text-tag
  * [Issue 305](https://code.google.com/p/svgweb/issues/detail?id=305) : Changing shapes and paths from 'hidden' to 'visible' does not work.
  * [Issue 306](https://code.google.com/p/svgweb/issues/detail?id=306) : Regression in test\_js1.html: Text that should be hidden is not
  * [Issue 311](https://code.google.com/p/svgweb/issues/detail?id=311) : Summation of transform causes shaking and invalid transformations.
  * [Issue 254](https://code.google.com/p/svgweb/issues/detail?id=254) : Lamb Animation Sample Doesn't Look Correct
  * [Issue 315](https://code.google.com/p/svgweb/issues/detail?id=315) : Reduce the number of Sprites created per Node to increase performance
  * [Issue 321](https://code.google.com/p/svgweb/issues/detail?id=321): Support for animating path "d" attribute (except interpolation)
  * [Issue 325](https://code.google.com/p/svgweb/issues/detail?id=325) : Support data: URL scheme for object tag
  * [Issue 329](https://code.google.com/p/svgweb/issues/detail?id=329) : in flash renderer, images get cropped if they are moved programmatically
  * [Issue 330](https://code.google.com/p/svgweb/issues/detail?id=330) : in flash renderer, fill with image pattern does not work (programmatically)
  * [Issue 293](https://code.google.com/p/svgweb/issues/detail?id=293) : Position of image differs in native vs flash
  * [Issue 207](https://code.google.com/p/svgweb/issues/detail?id=207) : Doing transform on image dynamically throws exception
  * [Issue 343](https://code.google.com/p/svgweb/issues/detail?id=343) : Support on`*` events in SVG "use" element.
  * [Issue 344](https://code.google.com/p/svgweb/issues/detail?id=344) : Cache image requests for same file

[Download the new release](http://svgweb.googlecode.com/files/svgweb-2009-10-12-Beholder.zip) and [read the Quick Start guide](http://codinginparadise.org/projects/svgweb/docs/QuickStart.html).

### September 16th, 2009: New Release! ###

Hear ye! Hear ye! The SVG Web team has pushed out another [release](http://svgweb.googlecode.com/files/svgweb-2009-09-16-Umberhulk-B.zip), code named Umber Hulk.

[Umber Hulk](http://codinginparadise.org/monsters/umberhulk.jpg): "_A human-shaped creature with gaping maws flanked by pairs of exceedingly sharp mandibles. Despite their bestial appearance, umber hulks possess a significant intelligence and language of their own._"

Notable highlights of this release:

  * Having Chinese characters in SVG filenames now works
  * getCTM, currentScale, and currentTranslate are now supported, making dragging easier
  * Inline on`*` style events (onclick, etc.) handlers directly in markup is now supported for SVG OBJECTs
  * Several fixes for IE 8
  * Several fixes when the DOCTYPE is specified
  * Lots of fixes around resizing an SVG image based on resizing the browser and it's container
  * Fixes to help Shelley Power's Burning Bird site
  * Fixes to help the Wikipedia SVG Zoom and Pan too
  * Fixes to help Michael Neutzes' German Atlas work
  * Fixes to help other developers in the community

and much much more. Special thanks to the many people who helped with this one:

  * Rick Masters
  * Jeff Schiller
  * Michael Neutze
  * Shelley Powers
  * Ciaranj
  * Felix Buenemann
  * Le Roux Bernard
  * Glen Bremner Stokes
  * Bradbury.e
  * Richbk
  * Fangqq

Please keep in mind SVG Web is still in alpha.

[Read the full release notes](http://code.google.com/p/svgweb/wiki/ReleaseNotes#svgweb-2009-09-16-Umberhulk-B.zip_(_)) or [download the release](http://svgweb.googlecode.com/files/svgweb-2009-09-16-Umberhulk-B.zip).

### September 9th, 2009: New Release! ###

Hi everyone, the SVG Web team has another release packed with lots of goodness.

Starting now we are giving releases not only a date stamp but also simple names, taken from the classic [Fiend Folio](http://en.wikipedia.org/wiki/Fiend_Folio) D&D monster manual. Why? Because the world needs more cheesy release names.

Notable highlights of the svgweb-2009-09-09 release, also known as the [Owlbear](http://codinginparadise.org/monsters/owlbear.jpg) release ("Terrifying: the body of a bear... the head of an owl"):
  * View source - You can now right click on an Flash SVG image and view the SVG source
  * Huge improvements to the resizing code - the size of SVG objects on the page now change based on the zoom factor, resizing the window, etc.
  * Performance improvements
  * The demo.html file is much more robust now
  * getScreenCTM, matrix inversions, createSVGPoint, and SVGPoint.matrixTransform are now implemented
  * The internal JavaScript architecture has been cleaned up and simplified for Internet Explorer

Learn more:
  * [Full release note details](http://code.google.com/p/svgweb/wiki/ReleaseNotes#svgweb-2009-09-09-Owlbear.zip_(_))
  * [svgweb-2009-09-09-Owlbear.zip Download](http://svgweb.googlecode.com/files/svgweb-2009-09-09-Owlbear.zip)


---


### **August 20th, 2009: New Release!** ###
[svgweb-2009-08-20.zip](http://svgweb.googlecode.com/files/svgweb-2009-08-20-B.zip) - Another release with performance improvements and important bug fixes. The [DocumentFragment](http://codinginparadise.org/projects/svgweb/docs/QuickStart.html#document_fragment) API is now implemented; page load time is faster; important bug fixes for path and entity handling are present; and several page onload bugs have been knocked out. See the [full Release Notes](http://code.google.com/p/svgweb/wiki/ReleaseNotes#svgweb-2009-08-20.zip_(_)) for this release for details.


---


### **August 11th, 2009: New Release!** ###
[svgweb-2009-08-11-C.zip](http://svgweb.googlecode.com/files/svgweb-2009-08-11-C.zip) - The focus of this release is performance and bug fixes. [suspendRedraw is now implemented](http://codinginparadise.org/projects/svgweb/docs/QuickStart.html#tip_suspendRedraw), Flash/JS communication is faster, and there are some great bug fixes on the Flash side mostly related to event handling. See the [full Release Notes](http://code.google.com/p/svgweb/wiki/ReleaseNotes#svgweb-2009-08-11.zip_(_)) for details.


---


### **July 28th, 2009: New Release!** ###
[svgweb-2009-07-28.zip](http://svgweb.googlecode.com/files/svgweb-2009-07-28.zip) - Big changes include a new [Quick Start guide](http://codinginparadise.org/projects/svgweb/docs/QuickStart.html) to get going fast; [a small embedded web server](http://code.google.com/p/svgweb/issues/detail?id=159) (Jetty) to make development easier; [simple utilities](http://code.google.com/p/svgweb/issues/detail?id=157) for setting the MIME types necessary for SVG Web if you don't have admin access; a [config.html utility](http://code.google.com/p/svgweb/issues/detail?id=174) to make QAing installation issues easier; and lots of bug fixes (16 issues closed)! See the [full Release Notes](http://code.google.com/p/svgweb/wiki/ReleaseNotes#svgweb-2009-07-28.zip_(_)) for this release for details. [Download](http://svgweb.googlecode.com/files/svgweb-2009-07-28.zip) it now. Please keep in mind SVG Web is still in alpha, so expect to help us by [filing bugs](http://code.google.com/p/svgweb/issues/list) :)