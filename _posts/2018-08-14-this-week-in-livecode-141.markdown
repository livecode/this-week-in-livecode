---
layout: post
title:  "This Week In LiveCode 141"
date:   2018-08-14 10:00
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

- [LC Builder and 3rd Part DLLs under Windows](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96674.html)
- [Windows: "not responding"](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96689.html)
- [HTML to text in field](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96760.html)
- [Android and https](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96694.html)
- [Android, local PDF and the Browser Widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96698.html)
- [Re: valueDiff for arrays](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96715.html)
- [LCB Performance](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96722.html)
- [Array converted to text in IDE...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96732.html)
- [Intersect outputs different result in desktop and LC server](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96744.html)
- [A few solutions to problems I had](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96751.html)
- [searching lists.runrev.com](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96752.html)
- [Regaining IDE Efficiency: Property Inspector](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96757.html)
- [stackfiles](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96758.html)
- [Tree View / Custom Properties PI](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96814.html)
- [Writing to SMB Share?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96815.html)
- [Repeat for each element failing](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96831.html)
- [Navigator v 6 is out](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96839.html)
- [Need a little help with image resizing](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96853.html)
- [Android compass question](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96856.html)
- [Resetting waitDepth](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96857.html)
- [Text rendering of Unicode text in LC](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96866.html)
- [How to filter a list with a variable anywhere in a line](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96878.html)
- [LC 9 and Memory](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96898.html)
- [Using stackoverflow.com](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96911.html)
- [stack rect with decorations?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96935.html)
- [My Button Bar](http://forums.livecode.com/viewtopic.php?t=31393&p=170051#p170051)
- [ANN: Calendar Plugin](http://forums.livecode.com/viewtopic.php?t=31390&p=170014#p170014)
- [Multi Threadedness?](http://forums.livecode.com/viewtopic.php?t=31382&p=169929#p169929)


## Updates in the LiveCode open source project

4 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-08-06..2018-08-13&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 9.0.1 RC-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95867.html) Get this new release that includes more than 90 bugfixes and performance improvements.
--->


### Notable changes

- [Recursively sign frameworks in iOS apps](https://github.com/livecode/livecode/pull/6630)
- [Include folders in iOS extension code folders](https://github.com/livecode/livecode/pull/6629)
- [Update ParseStringAsNumber dictionary](https://github.com/livecode/livecode/pull/6627)


<!---
### Bug of the week

- [Bug 21437 - hard crash on backSpaceKey if tab is at the end of line 1](http://quality.livecode.com/show_bug.cgi?id=21437)

The user provided a detailed recipe that allowed us to test and confirm the problem quickly.
--->

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

- [Gregory Miller](https://github.com/madpink)
- [Trevor DeVore](https://github.com/trevordevore)
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Tutorial for MAP widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96771.html)



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
