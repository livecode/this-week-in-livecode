---
layout: post
title:  "This Week In LiveCode 62"
date:   2016-12-05 11:15
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

* [Some exciting HTML5 demos for LiveCode 9 DP 3](https://livecode.com/some-exciting-html5-demos-for-livecode-9-dp-3/)
* [LiveCode Widgets: The Segmented Control](https://livecode.com/livecode-widgets-the-segmented-control/)

### Interesting discussions

* [Cloning a graphic object does not respect dimensions](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80784.html)
* [Tips for good HTML5 standalone performance](http://forums.livecode.com/viewtopic.php?f=120&t=28406)
* [Working with regular polygons](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80708.html)

## Updates in the LiveCode open source project

38 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-11-28..2016-12-04&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 9.0.0 dp 3](https://downloads.livecode.com/livecode/#9_0_0)

### Notable changes

- [Create behaviors from script only stacks in behavior area of PI](https://github.com/livecode/livecode-ide/pull/1485):
  It's now much easier to create new behavior stacks or scriptify stack scripts
- [Interpret `.` as an LCB namespace operator](https://github.com/livecode/livecode/pull/4909):
  When 2 LCB modules define a handler with the same name, you can now specify
  which one to use
- [Add `expect that _ because _` syntax to LCB](https://github.com/livecode/livecode/pull/4905):
  LCB gets some syntax for assertions
- [lc-compile: Fix namespace-related crash in some compilation modes](https://github.com/livecode/livecode/pull/4942):
  For such a small bug, this was extremely difficult to track down
- [Ensure &lt;Shift+Tab&gt; reformats entire script](https://github.com/livecode/livecode-ide/pull/1494)

### Bug of the week

[Bug 18927 - `revXMLSetAttribute` with diacritics or Unicode characters breaks the XML tree instead of throwing an error](http://quality.livecode.com/show_bug.cgi?id=18927)

When LiveCode gained general support for Unicode strings, many of the external
APIs didn't get updated to transparently support Unicode, including revXML.

The reporter of this bug provided an extremely effective and well-explained
demonstration of some of the problems this causes.

Currently, strings passed to some revXML handlers, including
`revXMLSetAttribute`, may need to be pre-encoded to UTF-8 using the
`textEncode()` function.

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

- [asayd](https://github.com/asayd)
- [BerndN](https://github.com/BerndN)
- [seaniepie](https://github.com/seaniepie)
- [trevordevore](https://github.com/trevordevore)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
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
