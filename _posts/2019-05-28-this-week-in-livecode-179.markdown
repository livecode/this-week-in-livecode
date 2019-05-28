---
layout: post
title:  "This Week In LiveCode 179"
date:   2019-05-28 15:30
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

- [Mobile - Open file dialog?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101823.html)
- [Dash docset for LC now at 1.76, Make_DocSet on Livecode Share updated](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101833.html)
- [play sounds in HTML5](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101846.html)
- [Seeking confirmation of a bug...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101864.html)
- [Failure to build on Android](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101882.html)
- [Question on automatically generating an MSI file](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101899.html)
- [The correct way to quit a Windows standalone](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101899.html)
- [There is a file](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101907.html)
- [LC and live video streaming](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101931.html)
- [Livecode Array Encoding / Decoding using other platforms?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101948.html)
- [repeat with times](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101966.html)
- [IDE 9.0.4 and 9.0.5rc1 getting slow again on win10?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101975.html)
- [Download file from widget browser ?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101979.html)
- [9.5 DP 1 Unadorned - LayerMode - Container](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101989.html)
- [Windows 64](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102014.html)
- [App Store changes in August?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102022.html)
- [Opening a stack changes it's set rect](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102023.html)
- [how to load a local file into the browser widget?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102042.html)
- [Player object controller bar](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102048.html)
- [Identifying macOS folders that are considered to be files?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102056.html)
- [windowBoundingRect on multiple monitors? Is this a bug?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102079.html)
- [Setting mobile scroller hScroll fails](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg102085.html)



## Updates in the LiveCode open source project

35 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2019-05-13..2019-05-27&type=Issues).



### New LiveCode releases

- [LiveCode 9.0.5 RC-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101861.html)
- [LiveCode 9.5.0 DP-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101932.html)

### Notable changes

- [FasterDG: Use container layerMode in form view](https://github.com/livecode/livecode-ide/pull/2065)
- [AndroidPermissionsLCB: Added permission checking handlers to android-utils](https://github.com/livecode/livecode/pull/7027)
- [Mac Status Menu: Implement mac status menu library](https://github.com/livecode/livecode/pull/6660)
- [Add 'layerClipRect' property to controls](https://github.com/livecode/livecode/pull/7007)
- [Ensure Android ScrollViews don't cancel touch events](https://github.com/livecode/livecode/pull/6942)
- [Add support for building win64 standalones](https://github.com/livecode/livecode-ide/pull/2020)
- [Allow infinite result in div, times and pow operations](https://github.com/livecode/livecode/pull/6813)
- [Browser Widget: Progress, isSecure and allowUserInteraction](https://github.com/livecode/livecode/pull/6810)



### Bugs of the week

- [Bug 22091 - Preset icon disappears from SVG Icon widget when selecting the same icon](https://quality.livecode.com/show_bug.cgi?id=22091)
- [Bug 22103 - Effective textFont of chunk reports field font](https://quality.livecode.com/show_bug.cgi?id=22103)

The reporters provided a helpful sample stack and/or a detailed description that allowed us to test and confirm the problem quickly.


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

- *[livecodeian](https://github.com/livecodeian)*
- *[livecodemichael](https://github.com/livecodemichael)*
- *[livecodepanos](https://github.com/livecodepanos)*  
- *[montegoulding](https://github.com/montegoulding)*  
- *[runrevmark](https://github.com/runrevmark)*

<!---
## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Apple Provisioning Profile Is Missing](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101753.html)
- [TSNet hanging](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101795.html)
--->


## Upcoming events

* [SoCal LiveCode Group Meeting: June 7, Pasadena](http://forums.livecode.com/viewtopic.php?t=32559&p=179454#p179454)

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
