---
layout: post
title:  "This Week In LiveCode 133"
date:   2018-06-18 15:00
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

- [LiveCode 9.0 GM](https://livecode.com/livecode-9-0-gm/)
--->



### Interesting discussions

- [scancodes](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95313.html)
- [Optimization can be tricky](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95319.html)
- [How to use the scale geometry property of an object?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95331.html)
- [Need help with a Datagrid error...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95333.html)
- [Linux Screen Resolution](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95354.html)
- [Close nodes in Tree View widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95355.html)
- [Dark Mode in macOS Mojave, any thoughts from the mothership?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95361.html)
- [Need help with a project](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95371.html)
- [Listfield Questions](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95384.html)
- [LiveCode - Andoid SDK - Java compatibility chart?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95387.html)
- [Calling an api from a stack?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95389.html)
- [Regex (matchChunk) help...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95395.html)
- [Multiple Monitors ; However, LC IDE want a 0,0,X X working rect](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95411.html)
- [merge()](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95422.html)
- [iOS / Android differences on a scrolling list field](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95428.html)
- [Reporting the ScreenSize of a iPhone7: 0,0,375,667](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95438.html)

## Updates in the LiveCode open source project

9 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-06-11..2018-06-17&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 8.1.10](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94867.html) Note 8.1.10 STABLE is the last planned release in the 8.x series.
--->


### Notable changes

- [Add `Clear Recent Files` option to Open Recent File menu](https://github.com/livecode/livecode-ide/pull/1984)
- [Ensure horizontal property of segmented control is saved](https://github.com/livecode/livecode/pull/6580)
- [Ensure option menu works on Android](https://github.com/livecode/livecode/pull/6578)
- [Fix potential crash on relaunch due to uninitialized static variable](https://github.com/livecode/livecode/pull/6575)
- [Android: fix crash on relaunch when calling extension handler from script](https://github.com/livecode/livecode/pull/6574)
- [Ensure true and false names are finalized](https://github.com/livecode/livecode/pull/6571)
- [Use content:// uris to transfer file data to/from other apps](https://github.com/livecode/livecode/pull/6566)


### Bug of the week

- [Bug 21345 - segmented control widget vertical orientation does not work on iOS](http://quality.livecode.com/show_bug.cgi?id=21345)

A user provided useful info, a detailed recipe as well as a helpful sample stack that allowed us to test, confirm and fix the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Docs: Command line installation needs "-ui" instead of "noui" since LC 9 DP-5](https://quality.livecode.com/show_bug.cgi?id=21340)
- (Easy) [Dictionary: revOpenDatabase("sqlite"...) doesn't work on some Linux versions with LC9 - needs gcc4.9](https://quality.livecode.com/show_bug.cgi?id=21270)
- (Easy) [Dictionary: Unlock Screen documentation has typos/errors and needs to reference "lock screen for visual effect"](https://quality.livecode.com/show_bug.cgi?id=21312)
- (Easy) [Dictionary: Mention that in ReplaceText function you might need to escape RegExp metacharacters, if the "replacementString" is the char itself (e.g. ".")](http://quality.livecode.com/show_bug.cgi?id=20943)
- (Easy) [Dictionary: Improve documentation for launch URL & specialFolderPath for Android](http://quality.livecode.com/show_bug.cgi?id=20722)
- (Easy) [Dictionary: Mention that iPhone X does not support "portrait upside down" orientation](http://quality.livecode.com/show_bug.cgi?id=20640)
- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [MouseEnter / MouseLeave infinite Loop trap - documentation enhancement](http://quality.livecode.com/show_bug.cgi?id=20529)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Applescript "do script" missing from standalone](http://quality.livecode.com/show_bug.cgi?id=20993)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- [Charles Warwick](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*



## Other LiveCode News

<!--
This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Strange error from iOS Standalone Builder](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94976.html)
- [mergDoc - no preview, no sharing](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95026.html)
-->


## Upcoming events

* [5th of July : SoCal LiveCode Group meetup - Pasadena](http://forums.livecode.com/viewtopic.php?f=50&t=31125)

* [LiveCode Global: 12 Months Streamed Live Around the Globe - Running every 2nd month throughout 2018!](https://livecode.com/global/) 

Save the dates:

- 19th of July 2018
- 20th of September 2018
- 15th of November 2018

* [The next LiveCode Conference is in...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94801.html)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
