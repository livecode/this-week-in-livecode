---
layout: post
title:  "This Week In LiveCode 234"
date:   2020-07-27 15:30
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

- [New Campaign](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108345.html)
--->

### Interesting discussions

- [Tab Buttons Mac vs. Win](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108671.html)
- [LiveCode Server revOpenDatabase help needed](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108675.html)
- [Functions running in IDE, but not running in standalone](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108716.html)
- [breakpoint causes 3 second delay then exit to top](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108684.html)
- [Styled text on mobile](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108695.html)
- [text to speech android](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108703.html)
- [Browser widget scrolling](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108723.html)
- [Wrapping Text](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108738.html)
- [Using OAuth2 with Microsoft API services](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108748.html)
- [ANN: FieldGroup - a simple rich text editor field](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108755.html)
- [Is "import snapshot" without parameters broken?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108768.html)
- [Android target needs api-29 as of august 2020](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108773.html)
- [Scrolling in a widget](http://forums.livecode.com/viewtopic.php?t=34410&p=194236#p194236)

## Updates in the LiveCode open source project

6 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2020-07-14..2020-07-26&type=Issues).

<!--
### New LiveCode releases

- [Release 9.6.0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108199.html)
-->

### Notable changes

- [Enable text editing options in CEF context menu](https://github.com/livecode/livecode/pull/7405)
- [Ensure the captured image is not rotated when saved](https://github.com/livecode/livecode/pull/7398)
- [emscripten: Use a single hidden input field for all LC windows](https://github.com/livecode/livecode/pull/7400)
- [Have revPrintText keep modal defaultStack](https://github.com/livecode/livecode-ide/pull/2135)


### Bug of the week

- [Bug 22822 - PDF widget has a page drift on pagingEnabled](https://quality.livecode.com/show_bug.cgi?id=22822)

The reporter provided a helpful sample stack that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop-9.6` branch

Then try one of these:

- (Easy) [Docs: Mention that matchText/matchChunk/replaceText all operate as if form-sensitive were true](https://quality.livecode.com/show_bug.cgi?id=15311)
- (Easy) [Dictionary: more examples for IF entry in Dictionary](https://quality.livecode.com/show_bug.cgi?id=22589)
- (Easy) [Dictionary: incorrect description of resizeControl message](https://quality.livecode.com/show_bug.cgi?id=17118)
- (Easy) [Docs: Update the dict entry of the "propertynames"](https://quality.livecode.com/show_bug.cgi?id=7375)
- (Medium) [Add support for unblocking http requests on Android 9+](http://quality.livecode.com/show_bug.cgi?id=22400)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Applescript "do script" missing from standalone](http://quality.livecode.com/show_bug.cgi?id=20993)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Medium) [Relayer control crashes livecode](https://quality.livecode.com/show_bug.cgi?id=21460)
- (Medium) [Datagrid not protected for drag and drop in project view (labels can get inserted into the DGgrp itself)](https://quality.livecode.com/show_bug.cgi?id=21750)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)
- (Hard) [Case insensitive matchText returns incorrect result](https://quality.livecode.com/show_bug.cgi?id=15312)


### Contributors this week

- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [tsnetGetFile() example using HTTP?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108700.html)


<!---
## Upcoming events

* [SoCal LiveCode Group Meeting: March 5, Pasadena](https://forums.livecode.com/viewtopic.php?f=50&t=33729)
--->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
