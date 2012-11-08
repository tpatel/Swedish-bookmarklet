Swedish-bookmarklet
===================

A bookmark to point the user to a swedish dictionary for each word in a website.

How to use it ?
---------------

1. Drap and drop [this link](https://raw.github.com/tpatel/Swedish-bookmarklet/master/swedish-bookmarklet.js) in your bookmarks toolbar.
2. Go to a swedish website, for example [KTH's website](https://www.kth.se/).
3. Clik on your bookmark, and enjoy !

Description
-----------

The bookmarklet is doing the following actions :
* Looks for the content of tags `<p>`.
* Stripes the html tags.
* Extracts each word.
* Remplaces the word by a link on [The People's Dictionary](http://folkets-lexikon.csc.kth.se/folkets/folkets.en.html) (we lowercase the word before contructing the link as the dictionary used accepts only lowercase words).

Used
----
* [The People's Dictionary](http://folkets-lexikon.csc.kth.se/folkets/folkets.en.html)
* [Vanilla-js](http://vanilla-js.com/)

By [@thibpat](https://twitter.com/thibpat)
