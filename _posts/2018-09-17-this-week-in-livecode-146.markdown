---
layout: post
title:  "This Week In LiveCode 146"
date:   2018-09-17 14:00
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

- [Develop Yourself Video Competition Winner Announced](https://livecode.com/develop-yourself-video-competition-winner-announced/)
--->

### Interesting discussions

- [Navigator 6.2 alpha 1 is out](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97846.html)
- [Internet Date Service test](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97908.html)
- [Calendar Widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97852.html)
- [Datagrid dgData bug](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97859.html)
- [Answer & Ask dialogs in Windows Standalones](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97868.html)
- [LiveCode 6.7.11 and OSX Mojave](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97881.html)
- [LC 9.0.1 Stable Redraw Problem](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97895.html)
- [SVG to image](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97932.html)
- [LiveCode Multi-Search](http://forums.livecode.com/viewtopic.php?t=31504&p=171301#p171301)
- [Collapse and expand Tree View Widget from code](http://forums.livecode.com/viewtopic.php?f=9&t=31493&p=171391#p171391)

## Updates in the LiveCode open source project

12 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-09-10..2018-09-16&type=Issues).


### New LiveCode releases

- [LiveCode 9.0.1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97854.html)



### Notable changes

- [Fix tree View Widget hilitedElement execution error](https://github.com/livecode/livecode/pull/6675)
- [Ensure graphics can be reshaped more than once for Object menu](https://github.com/livecode/livecode-ide/pull/1996)
- [Retain mouse focus when taking snapshot](https://github.com/livecode/livecode/pull/6652)
- Dozens of Dictionary fixes, including fixing broken links, adding missing text, adding important notes. Thank you @livecodesam


### Bug(s) of the week

- [Bug 21580 - Properties Inspector ->fields -> contents tab -> "show grid" does not toggle](http://quality.livecode.com/show_bug.cgi?id=21580)

The reporter provided a detailed recipe as well as a suggested fix that allowed us to test and confirm the problem quickly.

- [Bug 21581 - clipboardData["styledText"] data loss in some circumstances](http://quality.livecode.com/show_bug.cgi?id=21581)

The reporter provided a detailed recipe as well as a simple sample stack that isolated the problem which allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:


- (Easy) [Docs: Command line installation needs "-ui" instead of "noui" since LC 9 DP-5](https://quality.livecode.com/show_bug.cgi?id=21340)
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
- (Medium) [Relayer control crashes livecode](https://quality.livecode.com/show_bug.cgi?id=21460)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)
- (Hard) [Case insensitive matchText returns incorrect result](https://quality.livecode.com/show_bug.cgi?id=15312)


### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Remote Debugger Anomalies](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97858.html)



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
