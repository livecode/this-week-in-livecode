---
layout: post
title:  "This Week In LiveCode 70"
date:   2017-02-13 10:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [Bernd's alternative dictionary stack, v0.2](http://forums.livecode.com/viewtopic.php?f=67&t=28731&start=30#p151272)
- [Using LiveCode for data visualisation in molecular biology](https://www.facebook.com/groups/livecodeusers/permalink/1245285052177009/)

### Interesting discussions

- [Processing huge images in 32-bit engines](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82367.html)
- [`urlProgress` message incompatibility with Internet library](http://forums.livecode.com/viewtopic.php?f=49&t=28783)
- [Offline PDF viewing inside Android browser widget](http://forums.livecode.com/viewtopic.php?f=53&t=28518)
- [Script-local variables in library stack scripts](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82318.html)
- [Where does the response data from a PUT request end up?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82308.html)

## Updates in the LiveCode open source project

34 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-02-06..2017-02-12&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 8.1.3 rc 2](https://downloads.livecode.com/livecode/#8_1_3)

### Notable changes

- [Make sure ASLR is taken into account on Mac](https://github.com/livecode/livecode/pull/5174):
  Allows LiveCode to be built with the `macosx10.9` SDK, which allows it to be
  built with `libc++`, which permits the use of the C++11 standard library
- Relatedly, [Update Mac builds to use libc++](https://github.com/livecode/livecode/pull/5169)
- [Replace `config.sh` script with Python script](https://github.com/livecode/livecode/pull/5150) and
  [Re-implement some buildbot build steps in Python](https://github.com/livecode/livecode/pull/5160):
  Avoid using `make` or `bash` for builds to make it easier to build on Windows
- [Add access to LCS delimiter local properties to LCB](https://github.com/livecode/livecode/pull/5044):
  You can now use `the line delimiter`, `the row delimiter`,
  `the column delimiter` and `the item delimiter` in LiveCode Builder widgets
  and libraries

<!---
### Bug of the week

[Bug 19209 - bgcolor in text not transferred to the public clipboard](http://quality.livecode.com/show_bug.cgi?id=18970)

On Linux, HTML-formatted styled text placed on the system clipboard doesn't
contain background colour information.  The report contains a clear and
detailed set of steps to reproduce the problem, along with a well-structured
and self-explanatory sample stack.
-->

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
- [techstrategies](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*

<!---
## Upcoming events
-->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
