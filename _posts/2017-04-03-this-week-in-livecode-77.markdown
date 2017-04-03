---
layout: post
title:  "This Week In LiveCode 77"
date:   2017-04-03 12:00
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

- [tinyDictionary v0.7.7.7 by Bernd Niggemann has been released](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83246.html)
-->

### Interesting discussions

- [Cheesed off by 32xxx](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83554.html)
- [OMG WTF detailed files BST?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83527.html)
- [Transparent Images in LC](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83508.html)
- [shell("netstat -i") has getting slow on MacOS10.x](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83489.html)
- [Playing multiple audio files simultaneously](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83470.html)
- [Blowfish digest , how to create in Livecode](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83412.html)
- [Object Selection Handles](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83400.html)
  
## Updates in the LiveCode open source project

29 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-03-27..2017-04-02&type=Issues&ref=searchresults).

<!---
### New LiveCode releases

- [LiveCode 9.0-dp-6](https://downloads.livecode.com/livecode/#9_0_0)
-->

### Notable changes

- [Fix dynamic path behavior](https://github.com/livecode/livecode/pull/5325): This fix will allow a Rev 3.0 user to upgrade to LiveCode 8.1.4-x
- [Fix inclusion of dbdrivers in Desktop standalones](https://github.com/livecode/livecode/pull/5320): The previous Bug of the Week is now fixed.
- [Fix regression in 24-hour time format](https://github.com/livecode/livecode/pull/5316): This innocent regression was causing strange unexpected results, see [here](http://forums.livecode.com/viewtopic.php?t=29044&p=152683#p152683) for more details.
- [Remove need to save stack to temporary location when building standalone](https://github.com/livecode/livecode/pull/5314)


### Bug of the week

[Bug 19500 -  iOS crash when native browser gets an invalid URL](http://quality.livecode.com/show_bug.cgi?id=19500)

The reporter attached helpful sample stack, as well as all the necessary resources that helped us to test, confirm and fix the problem quickly.

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

- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
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
