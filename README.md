Swedish-bookmarklet
===================

A bookmark to point the user to a swedish dictionary for each word in a website.

How to use it ?
---------------

1. Create a new bookmark in your bookmarks toolbar.
2. Copy/paste the content of [the bookmarlet](https://raw.github.com/tpatel/Swedish-bookmarklet/master/swedish-bookmarklet.js) in the url field of your new bookmark.
3. Go to a swedish website, for example [KTH's website](https://www.kth.se/).
4. Clik on your bookmark, enjoy, and learn swedish !

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

<a href="https://twitter.com/thibpat" class="twitter-follow-button" data-show-count="false">Follow @thibpat</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src="//platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
