---
layout: post
title:  "This Week In LiveCode 74"
date:   2017-03-13 12:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [LiveCode 9.0 DP 6 – Infinite LiveCode Preview](https://livecode.com/livecode-9-0-dp-6-infinite-livecode-preview/)
- [brimmEng, a free English language learning app for Android that was developed with LiveCode, has been released](http://www.edvista.com/claire/apps/brimmeng.htmlA)


### Interesting discussions

- [Messages sent while mouse is down](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82994.html):
- [LC for Raspberry Pi](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83001.html)
- [Searching "teh" or tihs"](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82732.html):
  Hermann Hoch has implemented a fuzzySearch algorithm in LiveCode script
- [Breakpoints being ignored](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82892.html)
- [Trouble playing videos with MS DirectShow LC 8](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82867.html)
  
## Updates in the LiveCode open source project

33 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-03-06..2017-03-12&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 9.0-dp-6](https://downloads.livecode.com/livecode/#9_0_0)

### Notable changes

- [Add support for building with Visual Studio 2015](https://github.com/livecode/livecode-thirdparty/pull/91):
  This change will allow us to use some of the C++11 features, which are needed to update our Skia library to support emoji rendering.
- [Update OpenSSL to version 1.1.0e](https://github.com/livecode/livecode/pull/5205)
- [Add messageDigest() function with SHA2 and SHA3 support](https://github.com/livecode/livecode/pull/5229)
- [Fix crash in standalone when connecting an IR Receiver](https://github.com/livecode/livecode/pull/5253)
- [Reposition native layer controls when resizing stacks](https://github.com/livecode/livecode/pull/5255)
- [Prevent crash when calling `mobilePickMedia` and correct return value](https://github.com/livecode/livecode/pull/5210)


### Bug of the week

[Bug 19364 - Import snapshot uses wrong coordinates when a secondary monitor is connected](http://quality.livecode.com/show_bug.cgi?id=19364)

The reporter attached a nice and very helpful sample stack, which helped us to test and identify the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) [selectionChanged does not appear in the player object page of the dictionary](http://quality.livecode.com/show_bug.cgi?id=19083)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [asayd](https://github.com/asayd)
- [HedgeHao](https://github.com/HedgeHao)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*

## Upcoming events

* [6th April: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=28970)

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
