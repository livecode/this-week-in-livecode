---
layout: post
title:  "This Week In LiveCode 241"
date:   2020-10-19 15:30
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community


### News & blog posts

- [October only: Get a Hacktoberfest t-shirt by contributing to LiveCode](https://hacktoberfest.digitalocean.com): Submit 4 pull requests and get a free Hacktoberfest T-shirt!


### Interesting discussions

- [Android Status Bar](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg109566.html)
- [Interface Resolution](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg109590.html)
- [Correct use of string A 'is in' string B?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg109597.html)
- [Standalone failures](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg109610.html)
- [Livecode server UNIX version (not Linux)](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg109619.html)
- [SSL cPanel mySql setup](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg109630.html)
- [Odd data in message box](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg109636.html)
- [Help needed :)](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg109685.html)
- [Livecode syntax highlighting in VSCode](https://forums.livecode.com/viewtopic.php?f=108&t=34778)

## Updates in the LiveCode open source project

8 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2020-10-12..2020-10-18&type=Issues).

<!---
### New LiveCode releases

- [Release 9.6.1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg109012.html)
--->

### Notable changes

- [Remove support for 32bit on MacOS IDE and standalones](https://github.com/livecode/livecode/pull/7449)
- [Fix printing with vGrid enabled on Windows](https://github.com/livecode/livecode/pull/7448)
- [Fix tracking of mouse events during modal session](https://github.com/livecode/livecode/pull/7445)
- [Send RowLeftSwipeControlClicked with target param](https://github.com/livecode/livecode-ide/pull/2143)
- [Remove unneccessary creation and clearance of SKBitmap](https://github.com/livecode/livecode/pull/7442)

<!---
### Bug of the week

- [Bug 22928 - Loading audio file in iOS native player randomly causes app to freeze ](https://quality.livecode.com/show_bug.cgi?id=22928)

The reporter provided a helpful sample stack that allowed us to test and confirm the problem quickly.
--->

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop-9.6` branch

Then try one of these:

- (Easy) [Docs: Mention the behavior of 'the screenrect' on iOS if "Display Zoom" is checked](https://quality.livecode.com/show_bug.cgi?id=22949)
- (Easy) [Docs: Mention that matchText/matchChunk/replaceText all operate as if form-sensitive were true](https://quality.livecode.com/show_bug.cgi?id=15311)
- (Easy) [Dictionary: more examples for IF entry in Dictionary](https://quality.livecode.com/show_bug.cgi?id=22589)
- (Easy) [Dictionary: incorrect description of resizeControl message](https://quality.livecode.com/show_bug.cgi?id=17118)
- (Easy) [Docs: Update the dict entry of the "propertynames"](https://quality.livecode.com/show_bug.cgi?id=7375)
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


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [ LC iOS Command 'mergPopActivity'](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg109675.html)

<!---
## Upcoming events

* [SoCal LiveCode Group Meeting: March 5, Pasadena](https://forums.livecode.com/viewtopic.php?f=50&t=33729)
--->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
