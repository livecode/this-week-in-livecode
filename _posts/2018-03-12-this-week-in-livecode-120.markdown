---
layout: post
title:  "This Week In LiveCode 120"
date:   2018-03-12 14:00
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

- [Functional features in LiveCode – is it just a dream?](https://livecode.com/functional-features-in-livecode-is-it-just-a-dream/)
--->



### Interesting discussions

- [Trace_to_SVG](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93254.html)
- [Forcing a device update](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93276.html)
- [Slide puzzle question](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93289.html)
- [Issues with storage of data in stack](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93294.html)
- [Standalone compile problem including more than two stack files to the mainstack](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93295.html)
- [how to copy a card?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93298.html)
- [Saving stack locations in multi monitor setups](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93334.html)
- [Bizarre Number Sort of Files Mac](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93337.html)
- [Unicode inconsistency](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93340.html)
- [Callbacks fail](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93363.html)
- [New Game By Fasasoftware - Apple Toe](http://forums.livecode.com/viewtopic.php?t=30719&p=164837#p164837)


## Updates in the LiveCode open source project

44 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-03-05..2018-03-11&type=Issues).

<!---
### New LiveCode releases

- [LiveCode 8.1.9](https://downloads.livecode.com/livecode/#8_1_9)
--->


### Notable changes

- [Fix linux fullscreen window manager issues](https://github.com/livecode/livecode/pull/6392)
- [Ensure malloc'd pointer is not incremented before free](https://github.com/livecode/livecode/pull/6377)
- [Use local frame for interface proxy creation](https://github.com/livecode/livecode/pull/6369): This fixes a crash when more than 6 Android native fields are present in a card.
- [Use PAC file found via WPAD protocol to resolve proxy server settings for url requests](https://github.com/livecode/livecode/pull/6354) Thank you @trevordevore
- [Fix print to pdf](https://github.com/livecode/livecode/pull/6335): A recent regression is now fixed.
- [Add a time zone handling library](https://github.com/livecode/livecode/pull/6327)
- [Fix Segmented Control perimeter when it has one segment](https://github.com/livecode/livecode/pull/6381)
- [Send touch messages when scroller disabled](https://github.com/livecode/livecode/pull/6372): This fixes a DataGrid2 issue on Android, where you had to swipe twice when a native scroller was present.
- [Ensure missing extension produces warning](https://github.com/livecode/livecode/pull/6370)
- [Add support for Local Storage to Android browser](https://github.com/livecode/livecode/pull/6362)
- [Fix handling of binary URL data in HTML5](https://github.com/livecode/livecode/pull/6394)

<!---
### Bug of the week

- [Bug 21022 - IDE Search doesn't look in grouped groups](http://quality.livecode.com/show_bug.cgi?id=21022)

The reporter provided useful info, a detailed recipe as well as a helpful sample stack that allowed us to test, confirm and fix the problem quickly.
--->

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

- [Trevor DeVore](https://github.com/trevordevore)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodemiriam](https://github.com/livecodemiriam)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [tsNet documentation](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93286.html)
- [tsNet and Digest Authentication - some problems or better said: missing knowledge](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93301.html)



## Upcoming events

* [LiveCode Global: 12 Months Streamed Live Around the Globe - Running every 2nd month throughout 2018!](https://livecode.com/global/) 

Save the dates:

- 15th of March 2018
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
