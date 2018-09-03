---
layout: post
title:  "This Week In LiveCode 144"
date:   2018-09-03 14:00
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

- [RE: Best way to store videos](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97397.html)
- [textHeight changing again when copying fields from one stack to another](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97399.html)
- [Datagrid substack question](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97401.html)
- [ImageStatistics_v100](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97410.html)
- [LiveCode 1.6.1 docset now available](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97416.html)
- [XML to File](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97418.html)
- [What do we know about LC 10?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97421.html)
- [Tree View Values](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97423.html)
- [How to get word offset all instances of a string in a chunk of text?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97435.html)
- [am I regexing by mistake?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97470.html)
- [Mobile Rotation Redux](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97462.html)
- [On Performance of Array Access](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97469.html)
- [Deleting a char inside a textField via code](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97477.html)
- [Android Audio Recorder Woes](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97478.html)
- [Missing function selectedWords/selectedTrueWords](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97487.html)
- [Trouble with iOS Logos/No Appearing on Home Screen](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97509.html)
- [Searching for a word when it's more than one word](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97512.html)
- [Chunked Off - replace with empty](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97532.html)
- [startUp messaging hierarchy](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97533.html)
- [ImageHandles_v105](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97538.html)
- [Up to date installation guide for LiveCode community server?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97557.html)
- [ANN: LC Documentation Cache Cleaner](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97561.html)
- [SVGHandles89_v100](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97569.html)

## Updates in the LiveCode open source project

10 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-08-27..2018-09-02&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 9.0.1 RC-2](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97235.html)
--->


### Notable changes

- [Move dragboard rebind to mousedown](https://github.com/livecode/livecode/pull/6662)
- [Include iPadPro splash image in plist file](https://github.com/livecode/livecode/pull/6655)
- [Ensure pageRanges and pageHeights return correct results](https://github.com/livecode/livecode/pull/6637)
- [Document "number of elements of tArray"](https://github.com/livecode/livecode/pull/6634)
- [Extensions: Add support for snippets and sample stacks](https://github.com/livecode/livecode-ide/pull/1985)


### Bug of the week

- [Bug 21532 - Drag and Drop Functionality not working with LC versions 9.01 rc1 and rc2 on Mac](http://quality.livecode.com/show_bug.cgi?id=21532)

The user provided a helpful stack and a detailed recipe that allowed us to test, confirm and fix the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

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

- [Brian Milby](https://github.com/bwmilby)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News

<!---
This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [For those who do not know lcTasklist](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97183.html)
- [ANN: DGH 2.5.1 is released](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97223.html)
- [Binary Rejected!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97286.html)
--->

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
