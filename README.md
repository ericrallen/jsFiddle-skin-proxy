jsFiddle-skin-proxy
===================

Forked from [@Naatan](https://github.com/Naatan/)'s [jsFiddle-skin-proxy](https://github.com/Naatan/jsFiddle-skin-proxy) code that allows custom skins to be attached to embedded JSFiddles.

![Example of multiple skins](http://dl.dropbox.com/u/10476852/jsFiddle-skin-proxy.png)

(note: the link in the image above is inserted by part of a Wordpress plug-in and is not included in this script)

Changes in this version:
========================

* Allows for multiple skins (chosen skin is passed through a get variable)
* Allows for custom skin directory to be selected (chosen directory is also passed through a get variable)
* Allows for skin-specific JavaScript to be included in a skin folder

Reason for this version:
========================

I forked and updated this script for use in my [jsfiddle-plugin](https://github.com/ericrallen/jsfiddle-plugin) Wordpress Plug-in.

Use
===

You can use it like this:

	<iframe src="http://hostname/jsFiddle-skin-proxy/?id=9jHcF&skindir=http://hostname/fiddle-skins/&skin=dark&tabs=js,resources,result" allowfullscreen="allowfullscreen" frameborder="0"></iframe>

misc.
=====

The original readme was a .textile file and I prefer markdown, so I've switched it and included it below. The full original readme can be found in the file [orig.readme.textile](https://github.com/ericrallen/jsFiddle-skin-proxy/blob/master/orig.readme.textile)

![Original Example](http://f.cl.ly/items/272n0M0x3p301U41311v/jsfiddle-skin.png)

Just threw this together quickly so that I can style jsfiddle embeds on my website (the default doesn't go well with dark websites).

To use, simply call:

	http://hostname/jsFiddle-skin-proxy/?id=mfKZF

To use an updated version of the jsfiddle simply add it to the id:

	http://hostname/jsFiddle-skin-proxy/?id=mfKZF/5

I make no guarantees for this script. I just threw it together quickly so that I can use embeds on my site properly. Hopefully jsFiddle will support custom css natively in the future.. or at least provide some more varied skins.