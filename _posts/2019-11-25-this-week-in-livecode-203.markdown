---
layout: post
title:  "This Week In LiveCode 203"
date:   2019-11-25 15:30
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

- [WebP-Tool v103](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104922.html)
- [Special Graphic Effects - Kill Performance On Rapid Redraws](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104935.html)
- [browserDocumentLoadComplete working correctly?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104957.html)
- [xpaj-gen infection?]https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104965.html)
- [remove DEFAULTMENUBAR?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104970.html)
- [Help Wrapping HTMLTidy in LCB](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104973.html)
- [macOS, is my app active?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104981.html)
- [DocuSign lib](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg105008.html)


## Updates in the LiveCode open source project

17 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2019-11-18..2019-11-24&type=Issues).



<!---
### New LiveCode releases

- [LiveCode 9.5.1 RC-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104698.html)
--->

### Notable changes

- [libbrowser: Update iOS browser implementation to use WKWebView](https://github.com/livecode/livecode/pull/7222)
- [Update iOS mobile player control to use AVKit framework](https://github.com/livecode/livecode/pull/7218)
- [RevPDFPrinter: Add Android support to revpdfprinter library](https://github.com/livecode/livecode/pull/7201)
- [Fix error when deploying to iOS 13.x simulator](https://github.com/livecode/livecode/pull/7183)
- [Fix abort on error when query contains format specifier](https://github.com/livecode/livecode-thirdparty/pull/138)
- [Fix compilation of SVG ellipses](https://github.com/livecode/livecode/pull/7225)

<!---
### Bug of the week

- [Bug 22447 - mouseDoubleUp sent to wrong control when popup menu is displayed and controls are grouped](https://quality.livecode.com/show_bug.cgi?id=22447)

The reporter provided a detailed description and a helpful sample stack that allowed us to test and confirm the problem quickly. Moreover, he suggested a solution fixes the problem :)
--->

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

- [Brian Milby](https://github.com/bwmilby)
- [macMikey](https://github.com/macMikey)
- [Ralf Bitter](https://github.com/revig)
- *[livecodeian](https://github.com/livecodeian)*  
- *[livecodepanos](https://github.com/livecodepanos)*  
- *[montegoulding](https://github.com/montegoulding)*  
- *[runrevmark](https://github.com/runrevmark)* 



## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [encrypt a standalone html5](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg104934.html)

<!---
## Upcoming events

* [SoCal LiveCode Group Meeting: November 7, Pasadena](http://forums.livecode.com/viewtopic.php?f=50&t=33187)
--->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
