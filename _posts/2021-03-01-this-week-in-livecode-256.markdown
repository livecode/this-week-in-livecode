---
layout: post
title:  "This Week In LiveCode 256"
date:   2021-03-01 15:30
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community


### News & blog posts

- [How I built a Mobile App in LiveCode and Took Over the World](https://livecode.com/how-i-built-a-mobile-app-in-livecode-and-took-over-the-world/)


### Interesting discussions

- [Re: Polygon fill algo?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111050.html)
- [How do I interpret this Build Error dialog?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111059.html)
- [iOS App just shows Splash Screen then quits](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111081.html)
- [scrollbar question](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111118.html)
- ["within graphic" question](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111125.html)
- [Which Monitor to Open LC In](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111133.html)
- [S3 Compatible?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111161.html)
- [Mandatory for new Andorid apps on Play](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111186.html)
- [Lost or slow messages resulting in partial redraw of card.](https://forums.livecode.com/viewtopic.php?t=35462&p=202344#p202344)
- [Push notifications for android [Solved]](https://forums.livecode.com/viewtopic.php?t=35453&p=202246#p202246)

## Updates in the LiveCode open source project

14 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2021-02-15..2021-02-28&type=Issues).

<!--
### New LiveCode releases

- [Release 9.6.2 RC-2](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg110561.html)
-->


### Notable changes

- [Fix Accelerated rendering glitch when multiple stacks are open](https://github.com/livecode/livecode/pull/7494)
- [Reset EOF marker when seeking in a file on macOS](https://github.com/livecode/livecode/pull/7499)
- [Fix crash when restarting location tracker on Android](https://github.com/livecode/livecode/pull/7515)
- [Fix native layers not relayering after object relayer](https://github.com/livecode/livecode/pull/7531)
- [Use AbsoluteLayout class to position native layers](https://github.com/livecode/livecode/pull/7525/files)

<!--
### Bug of the week

- [Bug 23085 - VIsual effects doesn't wok on macOS Big Sur (11.2)](https://quality.livecode.com/show_bug.cgi?id=23085)

The reporter and the commenters provided a helpful sample stack and recipe that allowed us to test and confirm the problem quickly.
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

- [Charles Warwick](https://github.com/techstrategies)
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)* 

### Useful references

Do you need help with your project? Have a look at these useful resources:

- [LiveCode Lessons](https://lessons.livecode.com)
- [LiveCode Forums](https://forums.livecode.com/index.php)


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [SSL Error - question from Stack Overflow](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111089.html)


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
