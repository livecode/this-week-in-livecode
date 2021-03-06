---
layout: post
title:  "This Week In LiveCode 252"
date:   2021-01-25 15:30
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

- [Swipe gesture script on datagrid](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110647.html)
- [Grid and gridsize](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110684.html)
- [Call lc from php?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110694.html)
- [LC Community Ask Password](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110695.html)
- [How to find the offset of the first character in a string that's not a tab?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110700.html)
- [Fwd: xAPI in LiveCode (was Cmi5 eLearning Standard in LiveCode)](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110716.html)
- [lock screen](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110720.html)
- [Comments for Properties in the Property Inspector?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110746.html)
- [Test on android Simulator: app has stopped](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110753.html)
- [mobilePickPhoto Save the Photo](http://forums.livecode.com/viewtopic.php?t=35258&p=200566#p200566)
- [stdout on macOS 11.0.1 - working??](http://forums.livecode.com/viewtopic.php?t=35268&p=200635#p200635)
- [JDK Path: None](http://forums.livecode.com/viewtopic.php?t=35278&p=200708#p200708)
- [Parsing Word files](http://forums.livecode.com/viewtopic.php?t=35280&p=200722#p200722)
- [Override arrow action on DataGrid controls](http://forums.livecode.com/viewtopic.php?t=35288&p=200774#p200774)
- [Video "player" won't show video, but plays audio - Windows 10](http://forums.livecode.com/viewtopic.php?t=35289&p=200788#p200788)
- [Simultaneously updating fields](http://forums.livecode.com/viewtopic.php?t=35291&p=200807#p200807)

## Updates in the LiveCode open source project

2 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2021-01-18..2021-01-24&type=Issues).

<!--
### New LiveCode releases

- [Release 9.6.2 RC-2](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110561.html)
-->


### Notable changes

- [Add support for building apps against iOS 14.3 SDK](https://github.com/livecode/livecode/pull/7505)
- [Enable WebRTC on CEF browser](https://github.com/livecode/livecode/pull/7503)

<!--
### Bug of the week

- [Bug 23056 - tree view widget - array key doesn not exist error](https://quality.livecode.com/show_bug.cgi?id=23056)

The reporter provided a helpful sample stack that allowed us to test and confirm the problem quickly.
-->

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop-9.6` branch

Then try one of these:

- (Easy) [Docs: Paragraphs out of order in Description for split command](https://quality.livecode.com/show_bug.cgi?id=23071)
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

- *[livecodepanos](https://github.com/livecodepanos)*

## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [How to configure Self-Signed SSL certificates with tsNet?](http://forums.livecode.com/viewtopic.php?f=11&t=35274)

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
