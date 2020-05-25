---
layout: post
title:  "This Week In LiveCode 227"
date:   2020-05-25 15:30
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

- [Our Next Community Zoom Meeting](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108032.html)
--->

### Interesting discussions

- [Linking to a LC desktop app with a URL](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108069.html)
- [Changing text properties in a field via the IDE](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108038.html)
- [Drawing a blank on simple code...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108048.html)
- [Mouse messages in scrollers](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108049.html)
- [Obtaining URL to latest Stable LC Server](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108065.html)
- [ANN: glx2 script editor 4.1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108086.html)
- [Saving stacks before closing](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108113.html)
- [Get FileList on Remote PC via SFTP](http://forums.livecode.com/viewtopic.php?f=11&t=34143)
- [MacOS - "Adding ad-hoc signature failed with error"](http://forums.livecode.com/viewtopic.php?t=34126&p=191941#p191941)
- [Bayes Calculator for Covid-19](http://forums.livecode.com/viewtopic.php?t=34135&p=191997#p191997)
- [Can LC set an objet to the top layer of a group with script?](http://forums.livecode.com/viewtopic.php?t=34148&p=192098#p192098)

## Updates in the LiveCode open source project

3 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2020-05-19..2020-05-24&type=Issues).


### New LiveCode releases

- [Release 9.6.0 RC-2](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108061.html)


### Notable changes

- [Ensure the externals lcextd folder is not copied into the apk](https://github.com/livecode/livecode/pull/7361)
- [Ensure iOS time picker always returns the displayed time](https://github.com/livecode/livecode/pull/7190)
- [Ensure rewind and fast forward buttons do not affect playrate](https://github.com/livecode/livecode/pull/7108)


### Bug of the week

- [Bug 22727 - [FIX] revPrintText does not keep defaultStack when it's opened as a modal stack](https://quality.livecode.com/show_bug.cgi?id=22727)

The reporter provided a detailed recipe that allowed us to test and confirm the problem quickly, and also suggested a fix.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop-9.6` branch

Then try one of these:

- (Easy) [revPrintText does not keep defaultStack when it's opened as a modal stack](https://quality.livecode.com/show_bug.cgi?id=22727)
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

- *[livecodepanos](https://github.com/livecodepanos)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [iOS Provisioning Profile issue](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108087.html)


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
