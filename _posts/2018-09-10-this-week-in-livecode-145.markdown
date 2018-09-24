---
layout: post
title:  "This Week In LiveCode 145"
date:   2018-09-10 14:00
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

- [Android install on Lollypop 9.01 rc2](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97590.html)
- [Play YouTube in Portrait and Turn Landscape](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97601.html)
- [Timezone library - how to use in Livecode Server?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97605.html)
- [3WDevolution question](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97607.html)
- [Slow LC 9 Performance - Test Stack, Video, QA Report](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97617.html)
- [PreOpenBackground Messages](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97618.html)
- [Stacks in Memory](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97637.html)
- [Project Browser - refresh button still not available](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97641.html)
- [Another Tree View Oddity](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97657.html)
- [Sample Stacks](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97670.html)
- [Is "6. " equal to "6."?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97685.html)
- [The Visible Hilited Line of a Datagrid](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97720.html)
- [Script Editor Magic Keys](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97727.html)
- [Using RevMail in Server?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97779.html)
- [Datagrid deleteline vs deletelines issue](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97787.html)
- [Livecode's CEF Builds](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97789.html)
- [unknown C++ exception error when launching iOS simulator](http://forums.livecode.com/viewtopic.php?t=31488&p=171178#p171178)

## Updates in the LiveCode open source project

3 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-09-03..2018-09-09&type=Issues).


### New LiveCode releases

- [LiveCode 9.0.1 RC-3](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97589.html)



### Notable changes

- [Remove AutoLock from AddTextToItem](https://github.com/livecode/livecode/pull/6673)
- [Ensure arrays with comma in the key name can be displayed in the variable viewer](https://github.com/livecode/livecode-ide/pull/1997)
- [Move clear before creation of clipboard item](https://github.com/livecode/livecode/pull/6672)


### Bug of the week

- [Bug 21562 - DragImage not shown in a drag and drop operation in Windows](http://quality.livecode.com/show_bug.cgi?id=21562)

The user provided a helpful stack and a detailed recipe that allowed us to test, confirm and fix the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [LCB docs: include the list of blend modes in the Dictionary](https://quality.livecode.com/show_bug.cgi?id=21572)
- (Easy) [Documentation: libraryStack summary missing 'startUsing' at end of sentence](https://quality.livecode.com/show_bug.cgi?id=21556)
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
- (Medium) [Relayer control crashes livecode](https://quality.livecode.com/show_bug.cgi?id=21460)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)
- (Hard) [Case insensitive matchText returns incorrect result](https://quality.livecode.com/show_bug.cgi?id=15312)


### Contributors this week

- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [mergButton - transparent image possible?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97737.html)



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
