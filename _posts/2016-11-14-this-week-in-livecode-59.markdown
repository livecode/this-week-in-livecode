---
layout: post
title:  "This Week In LiveCode 59"
date:   2016-11-14 11:45
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [Ignite your sites with revIgniter](https://livecode.com/ignite-your-sites-with-revigniter/)
- [Infinite LiveCode: Java progress](https://livecode.com/infinite-livecode-java-progress/)

### Interesting discussions

- [How to get LiveCode running on a Raspberry Pi 3](http://forums.livecode.com/viewtopic.php?f=76&t=26738#p148267)
- [Preventing keyboard display for an Android native field](http://forums.livecode.com/viewtopic.php?f=53&t=28280)
- [What speed advantage comes from a private handler?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80238.html)

## Updates in the LiveCode open source project

37 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-11-07..2016-11-13&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 8.1.2 rc 1](https://downloads.livecode.com/livecode/#8_1_2)

### Notable changes

- [Add `do ... as JavaScript` to HTML5 engine](https://github.com/livecode/livecode/pull/4851):
  Integrate your HTML5 apps with the rest of page
- [treeview: Calculate only 1000 keys of subarray display data](https://github.com/livecode/livecode/pull/4860):
  Enables browsing really huge arrays with the Script Editor's variable viewer
- [Update OpenSSL to 1.1.0c and libcurl to 7.51.0](https://github.com/livecode/livecode/pull/4850):
  Adds support for the latest and most secure encryption algorithms
- [Use object handles instead of global object pointers](https://github.com/livecode/livecode/pull/4804):
  Extensive low-level changes to ensure that if LiveCode crashes, it crashes
  consistently and reproducibly (so that the crashes can be fixed quickly)
- [Add a document describing C++ language policies](https://github.com/livecode/livecode/pull/4301):
  Which C++ language features we use in LiveCode's source code, and why

### Bug of the week

[Bug 18826 - Player displays a video window in upper left when navigating to another card](http://quality.livecode.com/show_bug.cgi?id=18689)

The reporter found an interesting bug in the Windows player's rendering.  The
steps to reproduce are detailed and easy-to-follow, and the report includes
both a test stack and a helpful screenshot illustrating the issue.

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

- [mwieder](https://github.com/mwieder)
- [techstrategies](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
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
