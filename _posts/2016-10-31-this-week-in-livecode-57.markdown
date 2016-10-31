---
layout: post
title:  "This Week In LiveCode 57"
date:   2016-10-31 11:30
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- More LCB examples from [-hh] on the forums:
  [drawing a grid of rectangles](http://forums.livecode.com/viewtopic.php?f=93&t=28020&view=unread&sid=6cb3ca997c4186e543dfaa5485844503#p147913),
  and [listing a range of numbers](http://forums.livecode.com/viewtopic.php?f=93&t=28020&view=unread&sid=6cb3ca997c4186e543dfaa5485844503#p147914)

### Interesting discussions

- [How do I codesign an app?](https://www.mail-archive.com/use-livecode@lists.runrev.com/)
- [Overriding HTTPS certificate verification failure](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg79744.html)

## Updates in the LiveCode open source project

56 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-10-24..2016-10-30&type=Issues&ref=searchresults).

### Notable changes

- Updated versions of libxml, libpng, libgif, libjpeg, libexpat, and libpcre.
- [New OAuth2 authentication library](https://github.com/livecode/livecode/pull/4767)
- [Add support for Xcode 8.1 / iOS 10.1](https://github.com/livecode/livecode/pull/4812)
- [Prevent crash on iOS 10 when the app wants to use the device's microphone](https://github.com/livecode/livecode/pull/4810):
  Caused by a misplaced space character, of all things...
- [Add MCSpan class for wrapping pointer + length pairs](https://github.com/livecode/livecode/pull/4791)

### Bug of the week

[Bug 18689 - Pressing the right arrow key to navigate characters in a paragraph with listStyle set will prematurely jump to next line at end of text style run](http://quality.livecode.com/show_bug.cgi?id=18689)

This bug report describes a keyboard navigation regression in the field.  The
recipe and sample stack make it really easy to reproduce the bug, and the
reporter even included a GIF animation that shows the bug happening.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) [Add a default script for scroll bars](http://quality.livecode.com/show_bug.cgi?id=17975)
- (Medium) [Teach the Project Browser to show parent behaviours](http://quality.livecode.com/show_bug.cgi?id=18176)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [seaniepie](https://github.com/seaniepie)
- [trevordevore](https://github.com/trevordevore)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[montegoulding](https://github.com/montegoulding)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[peter-b](https://github.com/peter-b)*

## Upcoming events

* [3rd November: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=28138)

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
