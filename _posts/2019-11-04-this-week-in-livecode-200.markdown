---
layout: post
title:  "This Week In LiveCode 200"
date:   2019-11-04 15:30
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

- [Effective rect of stacks on Windows 10](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104371.html)
- [PDF-Tools](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104373.html)
- [Push Card](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104403.html)
- [Possible solution to determine if default network has changed (MacOS only for now)](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104419.html)
- [Slowdown when printing to PDF in a loop](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104434.html)
- [Signing, Notarizing, and Stapling and macOS versions](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104438.html)
- [Windows Command Line Silent Option](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104442.html)
- [CEF Browser woes! no console.](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104463.html)
- [Can I find out what handler I am in?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104482.html)
- [Livecodeshare/SampleStacks](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104506.html)
- [Weird macOS error dialog](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104516.html)
- [Steganograph_v110](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104528.html)
- [identifying text chars in an image](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104549.html)
- [paste unformatted & inspector field "styled text"](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104558.html)
- [drag'n'drop in text fields](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104572.html)
- [OCR-Lite_v100](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104595.html)
- [Need trig & LCB help](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104606.html)
- [encoding woes!?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104612.html)
- [in case you need another reason to love LiveCode...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104629.html)
- [scroll browser widget via script?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104631.html)
- [cr, lf, and reading in terminals/vim](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104651.html)
- ["empty" background in printed pdf is actually grey](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104659.html)
- [Windows, Underlines and Printing](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104734.html)

## Updates in the LiveCode open source project

7 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2019-10-21..2019-11-03&type=Issues).




### New LiveCode releases

- [LiveCode 9.5.1 RC-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104698.html)

<!---
### Notable changes

- [Disable deleted object pool creation whilst debugging](https://github.com/livecode/livecode/pull/7185): The random crashes while debugging in the script editor are now fixed!
--->

<!---
### Bug of the week

- [Bug 22408 - Display issues when changing stack and orientation on iOS](https://quality.livecode.com/show_bug.cgi?id=22408)

The reporter provided a detailed description and a helpful sample stack that allowed us to test and confirm the problem quickly.
--->

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop-9.5` branch

Then try one of these:

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

- [Charles Warwick](https://github.com/techstrategies)
- *[livecodepanos](https://github.com/livecodepanos)*  


<!--
## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [macOS Notarization helper for Levure](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104215.html)
-->


## Upcoming events

* [SoCal LiveCode Group Meeting: November 7, Pasadena](http://forums.livecode.com/viewtopic.php?f=50&t=33187)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
