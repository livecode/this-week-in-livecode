---
layout: post
title:  "This Week In LiveCode 221"
date:   2020-04-13 15:30
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

- [Who else doesn't want auto-select when opening a card?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107052.html)
- [Apps to fight COVID-19](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107075.html)
- [Building a Board Game](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107089.html)
- [LC Android deployment working on Windows 10 under ARM64](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107111.html)
- [Video format for mobile](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107129.html)
- [Umlauts (again) and arraytojson](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107145.html)
- [Mobile screen sizes - another naive question](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107155.html)
- [Livecode and AWS Sql](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107200.html)
- [WebDAV library for LC community available which does not depend on tsNet](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107283.html)
- [What is a token](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107286.html)
- [MP3s](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107312.html)
- [LC equivalent of php utf8_encode and utf8_decode?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107344.html)
- [Getting started with Java bindings](http://forums.livecode.com/viewtopic.php?t=33882&p=189869#p189869)
- [Linking Xcode and Livecode](http://forums.livecode.com/viewtopic.php?t=33878&p=189840#p189840)
- [Missing required architecture arm64](http://forums.livecode.com/viewtopic.php?f=49&t=33887&p=190162#p190162)
- [build apps for ios13.3](http://forums.livecode.com/viewtopic.php?f=19&t=33893&p=190163#p190163)
- [External Dev Kit vs LiveCode Builder](http://forums.livecode.com/viewtopic.php?t=33912&p=190123#p190123)
- [Copying standalone iOS app onto an iPad](http://forums.livecode.com/viewtopic.php?t=33917&p=190145#p190145)
- [Sending smtp email on android device](http://forums.livecode.com/viewtopic.php?t=33919&p=190154#p190154)

## Updates in the LiveCode open source project

10 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2020-04-06..2020-04-12&type=Issues).

<!--
### New LiveCode releases

- [Release 9.6.0 DP-3](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg106553.html)
-->

### Notable changes

- [Fix bug preventing JS execution in Android browser](https://github.com/livecode/livecode/pull/7318)
- [Add support for front camera in Android mobilePickPhoto](https://github.com/livecode/livecode/pull/7314)
- [Implement system appearance support](https://github.com/livecode/livecode/pull/7298)
- [Ensure multiple queued requests are handled correctly](https://github.com/livecode/livecode/pull/7280)
- [Fix crash when opening and closing modal windows](https://github.com/livecode/livecode/pull/7232)
- [Navigation Bar: Add option to highlight none of the icons](https://github.com/livecode/livecode/pull/6404)


### Bug of the week

- [Bug 22662 - Script editor Find & Replace fails to find proper matches using regex pattern option](https://quality.livecode.com/show_bug.cgi?id=22662)

The reporter provided a detailed recipe and a helpful sample stack that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop` branch

Then try one of these:

- (Easy) [Dictionary: more examples for IF entry in Dictionary](https://quality.livecode.com/show_bug.cgi?id=22589)
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
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*  


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [ANN: glx2 script editor 4.0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107047.html)
- [Another Apple iOS Deadline](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107159.html)
- [iOS TextToSpeech extension for free](http://forums.livecode.com/viewtopic.php?t=33895&p=189960#p189960)
- [Demo DropBox Library (LC 9)](http://forums.livecode.com/viewtopic.php?t=33901&p=190011#p190011)

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
