---
layout: post
title:  "This Week In LiveCode 69"
date:   2017-02-06 10:15
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- Trevor DeVore has created a new application framework & workflow called
'levure'
  - [Levure Application Framework](https://github.com/trevordevore/levure) on
    GitHub
  - [Thoughts on using script only stacks and levure framework](https://www.youtube.com/watch?v=e1p_FTRi1-Q) (video)
  - [LiveCode Language package for SublimeText](https://packagecontrol.io/packages/LiveCode)
- [ReadBar](https://github.com/ApplicationInsight/ReadBar): A basic
  barcode-checking app created at the January 2017 NHS HackDay in Cardiff
- [How to create the Untrue Zoo in LiveCode](https://www.youtube.com/watch?v=37nfon24_aY):
  An intro to LiveCode for HyperCard enthusiasts (video)

### Interesting discussions

- [Creating applications that play well with version control software](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82202.html)
- [Converting scripts in stacks to script-only stack behaviors](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82200.html)
- [Difference between "html" and "htmlText" in clipboardData](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82143.html)
- [Dragging list items up and down](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82157.html)
- [Importing text on iOS](http://forums.livecode.com/viewtopic.php?f=49&t=28738)
- [How do you specify a Build Number for iOS apps?](http://forums.livecode.com/viewtopic.php?f=49&t=28743)

## Updates in the LiveCode open source project

22 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-01-30..2017-02-05&type=Issues&ref=searchresults).

### Notable changes

- [Allow modules to declare Android app requirements in metadata](https://github.com/livecode/livecode/pull/4969)
- [Allow sockets to send broadcast packets on Android](https://github.com/livecode/livecode/pull/5081)
- [Ensure correct debug context is used when executing in message box](https://github.com/livecode/livecode-ide/pull/1530)

### Bug of the week

[Bug 19209 - bgcolor in text not transferred to the public clipboard](http://quality.livecode.com/show_bug.cgi?id=18970)

On Linux, HTML-formatted styled text placed on the system clipboard doesn't
contain background colour information.  The report contains a clear and
detailed set of steps to reproduce the problem, along with a well-structured
and self-explanatory sample stack.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) [selectionChanged does not appear in the player object page of the dictionary](http://quality.livecode.com/show_bug.cgi?id=19083)
- (Easy) [Fix format of `mobileControlDo` dictionary entries](http://quality.livecode.com/show_bug.cgi?id=17318)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [asayd](https://github.com/asayd)
- [HedgeHao](https://github.com/HedgeHao)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*

<!---
## Upcoming events
-->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
