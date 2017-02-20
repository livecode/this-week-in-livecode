---
layout: post
title:  "This Week In LiveCode 71"
date:   2017-02-20 10:30
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

<!---
### News & blog posts
-->

### Interesting discussions

- [Library for using associative arrays as indexed arrays](http://forums.livecode.com/viewtopic.php?f=108&t=28828)
- [Over-the-air installation on iOS](http://forums.livecode.com/viewtopic.php?f=49&t=28812)
- [How to run a hidden standalone under OSX](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg82418.html)

## Updates in the LiveCode open source project

30 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-02-13..2017-02-19&type=Issues&ref=searchresults).

### Notable changes

- [Allow script-only stacks in deploy params](https://github.com/livecode/livecode/pull/5182): You can now deploy script-only stacks as standalones
- [Remove revFont in favour of the commands added in 6.5](https://github.com/livecode/livecode/pull/4865)
- [Ensure browser widget doesn't get stuck handling JavaScript](https://github.com/livecode/livecode/pull/5119)

### Bug of the week

[Bug 19266 - Android native text control keyboard issue with 'Go', 'Search' and 'Send' return types](http://quality.livecode.com/show_bug.cgi?id=19266)

The reporter found a really interesting bug in Android standalones that use
native text controls with certain return types.  When tapping the return button,
sometimes the keyboard gets "stuck" and won't go away.  The sample stack that
the reporter provided lets you test all possible values for the `returnKeyType`
and clearly demonstrates the bug.

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
- [trevordevore](https://github.com/trevordevore)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*

## Upcoming events

- [25th February: eHUG International Mini Conference on LiveCode](http://economy-x-talk.com/conf): Antwerp, Belgium

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
