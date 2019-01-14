---
layout: post
title:  "This Week In LiveCode 163"
date:   2019-01-14 15:30
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

- [Checking xml string](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg100037.html)
- [Livecode Server Post](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg100064.html)
- [screenRect and screenLoc weirdness](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg100050.html)
- [How to remove emoji's from unicode string](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg100086.html)
- [Repeat for each line of a variable or field?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg100077.html)
- [Navigator 7.1rc1 is available](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg100083.html)
- [LCImageToolBox_v190](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg100085.html)
- [Reorder by drag and drop](http://forums.livecode.com/viewtopic.php?t=32024&p=175201#p175201)


## Updates in the LiveCode open source project

17 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2019-01-07..2019-01-13&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 9.0.2](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg99471.html
)
--->



### Notable changes

- [Add sorting / collation support for more locales](https://github.com/livecode/livecode/pull/6846)
- [Support for splash images for iPhone XR and XSMAX](https://github.com/livecode/livecode/pull/6836)
- [Fix Return key finding only first result in SE Search](https://github.com/livecode/livecode-ide/pull/2023)
- [Ensure setting the imagesource to a remote image works](https://github.com/livecode/livecode/pull/6832)
- [Fix DataGrid cached control error](https://github.com/livecode/livecode-ide/pull/2021)
- [Fixed offset bugs](https://github.com/livecode/livecode/pull/6797)


### Bug of the week

- [Bug 21787 - Deleting a stack does not clean up memory used by substack](http://quality.livecode.com/show_bug.cgi?id=21787)

The reporter provided a helpful sample stack and a detailed description that allowed us to test and confirm the problem quickly.



### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Then try one of these:

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

- [Trevor DeVore](https://github.com/trevordevore)
- *[livecodealex](https://github.com/livecodealex)*   
- *[livecodeian](https://github.com/livecodeian)*  
- *[livecodepanos](https://github.com/livecodepanos)*  
- *[livecodesam](https://github.com/livecodesam)*  

<!---
## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [IMAP library, or support via tsNet?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg99875.html)

--->

## Upcoming events

* [SoCal LiveCode Group Meeting - February 7, 2019, Pasadena](http://forums.livecode.com/viewtopic.php?f=50&t=32009)
* [The next LiveCode Conference is in...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94801.html)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
