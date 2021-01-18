---
layout: post
title:  "This Week In LiveCode 251"
date:   2021-01-18 15:30
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

<!--
### News & blog posts

- [October only: Get a Hacktoberfest t-shirt by contributing to LiveCode](https://hacktoberfest.digitalocean.com): Submit 4 pull requests and get a free Hacktoberfest T-shirt!
-->

### Interesting discussions

- [Bug 22999 - iOS location updates not received in the background](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110503.html)
- [Building a Standalone MacOS App in 9.6.1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110508.html)
- [POST does not work under lock messages](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110527.html)
- [POST data size bug](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110544.html)
- [disabling a group](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110573.html)
- [opened socket in IDE prevents script changes](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110594.html)
- [mobileControlCreate (set, do, etc)](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110609.html)
- [Printing borked for LC Linux?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110614.html)
- [Is there a way to manually trigger GC?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110615.html)
- [No matter the Launch image, I get 320x480](http://forums.livecode.com/viewtopic.php?t=35250&p=200458#p200458)

## Updates in the LiveCode open source project

6 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2021-01-04..2021-01-17&type=Issues).


### New LiveCode releases

- [Release 9.6.2 RC-2](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110561.html)



### Notable changes

- [Fix frozen color picker launched from modal stack on macOS](https://github.com/livecode/livecode/pull/7501)
- [Update SQLite to v3.34.0](https://github.com/livecode/livecode-thirdparty/pull/152)
- [Fix emscripten crash when loading custom TTF font files](https://github.com/livecode/livecode/pull/7488)


### Bug of the week

- [Bug 23056 - tree view widget - array key doesn not exist error](https://quality.livecode.com/show_bug.cgi?id=23056)

The reporter provided a helpful sample stack that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop-9.6` branch

Then try one of these:

- (Easy) [Docs: Mention the behavior of 'the screenrect' on iOS if "Display Zoom" is checked](https://quality.livecode.com/show_bug.cgi?id=22949)
- (Easy) [Docs: Mention that matchText/matchChunk/replaceText all operate as if form-sensitive were true](https://quality.livecode.com/show_bug.cgi?id=15311)
- (Easy) [Dictionary: more examples for IF entry in Dictionary](https://quality.livecode.com/show_bug.cgi?id=22589)
- (Easy) [Dictionary: incorrect description of resizeControl message](https://quality.livecode.com/show_bug.cgi?id=17118)
- (Easy) [Docs: Update the dict entry of the "propertynames"](https://quality.livecode.com/show_bug.cgi?id=7375)
- (Medium) [Make the scrollbars for a treeview widget a TAD wider](https://quality.livecode.com/show_bug.cgi?id=23000)
- (Medium) [Add support for unblocking http requests on Android 9+](http://quality.livecode.com/show_bug.cgi?id=22400)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Applescript "do script" missing from standalone](http://quality.livecode.com/show_bug.cgi?id=20993)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Medium) [Relayer control crashes livecode](https://quality.livecode.com/show_bug.cgi?id=21460)
- (Medium) [Datagrid not protected for drag and drop in project view (labels can get inserted into the DGgrp itself)](https://quality.livecode.com/show_bug.cgi?id=21750)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)
- (Hard) [Case insensitive matchText returns incorrect result](https://quality.livecode.com/show_bug.cgi?id=15312)


### Contributors this week

- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*

## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [New entry added to 1001 things to do with LiveCode - EchidnaCSI](http://forums.livecode.com/viewtopic.php?t=35232&p=200354#p200354)

<!---
## Upcoming events

* [SoCal LiveCode Group Meeting: March 5, Pasadena](https://forums.livecode.com/viewtopic.php?f=50&t=33729)
--->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
