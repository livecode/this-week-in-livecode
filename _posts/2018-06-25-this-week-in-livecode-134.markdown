---
layout: post
title:  "This Week In LiveCode 134"
date:   2018-06-25 15:00
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

- [8.1.10 Reporting the ScreenSize of a iPhone7: 0,0,375,667](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95443.html)
- [Changing backgroundColor of a button changes its style?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95447.html)
- [Must have flexible row height for Datagrid Table](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95460.html)
- [ANN: v2.2 of DB Lib](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95466.html)
- [Sparkle macOS App Updater extension for LC 9 - First Pass](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95486.html)
- [Align baselines of 2 fields](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95488.html)
- [Navbar widget limitations](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95489.html)
- [WordPress REST API's](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95492.html)
- [unicode & umlauts](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95497.html)
- [The results are in](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95512.html)
- [Data in Custom properties](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95535.html)
- [IOS 11.4 -- Stuck](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95543.html)
- [Browser Widget Layer on mobile](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95547.html)
- [Stripping styling from the clipboard...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95558.html)
- [How to get the dimensions of an image with LC server?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95560.html)
- [Translation Service Deepl.com](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95585.html)
- [Top Bottom Left Right](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95592.html)

## Updates in the LiveCode open source project

6 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-06-18..2018-06-24&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 8.1.10](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94867.html) Note 8.1.10 STABLE is the last planned release in the 8.x series.
--->


### Notable changes

- [Accelerated rendering issues](https://github.com/livecode/livecode/pull/6581): This PR fixes 9 long standing bugs, related to acceleratedRendering on Android
- [Fix issue loading mac frameworks](https://github.com/livecode/livecode/pull/6582)
- [Update android compile sdk to API 26](https://github.com/livecode/livecode/pull/6556)

<!---
### Bug of the week

- [Bug 21345 - segmented control widget vertical orientation does not work on iOS](http://quality.livecode.com/show_bug.cgi?id=21345)

A user provided useful info, a detailed recipe as well as a helpful sample stack that allowed us to test, confirm and fix the problem quickly.
--->

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

- *[livecodeali](https://github.com/livecodeali)*
- *[montegoulding](https://github.com/montegoulding)*



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
