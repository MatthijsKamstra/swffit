# Introduction #

This page is used to keep track of ideas for future features and optimizations. Some stuff may already been done and some may never be done... So **don't take it too serious...**

View the [change\_log](change_log.md) to see if the feature that you want wasn't already released on a previous version of swffit.

## Todo ##
  * **improve the documentation:** split documentation, about and examples into different pages.
  * remove closures and listeners on `onunload` on IE to avoid memory leaks.
  * change way swffit sets the minimum/maximum size to a full CSS based method to improve performance but keeping current method for browsers that doesn't support `min-width`/`max-width`. _(under development)_
  * only enable swffit if flash movie was embedded to avoid alternate content being displayed on the wrong position as described on [this e-mail thread](http://groups.google.com/group/swffit/browse_thread/thread/6ce037dfcb1e1ff2).
  * use YUI compressor to generate deploy file with munging option enabled (obfuscate local variables).
  * optimize source code. _(constantly under development)_

## Maybe ##

  * add fix for flash movie files bigger than 4000px as described on [this e-mail thread](http://groups.google.com/group/swffit/browse_thread/thread/d493f159a009689/).
  * make swffit work without [swfobject](http://code.google.com/p/swfobject/).

## Will be released on future versions ##

  * add public methods to return window `innerHeight` and `innerWidth`. _(v3.0)_
  * change `addEventListener` structure and add `window.scroll` Event. _(v3.0)_
  * change swffit private vars names to something more readable (ex: `_minWid` instead of `_mw`) making it easier to other people edit the source code. _(v3.0)_

## Contribute/Fork ##

If you want to contribute with swffit development or create your custom version just fork/branch/clone the swffit GIT repository: http://github.com/millermedeiros/swffit