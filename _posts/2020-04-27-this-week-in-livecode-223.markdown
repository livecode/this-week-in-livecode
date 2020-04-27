---
layout: post
title:  "This Week In LiveCode 223"
date:   2020-04-27 15:30
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

- [Fence Painting or Coding Challenges?](https://livecode.com/fence-painting-or-coding-challenges/#comments)
--->

### Interesting discussions

- [Stack Files](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107549.html)
- [HTTPHeaders](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107556.html)
- [Scrollbar scale value not showing in Windows](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107583.html)
- [Which git service suits a LiveCoder best?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107585.html)
- [Mobile text input mystery](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107589.html)
- [Testing spell checking with Hunspell Extension](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107598.html)
- [Native Switch Button?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107600.html)
- [Widget Properties](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107614.html)
- [Detecting full Mobile Sensor activation](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107637.html)
- [What is a real?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107641.html)
- [Wildcard? replaceText, offset?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107675.html)
- [Three very simple questions](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107660.html)
- [no internet on Android via Browser widget](http://forums.livecode.com/viewtopic.php?t=33964&p=190660#p190660)

## Updates in the LiveCode open source project

9 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2020-04-20..2020-04-26&type=Issues).

<!---
### New LiveCode releases

- [Release 9.6.0 DP-4](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107407.html)
--->

### Notable changes

- [Fix crash on enter in android native field widget](https://github.com/livecode/livecode/pull/7334)
- [Fix url callbacks sent when setting html in CEF browser](https://github.com/livecode/livecode/pull/7331)
- [Fix bug preventing mobile browser control from loading after setting the "url" property to empty](https://github.com/livecode/livecode/pull/7329)
- [Fix execution error when calling JavaScript in iOS browser widget](https://github.com/livecode/livecode/pull/7328)
- [Tree View Widget sends click when scrolling](https://github.com/livecode/livecode/pull/7296)
- [Ensure Windows player shows correct frame for currentTime when paused](https://github.com/livecode/livecode/pull/7252)


### Bug of the week

- [Bug 22698 - relayering group inside of closefield handler can cause Crash to Desktop](https://quality.livecode.com/show_bug.cgi?id=22698)

The reporter provided a detailed recipe and a helpful sample stack that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop` branch

Then try one of these:

- (Easy) [Dictionary: more examples for IF entry in Dictionary](https://quality.livecode.com/show_bug.cgi?id=22589)
- (Easy) [Dictionary: incorrect description of resizeControl message](https://quality.livecode.com/show_bug.cgi?id=17118)
- (Easy) [Docs: Update the dict entry of the "propertynames"](https://quality.livecode.com/show_bug.cgi?id=7375)
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

- [Brian Milby](https://github.com/bwmilby)
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [What's a Capability in an Apple Provisioning Profile?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107570.html)
- [How to make a mobile app stay alive in the background?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107682.html)
- [Seth is now free under a MIT License (custom color themes)](http://forums.livecode.com/viewtopic.php?t=33985&p=190858#p190858)

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
