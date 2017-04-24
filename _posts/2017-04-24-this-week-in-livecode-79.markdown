---
layout: post
title:  "This Week In LiveCode 79"
date:   2017-04-24 12:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

- [Android audio recording library using Java FFI](https://livecode.com/android-audio-recording-library-using-java-ffi/)


### Interesting discussions

- [OS X Firewall triggering on launch](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83866.html)
- [Vertical text?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83905.html)
- [Browser widget on linux](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83949.html)
- [iOS plist concern from Apple](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg83976.html)
- [The selectedObjects - is it a container or not?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84028.html)
- [Initializing the segmented control](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84034.html)
- [Standard icons included in standalone](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84057.html)
- [numberFormat affecting array keys???](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84078.html)
- [List of available SVG icons, name AND icon?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84106.html)
- [Cognitive load](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84129.html)
- [Legofied thistle](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84154.html)
  
## Updates in the LiveCode open source project

38 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-04-10..2017-04-23&type=Issues&ref=searchresults).

<!---
### New LiveCode releases

- [LiveCode 8.1.4-rc-1](https://downloads.livecode.com/livecode/#8_1_4)
-->

### Notable changes

- [Fix card deletion issues](https://github.com/livecode/livecode/pull/5378): A nasty regression introduced in LiveCode 8.1.4 RC1 is now fixed for LiveCode 8.1.4 RC2
- [Ensure 'type' works correctly for accented chars ](https://github.com/livecode/livecode/pull/5376)
- [Cleanup code that uses MCStringGetCString(), part 1](https://github.com/livecode/livecode/pull/5355)
- [New tsNet build 1.2.8](https://github.com/livecode/livecode/pull/5367): Expected in LiveCode 8.1.4 RC2, and it fixes various network-related bugs
- [Add a recordFormats function](https://github.com/livecode/livecode/pull/5341)
- [Xcode 8.3.x support](https://github.com/livecode/livecode/pull/5293): Expected in LiveCode 8.1.4 RC2


### Bug of the week

[Bug 19564 -  Closing a background tab can confuse the Script Editor](http://quality.livecode.com/show_bug.cgi?id=19564)

The reporter attached a helpful sample stack and a detailed recipe that helped us to test and confirm the problem quickly.

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

- [seaniepie](https://github.com/seaniepie)
- [techstrategies](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*


## Upcoming events

* [4th May - Pasadena: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=29156)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
