---
layout: post
title:  "This Week In LiveCode 66"
date:   2017-01-16 13:15
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

<!---
### News and blog posts
-->

### Interesting discussions

- [Android Keyboard Activation Issue](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81603.html)
- [Array Properties in a Standalone](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81580.html)
- [Documentation on Dispatch](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81570.html)
- [Question about code signing](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81663.html)

## Updates in the LiveCode open source project

24 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-01-09..2017-01-15&type=Issues&ref=searchresults).

<!---
### New LiveCode releases
-->


### Notable changes

- [Local .html files can now be loaded into browser widget on Android](https://github.com/livecode/livecode/pull/5053):
  This bug was caused because of an incorrect path to local assets being passed to browser widget.
- [Fix incorrect behavior of `files()` and `folders()` under some circumstances on Android](https://github.com/livecode/livecode/pull/5033):
  A nasty bug, caused by the evaluation order of conditionals in an `if` statement (see [Short-circuit evaluation](https://en.wikipedia.org/wiki/Short-circuit_evaluation)).
- [Xcode 8.2 / iOS 10.2 support](https://github.com/livecode/livecode/pull/4974)
- [Convert empty in LCS to empty list in LCB](https://github.com/livecode/livecode/pull/5035):
  This patch ensures that when empty is passed to an LCB library handler argument with type List, that the empty list is passed rather than throwing a type conversion error.
- Various fixes to defects detected by Coverity Scan Static Analysis tool.


### Bug of the week

[Bug 19051 -  The endTime of a player can be set to a value greater that the duration](http://quality.livecode.com/show_bug.cgi?id=19051)

The simple and self-explanatory example stack, combined with the detailed recipe in the bug report, nicely demonstrates the problem.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [HedgeHao](https://github.com/HedgeHao)
- [techstrategies](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesebastien](https://github.com/livecodesebastien)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*


## Upcoming events

- [Greater Toronto Area LiveCode Meetup Jan 25, 2017](http://forums.livecode.com/viewtopic.php?t=28620&p=150027#p150027)

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
