---
layout: post
title:  "This Week In LiveCode 143"
date:   2018-08-27 14:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community


### News & blog posts

- [Develop Yourself Video Competition Winner Announced](https://livecode.com/develop-yourself-video-competition-winner-announced/)



### Interesting discussions

- [Navigator 6.1 alpha1 is out](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97182.html)
- [revNavigator - Cloning a card - am I doing something wrong?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97190.html)
- [editing & combining sound files?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97250.html)
- [Set the backgroundcolor of all lines a field to null](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97252.html)
- [Best way to store videos](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97274.html)
- [Recommend Directory for Installation of Windows Apps](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97268.html)
- [What happened to the LC 9 UI font?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97291.html)
- [LC displaying colors incorrectly in macOS 10.13](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97294.html)
- [Android permissions](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97311.html)
- [Load data into a tree view](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97314.html)
- [iPad Pro Simulator](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97336.html)
- [Datagrid Scrolling](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97343.html)
- [Word counter crashing LiveCode?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97346.html)
- [Mojave beta & 32 bit LC](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97355.html)
- [LC-ImageToolbox_v185](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97382.html)
- ["Make Docset" updated to version 2.8](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97386.html)


## Updates in the LiveCode open source project

17 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-08-20..2018-08-26&type=Issues).

6 of them were submitted by @BrianMilby - Thanks Brian :)


### New LiveCode releases

- [LiveCode 9.0.1 RC-2](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97235.html)



### Notable changes

- [Automatically select text of fields in PI](https://github.com/livecode/livecode-ide/pull/1991)
- [Add multiple android archs to IDE](https://github.com/livecode/livecode-ide/pull/1990)
- [Fix crash when moving a group before calling quit](https://github.com/livecode/livecode/pull/6649)
- [Tree widget - prevent value removal on key addition](https://github.com/livecode/livecode/pull/6643)
- [Add color to the clock widget](https://github.com/livecode/livecode/pull/6638)
- [Allow scroll wheel to work in PI text fields](https://github.com/livecode/livecode-ide/pull/1989)
- [LCB: Implement key is down](https://github.com/livecode/livecode/pull/6537)
- [Icon Picker: Use a popup stack for icon property](https://github.com/livecode/livecode-ide/pull/1975)
- [Script Editor indent errors with inline block comments ](https://github.com/livecode/livecode-ide/pull/1971)


### Bug of the week

- [Bug 21500 - Grouping Controls, then Dragging the Resulting Group, Prevents a Mac Standalone from Closing Properly](http://quality.livecode.com/show_bug.cgi?id=21500)

The user provided a helpful stack and a detailed recipe that allowed us to test, confirm and fix the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [typo in 9.0 release notes "closesstack" instead of "closestack"](https://quality.livecode.com/show_bug.cgi?id=21529)
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

- [andrewferguson](https://github.com/andrewferguson)
- [Brian Milby](https://github.com/bwmilby)
- [Gregory Miller](https://github.com/madpink)
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevelanor](https://github.com/runrevelanor)*


## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [For those who do not know lcTasklist](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97183.html)
- [ANN: DGH 2.5.1 is released](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97223.html)
- [Binary Rejected!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97286.html)

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
