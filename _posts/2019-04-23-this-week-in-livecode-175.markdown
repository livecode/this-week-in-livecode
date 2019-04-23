---
layout: post
title:  "This Week In LiveCode 175"
date:   2019-04-23 15:30
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

- [Browser layering](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101342.html)
- [Hit Box for widgets](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101346.html)
- [MouseMove less responsive in 9.0.4](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101354.html)
- [LC Server on OSX Mojave - Local host & sites](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101369.html)
- [Browser selections](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101393.html)
- [Saving a tab formatted field to a file and retaining its formatting](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101397.html)
- [LC Server permissions](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101498.html)
- [Panel/Form Widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101448.html)
- [setting file created date in livecode from script](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101509.html)
- [button ICON](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101562.html)
- [Open Printing to PDF](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101579.html)

## Updates in the LiveCode open source project

66 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2019-04-01..2019-04-22&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 9.0.4 RC-2](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101297.html)
--->


### Notable changes

- [More than 30 memory leaks in various areas have been identified and fixed](https://github.com/livecode/livecode/pulls?utf8=✓&q=leak+is%3Apr+author%3Arunrevmark+milestone%3A9.0.5-rc-1+is%3Aclosed+): Special thanks to @runrevmark
- [Update the iconpicker to allow filtering](https://github.com/livecode/livecode/pull/6534)
- [Make manual height in PI consistent](https://github.com/livecode/livecode-ide/pull/2003)
- [Update TreeView to ignore mouseUp when row has changed](https://github.com/livecode/livecode/pull/6764)
- [Fix MCWidget::hittest for invisible/disabled widgets](https://github.com/livecode/livecode/pull/6933)
- [Fix Autocomplete IF-structs](https://github.com/livecode/livecode-ide/pull/2046)
- [Project browser fix display errors for missing behaviors, add alert](https://github.com/livecode/livecode-ide/pull/2035)
- [TreeView Widget: Get/Set Fold State](https://github.com/livecode/livecode/pull/6770)


### Bug of the week

- [Bug 21952 - Setting cursor property to an image created with SVG data doesn't render cursor at hi-res](https://quality.livecode.com/show_bug.cgi?id=21952)

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

- [Andrew Bell](https://github.com/MWCoastMedia)
- [BerndN](https://github.com/BerndN)
- [Brian Milby](https://github.com/bwmilby)
- [Charles Warwick](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*  
- *[livecodeian](https://github.com/livecodeian)*  
- *[livecodepanos](https://github.com/livecodepanos)*  
- *[livecodesam](https://github.com/livecodesam)*  
- *[montegoulding](https://github.com/montegoulding)*  
- *[runrevelanor](https://github.com/runrevelanor)*
- *[runrevmark](https://github.com/runrevmark)* 


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Notarizing applications for macOS](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101424.html)
- [Upcoming MacOS 14.5 with software “notarization” requirements](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101439.html)
- [Encrypted standalones](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg101526.html)

## Upcoming events

* [The next LiveCode Conference is in...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94801.html)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
