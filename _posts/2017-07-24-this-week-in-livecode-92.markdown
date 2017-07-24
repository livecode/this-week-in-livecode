---
layout: post
title:  "This Week In LiveCode 92"
date:   2017-07-24 14:00
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

- [Find some text characters](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87122.html)
- [Sending an FTP command from one web server to another?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87138.html)
- [Why is libcef included in standalone?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87153.html)
- [ANN: TinyDictionary updated to display Synonyms](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87177.html)
- [What happened to LC version numbers?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87210.html)
- [Window layering](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87224.html)
- [Export SVG as PNG?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87217.html)
- [Swipe transitions](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87250.html)
- [h.264 alternatives](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87254.html)
- [IntelliSense - Intelligent code completion for LiveCode](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87260.html)
- [Restrictions on mobile servers?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87289.html)
- [iPad portrait size stack doesn't fit to display](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87323.html)
- [Problem after putting executable into installer](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87341.html)
- [suggestion for in-app ads](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87345.html)
- [Ethereal Breakpoints](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87347.html)
- [Setting image source of fld char to remote URL](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87372.html)
- [XAML tools, viewers and converters](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87378.html)

  
## Updates in the LiveCode open source project

42 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-07-17..2017-07-23&type=Issues).


### New LiveCode releases

- [LiveCode 8.1.6 RC-2](https://downloads.livecode.com/livecode/#8_1_6)


### Notable changes

- [Fix backdrop preference setting](https://github.com/livecode/livecode-ide/pull/1689)
- [Add useful properties to icon picker](https://github.com/livecode/livecode/pull/5719)
- [Show only valid provisioning profiles](https://github.com/livecode/livecode-ide/pull/1688)
- [Dictionary Whitespace](https://github.com/livecode/livecode-ide/pull/1687): Improved layout of the LiveCode dictionary, special thanks to Brian Milby.
- [Unlock cursor on tab-control-alt key](https://github.com/livecode/livecode-ide/pull/1685)
- [Linux backdrop issues](https://github.com/livecode/livecode/pull/5714)
- [Add 2 new coding tutorials to the Start Center](https://github.com/livecode/livecode-ide/pull/1678)
- [Render caret with the correct blend mode](https://github.com/livecode/livecode/pull/5703): A regression caused by the update of the Skia library, affecting LiveCode on Linux, is now fixed.
- [Add square root operator to math lib](https://github.com/livecode/livecode/pull/5702)
- [Various improvements in the default handlers](https://github.com/livecode/livecode-ide/pull/1666): Thank you for the useful suggestions :)
- [Use the hex code of the cert in iOS codesign step instead of cert name](https://github.com/livecode/livecode/pull/5692): Fixes a potential segmentation fault in case there are more than one certificates with the same name installed (e.g. one expired and one valid).
- Various fixes in malformed Dictionary entries
- Various improvements in the existing Interactive Tutorials

### Bug of the week

- [Bug 20142 - TreeView widget unable to display more than 1030 keys](http://quality.livecode.com/show_bug.cgi?id=20142)

The reporter attached a helpful sample stack, and provided a detailed recipe that helped us to test and confirm the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Searching the Dictionary with $](http://quality.livecode.com/show_bug.cgi?id=19031)
- (Medium) [Dictionary auto-searches on first char freezing cursor](http://quality.livecode.com/show_bug.cgi?id=18739)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [BerndN](https://github.com/BerndN)
- [Bob Hall](https://github.com/bhall2001)
- [Brian Milby](https://github.com/bwmilby)
- [Devin Asay](https://github.com/asayd)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevelanor](https://github.com/runrevelanor)*
- *[runrevmark](https://github.com/runrevmark)*

<!---
## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Submitting to the #%^%#? App Store](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86577.html)
- [Augmented Earth now on the App Store!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86655.html)
- [Oracle DB driver is now back in LiveCode Business Edition](https://github.com/livecode/livecode/pull/5636)
--->

## Upcoming events

* [3rd August - Pasadena: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=29460)

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
