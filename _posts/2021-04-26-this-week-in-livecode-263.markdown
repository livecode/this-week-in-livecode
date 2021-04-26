---
layout: post
title:  "This Week In LiveCode 263"
date:   2021-04-26 15:30
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

<!--
### News & blog posts

- [How I built a Mobile App in LiveCode and Took Over the World](https://livecode.com/how-i-built-a-mobile-app-in-livecode-and-took-over-the-world/)
-->

### Interesting discussions

- [On the dangers of automated refactoring](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111950.html)
- [How do I change the textcolor of the selected text in a native iOS field?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111957.html)
- [Snapshot image density](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112028.html)
- [Mobile Scroller Advice](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg111992.html)
- [Positioning object in a loclocked group](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112016.html)
- [Android splash and icon](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112029.html)
- [launch url and then close](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112050.html)
- [lineOffset wildcard](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112057.html)
- [rant: truewordOffset](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112072.html)
- [native scroller cuts off parts of last line in a field](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112075.html)
- [What exactly does "put" do on Server?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112087.html)
- [Changes to revsecurity.dylib in LC 9.6.2?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112100.html)
- [Failed to get the keychain item](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112111.html)
- [iOS push notifications on Windows](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112117.html)
- [Show Tree widget row contents on hover?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112122.html)
- [Dynamic scripted nested array keys?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112134.html)
- [App fails to launch after code signing](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112144.html)

## Updates in the LiveCode open source project

7 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2021-04-13..2021-04-26&type=Issues).


### New LiveCode releases

- [Release 9.6.2 RC-5](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112000.html)



### Notable changes

- [Fix 100% CPU load when playing unsupported media file on Big Sur](https://github.com/livecode/livecode/pull/7554)
- [Fix memory leak when using arrayEncode in legacy mode](https://github.com/livecode/livecode/pull/7552)
- [Fix memory leak when parsing visual effect parameters](https://github.com/livecode/livecode/pull/7551)
- [Implement translated environment AppleScript workaround](https://github.com/livecode/livecode/pull/7542)
- [Use default browser to show OAuth2 dialog on Linux](https://github.com/livecode/livecode/pull/7511)
- [Tree View Widget error when values hidden](https://github.com/livecode/livecode/pull/7504)


### Bug of the week

- [Bug 23171 - RevCopyfile in a popUp menu blocks messages in non main stacks](https://quality.livecode.com/show_bug.cgi?id=23171)

The reporter provided a helpful sample stack and a detailed recipe that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop-9.6` branch

Then try one of these:

- (Easy) [Docs: Paragraphs out of order in Description for split command](https://quality.livecode.com/show_bug.cgi?id=23071)
- (Easy) [Docs: Mention the behavior of 'the screenrect' on iOS if "Display Zoom" is checked](https://quality.livecode.com/show_bug.cgi?id=22949)
- (Easy) [Docs: Mention that matchText/matchChunk/replaceText all operate as if form-sensitive were true](https://quality.livecode.com/show_bug.cgi?id=15311)
- (Easy) [Dictionary: more examples for IF entry in Dictionary](https://quality.livecode.com/show_bug.cgi?id=22589)
- (Easy) [Dictionary: incorrect description of resizeControl message](https://quality.livecode.com/show_bug.cgi?id=17118)
- (Easy) [Docs: Update the dict entry of the "propertynames"](https://quality.livecode.com/show_bug.cgi?id=7375)
- (Medium) [Support for Drag and Drop in TreeView Widget](https://quality.livecode.com/show_bug.cgi?id=23147)
- (Medium) [Make the scrollbars for a treeview widget a TAD wider](https://quality.livecode.com/show_bug.cgi?id=23000)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Applescript "do script" missing from standalone](http://quality.livecode.com/show_bug.cgi?id=20993)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Medium) [Relayer control crashes livecode](https://quality.livecode.com/show_bug.cgi?id=21460)
- (Medium) [Datagrid not protected for drag and drop in project view (labels can get inserted into the DGgrp itself)](https://quality.livecode.com/show_bug.cgi?id=21750)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)
- (Hard) [Case insensitive matchText returns incorrect result](https://quality.livecode.com/show_bug.cgi?id=15312)


### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)* 


### Useful references

Do you need help with your project? Have a look at these useful resources:

- [LiveCode Lessons](https://lessons.livecode.com)
- [LiveCode Forums](https://forums.livecode.com/index.php)


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Android Barcode Scanner widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112030.html)
- [IOS required SDK](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg112129.html)

<!---
## Upcoming events

* [New England Livecode Users Group - May 1st 2021](https://forums.livecode.com/viewtopic.php?f=50&t=33729)
--->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
