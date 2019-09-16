---
layout: post
title:  "This Week In LiveCode 194"
date:   2019-09-16 15:30
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

- [Merge and unicode](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103646.html)
- [Stop Integer Coercion to Scientific Notation in JSON](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103672.html)
- [OSTimeInfo_105](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103677.html)
- [Odd paste in 9.5](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103694.html)
- [BasicGeoLib_v100](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg103711.html)
- [Double Title Bar](http://forums.livecode.com/viewtopic.php?t=33109&p=183296#p183296)


## Updates in the LiveCode open source project

13 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2019-09-09..2019-09-15&type=Issues).



<!---
### New LiveCode releases

- [LiveCode 9.0.5 RC-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101861.html)
- [LiveCode 9.5.0 DP-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101932.html)
--->


### Notable changes

- [Add tsNet/libUrl conflict warning to urlProgress dictionary entry](https://github.com/livecode/livecode/pull/7160)
- [Use correct user info key to obtain keyboard size](https://github.com/livecode/livecode/pull/7155)
- [Fix graphical artefacts after removing focus from a group on mobile](https://github.com/livecode/livecode/pull/7144)
- [Ensure Search for Inclusions works if script is unlocked](https://github.com/livecode/livecode/pull/7141)

### Bug of the week

- [Bug 22376 - Selected text containing tab displays additional false selection area](https://quality.livecode.com/show_bug.cgi?id=22376)

The reporter provided a detailed description and sample stack that allowed us to test and confirm the problem quickly.


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

- *[livecodeian](https://github.com/livecodeian)*  
- *[livecodepanos](https://github.com/livecodepanos)*  
- *[livecodesam](https://github.com/livecodesam)*  
- *[montegoulding](https://github.com/montegoulding)*  


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Apple Submission - "Deprecated Info.plist Key. The Info.plist contains a key 'UIApplicationExitsOnSuspend' in bundle](http://forums.livecode.com/viewtopic.php?t=33102&p=183224#p183224)

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
