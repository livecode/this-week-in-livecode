---
layout: post
title:  "This Week In LiveCode 181"
date:   2019-06-10 15:30
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

- [Visitors in LiveCode](https://livecode.com/visitors-in-livecode/)
--->

### Interesting discussions

- [Black boxes replace images in Mojave](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102187.html)
- [Line Graph Widget - Plotting time series](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102193.html)
- [View XML file in Tree View widget - worth the effort?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102201.html)
- [Design questions...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102214.html)
- [Date and time](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102226.html)
- [Realtime sound generation in LC](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102237.html)
- [Duplicate card and object command lc 9.0.4](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102248.html)
- [Big problems creating standalone](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102254.html)
- [mouseChunk in a loop](http://forums.livecode.com/viewtopic.php?f=9&t=32694)
- [Could not find a valid identity to use for the selected profile ..](http://forums.livecode.com/viewtopic.php?t=32674&p=180278#p180278)

## Updates in the LiveCode open source project

18 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2019-06-03..2019-06-09&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 9.0.5 RC-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101861.html)
- [LiveCode 9.5.0 DP-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101932.html)
--->

### Notable changes

- [Implement delete undo for widgets](https://github.com/livecode/livecode/pull/7079)
- [Ensure default device theme is used on Android datePicker](https://github.com/livecode/livecode/pull/7061)
- [Add `this widget` and `trigger all in <widget>` syntax](https://github.com/livecode/livecode/pull/7048)
- [Prebuilt: Ensure linux thirdparty libs are prebuilt with position-independent code](https://github.com/livecode/livecode/pull/7032)
- [CEF: Update to 74.1.16+ge20b240+chromium-74.0.3729.131](https://github.com/livecode/livecode-thirdparty/pull/133)

<!---
### Bugs of the week

- [Bug 22091 - Preset icon disappears from SVG Icon widget when selecting the same icon](https://quality.livecode.com/show_bug.cgi?id=22091)
- [Bug 22103 - Effective textFont of chunk reports field font](https://quality.livecode.com/show_bug.cgi?id=22103)


The reporters provided a helpful sample stack and/or a detailed description that allowed us to test and confirm the problem quickly.
--->

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Then try one of these:

- (Easy) [Docs: the machine on windows can now return x86_64](https://quality.livecode.com/show_bug.cgi?id=22142)
- (Easy) [IDE: Cancel standalone pop up wrong message](https://quality.livecode.com/show_bug.cgi?id=22136)
- (Easy) [Docs: Mention that drawingSvgCompileFile() cannot read from resources folder on Android](https://quality.livecode.com/show_bug.cgi?id=21822)
- (Easy) [Docs: Mention that mobile player controller does not show if video file is missing or invalid](https://quality.livecode.com/show_bug.cgi?id=19631)
- (Easy) [Docs: Describe the behavior of stack title/label property](https://quality.livecode.com/show_bug.cgi?id=19660)
- (Easy) [Dictionary entry of the menu keyword is incorrectly formatted](https://quality.livecode.com/show_bug.cgi?id=20364)
- (Easy) [Docs say fullclipboarddata["image"] can be gif, png, or jpeg but BMP data can be present on Windows](https://quality.livecode.com/show_bug.cgi?id=20472)
- (Easy) [Docs: Livecode dictionary entry for videoClip](https://quality.livecode.com/show_bug.cgi?id=21156)
- (Easy) [Docs: specialFolderPath("resources") for stacks with empty filename is not documented](https://quality.livecode.com/show_bug.cgi?id=21183)
- (Easy) [Docs: Datagrid Deleteline and Deletelines commands are no longer synonymous in DG2](https://quality.livecode.com/show_bug.cgi?id=21576)
- (Medium) [IDE: when command exceeds width of message box, backspacing causes ghost characters](https://quality.livecode.com/show_bug.cgi?id=22092)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Applescript "do script" missing from standalone](http://quality.livecode.com/show_bug.cgi?id=20993)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Medium) [Relayer control crashes livecode](https://quality.livecode.com/show_bug.cgi?id=21460)
- (Medium) [Datagrid not protected for drag and drop in project view (labels can get inserted into the DGgrp itself)](https://quality.livecode.com/show_bug.cgi?id=21750)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)
- (Hard) [Case insensitive matchText returns incorrect result](https://quality.livecode.com/show_bug.cgi?id=15312)


### Contributors this week

- [BerndN](https://github.com/BerndN)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*  
- *[livecodepanos](https://github.com/livecodepanos)*  
- *[montegoulding](https://github.com/montegoulding)*  


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Compatible software?](http://forums.livecode.com/viewtopic.php?f=49&t=32693&p=180444#p180444)


<!---
## Upcoming events

* [SoCal LiveCode Group Meeting: June 7, Pasadena](http://forums.livecode.com/viewtopic.php?t=32559&p=179454#p179454)
--->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
