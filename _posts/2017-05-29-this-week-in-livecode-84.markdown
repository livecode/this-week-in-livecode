---
layout: post
title:  "This Week In LiveCode 84"
date:   2017-05-29 12:00
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

- [LiveCode: an inside perspective from the outside](https://livecode.com/livecode-an-inside-perspective-from-the-outside/)
-->



### Interesting discussions

- [send mouseup to control](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85148.html)
- [Is there any way at all to have a mobile app simply resume rather than restart?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85164.html)
- [Does MobileSensorReading work?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85289.html)
- [FTP from iOS but getting tsneterr: (67) Access denied: 530](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85265.html)
- [Uploading Image - Livecode Tutorial Example? Sessions?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85294.html)
- [File - read from EOF](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85324.html)
- [nice Sierra feature](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85335.html)

  
## Updates in the LiveCode open source project

21 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-05-24..2017-05-28&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 8.1.4-rc-2](https://downloads.livecode.com/livecode/#8_1_4)
-->


### Notable changes

- [Fix a few variants of message box intelligence](https://github.com/livecode/livecode-ide/pull/1598)
- [LCB: Generate builtin module in --outputc mode](https://github.com/livecode/livecode/pull/5520): A necessary restructuring to allow widgets to work in HTML5.
- [Fix crash when deleting object](https://github.com/livecode/livecode/pull/5517)
- [Feature: Added "Exit On Suspend" checkbox in iOS Standalone Settings](https://github.com/livecode/livecode-ide/pull/1596):You no longer have to hack the plist file to allow your iOS apps to run in the background :)
- [Feature: Added "Build No" field in iOS Standalone Settings](https://github.com/livecode/livecode-ide/pull/1595): You no longer have to change the "Build Version" when submitting new binaries to the AppStore. Just increment the "Build No".
- [Fix positioning of windows in the Interactive Tutorial if screenPixelScale != 1](https://github.com/livecode/livecode-ide/pull/1594)
- [Modify MCGMaskedFill to operate on device coordinates](https://github.com/livecode/livecode/pull/5483): Another regression caused by the update of Skia library is now fixed.
- [Add missing `create` syntax forms](https://github.com/livecode/livecode/pull/5478): You can now `create card X in stack Y` and `create control Y in card Z`.

### Bug of the week

- [Bug 19745 - Livecode crashes on reading a "large" text file](http://quality.livecode.com/show_bug.cgi?id=19745)

The reporter attached a helpful sample stack, and provided a detailed recipe as well as a resource file that helped us to test and confirm the problem quickly. 

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) ["width" property dictionary entry missing words "lockLocation property" in description](http://quality.livecode.com/show_bug.cgi?id=19727)
- (Easy) [Dictionary entry for compositorType says OpenGL is iOS only](http://quality.livecode.com/show_bug.cgi?id=19496)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- *[livecodealex](https://github.com/livecodealex)*
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevelanor](https://github.com/runrevelanor)*
- *[runrevmark](https://github.com/runrevmark)*


<!---
## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

-->


## Upcoming events

* [1st June - Pasadena: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=29292)

* [LiveCode Global: Our Next Conference in Your City](https://livecode.com/livecode-global-our-next-conference-in-your-city/): 48 hours of Conference content streamed live around the globe! Save the dates:

- 15th of June 2017
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
