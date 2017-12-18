---
layout: post
title:  "This Week In LiveCode 111"
date:   2017-12-18 15:00
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
--->


### Interesting discussions

- [Tab alignment in fields](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg91279.html)
- [Website scraping - How can I load a 'partial' page?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg91293.html)
- [Dash Docs and Docset Creator updates](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg91306.html)
- [rename folder not working?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg91307.html)
- [Update to FMaker utility stack](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg91314.html)
- [Revigniter Sessions](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg91326.html)
- [Screen Resolution for Desktop Apps](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg91336.html)
- [Shout Out to dev@livecode](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg91351.html)
- [LC Server 8.1.7 Community - Sessions work?](http://forums.livecode.com/viewtopic.php?f=15&p=161401#p161401)
- [I can not delete files on Windows](http://forums.livecode.com/viewtopic.php?f=18&t=30304)
- [Windows system tray icon](http://forums.livecode.com/viewtopic.php?f=18&t=30297)

## Updates in the LiveCode open source project

42 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-12-11..2017-12-17&type=Issues).

<!---
### New LiveCode releases

- [LiveCode 8.1.8](https://downloads.livecode.com/livecode/#8_1_8)
--->


### Notable changes

- [Make corner radius of segmented control a property](https://github.com/livecode/livecode/pull/6204) Thanks @jameshale
- [EmscriptenWindows: Track mouseevents outside window when click-dragging](https://github.com/livecode/livecode/pull/6202) 
- [Enable creation of objc delegates implementing protocol methods](https://github.com/livecode/livecode/pull/6199): New handlers for Objective-C delegate support
- [Add dynamic instance method binding](https://github.com/livecode/livecode/pull/6200): More progress on Objective-C FFI
- [Add optional 'kind' parameter to files/folders](https://github.com/livecode/livecode/pull/6198)
- [Fix replaceText performance regression](https://github.com/livecode/livecode/pull/6197)
- [Added support for Xcode 9.2 / iOS 11.2](https://github.com/livecode/livecode/pull/6193)
- [Show soft keyboard when Android native field widget receives focus](https://github.com/livecode/livecode/pull/6166)
- [Fix crash when undo group deletion](https://github.com/livecode/livecode/pull/6124)
- [Extensions: Add a way to launch sample stacks](https://github.com/livecode/livecode-ide/pull/1825)
- [Profile Manager/Geometry Manager on Mobile](https://github.com/livecode/livecode-ide/pull/1822) Thanks @Brian Milby
- [EmscriptenWindows: Implement windows in HTML5 using floating 'canvas' elements](https://github.com/livecode/livecode/pull/6097): Four bugs are fixed by this PR :)
- [Toast notification library](https://github.com/livecode/livecode/pull/5860): This provides the ability to pop up a transient, non-modal notification to the user. Currently, the library is only supported on Android.

<!---
### Bug of the week

- [Bug 20727 - Can't move objects together with lock moves](http://quality.livecode.com/show_bug.cgi?id=20726)

The reporter attached a simple and helpful sample stack, and provided useful info and a detailed recipe that helped us to test and confirm the problem quickly.
--->


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Dictionary: Improve documentation for launch URL & specialFolderPath for Android](http://quality.livecode.com/show_bug.cgi?id=20722)
- (Easy) [Dictionary: Mention that iPhone X does not support "portrait upside down" orientation](http://quality.livecode.com/show_bug.cgi?id=20640)
- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [MouseEnter / MouseLeave infinite Loop trap - documentation enhancement](http://quality.livecode.com/show_bug.cgi?id=20529)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Easy) [Info missing from mobileGetContactData entry](http://quality.livecode.com/show_bug.cgi?id=20359)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [LC8 Dictionary Copy **using cmd+C** only works after Run Tool selected](http://quality.livecode.com/show_bug.cgi?id=17819)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [BerndN](https://github.com/BerndN)
- [Brian Milby](https://github.com/bwmilby)
- [Charles Warwick](https://github.com/techstrategies)
- [Devin Asay](https://github.com/asayd)
- [James Hale](https://github.com/jameshale)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevelanor](https://github.com/runrevelanor)*
- *[runrevmark](https://github.com/runrevmark)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [What answer to testFlight encryption four questions?](http://forums.livecode.com/viewtopic.php?f=49&t=30275&p=161378#p161378)


<!---
## Upcoming events

* [7th Dec : SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=30227)
--->

## Thank you!

Thank you so much everyone for your contributions this year. We wish you all a very Merry Holiday season, and a Happy New Year! *This Week in LiveCode* will be with you again on Monday 15th January, 2018.


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
