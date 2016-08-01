---
layout: post
title:  "This Week In LiveCode 44"
date:   2016-08-01 10:45
categories: issue
---

Welcome to *This Week in LiveCode*!  [LiveCode](https://livecode.com/) is a
high-level language with an easy-to-learn English-like syntax.  This is a
weekly summary of what's been going on in the LiveCode open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).
Want to get involved?
[We welcome contributions](https://github.com/livecode/livecode).

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).

This week's edition was edited by [peter-b](https://github.com/peter-b) and
[livecodepanos](https://github.com/livecodepanos).

## Updates from the LiveCode open source community

The [LiveCode Conference 2016](https://livecode.com/edinburgh-2016/) is in
Edinburgh this week -- and if you're not there in person, don't forget that you
can follow along on the [live stream](https://livecode.com/edinburgh-2016/livestream-bundle/).

### Interesting discussions

We're unable to use the GMane mailing list archive for the discussion links
this week.  The sole maintainer of GMane is
[suffering from burnout](https://lars.ingebrigtsen.no/2016/07/28/the-end-of-gmane/)
and has taken the web frontend offline
[for the foreseeable future](https://lars.ingebrigtsen.no/2016/07/28/the-end-of-gmane/comment-page-1/#comment-13502).

- [A DataGrid is not a spreadsheet](http://lists.runrev.com/pipermail/use-livecode/2016-July/229461.html): ...but can be used like one
- [When is openStack sent on mobile?](http://lists.runrev.com/pipermail/use-livecode/2016-July/229440.html)

## Updates in the LiveCode open source project

21 pull requests were [merged since the last issue](https://github.com/search?l=&o=asc&s=created&type=Issues&utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-07-25..2016-07-31).

### New LiveCode releases

- [LiveCode 8.1.0-dp-3](https://downloads.livecode.com/livecode/#8_1_0)
- [LiveCode 8.0.2-rc-4](https://downloads.livecode.com/livecode/#8_0_2)

### Notable changes

- [Remove use of infinity from revIDEIsFilesetStale](https://github.com/livecode/livecode-ide/pull/1292): It turns out that "infinity" isn't actually treated as a number on all platforms
- [Fix data grid refresh button in the Property Inspector](https://github.com/livecode/livecode-ide/pull/1289)

### Bug of the week

[Bug 18068 - HTML encoding of high-numbered Unicode characters with two codeunits](http://quality.livecode.com/show_bug.cgi?id=18068)

This e-mail is about an html encoding problem with the field, where the
**htmlText** of a field that contains codepoints that aren't in the Basic
Multilingual Plane get encoded with two HTML entities rather than one.

This is the bug of the week this week because it has an amazing sample stack
that clearly demonstrates the problem, and because the report contains lots of
hints, observations and comparisons that clearly indicate where the problem
lies.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these!

- (Easy)  [Make the background colour of the script editor handler list the same as the background colour of the script editor](http://quality.livecode.com/show_bug.cgi?id=17946)
- (Medium) [Add an "Open Recent Script" menu to the script editor menus](http://quality.livecode.com/show_bug.cgi?id=17975)
- (Medium) [Add the ability to select text or icon separately for each action in a header bar widget](http://quality.livecode.com/show_bug.cgi?id=17913)

### Contributors this week

- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*

## Upcoming events

* [2nd-4th August: LiveCode Conference 2016](https://livecode.com/edinburgh-2016/)
* [4th August: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&27600)
* [17th September: Make something cool with LiveCode!](http://www.meetup.com/The-THINQTANQ-Events-Meetups-and-More-in-Plymouth/events/226749341/)
