---
layout: post
title:  "This Week In LiveCode 173"
date:   2019-03-25 15:30
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

- [LC 9 and Externals](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101047.html)
- [BACKUPS !!!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101076.html)
- [Localisation - Internationalization Package](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101103.html)
- [A Question about Ask File](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101112.html)
- [Browser widget and downloading of files](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101114.html)
- [ANN: Script Editor Refactoring Support](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101115.html)
- [ignore close button?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101162.html)
- [Find offset of first and last char of Word x in a field](http://forums.livecode.com/viewtopic.php?t=32379&p=178075#p178075)

## Updates in the LiveCode open source project

5 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2019-03-18..2019-03-24&type=Issues).



### New LiveCode releases

- [LiveCode 9.0.3](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101107.html)



### Notable changes

- [Reduce time taken to compute minimum required file version for stack](https://github.com/livecode/livecode/pull/6910): This fixes a regression, where in some edge cases with really huge stacks involved, saving could take up to 13 minutes. With this patch, the time needed to save the stack drops to just 2 minutes.
- [Prevent unnecessary disk writes of revPreferences stack](https://github.com/livecode/livecode-ide/pull/2043): This should improve performance on Windows.

### Bugs of the week

- [Bug 21900 - Zip, attachment and crash under iOS](https://quality.livecode.com/show_bug.cgi?id=21900)

The reporter provided a helpful sample stack and a detailed description that allowed us to test, confirm and fix the problem quickly.


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

- *[livecodeian](https://github.com/livecodeian)*  
- *[livecodepanos](https://github.com/livecodepanos)*  
- *[livecodesam](https://github.com/livecodesam)*  


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [password protected stack and passkey](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101083.html)



## Upcoming events

* [The next LiveCode Conference is in...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94801.html)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
