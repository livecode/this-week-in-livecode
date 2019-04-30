---
layout: post
title:  "This Week In LiveCode 176"
date:   2019-04-30 15:30
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

- [specialFolderPath("preferences") returns empty on Windows???](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101584.html)
- [Seeking philosophical guidance on library interface design.](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101594.html)
- [Engine: Socket limit?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101614.html)
- [Lesson on Accelerated Rendering](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101618.html)
- [mobilePickPhoto on Android](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101621.html)
- [Bug drawing card in LC9](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101622.html)
- [Can LC Server code export images of cards and objects](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101659.html)
- [Allow navigation in field but prevent editing](http://forums.livecode.com/viewtopic.php?t=32530&p=179247#p179247)

## Updates in the LiveCode open source project

13 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2019-04-23..2019-04-29&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 9.0.4 RC-2](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101297.html)
--->


### Notable changes

- [Fix memory leak when using printing on macOS](https://github.com/livecode/livecode/pull/6915)
- [Build Linux prebuilt libraries with position-independant code](https://github.com/livecode/livecode/pull/6953)
- [Fix LCB's 'is among the elements of' operator](https://github.com/livecode/livecode/pull/7001)

### Bug of the week

- [Bug 22027 - Bottom of card not drawn correctly (clipped) when stack has Mac menubar](https://quality.livecode.com/show_bug.cgi?id=22027)

The reporter provided a helpful sample stack, a screenshot and a detailed description that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Then try one of these:

- (Easy) [Docs: Mention that drawingSvgCompileFile() cannot read from resources folder on Android](https://quality.livecode.com/show_bug.cgi?id=21822)
- (Easy) [Docs: Mention that mobile player controller does not show if video file is missing or invalid](https://quality.livecode.com/show_bug.cgi?id=19631)
- (Easy) [Docs: Describe the behavior of stack title/label property](https://quality.livecode.com/show_bug.cgi?id=19660)
- (Easy) [Dictionary entry of the menu keyword is incorrectly formatted](https://quality.livecode.com/show_bug.cgi?id=20364)
- (Easy) [Docs say fullclipboarddata["image"] can be gif, png, or jpeg but BMP data can be present on Windows](https://quality.livecode.com/show_bug.cgi?id=20472)
- (Easy) [Docs: Livecode dictionary entry for videoClip](https://quality.livecode.com/show_bug.cgi?id=21156)
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

- *[livecodeali](https://github.com/livecodeali)*  
- *[livecodeian](https://github.com/livecodeian)*  
- *[livecodepanos](https://github.com/livecodepanos)*  
- *[livecodesam](https://github.com/livecodesam)*  
- *[runrevmark](https://github.com/runrevmark)* 

<!--
## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Notarizing applications for macOS](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101424.html)
- [Upcoming MacOS 14.5 with software “notarization” requirements](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101439.html)
- [Encrypted standalones](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101526.html)
--->

## Upcoming events

* [The next LiveCode Conference is in...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94801.html)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
