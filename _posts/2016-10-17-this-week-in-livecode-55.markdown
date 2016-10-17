---
layout: post
title:  "This Week In LiveCode 55"
date:   2016-10-17 11:10
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [LiveCode: Yesterday and Today](https://zcast.co/player/jyBjle2QnD): Sarah
  Reichelt and Jerry Daniels talk about the evolution of HyperCard into LiveCode
- [Coding Malaysia](https://livecode.com/coding-malaysia/): Teaching thousands
  of primary school students with LiveCode in the Malaysian Coding@Schools
  program.
- [Updated id3lib library for reading ID3 tags](https://github.com/PaulMcClernan/id3lib)
- [New SVG display widget](http://forums.livecode.com/viewtopic.php?f=93&t=27811&p=147279#p147279)
- [Alternative dictionary stack by MaxV](https://www.facebook.com/groups/livecodeusers/permalink/1139452462760269/)

### Interesting discussions

- [Reliably closing & deleting a stack](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg79385.html)
- [Customising the IDE context menu](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg79295.html)

## Updates in the LiveCode open source project

64 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-10-10..2016-10-16&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 8.1.1-rc-2](https://downloads.livecode.com/livecode/#8_1_1)

### Notable changes

- [Support `defaultNetworkInterface` in `accept`](https://github.com/livecode/livecode/pull/4751):
  You can open a server socket that only listens on a specific network interface
- [Segmented control fill was bleeding outside of the border](https://github.com/livecode/livecode/pull/4730):
  [@trevordevore](https://github.com/trevordevore) took on one of the "help
  needed" bugs
- Loads more dictionary documentation improvements from
  [@asayd](https://github.com/asayd) and
  [@seaniepie](https://github.com/seaniepie)

### Bug of the week

[Bug 18578 - Certain Gray Colornames variants throw an error when used](http://quality.livecode.com/show_bug.cgi?id=18578)

This bug occurred because of a subtle bug in the C++ source code for colour
names: the names were listed in the "correct" order (`Gray99` before `Gray100`),
but in order for the engine to work properly they need to be listed in
_lexicographic_ order (i.e. `Gray1`, `Gray10`, `Gray100`, `Gray11` etc.)

The test stack provided by the bug reporter was very simple, effective and
self-explanatory, and came with a very good set of steps to reproduce the bug.
The steps gave clear results that indicated _exactly_ where the the problem was.

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
- [seaniepie](https://github.com/seaniepie)
- [trevordevore](https://github.com/trevordevore)
- *[livecodepanos](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*

<!--
## Upcoming events
-->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
