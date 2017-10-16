---
layout: post
title:  "This Week In LiveCode 102"
date:   2017-10-16 14:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

<!---
### News & blog posts

- [Testing 1, 2, 28534](https://livecode.com/testing-1-2-28534/): A very interesting blog post by @livecodeali, describing all the different sorts of tests we run.
--->


### Interesting discussions

- [Creeping IDE Script Editor window position](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89989.html)
- [OAuth2 Status?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89994.html)
- [Dropbox library (LC 9) - does dropboxGetCurrentAccount work?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90007.html)
- [Handy behavior snippet](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90025.html)
- [controlNames??](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90029.html)
- [Dropbox library in LC 9 - centralise the access token?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90041.html)
- [Atkinson dither algorithm & 'for each' loop](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90065.html)
- [Microsoft 365 Rest API](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90068.html)
- [Query Input Form](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90079.html)
- [Repeat For Each Iteration Order](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90083.html)
- [libURLLast/xx/headers on mobile?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90097.html)
- ['manual' Copy and paste of multiple objects to new card ungroups	grouped objects](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90099.html)
- [DG2 Question](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90119.html)
- [is a date](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90126.html)
- [Rotating Widgets](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90129.html)
- [Send "rawKeyUp"](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90141.html)
- [In GRAB control](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90149.html)
- [Community widget #53](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90159.html)
- [Tiny Dictionary and Plug-ins Folder in LC 8.1.6 for Linux Ubuntu 16.04](http://forums.livecode.com/viewtopic.php?t=29987&p=159195#p159195)


## Updates in the LiveCode open source project

29 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-10-09..2017-10-15&type=Issues).


### New LiveCode releases

- [LiveCode 8.2.0 DP-2](https://downloads.livecode.com/livecode/#8_2_0)


### Notable changes

- [Don't apply color to SkPaint when using a gradient or pattern](https://github.com/livecode/livecode/pull/6054): A LC 9 regression is now fixed.
- [Map ISOSection key code to appropriate XK code](https://github.com/livecode/livecode/pull/6052): This fixes a regression bug affecting specific keyboard layouts
- [Fix incorrect java binding string parsing](https://github.com/livecode/livecode/pull/6047)
- [Segmented control posts hiliteChanged when created](https://github.com/livecode/livecode/pull/6044): Thanks @Brian Milby
- [Set correct input type for passwords](https://github.com/livecode/livecode/pull/6039)
- [Ensure Y is respected in 'read from socket X for Y'](https://github.com/livecode/livecode/pull/6033): A previous "Bug of the week" is now fixed
- [Native scrollers on DataGrid](https://github.com/livecode/livecode-ide/pull/1779)
- [Put all docs of a particular type together in API](https://github.com/livecode/livecode/pull/6014)
- Lots of fixes (regarding invalid links, malformed text) in various dictionary entries in LiveCode 8.2.x. Thanks @livecodesam :)

### Bug of the week

- [Bug 20534 - LC9dp9 - Segmented Control doesn't work with LC8](http://quality.livecode.com/show_bug.cgi?id=20534)

The reporter attached a simple and helpful sample stack, and provided useful info and a detailed recipe that helped us to test, confirm and fix the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [MouseEnter / MouseLeave infinite Loop trap - documentation enhancement](http://quality.livecode.com/show_bug.cgi?id=20529)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Easy) [Info missing from mobileGetContactData entry](http://quality.livecode.com/show_bug.cgi?id=20359)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [LC8 Dictionary Copy **using cmd+C** only works after Run Tool selected](http://quality.livecode.com/show_bug.cgi?id=17819)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*

<!---
## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [the dreaded "cannot connect to iTunes" - inapp purchase problem](http://forums.livecode.com/viewtopic.php?f=49&t=29923)
--->

## Upcoming events

* [LiveCode Global: Our Next Conference in Your City](https://livecode.com/livecode-global-our-next-conference-in-your-city/): 48 hours of Conference content streamed live around the globe! Save the dates:

- 19th of October 2017
- 16th of November 2017

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
