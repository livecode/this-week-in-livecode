---
layout: post
title:  "This Week In LiveCode 73"
date:   2017-03-06 11:30
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [German LiveCode book published](https://livecode.com/german-livecode-book-published/)
- On Gitter, @HedgeHao reported a
  [successful build of LiveCode 8.1.3 on a Raspberry Pi 3](https://gitter.im/LiveCode/Lobby?at=58b403c700c00c3d4f935d8b)

### Interesting discussions

- [SHA1 cracked; what are the chances this will be addressed in LC](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82550.html):
  Includes some in-depth discussion of how to use cryptographic hash functions
  and whether you should be worried about using SHA-1.
- [Compressing and extracting folders for transfer with revZip](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82817.html)
- [Image manipulation via JavaScript/HTML5 using a widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82732.html)

## Updates in the LiveCode open source project

23 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-02-27..2017-03-05&type=Issues&ref=searchresults).

### Notable changes

- @livecodeali has landed Java FFI support in the 9.0 development branch:
  - [Add Java FFI support to libfoundation and libscript](https://github.com/livecode/livecode/pull/5214)
  - [Implement a parser for the Java FFI DSL](https://github.com/livecode/livecode/pull/4548)
- [Improve LCB's `execute script` command](https://github.com/livecode/livecode/pull/5040):
  You can now run the script in the context of a specific object, and pass a
  list of arguments.
- @asayd has been providing a continuous stream of great improvements to the
  documentation.

<!---
### Bug of the week

[Bug <number> - <description>](<link>)

<summary>
-->
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
- [BerndN](https://github.com/BerndN)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*

<!---
## Upcoming events

* [<date>: <title>](<url>)
-->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
