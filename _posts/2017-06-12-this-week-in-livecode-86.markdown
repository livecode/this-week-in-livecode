---
layout: post
title:  "This Week In LiveCode 86"
date:   2017-06-12 12:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [A cool gauge widget - developed by Bernd Niggemann](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85621.html)


### Interesting discussions

- [64 bit desktop apps](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85518.html)
- [Instantiating Grouped Controls - Templates - Responsive](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85562.html)
- [LC 8.1.4 and Xcode 8.3.3](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85565.html)
- [Changes to Msg Path from LC 7 to 8?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85599.html)
- [Help me test Levure](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85686.html)
- [Word delimiters](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85695.html)
- [Sample Stack for uploading files to a lc server](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85699.html)

  
## Updates in the LiveCode open source project

50 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-06-05..2017-06-11&type=Issues).


### New LiveCode releases

- [LiveCode 8.1.4](https://downloads.livecode.com/livecode/#8_1_4)


### Notable changes

- [Fix pending message object deletion crash](https://github.com/livecode/livecode/pull/5585)
- [Interactive tutorial todo list](https://github.com/livecode/livecode-ide/pull/1615): A new interactive tutorial is added.
- [Fix iOS simulator deployment with Xcode 8.3.3](https://github.com/livecode/livecode/pull/5579)
- [Set the Standard Arch for Mac in the S/B to 64-bit](https://github.com/livecode/livecode-ide/pull/1610)
- [Trigger propertyChanged when text property mutated by script](https://github.com/livecode/livecode/pull/5570)
- [Implement put before msg in Emscripten](https://github.com/livecode/livecode/pull/5557)
- [Fix incorrect text metrics calculation on Mac](https://github.com/livecode/livecode/pull/5548): Another regression caused by the update of Skia library is now fixed.
- [Redesigned iOS Standalone Builder Settings Pane](https://github.com/livecode/livecode-ide/pull/1600): New background modes added, as well as ability to whitelist custom app url schemes.
- [Add support for Android listener callbacks in LCB](https://github.com/livecode/livecode/pull/5534)
- [Fix crash when attempting to set a graphic to have more than 65535 points](https://github.com/livecode/livecode/pull/5526)


### Bug of the week

- [Bug 19814 - hight of menu bar is handled differently](http://quality.livecode.com/show_bug.cgi?id=19814)

The reporter attached a helpful simple sample stack, and provided a detailed recipe that helped us to test and confirm the problem quickly. 

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) [Dictionary entry for compositorType says OpenGL is iOS only](http://quality.livecode.com/show_bug.cgi?id=19496)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- *[livecodealex](https://github.com/livecodealex)*
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevelanor](https://github.com/runrevelanor)*
- *[runrevmark](https://github.com/runrevmark)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Introducing Remote DB Lib, by Andre Garzia](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85505.html)
- [Livecode connect framework](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85641.html)


## Upcoming events

* [LiveCode Global: Our Next Conference in Your City](https://livecode.com/livecode-global-our-next-conference-in-your-city/): 48 hours of Conference content streamed live around the globe! Save the dates:

- 15th of June 2017
- 13th of July 2017
- 17th of August 2017
- 21st of September 2017
- 19th of October 2017
- 16th of November 2017


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
