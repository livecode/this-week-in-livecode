---
layout: post
title:  "This Week In LiveCode 61"
date:   2016-11-28 12:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [What's new in LiveCode 9.0 DP 2?](https://livecode.com/whats-new-in-livecode-9-0-dp-2/)
- [Control your webpage with LiveCode HTML5](https://livecode.com/control-your-webpage-with-livecode-html5/)
- [Giving thanks to the LiveCode community for their help in solving a pending messages problem](http://learninglivecode.blogspot.com/2016/11/giving-thanks-to-livecode-community-for.html)
- [An HTML5 blackjack game using a REST API](http://forums.livecode.com/viewtopic.php?f=120&t=28396)
- [Transferring data between the browser and an HTML5 standalone](http://forums.livecode.com/viewtopic.php?f=120&t=25210#p148867)

### Interesting discussions

- [External communication for HTML5 standalones](http://forums.livecode.com/viewtopic.php?f=120&t=28353)
- [JavaScript + LC HTML5 = LiveCode.js](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80583.html)
- [Stopping accepting socket connections](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80534.html)
- [Typing at an angle](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80448.html)

## Updates in the LiveCode open source project

19 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-11-21..2016-11-27&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 9.0.0 dp 2](https://downloads.livecode.com/livecode/#9_0_0)

### Notable changes

- [Support for adding icon and splash screen for iPad Pro 12.9](https://github.com/livecode/livecode/pull/4917)
- [Allow any delimiter in card/group/control names](https://github.com/livecode/livecode-ide/pull/1490):
  You can no longer break the Project Browser by giving a control a name
  containing a tab character
- [Fix a crash on saving field data under obscure circumstances](https://github.com/livecode/livecode/pull/4907):
  Some complex stacks could get into a state where saving them would crash the
  engine and corrupt the stack file on disk

### Bug of the week

[Bug 18876 - LiveCode field misbehaves on Android with Google keyboard and Samsung keyboard's predictive text](http://quality.livecode.com/show_bug.cgi?id=18876)

The reporter found a very tricky bug in the LiveCode field in Android apps.  It
appears on Android lollipop devices when predictive text text and/or auto
correction is enabled.  The report is particularly good because it has a clear
and easy-to-follow set of steps to reproduce, and a video of the problem as
well.  This seems to be a long-standing bug which will be exceedingly
challenging to fix.

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
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
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
