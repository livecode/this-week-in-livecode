---
layout: post
title:  "This Week In LiveCode 95"
date:   2017-08-14 14:00
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

- [Sorting out the sheep from the goats](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88039.html)
- [Recursive folder creation](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88046.html)
- [SORT by length](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88066.html)
- [How to get the value of a custom property if the name of the cProperty is in a variable?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88079.html)
- [Script Editor Window being bl**dy-minded](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88080.html)
- [FOR YOU: OSX-style push reorder of objects](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88090.html)
- [How to fake having the altKey pressed](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88101.html)
- [Android Browser Widget JS problem](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88132.html)
- [math, bigly](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88135.html)
- [Parent of Target](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88136.html)
- [the defaultStack changes on resume](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88143.html)
- [SMS message in LC?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88164.html)
- [LC stack version changes between 8 and 9](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88166.html)
- [Bug 20255 - Simple Loop Labeling](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88176.html)
- [Using Find with Shell on Mac](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88185.html)
- [Weird thing I noticed with a graphics speed test](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88192.html)
- [Common code patterns](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88205.html)
- [Bug regression](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88211.html)
- [JPNG](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88266.html)
- [Crash with mobilePickPhoto and Android](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88274.html)
- [Mobile LC Apps Downloading Stacks After installation](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88283.html)
- [Speed of control lookup](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88312.html)
- [Livecode Mobile App in Background](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88377.html)
- [LC 9.0.0 dp8 won't launch iOS simulator?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88389.html)
- [Android Virtual Device Application Binary Interface](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88414.html)
- [Android App Woes](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88423.html)
  
## Updates in the LiveCode open source project

18 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-08-07..2017-08-13&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 8.1.6](https://downloads.livecode.com/livecode/#8_1_6)
--->


### Notable changes

- [Fix inability to use custom fonts on Window](https://github.com/livecode/livecode/pull/5722): A regression bug caused by the update of the Skia library is now fixed.
- [Implement Win32 font listing using DirectWrite](https://github.com/livecode/livecode/pull/5732): Another regression bug caused by the update of the Skia library is now fixed.
- [Fix rendering of mirrored + wrapped gradients](https://github.com/livecode/livecode/pull/5759): Yet another regression bug caused by the update of the Skia library is now fixed.
- [Fix incorrectly masked rendering of legacy gradients when scaled](https://github.com/livecode/livecode/pull/5769): Yes, this is another Skia-related regression that is now fixed :)
- [Fix vertical placement of caret on wrapped lines](https://github.com/livecode/livecode/pull/5760): A long standing issue is now fixed.
- [Ensure there is always a segment for each tab](https://github.com/livecode/livecode/pull/5762): An annoying LC 7.x regression is now fixed.
- [Synthesize DIBV5 from PNG, GIF and JPEG on Win32](https://github.com/livecode/livecode/pull/5765): A clipboard-related LC 8 regression on Windows is now fixed.
- [Ensure dragdata["files"] uses Unix paths + supports multiple files](https://github.com/livecode/livecode/pull/5772)
- [Allow binding to interface callbacks with non-void return](https://github.com/livecode/livecode/pull/5742): Another feature for Infinite LiveCode on Android is now implemented.

### Bug of the week

- [Bug 20218 - Gradient Mirror does not work if repeat is 1](http://quality.livecode.com/show_bug.cgi?id=20218)

The reporter attached a simple and helpful sample stack, and provided a detailed recipe that helped us to test, confirm and fix the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [LC8 Dictionary Copy **using cmd+C** only works after Run Tool selected](http://quality.livecode.com/show_bug.cgi?id=17819)
- (Medium) [Dictionary auto-searches on first char freezing cursor](http://quality.livecode.com/show_bug.cgi?id=18739)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [techstrategies](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*

<!---
## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Submitting to the #%^%#? App Store](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86577.html)
- [Augmented Earth now on the App Store!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86655.html)
- [Oracle DB driver is now back in LiveCode Business Edition](https://github.com/livecode/livecode/pull/5636)
--->

## Upcoming events

* [LiveCode Global: Our Next Conference in Your City](https://livecode.com/livecode-global-our-next-conference-in-your-city/): 48 hours of Conference content streamed live around the globe! Save the dates:

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
