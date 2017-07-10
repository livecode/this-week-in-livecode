---
layout: post
title:  "This Week In LiveCode 90"
date:   2017-07-03 14:00
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

- [Using Infinite LiveCode for Android to Create Native Controls and Wrap OS APIs](https://livecode.com/using-infinite-livecode-for-android-to-create-native-controls-and-wrap-os-apis/)
--->


### Interesting discussions

- [Recursion limit](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86523.html)
- [Debugging a CEF browser instance](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86539.html)
- [I need a "slider" in a circle](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86541.html)
- [Object->New Control->Polygon Graphic in 8.1.4?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86547.html)
- [Can I lock screen over more than one handler?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86589.html)
- [fonts v8 vs v9](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86615.html)
- [Saturated fat](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86644.html)
- [Codesigning a Mac desktop version](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86637.html)
- [play sound plays the wrong sound](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86658.html)
- [iOS Browser Widget and PDFs?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86690.html)
- [Biased testing and micro-coaching](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86709.html)
- [Text style is hit or miss for me](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86714.html)
- [Division by Zero Error](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86745.html)
- [Fat widgets](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86751.html): Includes a script that automatically recompiles custom widgets on startup, when switching between LiveCode 8 and 9.
- [Mysterious new MetaCard file](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86762.html)
- [Image Metadata Enhancement Request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86773.html)
- [modal window = block handler?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86778.html)

  
## Updates in the LiveCode open source project

38 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-07-03..2017-07-09&type=Issues).


### New LiveCode releases

- [LiveCode 8.1.5 RC-3](https://downloads.livecode.com/livecode/#8_1_5)



### Notable changes

- [Add Synonyms to Dictionary](https://github.com/livecode/livecode/pull/5669)
- [Various fixes and updates to lc-compile-ffi-java](https://github.com/livecode/livecode/pull/5646)
- [Restrict SSE compiler flag scope in Skia](https://github.com/livecode/livecode-thirdparty/pull/105): Fixes a potential crash on some Linux distros with specific configurations
- [Use new send command form to fix message box issues](https://github.com/livecode/livecode/pull/5654)
- [Fix some inconsistencies in the player object](https://github.com/livecode/livecode/pull/5622): A previous bug of the week is now fixed
- [LCB: Add varargs support to foreign handlers](https://github.com/livecode/livecode/pull/5666): It is now possible to bind to variadic C functions
- [Clear substacks in destroystack](https://github.com/livecode/livecode/pull/5668): Fixes a potential crash
- [Ensure the defaultScript is editable in Extesions Builder](https://github.com/livecode/livecode-ide/pull/1654)

### Bug of the week

- [Bug 20012 - Browser Widget: Memory leak](http://quality.livecode.com/show_bug.cgi?id=20012)
- [Bug 19948 - [LCB] sector path radius changed to diameter in 8.1.5 RC1 and LC 9 DP7](http://quality.livecode.com/show_bug.cgi?id=19948)

In both reports the reporter attached a helpful simple sample stack, and provided a detailed recipe that helped us to test and confirm the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodemichael](https://github.com/livecodemichael)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Submitting to the #%^%#? App Store](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86577.html)
- [Augmented Earth now on the App Store!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86655.html)
- [Oracle DB driver is now back in LiveCode Business Edition](https://github.com/livecode/livecode/pull/5636)

## Upcoming events

* [3rd August - Pasadena: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=29460)

* [LiveCode Global: Our Next Conference in Your City](https://livecode.com/livecode-global-our-next-conference-in-your-city/): 48 hours of Conference content streamed live around the globe! Save the dates:

- 13th of July 2017
- 17th of August 2017
- 21st of September 2017
- 19th of October 2017
- 16th of November 2017


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
