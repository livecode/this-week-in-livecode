---
layout: post
title:  "This Week In LiveCode 58"
date:   2016-11-07 11:30
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [LiveCode widgets: more line chart madness](https://livecode.com/livecode-widgets-more-line-chart-madness/)
- [revIgniter v1.9.4 released](http://revigniter.com/news/newsitem/revIgniter_v1.9.4_Released)
- The [Hacktoberfest event](https://hacktoberfest.digitalocean.com/) is over!
  Thank you to everybody who took the opportunity to start contributing to the
  LiveCode open source project during October

### Interesting discussions

- [Dealing with multiple stacks with the same name](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80115.html)
- [Getting prompt screen updates in HTML5 standalones](http://forums.livecode.com/viewtopic.php?f=120&t=28263)
- [Computing the convex hull of of a set of points using LCB](http://forums.livecode.com/viewtopic.php?f=93&t=28225#p148177)
- [Loss of access to stacks after "Save As"](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80083.html): It's best not to reference a stack by its filename after it's been loaded into memory

## Updates in the LiveCode open source project

29 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-10-31..2016-11-06&type=Issues&ref=searchresults).

### Notable changes

- [Add support for deploying to the iOS 10.1 simulator](https://github.com/livecode/livecode/pull/4841):
  Because Apple changed the APIs _again_
- [Massively expanded JSON test suite and conformance fixes](https://github.com/livecode/livecode/pull/4815)
- [New spinner widget](https://github.com/livecode/livecode/pull/4793)
- [Update sqlite to version 3.15.0](https://github.com/livecode/livecode-thirdparty/pull/74): Includes FTS5 support

### Bug of the week

[Bug 18628 - Random 'jumping' of LCB path elements](http://quality.livecode.com/show_bug.cgi?id=18689)

This bug was found when the reporter was building a really clever ["polygon
editor" widget](http://forums.livecode.com/viewtopic.php?f=93&t=28020&sid=8bc3c95ee0486303f35b2e98ef0a2a7a#p147467).
When the widget is resized, some of the points in the polygon jump around in a
bizarre way.  The widget demonstrates some very innovative uses of LiveCode
Builder.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) [Add a default script for scroll bars](http://quality.livecode.com/show_bug.cgi?id=17851)
- (Medium) [Teach the Project Browser to show parent behaviours](http://quality.livecode.com/show_bug.cgi?id=18176)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [andrewferguson](https://github.com/andrewferguson)
- [asayd](https://github.com/asayd)
- [seaniepie](https://github.com/seaniepie)
- [techstrategies](https://github.com/techstrategies)
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodemichael](https://github.com/livecodemichael)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*

<!---
## Upcoming events
-->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
