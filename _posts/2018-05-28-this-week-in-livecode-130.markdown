---
layout: post
title:  "This Week In LiveCode 130"
date:   2018-05-28 14:00
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

- [LiveCode Builder syntax added to LiveCode SublimeText language module](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94842.html)
- [LC ImageToolbox_89_v170](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94843.html)
- [LC & Java](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94847.html)
- [how to clear residual garbage in a stack?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94853.html)
- [Crash when moving video window to external monitor pc](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94857.html)
- [LiveCode Hosting and GDPR](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94863.html)
- [losing font info in fields again](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94879.html)
- [execution doesn't stop when multiple function calls in a line](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94880.html)
- [Should "put" to the Message Box be affected by lockMessages?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94890.html)
- [on-rev choosing engine](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94902.html)
- [Windows 10 and LC9.0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94904.html)
- [Update to SublimeText LiveCode Script linter](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94916.html)
- [Object Referencing in LC 9.0.0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94944.html)
- [group-editing mode](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94946.html)
- [Graphing Solution...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94953.html)
- [Version Control - Script Tracker](http://forums.livecode.com/viewtopic.php?t=31079&p=167618#p167618)


## Updates in the LiveCode open source project

18 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-05-21..2018-05-27&type=Issues).



### New LiveCode releases

- [LiveCode 8.1.10](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94867.html) Note 8.1.10 STABLE is the last planned release in the 8.x series.



### Notable changes

- [Force orientation when setting allowed orientations](https://github.com/livecode/livecode/pull/6499)
- [Dictionary - Turn off search field spell check](https://github.com/livecode/livecode-ide/pull/1969)
- [Make sure scripts are compiled when testing if object handles message](https://github.com/livecode/livecode/pull/6508)
- [Handle wchar_t size differences for ODBC](https://github.com/livecode/livecode/pull/6510)
- [Ensure playrate is respected when looping or when starting player after a pause](https://github.com/livecode/livecode/pull/6527)
- [Fix issue with importing foreign value types that require conversion](https://github.com/livecode/livecode/pull/6539)
- [Ensure .otf font files are recognized on iOS and Android](https://github.com/livecode/livecode/pull/6543)
- Plus tens of fixes in Dictionary entries, including correction of typos, broken links, malformed text etc. Thanks @Sam Norris!



### Bug of the week

- [Bug 21271 - Setting properties of a graphic can cause a crash](http://quality.livecode.com/show_bug.cgi?id=21271)

The reporter provided useful info, a detailed recipe as well as a helpful sample stack that allowed us to test, confirm and fix the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

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
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Is anyone using tsNet external with LCserver?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94956.html)



## Upcoming events

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
