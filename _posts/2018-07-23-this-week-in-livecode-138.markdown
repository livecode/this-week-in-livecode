---
layout: post
title:  "This Week In LiveCode 138"
date:   2018-07-23 15:00
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

- [Help Support LiveCode - Open Source Needs You](https://mailchi.mp/57bd2132b4ac/support-livecode-open-source)
--->


### Interesting discussions

- [Property inspector / custom properties - how can i resize the value field](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96010.html)
- [iOS and video mirroring](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96032.html)
- [How to create a QR Code Version 14 (73x73modules)](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96042.html)
- [How to refresh LC IDE dictionary after I changed a api.lcdoc file?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96052.html)
- [TextAlign not working in fields](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96055.html)
- [android heads up](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96062.html)
- [LiveCode server IDE - the current state of the art?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96065.html)
- [line 1 of the volumes](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96073.html)
- [drawing a Barcode without a Barcode font](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96076.html)
- [Android, acceleratedRendering and visual effect](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96077.html)
- [Trying to track down the reason for slow downloads](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96092.html)
- [Help with Bug #19550: Add support for symlinks to standalone builder](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96102.html)
- [OAuth2 Library troubleshooting](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96104.html)
- [adding a Shared (Background) Group after the fact](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96149.html)
- [Could not compile service support class - revisited](http://forums.livecode.com/viewtopic.php?t=31307&p=169292#p169292)
- [Unable to build app for testing: apk preparation failed](http://forums.livecode.com/viewtopic.php?f=53&t=31288)


<!---
## Updates in the LiveCode open source project

1 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-07-15..2018-07-22&type=Issues).
--->

<!---
### New LiveCode releases

- [LiveCode 9.0.1 RC-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95867.html) Get this new release that includes more than 90 bugfixes and performance improvements.
--->

<!---
### Notable changes

- [Fix crash in Mac player when changing filename repeatedly in a loop](https://github.com/livecode/livecode/pull/6607)
- [Do not split up .framework folders between MacOS and Resources/_MacOS…](https://github.com/livecode/livecode/pull/6606)
- [Fix crash on resume in commercial android engine](https://github.com/livecode/livecode/pull/6604)
- [Add stereo balance & panning properties to mac player](https://github.com/livecode/livecode/pull/6603)
- [Fix pattern to filter android externals](https://github.com/livecode/livecode/pull/6601)
- [Improve appearance of Motif theme disabled button text / icons](https://github.com/livecode/livecode/pull/6456)
--->


### Bug of the week

- [Bug 21437 - hard crash on backSpaceKey if tab is at the end of line 1](http://quality.livecode.com/show_bug.cgi?id=21437)

The user provided a detailed recipe that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Docs: The first example in mobileSetKeyboardType users an invalid parameter](https://quality.livecode.com/show_bug.cgi?id=21406)
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
- (Hard) [Case insensitive matchText returns incorrect result](https://quality.livecode.com/show_bug.cgi?id=15312)


### Contributors this week

- [Charles Warwick](https://github.com/techstrategies)



## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Autocomplete in 9.0.1 RC1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96111.html)



## Upcoming events

* [LiveCode Global: 12 Months Streamed Live Around the Globe - Running every 2nd month throughout 2018!](https://livecode.com/global/) 

Save the dates:

- 20th of September 2018
- 15th of November 2018

* [The next LiveCode Conference is in...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94801.html)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
