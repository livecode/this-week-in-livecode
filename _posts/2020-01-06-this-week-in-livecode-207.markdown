---
layout: post
title:  "This Week In LiveCode 207"
date:   2020-01-06 15:30
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

- [October only: Get a Hacktoberfest t-shirt by contributing to LiveCode](https://hacktoberfest.digitalocean.com): Submit 4 pull requests and get a free Hacktoberfest T-shirt!
--->

### Interesting discussions

- [Table Text Livecode vs .....](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105326.html)
- [Missing keys in datagrid?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105341.html)
- [using stdout](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105365.html)
- [DataGrid Crash to Desktop Revisited](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105384.html)
- [a windows 10 wtf](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105395.html)
- [Polygon Side Does Note Match to Polygon rect](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105413.html)
- [LiveCode won't recognize my stack](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105421.html)
- [mobile dev confusion](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105427.html)
- [Import SVG with Multi-Path and Two colors](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105463.html)
- [empty variable](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105481.html)
- [Baker's Assistant version 0.2.0](http://forums.livecode.com/viewtopic.php?t=33478&p=186493#p186493)
- [DataView and DataView Tree Updates](http://forums.livecode.com/viewtopic.php?t=33479&p=186505#p186505)

## Updates in the LiveCode open source project

13 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2019-12-16..2020-01-05&type=Issues).


### New LiveCode releases

- [LiveCode 9.6.0 DP-2](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105360.html)


### Notable changes

- [Implement detailed-utf8 files & folders](https://github.com/livecode/livecode/pull/7238)
- [Don't recalculate scaled width & height if widget dimensions are unchanged](https://github.com/livecode/livecode/pull/7237)
- [Fix web view not resizing on iOS after reconfiguration](https://github.com/livecode/livecode/pull/7235)
- [Add support for merging activity attributes in manifest](https://github.com/livecode/livecode/pull/7179)
- [Fix browser widget showing blank page after set htmltext](https://github.com/livecode/livecode/pull/7140)
- [Ensure setting spaceAbove does not affect spaceBelow](https://github.com/livecode/livecode/pull/7107)

### Bug of the week

- [Bug 22511 - JSONImport throws an error if JSON includes multi-codepoint characters](https://quality.livecode.com/show_bug.cgi?id=22511)
- [Setting dragData["private"] wipes out clipboarddata](https://quality.livecode.com/show_bug.cgi?id=22508)

The reporter provided a detailed recipe and a helpful sample stack that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop` branch

Then try one of these:

- (Easy) [Dictionary: incorrect description of resizeControl message](https://quality.livecode.com/show_bug.cgi?id=17118)
- (Easy) [Docs: Update the dict entry of the "propertynames"](https://quality.livecode.com/show_bug.cgi?id=7375)
- (Easy) [Docs: Mention that lockLoc property of an object only prevents it from being moved by the mouse when in Edit mode](https://quality.livecode.com/show_bug.cgi?id=19848)
- (Easy) [Docs: specialFolderPath("resources") for stacks with empty filename is not documented](https://quality.livecode.com/show_bug.cgi?id=21183)
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

- *[livecodeian](https://github.com/livecodeian)* 
- *[livecodepanos](https://github.com/livecodepanos)*  
- *[montegoulding](https://github.com/montegoulding)*  
- *[runrevmark](https://github.com/runrevmark)*


<!---
## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [iOS text file download from Dropbox](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105202.html)
- [LC #48 @TIOBE](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105211.html)
--->

<!---
## Upcoming events

* [SoCal LiveCode Group Meeting: January 2, Pasadena](http://forums.livecode.com/viewtopic.php?t=33407&p=185921#p185921)
--->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
