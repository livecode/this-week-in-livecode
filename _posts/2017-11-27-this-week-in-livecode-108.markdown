---
layout: post
title:  "This Week In LiveCode 108"
date:   2017-11-27 13:00
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
--->



### Interesting discussions

- [Universal error catching/debugger dropping](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90847.html)
- [Apps or via browser using HTML5](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90874.html)
- [Anyone can confirm laggy IDE on Windows 10?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90884.html)
- [Printing A Browser](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90899.html)
- ["export snapshot" still NOT in 8.1.7?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90905.html)
- [RESTful PUT error](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg90907.html)

## Updates in the LiveCode open source project

28 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-11-20..2017-11-26&type=Issues).


### New LiveCode releases

- [LiveCode 8.1.8 RC-2](https://downloads.livecode.com/livecode/#8_1_8)


### Notable changes

- [Split font name string correctly](https://github.com/livecode/livecode/pull/6163): This fixes a LC-9 regression where custom fonts did not display correctly on retina devices
- [Fix missing launcher icon on Linux](https://github.com/livecode/livecode/pull/6080): Another LC-8.2 regression is now fixed
- [Utilise SB library helpers when building html5](https://github.com/livecode/livecode/pull/6158)
- [Ensure Location Services work on iOS 11+](https://github.com/livecode/livecode/pull/6144)
- [Fill missing glyphs in DroidSansFallback from DroidSans font](https://github.com/livecode/livecode/pull/6147)
- [HTML5: fix issues with libURL encoding/decoding of binary data](https://github.com/livecode/livecode/pull/6143)
- [Fix revDocsParseDescriptionOfEnum continuation parse error](https://github.com/livecode/livecode/pull/6154) Thanks @Brian Milby
- Lots of fixes (regarding invalid links, malformed text) in various dictionary entries in LiveCode 8.2.x. Thanks @livecodesam 


<!---
### Bug of the week


- [Bug 20676 - Scrollbardrag on arrowKeyUp in fields fires twice ](http://quality.livecode.com/show_bug.cgi?id=20676)

The reporter attached a simple and helpful sample stack, and provided useful info and a detailed recipe that helped us to test and confirm the problem quickly.
--->

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Dictionary: Mention that iPhone X does not support "portrait upside down" orientation](http://quality.livecode.com/show_bug.cgi?id=20640)
- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [MouseEnter / MouseLeave infinite Loop trap - documentation enhancement](http://quality.livecode.com/show_bug.cgi?id=20529)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Easy) [Info missing from mobileGetContactData entry](http://quality.livecode.com/show_bug.cgi?id=20359)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [LC8 Dictionary Copy **using cmd+C** only works after Run Tool selected](http://quality.livecode.com/show_bug.cgi?id=17819)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- [Charles Warwick](https://github.com/techstrategies)
- [Devin Asay](https://github.com/asayd)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodemichael](https://github.com/livecodemichael)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Fix various remote debugger issues](https://github.com/livecode/livecode-ide/pull/1832)

<!---
## Upcoming events

* [LiveCode Global: Our Next Conference in Your City](https://livecode.com/livecode-global-our-next-conference-in-your-city/): 48 hours of Conference content streamed live around the globe! Save the last date: 16th of November 2017.
--->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
