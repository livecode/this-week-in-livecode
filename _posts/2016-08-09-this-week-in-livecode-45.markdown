---
layout: post
title:  "This Week In LiveCode 45"
date:   2016-08-09 14:30
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

- [A new community for LiveCode teachers and students](http://forums.livecode.com/viewtopic.php?f=107&t=27728)
- [revIgniter v1.9.1 released](http://revigniter.com/news/newsitem/revIgniter_v1.9.1_Released): Added support for uploading directories (multiple files)
- [The KAGI online purchase system has closed down](http://lists.runrev.com/pipermail/use-livecode/2016-August/229538.html)

### Interesting discussions

- [Topic ideas for LiveCode workshops](http://lists.runrev.com/pipermail/use-livecode/2016-August/229621.html)
- [Why don't arithmetic commands throw an error if the target isn't a number?](http://quality.livecode.com/show_bug.cgi?id=18136)
- [Deploying script-only library stacks into a standalone](http://forums.livecode.com/viewtopic.php?f=49&t=27659)

## Updates in the LiveCode open source project

This was a quiet week from a development point of view -- because everyone was
busy at the conference!

9 pull requests were [merged since the last issue](https://github.com/search?l=&o=asc&s=created&type=Issues&utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-08-01..2016-08-07).

### Notable changes

- [Implement "&" operator for LCB Lists](https://github.com/livecode/livecode/pull/4330)
- Several new contributors made improvements to the dictionary during
  [asayd](https://github.com/asayd)'s workshop on documentation

### Bug of the week

[Bug 18141 - min()/max() functions are not tolerant of poorly formatted number lists](http://quality.livecode.com/show_bug.cgi?id=18141)

This bug is about a list of numbers containing carriage return (CR) characters
not being processed properly by the `min()` and `max()` functions if it contains
a trailing CR.

This is the bug of the week because it has a simple and effective sample stack
that clearly demonstrates the problem; the reporter has made some helpful
comments that indicate where the problem lies; and by testing in LiveCode 6.x he
has helped narrow down what might have caused the problem (probably during the
LiveCode 7 refactoring to support Unicode).

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these!

- (Easy) [Add a default script for scroll bars](http://quality.livecode.com/show_bug.cgi?id=17851)
- (Easy) [Add extra spaces when commenting out script](http://quality.livecode.com/show_bug.cgi?id=8260)
- (Easy) [Add a &lt;Ctrl+Q&gt; shortcut to the Linux script editor](http://quality.livecode.com/show_bug.cgi?id=17435)

### Contributors this week

- [asayd](https://github.com/asayd)
- [beda123](https://github.com/beda123)
- [msiskin](https://github.com/msiskin)
- [Skipis](https://github.com/Skipis)
- *[livecodeali](https://github.com/livecodeali)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*

## Upcoming events

* [17th September: Make something cool with LiveCode!](http://www.meetup.com/The-THINQTANQ-Events-Meetups-and-More-in-Plymouth/events/226749341/)
