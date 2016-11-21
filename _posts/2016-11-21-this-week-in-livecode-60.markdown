---
layout: post
title:  "This Week In LiveCode 60"
date:   2016-11-21 12:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

[LiveCode for FM](https://filemaker.livecode.com/) is a new plugin for FileMaker
that lets you extend FileMaker using LiveCode.  Some of the components of
LiveCode for FM, including the OAuth2 authentication library, are being
integrated into the LiveCode open source project.

- [Quadrilateral perspective distortion in LiveCode](http://forums.livecode.com/viewtopic.php?f=76&t=19248&start=75#p148647)
- [Free simple tool for creating keystore file for Android deployment](http://forums.livecode.com/viewtopic.php?f=53&t=28322)

### Interesting discussions

- [How should the savingStandalone message work?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80311.html)
- [Swipe gestures on a mobile scroller](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80439.html)

## Updates in the LiveCode open source project

39 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-11-14..2016-11-20&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 8.1.2 rc 2](https://downloads.livecode.com/livecode/#8_1_2)

### Notable changes

- [Re-add support for BMPs as a clipboard image format](https://github.com/livecode/livecode/pull/4897)
- Many of this weeks changes fix crashes revealed by the recent object handle
  improvements, released in LiveCode 8.1.2-rc-1.

### Bug of the week

[Bug 18867 - Line graph widget doesn't parse empty datapoints correctly](http://quality.livecode.com/show_bug.cgi?id=18867)

The line graph widget, introduced in LiveCode 8, has problems when some of the
data points have empty values (not zero; points were no datum is available). The
reporter provided an excellent recipe to reproduce the bug, which was clearly
explained and very reliable, along with screenshots to illustrate the problem.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) [Add a default script for scroll bars](http://quality.livecode.com/show_bug.cgi?id=17851)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [angerangel](https://github.com/angerangel)
- [asayd](https://github.com/asayd)
- [BerndN](https://github.com/BerndN)
- [seaniepie](https://github.com/seaniepie)
- [trevordevore](https://github.com/trevordevore)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[peter-b](https://github.com/peter-b)*

## Upcoming events

* [1st December: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=28320)

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
