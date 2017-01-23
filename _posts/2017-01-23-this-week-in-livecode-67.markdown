---
layout: post
title:  "This Week In LiveCode 67"
date:   2017-01-23 13:15
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

- [Why do I still need MacToISO, when working with UTF-8?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81674.html)
- [What has changed in MacOS 10.12 in handling code pages?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81699.html)
- [Code signing - not out of the wood yet: please help!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81700.html)
- [Selling a download product for Windows](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81826.html)
- [Android deployment: Could not encode class bundle](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81848.html)

## Updates in the LiveCode open source project

26 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-01-09..2017-01-15&type=Issues&ref=searchresults).


### New LiveCode releases

- [LiveCode 8.1.3 rc 1](https://downloads.livecode.com/livecode/#8_1_3)


### Notable changes

- [Use blocking wait when waiting for screen refresh](https://github.com/livecode/livecode/pull/5088):
  Otherwise many snapshots in quick succession can cause `recursionLimit` to be reached.
- [Support mobilePickPhoto() maximum width and height settings on Android](https://github.com/livecode/livecode/pull/5087):
  A previously ios-only feature that is now supported on Android as well.
- [Fix memory corruption when getting regular polygon points](https://github.com/livecode/livecode/pull/5095)
- [Add slider to Property Inspector for `startAngle` and `arcAngle`](https://github.com/livecode/livecode-ide/pull/1521):
- [Ensure all menus are updated after mouseDown to group](https://github.com/livecode/livecode/pull/5073):
  Now all menus in the menubar are rebuilt after the `mouseDown` message has been sent to the menubar group. This fixes
  the long-standing problem where only the menu which was clicked on would be rebuilt, causing all other menus to be stale.
- [Uncache object IDs when removing from object tree](https://github.com/livecode/livecode/pull/5071):
  A nasty bug that could cause a crash on object deletion.
- [Various inter-related clipboard fixes](https://github.com/livecode/livecode/pull/5060)
- Various fixes to defects detected by Coverity Scan Static Analysis tool.


### Bug of the week

[Bug 19097 -  Mac Menubar not updated correctly at mouseDown](http://quality.livecode.com/show_bug.cgi?id=19097)

The simple and self-explanatory example stack, combined with the detailed recipe in the bug report, nicely demonstrates the problem. 

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

- [BerndN](https://github.com/BerndN)
- [HedgeHao](https://github.com/HedgeHao)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*


## Upcoming events

- [Greater Toronto Area LiveCode Meetup Jan 25, 2017](http://forums.livecode.com/viewtopic.php?t=28620&p=150027#p150027)
- [International LiveCode Mini Conference Jan 25, 2017, organised by Mark Schonewille](http://forums.livecode.com/viewtopic.php?f=4&p=150296#p150296)

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
