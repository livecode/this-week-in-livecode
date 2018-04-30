---
layout: post
title:  "This Week In LiveCode 126"
date:   2018-04-30 14:00
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

- [Any feedback for InstaMaker or WinSignHelper?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94069.html)
- [Contributing to the IDE](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94077.html)
- [filename in standalones for Mac - changed recently?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94089.html)
- [How to get the line break char?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94093.html)
- [Posting to LiveCode Server](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94094.html)
- [xaLib - library to extract data from an array](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94103.html)
- [LC PDF Viewer](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94111.html)
- [OpenLanguage: abstract syntax trees](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94130.html)
- [Has Anyone Got A Directory "Walker" Available](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94133.html)
- [Android assistance / information?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94134.html)
- [some thoughts on version 9.0.0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94135.html)
- [Search a multidimensional array](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94178.html)
- [Title Case](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94194.html)
- [Get only Pathname of a dragdropped Object](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94205.html)
- [Typesetting Fields](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94212.html)
- [macOS "Recovered files"](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94245.html)
- [Building for Android in v9](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94265.html)
- [Open printing to PDF error](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94267.html)
- [Q on Accessing multi-dimension arrays](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94270.html)
- [Enable/disable Group enables/disables all children](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94282.html)
- [Detailed File Information for One File](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94316.html)
- [Splitting long elements into two lines in an Option Menu](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94319.html)
- [Hex to Decimal 2s Complement](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94326.html)
- [create widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94349.html)
- [Identifying IDE stacks](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94356.html)
- [Down a leafy lane or up queer street?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94372.html)
- [Telling the IDE to build a standalone under script control](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94376.html)



## Updates in the LiveCode open source project

22 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-04-16..2018-04-29&type=Issues).



### New LiveCode releases

- [LiveCode 8.1.10 RC-1](https://downloads.livecode.com/livecode/#8_1_10)



### Notable changes

- [Add show documentation to extension context menu](https://github.com/livecode/livecode-ide/pull/1967)
- [Fix deselection of next find after replace](https://github.com/livecode/livecode-ide/pull/1966)
- [Only post hiliteChanged when value actually changes](https://github.com/livecode/livecode/pull/6486) Thanks @BrianMilby
- [Fix revMail on mobile](https://github.com/livecode/livecode-ide/pull/1960)
- [Ensure Replace history is remembered](https://github.com/livecode/livecode-ide/pull/1957)
- [Make sure emscripten behaviors are resolved](https://github.com/livecode/livecode/pull/6471)
- [Execute msg box if it compiles](https://github.com/livecode/livecode-ide/pull/1948)


### Bug of the week

- [Bug 21219 - Setting liststyle of selectecLines affects lines that aren't selected](http://quality.livecode.com/show_bug.cgi?id=21219)

The reporter provided useful info, a detailed recipe as well as a helpful sample stack that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Dictionary: Example of revQueryDatabase is incorrect](https://quality.livecode.com/show_bug.cgi?id=21234)
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
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [mergAccessory](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94136.html)
- [mergBLE usage](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94207.html)
- [Mac app code signing for beginners](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94306.html)
- [Scott Rossi and TactileMedia](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94375.html)



## Upcoming events

* [LiveCode Global: 12 Months Streamed Live Around the Globe - Running every 2nd month throughout 2018!](https://livecode.com/global/) 

Save the dates:

- 17th of May 2018
- 19th of July 2018
- 20th of September 2018
- 15th of November 2018


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
