---
layout: post
title:  "This Week In LiveCode 72"
date:   2017-02-27 12:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [Connecting a Sublime Text project to a Levure application running in the LiveCode IDE](https://www.youtube.com/watch?v=gkVo35Tb3ck) (video)
- [日常英語のようなプログラミング言語で1行ごとに何をやっているか確認しながらコードを書く](http://kenjikojima.com/livecode/anime/):
  LiveCode tutorial in Japanese

### Interesting discussions

- [The `selectedText` for controls without focus](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82589.html):
  Allowing users to select text in fields that they can't edit
- [Squashed Turtles](http://forums.livecode.com/viewtopic.php?f=8&t=28898):
  Richmond implements turtle graphics in LiveCode
- [Dictionary rewrite](http://forums.livecode.com/viewtopic.php?f=67&t=28731):
  Bernd continues to improve his IDE dictionary replacement
- [Can the IDE script editor be improved](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82483.html)

## Updates in the LiveCode open source project

17 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-02-20..2017-02-26&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 9.0-dp-5](https://downloads.livecode.com/livecode/#9_0_0)
- [LiveCode 8.1.3](https://downloads.livecode.com/livecode/#8_1_3)

### Notable changes

- [Enable NFC tag reading on Android](https://github.com/livecode/livecode/pull/5208)
- [Add ability to specify local host/port when opening a socket](https://github.com/livecode/livecode/pull/5198)

### Bug of the week

[Bug 19287 - clickLoc inconsistency between desktop (MacOS) and mobile (iOS)](http://quality.livecode.com/show_bug.cgi?id=19287)

The reporter discovered that `the clickLock` is the location where the mouse
was pressed when running on desktop, and the location where the touch was
released when running on a mobile device.  The problem was extremely
well-explained, and the reporter provided an easy-to-use code sample.

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

- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodemichael](https://github.com/livecodemichael)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesebastien](https://github.com/livecodesebastien)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevelanor](https://github.com/runrevelanor)*
- *[runrevmark](https://github.com/runrevmark)*

## Upcoming events

* [2nd March: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=28882)

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
