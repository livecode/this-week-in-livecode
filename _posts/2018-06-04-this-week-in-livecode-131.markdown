---
layout: post
title:  "This Week In LiveCode 131"
date:   2018-06-04 14:00
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

- [LiveCode 9.0 GM](https://livecode.com/livecode-9-0-gm/)
--->



### Interesting discussions

- [AVMIDIPlayerDemo by Paul McClernan](http://livecodeshare.runrev.com/stack/876/AVMIDIPlayerDemo): A self-contained demonstration of the AVMIDIPlayer LiveCode Builder Library Extension for macOS and theoretically iOS too
- [LiveCode Builder linter support for Sublime Text](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94979.html)
- [How To Become Android Developer](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95022.html)
- [LC9 and Windows Unicode bug?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95027.html)
- [button action different on Android](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95031.html)
- [LC >= 8 no more HC friendly?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95038.html)
- [Devawriter Pro: Fund Raiser Goes Live!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95048.html)
- [Android APK sanity check](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95051.html)
- [Livecode 9 Server seems not to run when custom installed on On-Rev and HostM](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95053.html)
- [HilitedLine of list field lost when unlocked field selected](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95056.html)
- [ANN: Script Tracker](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95060.html)
- [Crash after entering "put the hostnametoaddress" into msg](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95065.html)
- [UTF8 on LC server](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95075.html)
- [Help converting Hex UTF-8 bytes to character](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95099.html)
- [Access image EXIF info on mobile](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95119.html)
- [SQL Help](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95147.html)
- [scrollerdidscroll, but WHAT has bee scrolled?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95157.html)
- [Creating a PSD from Livecode Script?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95168.html)
- [Text with accented characters](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95172.html)


## Updates in the LiveCode open source project

20 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-05-28..2018-06-03&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 8.1.10](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94867.html) Note 8.1.10 STABLE is the last planned release in the 8.x series.
--->


### Notable changes

- [Update Android Notification module to compile against API 23](https://github.com/livecode/livecode/pull/6558)
- [Don't assume Intent action is non-null](https://github.com/livecode/livecode/pull/6555): Fixes a crash when launching an Android app from a local notification
- [Throw error when getting the hostnametoaddress with no param](https://github.com/livecode/livecode/pull/6554)
- [Added support for building with Xcode9.4 / iOS 11.4 SDK](https://github.com/livecode/livecode/pull/6551)
- [Update property inspector once for multiple objects](https://github.com/livecode/livecode-ide/pull/1978): Moving selected control with arrow keys is now faster on Windows
- [Make message box 'put' immune to 'lock messsages'](https://github.com/livecode/livecode/pull/6544) Thanks @Brian Milby
- [Fix crash which may occur when selected objects are deleted](https://github.com/livecode/livecode/pull/6533)
- [Ide performance issues](https://github.com/livecode/livecode-ide/pull/1974): Fixes various delays when using the Script Editor on Windows
- [Fix mirroring issues with video displayed using non-ARGB32 bitmap formats](https://github.com/livecode/livecode/pull/6522)
- [Don't clobber macroman casing tables on mac](https://github.com/livecode/livecode/pull/6519): Fixes incorrect result when doing a case-insensitive "filter" 
- Plus tens of fixes in Dictionary entries, including correction of typos, broken links, malformed text etc. Thanks @Sam Norris!



### Bug of the week

- [Bug 21322 - mergAVPick crashes iOS application](http://quality.livecode.com/show_bug.cgi?id=21322)

The reporter provided useful info, a detailed recipe as well as a helpful sample stack that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Dictionary: revOpenDatabase("sqlite"...) doesn't work on some Linux versions with LC9 - needs gcc4.9](https://quality.livecode.com/show_bug.cgi?id=21270)
- (Easy) [Dictionary: Unlock Screen documentation has typos/errors and needs to reference "lock screen for visual effect"](https://quality.livecode.com/show_bug.cgi?id=21312)
- (Easy) [Dictionary: Mention that in ReplaceText function you might need to escape RegExp metacharacters, if the "replacementString" is the char itself (e.g. ".")](http://quality.livecode.com/show_bug.cgi?id=20943)
- (Easy) [Dictionary: Improve documentation for launch URL & specialFolderPath for Android](http://quality.livecode.com/show_bug.cgi?id=20722)
- (Easy) [Dictionary: Mention that iPhone X does not support "portrait upside down" orientation](http://quality.livecode.com/show_bug.cgi?id=20640)
- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [MouseEnter / MouseLeave infinite Loop trap - documentation enhancement](http://quality.livecode.com/show_bug.cgi?id=20529)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Applescript "do script" missing from standalone](http://quality.livecode.com/show_bug.cgi?id=20993)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- [James Hale](https://github.com/jameshale)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*


## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Strange error from iOS Standalone Builder](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94976.html)
- [mergDoc - no preview, no sharing](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95026.html)


## Upcoming events

* [LiveCode Global: 12 Months Streamed Live Around the Globe - Running every 2nd month throughout 2018!](https://livecode.com/global/) 

Save the dates:

- 19th of July 2018
- 20th of September 2018
- 15th of November 2018

* [The next LiveCode Conference is in...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94801.html)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
