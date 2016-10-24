---
layout: post
title:  "This Week In LiveCode 56"
date:   2016-10-24 14:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [What's new in LiveCode 9 DP 1?](https://livecode.com/whats-new-in-livecode-9-dp-1/)
- [Using the livecode standalone engine to run script only stacks on a server](http://www.bluemangolearning.com/livecode/2016/10/using-the-livecode-standalone-engine-to-run-script-only-stacks-on-a-server/)
- [revIgniter v1.9.3 released](http://revigniter.com/news/newsitem/revIgniter_v1.9.3_Released)
- [Digital Pomegranate are working on MailChimp and One Signal libraries](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg79639.html)
- [hhPolygon v1.0.0](http://forums.livecode.com/viewtopic.php?f=93&t=28020#p147467):
  A widget that provides an interactive polygon editor

### Interesting discussions

- [`specialFolderPath("resources")` workaround for Windows](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg79661.html):
  Finding a workaround for [bug 18295](http://quality.livecode.com/show_bug.cgi?id=18295)
- Proposals for changing the [tools palette](http://forums.livecode.com/viewtopic.php?f=66&t=28162)
  and [menu bar](http://forums.livecode.com/viewtopic.php?f=67&t=28147):
  Interesting and well-presented ideas for improving the user experience
- [Why doesn't LiveCode 9 work on OS X 10.6?](https://www.facebook.com/groups/livecodeusers/permalink/1155001781205337/)
- [When does iOS Application Transport Security block HTTPS connections](http://quality.livecode.com/show_bug.cgi?id=18645):
  Diagnosing web servers with misconfigured or outdated SSL configuration

## Updates in the LiveCode open source project

56 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-10-17..2016-10-23&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 8.1.1](https://downloads.livecode.com/livecode/#8_1_1)
- [LiveCode 9.0 dp 1](https://downloads.livecode.com/livecode/#9_0_0)

### Notable changes

- [Re-write the LCB VM](https://github.com/livecode/livecode/pull/4464):
  [@runrevmark](https://github.com/runrevmark) and
  [@livecodefraser](https://github.com/livecodefraser) have completely reworked
  the LiveCode Builder virtual machine to get it ready for the Infinite
  LiveCode project.
- [Document `the scriptExecutionErrors`](https://github.com/livecode/livecode/pull/4765):
  [@asayd](https://github.com/asayd) documented this useful IDE-only global
  property
- [Replace `revSetEdited` with `revIDESetEdited`](https://github.com/livecode/livecode/pull/4745):
  Improved API for flagging stacks in the IDE as changed and requiring a save.

### Bug of the week

[Bug 18549 - `lock cursor` doesn't work in LiveCode 8+](http://quality.livecode.com/show_bug.cgi?id=18578)

This bug report is about some problems with the `lock cursor` command, which
stopped working in the IDE in LiveCode 8.  The stack is very simple to
understand and easy to use when replicating the bug.  The reporter spent some
time testing in older versions on LiveCode, and kindly saved the test stack in
5.5 format to help the dev team reproduce his results easily.

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

- [asayd](https://github.com/asayd)
- [Brahmanathaswami](https://github.com/Brahmanathaswami)
- [PaulMcClernan](https://github.com/PaulMcClernan)
- [seaniepie](https://github.com/seaniepie)
- [trevordevore](https://github.com/trevordevore)
- *[livecodepanos](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*

## Upcoming events

* [3rd November: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=28138)

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
