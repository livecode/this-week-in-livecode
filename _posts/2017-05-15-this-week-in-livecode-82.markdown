---
layout: post
title:  "This Week In LiveCode 82"
date:   2017-05-15 12:00
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

- [Android audio recording library using Java FFI](https://livecode.com/android-audio-recording-library-using-java-ffi/)
-->


### Interesting discussions

- [Unable to set breakpoint](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84593.html)
- [sysError List?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84615.html)
- [filter? replace? wildcard? reg exp? help please!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84626.html)
- [Update strategy?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84634.html)
- [poking around near the end of a string](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84646.html)
- [set the points of a widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84648.html)
- [Using a hidden browser widget to create a perfectly scalable LC control](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84671.html)
- [Feature request: Add a "back/forward" button in script editor](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84684.html)
- [PDF on Android](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84688.html)
- [SVG powered images](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84711.html)
- [Android Setup Config](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84754.html)
- [Seeking recommendations / suggestions for use of library stacks](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84823.html)
- [IP to decimal function?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84826.html)
  
## Updates in the LiveCode open source project

22 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-05-08..2017-05-14&type=Issues).


### New LiveCode releases

- [LiveCode 8.1.4-rc-2](https://downloads.livecode.com/livecode/#8_1_4)


### Notable changes

- [Draw player snapshot image at correct scale on hi-dpi displays](https://github.com/livecode/livecode/pull/5450): A bug in the player object, affecting only Retina displays, is now fixed.
- [Allow the same local port to be used for multiple connections](https://github.com/livecode/livecode/pull/5443)
- [Fix setting the iphoneSetAudioCategory](https://github.com/livecode/livecode/pull/5446): Allow your iOS app to play sounds even when the device is muted.
- [Fix native layer placement on Mac](https://github.com/livecode/livecode/pull/5439)
- [Make LC work with the latest version of Android Studio](https://github.com/livecode/livecode/pull/5436)
- [Update libgraphics to account for Skia API changes](https://github.com/livecode/livecode/pull/5269)
- [Update cursor when entering window](https://github.com/livecode/livecode/pull/5452): A regression bug affecting Windows is now fixed.


### Bug of the week

- [Bug 19666 - Browser Widget: Only one javascriptHandler possible on Win/Linux](http://quality.livecode.com/show_bug.cgi?id=19666)
- [Bug 19668 - undochanged used to manipulate image crashes LC](http://quality.livecode.com/show_bug.cgi?id=19668)

In both of these reports, the reporter attached a very helpful sample stack, and provided a detailed recipe that helped us to test and confirm the problem quickly. 
In one of them, the problem has been already fixed, and the fix will be included in the next LiveCode release.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) [Dictionary: print command "topLeft" should be "leftTop"](http://quality.livecode.com/show_bug.cgi?id=19570)
- (Easy) [Dictionary entry for compositorType says OpenGL is iOS only](http://quality.livecode.com/show_bug.cgi?id=19496)
- (Easy) [error in Dictionary Entry for revSpeak](http://quality.livecode.com/show_bug.cgi?id=19361)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [MartinKoob](https://github.com/MartinKoob)
- [mwieder](https://github.com/mwieder)
- [trevordevore](https://github.com/trevordevore)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodemichael](https://github.com/livecodemichael)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*

<!---
## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [tinyDictionary 0_8_1_0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84455.html): TinyDictionary is a small footprint dictionary for LiveCode (version 8.1
and up), developed by Bernd Niggemann.
- [PowerTools 2.0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84449.html): PowerTools is a drop-in plugin replacement for the IDE's built-in tools palette, developed by Mark Wieder.
- [New tsNet version](https://github.com/livecode/livecode/pull/5429): Expected in LiveCode 8.1.4 RC2
-->

<!---
## Upcoming events

* [4th May - Pasadena: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=29156)
-->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
