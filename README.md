Swedish-bookmarklet
===================

A bookmark to point the user to a swedish dictionary for each word in a website.

How to use it ?
---------------

* Create a new boomark on your toolbar
* Copy/Paste the content of [the bookmarklet](https://github.com/tpatel/Swedish-bookmarklet/blob/master/swedish-bookmarklet.js) in the url of your new bookmark
* Go to a swedish website, for example [KTH's website](https://www.kth.se/)
* Clik on your bookmark, and enjoy !

Description
-----------

The bookmarklet is doing the following actions :
* Look the content of tags `<p>`
* Stripe the html tags
* Extract each word
* Remplace the work by a link on [The People's Dictionary](http://folkets-lexikon.csc.kth.se/folkets/folkets.en.html) (we lowercase the word before contructing the link as the dictionary used accept only lowercase words)

Used
----
[The People's Dictionary](http://folkets-lexikon.csc.kth.se/folkets/folkets.en.html)
[Vanilla-js](http://vanilla-js.com/)

By [@thibpat](https://twitter.com/thibpat)
