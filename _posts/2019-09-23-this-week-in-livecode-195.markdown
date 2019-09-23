---
layout: post
title:  "This Week In LiveCode 195"
date:   2019-09-23 15:30
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

- [Sorting strangeness](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103735.html)
- [Guess encoding for text file...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103756.html)
- [Export Snapshot](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103763.html)
- [Print to PDF on Android?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103776.html)
- [No object selected](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103779.html)
- [Inter-app communication to LiveCode?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103793.html)
- [Access Resource Files](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103798.html)
- [DataView Paginated Scroll](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103822.html)
- [Android architectures](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103830.html)
- [HTML5: MultiWindows and GoStackURL v155](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103832.html)
- [ShowAll on Android 10](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103839.html)


## Updates in the LiveCode open source project

9 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2019-09-16..2019-09-22&type=Issues).



<!---
### New LiveCode releases

- [LiveCode 9.0.5 RC-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101861.html)
- [LiveCode 9.5.0 DP-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101932.html)
--->


### Notable changes

- [Add docs note about accelerometer differences](https://github.com/livecode/livecode/pull/7174)
- [Describe potential use of out-of-range values in dateItems](https://github.com/livecode/livecode/pull/7171)
- [Add support for building with Xcode 11 / iOS 13.0 SDK](https://github.com/livecode/livecode/pull/7165)

### Bug of the week

- [Bug 22381 - SE: "Select All" of a script sets scroll of field but not line numbers ](https://quality.livecode.com/show_bug.cgi?id=22381)

The reporter provided a detailed description and sample stack that allowed us to test and confirm the problem quickly. Moreover, he suggested a fix and submitted a pull request.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Then try one of these:

- (Easy) [Docs: Update the dict entry of the "propertynames"](https://quality.livecode.com/show_bug.cgi?id=7375)
- (Easy) [Docs: ControlAtScreenLoc incorrect entry](https://quality.livecode.com/show_bug.cgi?id=15645)
- (Easy) [Docs: Improve dateItems dictionary entry](https://quality.livecode.com/show_bug.cgi?id=19495)
- (Easy) [Docs: ask and answer file of type docs incorrect ](https://quality.livecode.com/show_bug.cgi?id=17201)
- (Easy) [Docs: Mention that lockLoc property of an object only prevents it from being moved by the mouse when in Edit mode](https://quality.livecode.com/show_bug.cgi?id=19848)
- (Easy) [Docs: Mention that values in accelerationChanged differ between iOS and Android](https://quality.livecode.com/show_bug.cgi?id=21111)
- (Easy) [Docs: Mention that urlProgress is not available on mobile if libUrl/tsNet is included in the standalone](https://quality.livecode.com/show_bug.cgi?id=21978)
- (Easy) [Docs: Mention that drawingSvgCompileFile() cannot read from resources folder on Android](https://quality.livecode.com/show_bug.cgi?id=21822)
- (Easy) [Docs: specialFolderPath("resources") for stacks with empty filename is not documented](https://quality.livecode.com/show_bug.cgi?id=21183)
- (Easy) [Docs: Datagrid Deleteline and Deletelines commands are no longer synonymous in DG2](https://quality.livecode.com/show_bug.cgi?id=21576)
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
- *[livecodesam](https://github.com/livecodesam)*  


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [WARNING ITMS-90339](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103741.html)
- [Audio Recording with cameracontrol](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103827.html)
- [LC apps on iOS 13?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103842.html)

<!--
## Upcoming events

* [SoCal LiveCode Group Meeting: Sept 5, Pasadena](http://forums.livecode.com/viewtopic.php?f=50&t=32935)
-->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
