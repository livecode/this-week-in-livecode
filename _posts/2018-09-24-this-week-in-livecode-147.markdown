---
layout: post
title:  "This Week In LiveCode 147"
date:   2018-09-24 14:00
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

- [Develop Yourself Video Competition Winner Announced](https://livecode.com/develop-yourself-video-competition-winner-announced/)
--->

### Interesting discussions

- [best way to open a script-only library stack?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97956.html)
- [Widget ColorPicker_v101](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97957.html)
- [iOS 12 and SDK](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98028.html)
- [App Dead on iOS 12](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97963.html)
- [Creating Array - Auto Numeric](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97996.html)
- [Navigator 6.3 alpha 1 is out -- major awesomeness!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98010.html)
- [editGroup message?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98019.html)
- [Standalone build workaround](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98033.html)
- [ControlHandles_v100](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98040.html)
- [When is suspendStack sent?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98065.html)
- [Mobile write to text file woes](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98083.html)
- [Script-only-stack file issue 9.0.1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98087.html)
- [mousemove doesn't recognize "shiftkey is down", but only under Windows](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98094.html)
- [(browser) focus hocus pocus broke us](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98095.html)
- [Script Editor Slow on Windows (any Macs?)](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98100.html)
- [Intersect Function](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98111.html)
- [iOS wows - Screen not updating on a card](http://forums.livecode.com/viewtopic.php?t=31553&p=171666#p171666)

## Updates in the LiveCode open source project

5 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-09-17..2018-09-23&type=Issues).

<!---
### New LiveCode releases

- [LiveCode 9.0.1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97854.html)
--->


### Notable changes

- [Correct code example and clarify about close/open messages](https://github.com/livecode/livecode/pull/6694)
- [Deploy - Handle payload and project out of order on windows](https://github.com/livecode/livecode/pull/6689)
- [Check if the name is taken before creating the standalone folder](https://github.com/livecode/livecode/pull/6678)
- [Tree View Widget - select new elements automatically](https://github.com/livecode/livecode/pull/6676)


### Bug of the week

- [Bug 21580 - Properties Inspector ->fields -> contents tab -> "show grid" does not toggle](http://quality.livecode.com/show_bug.cgi?id=21580)

The reporter provided a detailed recipe as well as a helpful simple sample stack that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Duplicate handler in drawing.livecodescript](https://quality.livecode.com/show_bug.cgi?id=21602)
- (Easy) [Docs: Command line installation needs "-ui" instead of "noui" since LC 9 DP-5](https://quality.livecode.com/show_bug.cgi?id=21340)
- (Easy) [Dictionary: Unlock Screen documentation has typos/errors and needs to reference "lock screen for visual effect"](https://quality.livecode.com/show_bug.cgi?id=21312)
- (Easy) [Dictionary: Mention that in ReplaceText function you might need to escape RegExp metacharacters, if the "replacementString" is the char itself (e.g. ".")](http://quality.livecode.com/show_bug.cgi?id=20943)
- (Easy) [Dictionary: Improve documentation for launch URL & specialFolderPath for Android](http://quality.livecode.com/show_bug.cgi?id=20722)
- (Easy) [Dictionary: Mention that iPhone X does not support "portrait upside down" orientation](http://quality.livecode.com/show_bug.cgi?id=20640)
- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [MouseEnter / MouseLeave infinite Loop trap - documentation enhancement](http://quality.livecode.com/show_bug.cgi?id=20529)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Applescript "do script" missing from standalone](http://quality.livecode.com/show_bug.cgi?id=20993)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Medium) [Relayer control crashes livecode](https://quality.livecode.com/show_bug.cgi?id=21460)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)
- (Hard) [Case insensitive matchText returns incorrect result](https://quality.livecode.com/show_bug.cgi?id=15312)


### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Plug-Ins](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98038.html)



## Upcoming events

* [LiveCode Global: 12 Months Streamed Live Around the Globe - Running every 2nd month throughout 2018!](https://livecode.com/global/) 

Save the dates:

- 15th of November 2018

* [The next LiveCode Conference is in...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94801.html)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
