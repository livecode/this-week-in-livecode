---
layout: post
title:  "This Week In LiveCode 43"
date:   2016-07-25 10:15
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

### News & blog posts

- [Updates to LiveCode's platform support policy](https://livecode.com/updated-platform-support-policy/)
- [revIgniter v1.9.0 released](http://revigniter.com/news/newsitem/revIgniter_v1.9.0_Released): Includes a new JSON Web Token helper.
- [Update on WordPress/LiveCode coding webinars](http://thread.gmane.org/gmane.comp.ide.revolution.user/228499)

### Interesting discussions

- [How to flip graphics](http://thread.gmane.org/gmane.comp.ide.revolution.user/228531/focus=228534)
- [Fullscreen issues on Mac OS 10.11 and workarounds](http://thread.gmane.org/gmane.comp.ide.revolution.user/228584)
- [LiveCode website and LiveNet plugin](http://forums.livecode.com/viewtopic.php?f=108&t=27610#p144915)

## Updates in the LiveCode open source project

28 pull requests were [merged since the last issue](https://github.com/search?l=&o=asc&s=created&type=Issues&utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-07-18..2016-07-24).

### Notable changes

- [Modify stack file format to allow block offsets to exceed UINT16_MAX](https://github.com/livecode/livecode/pull/4280): A clipboard bug turned out to be a field bug that needs a new 8.1 stack file format to fix!
- [Ensure _mainStacksChanged isn't sent to a deleted stack](https://github.com/livecode/livecode/pull/4286): Fix for many nasty crashes
- [Complete tokenOffset implementation](https://github.com/livecode/livecode/pull/4291)
- [Add ideControlMoved message](https://github.com/livecode/livecode-ide/pull/1285)

### Bug of the week

[Bug 18025 - Widget problems in Ubuntu 16.04](http://quality.livecode.com/show_bug.cgi?id=17905)

This bug is about some problems with widgets, including the browser widget,
found on Ubuntu Linux 16.04.

The reporter was very helpful, both over e-mail and on the bug report.  Because
he made a copy of his Ubuntu virtual machine available to us, we were able to
easily reproduce his bug.  Even better, we were able to use his VM to reproduce
5 other bugs that we were previously unable to, meaning that we are now able to
make some progress with fixing them.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these!

- (Easy) [Enhance the documentation for "the processor"](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Medium) [Improve extension builder to use property metadata when creating the test widget](http://quality.livecode.com/show_bug.cgi?id=18037)
- (Medium) [Make the language-livecode Atom package highlight doc comments differently](https://github.com/peter-b/atom-language-livecode/issues/26)

### Contributors this week

- [asayd](https://github.com/asayd)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*

## Upcoming events

* [2nd-4th August: LiveCode Conference 2016](https://livecode.com/edinburgh-2016/)
* [4th August: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&27600)
* [17th September: Make something cool with LiveCode!](http://www.meetup.com/The-THINQTANQ-Events-Meetups-and-More-in-Plymouth/events/226749341/)
