# PocketProxy

This is my own edition of *[http://joshdick.github.io/miniProxy](http://joshdick.github.io/miniProxy)*, renamed to PocketProxy!

Demo it in live at *[https://zrr.us/pocketproxy.php](https://zrr.us/pocketproxy.php)*

Joshua Dick originally made miniProxy and dropped development, I now occasionally update it under the name PocketProxy.

*[http://joshdick.github.io/miniProxy](http://joshdick.github.io/miniProxy)*

*[https://andrewsalmon.github.io/PocketProxy/](https://dehlirious.github.io/PocketProxy/)*

---

## About PocketProxy

PocketProxy is a simple web proxy written in PHP that can allow you to bypass Internet content filters, or to browse the internet anonymously. 
PocketProxy is the successor to [MiniProxy](http://pageforward.sf.net).

## Prerequisites

PocketProxy should be able to run on any web server with PHP 5.4.7 or later. PocketProxy requires PHP's `curl`, `mbstring` and `xml` extensions to be installed.

## Installation and Use

Simply copy `pocketproxy.php` to your web server (it's okay to rename it) and access it directly. That's it! You'll be presented with further usage instructions.

PocketProxy doesn't require any configuration out of the box, but configuration options are available; see the top of `pocketproxy.php` for details.

## Known Limitations

PocketProxy has several known limitations. Some of them may be fixed in future releases. For now, they include:

* `<object>` tags are not handled
* No cookie support
* Basic AJAX support, but only for browsers that use `XMLHttpRequest`

## Contact and Feedback

If you'd like to contribute to PocketProxy or file a bug or feature request, please visit [its GitHub page]

