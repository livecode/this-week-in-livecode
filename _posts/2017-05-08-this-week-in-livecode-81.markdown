---
layout: post
title:  "This Week In LiveCode 81"
date:   2017-05-08 12:00
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

- [Android audio recording library using Java FFI](https://livecode.com/android-audio-recording-library-using-java-ffi/)
-->


### Interesting discussions

- [put x into URL... error on Windows network drive](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84459.html)
- [Calling a livecode executable -ui from LC server and get back a result](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84470.html)
- [http calls blocked by virus protection?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84489.html)
- [looking for a smart approach to "sort" an array](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84491.html)
- [grabbing an SVG?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84559.html)
- [User friendly functions to replace MySQL queries?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84566.html)
- [tsNet and proxy servers](http://forums.livecode.com/viewtopic.php?f=11&t=29206)
  
## Updates in the LiveCode open source project

26 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-05-01..2017-05-07&type=Issues).

<!---
### New LiveCode releases

- [LiveCode 8.1.4-rc-1](https://downloads.livecode.com/livecode/#8_1_4)
-->

### Notable changes

- [New tsNet version](https://github.com/livecode/livecode/pull/5429): Expected in LiveCode 8.1.4 RC2
- [Fix mirrored property on Mac](https://github.com/livecode/livecode/pull/5416): A nasty bug, affecting only OSX 10.11 and above, is now fixed.
- [Defer deletion of script tab](https://github.com/livecode/livecode-ide/pull/1581): A previous "Bug of the Week" is now fixed.
- [Implement mirror property in windows directshow player](https://github.com/livecode/livecode/pull/5412): New feature for the player object on Windows! 
- [Fix inconsistent browser widget callbacks on iOS](https://github.com/livecode/livecode/pull/5408)
- [Allow deletion of a message's target object in a frontscript](https://github.com/livecode/livecode/pull/5413)


### Bug of the week

[Bug 19646 - Using mobile camera kills lockIdleTimer ](http://quality.livecode.com/show_bug.cgi?id=19646)

The reporter attached a very helpful sample stack, and provided a detailed recipe that helped us to test and confirm the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) [selectionChanged does not appear in the player object page of the dictionary](http://quality.livecode.com/show_bug.cgi?id=19083)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [techstrategies](https://github.com/techstrategies)
- [trevordevore](https://github.com/trevordevore)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*

## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [tinyDictionary 0_8_1_0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84455.html): TinyDictionary is a small footprint dictionary for Livecode (version 8.1
and up), developed by Bernd Niggemann.
- [PowerTools 2.0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84449.html): PowerTools is a drop-in plugin replacement for the IDE's built-in tools palette, developed by Mark Wieder.

<!---
## Upcoming events

* [4th May - Pasadena: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=29156)
-->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
