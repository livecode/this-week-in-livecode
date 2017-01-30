---
layout: post
title:  "This Week In LiveCode 68"
date:   2017-01-30 11:20
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [Curry Kenworthy](http://livecodeconsulting.com) has made some videos about LiveCode:
  - [How to download LiveCode - find the right version](https://www.youtube.com/watch?v=dEhx3VGhAn)
  - [LiveCode "Fight Night" - How to test computer programming engine performance](https://www.youtube.com/watch?v=6737_kCLOBU)
- [revIgniter v1.9.5 Released](https://revigniter.com/news/newsitem/revIgniter_v1.9.5_Released)

### Interesting discussions

- [Dictionary rewrite - thoughts, please](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82019.html):
  Mike Kerner is starting a new project
- [Not working as expected?](http://forums.livecode.com/viewtopic.php?f=120&t=28406):
  hh's guide to HTML5 standalone troubleshooting
- [Unusual field `backspaceKey` behaviour on Android](http://forums.livecode.com/viewtopic.php?f=53&t=28699)
- [Detecting clicks in the Segmented Control widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81930.html)
- [Text decoding and JSON arrays](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81830.html)


## Updates in the LiveCode open source project

42 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-01-23..2017-01-29&type=Issues&ref=searchresults).

### Notable changes

- [LCB: Implement record type definitions](https://github.com/livecode/livecode/pull/4329):
  It is now possible to define a `record type` in LCB composed of named, typed
  fields.  The syntax for creating and accessing them hasn't been defined yet,
  though.
- [HedgeHao](https://github.com/HedgeHao) fixed some defects on Android:
  - [Fix inconsistent result of `specialFolderPath("resources")`](https://github.com/livecode/livecode/pull/5098)
  - [Disable keyboard suggestion when entering password in Android native input field](https://github.com/livecode/livecode/pull/5102)

### Bug of the week

[Bug 19157 - too many null-bytes hang the debugger](http://quality.livecode.com/show_bug.cgi?id=18970)

When filling a variable with lots of null bytes, i.e. `numToByte(0)`, the
variable pane in the script editor may hang.  The reporter provided very clear
description of the problem, with easy-to-follow steps to reproduce and a
simple and effective sample stack.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) [selectionChanged does not appear in the player object page of the dictionary](http://quality.livecode.com/show_bug.cgi?id=19083)
- (Easy) [Fix format of `mobileControlDo` dictionary entries](http://quality.livecode.com/show_bug.cgi?id=17318)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [HedgeHao](https://github.com/HedgeHao)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*

## Upcoming events

* [2nd February: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=28721)

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
