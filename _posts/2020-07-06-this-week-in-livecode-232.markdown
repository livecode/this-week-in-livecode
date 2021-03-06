---
layout: post
title:  "This Week In LiveCode 232"
date:   2020-07-06 15:30
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community


### News & blog posts

- [New Campaign](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108345.html)


### Interesting discussions

- [Platform Divergence](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108403.html)
- [Mobile Keyboard](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108415.html)
- [iOS Browser Widget and javascriptHandlers](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108431.html)
- [datagrid delay hilite](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108413.html)
- [What the heck? Writing and reading ios files??](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108432.html)
- [How many objects (IDs) can be generated by script?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108450.html)
- [Quick question: player object callbacks still working?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108454.html)
- [Animation Engine: speed tips](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108455.html)
- [More Catalina permissions woes....](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108474.html)
- [AR in LiveCode Browser?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108486.html)
- [slow loading & navigation to card containing large field](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108519.html)
- [WebSites made using Livecode](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108528.html)
- [Redirecting stdout to file on server](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108555.html)
- [OAuth2 on Win10: not returning to my app](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108476.html)

## Updates in the LiveCode open source project

17 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2020-06-22..2020-07-05&type=Issues).

<!--
### New LiveCode releases

- [Release 9.6.0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108199.html)
-->

### Notable changes

- [Fix crash in HTML5 standalones when fetching the system date or system time](https://github.com/livecode/livecode/pull/7389)
- [Fix crash in HTML5 standalones when getting / setting the effective rect of a stack](https://github.com/livecode/livecode/pull/7388)
- [Fix event handling during modal sessions](https://github.com/livecode/livecode/pull/7385)
- [OAuth2 - Prevent double URL encoding of authentication code](https://github.com/livecode/livecode/pull/7381)
- [Fix resizing mobilePickPhoto for API Level < 24 ](https://github.com/livecode/livecode/pull/7368)
- [Fix input of alt+key combination characters in HTML5 standalones](https://github.com/livecode/livecode/pull/7363)
- [ Fix forwarding of key events in HTML5 engine](https://github.com/livecode/livecode/pull/7352)

<!--
### Bug of the week

- [Bug 22765 - Answer dialog doesn't go away after being dismissed until entire script executes](https://quality.livecode.com/show_bug.cgi?id=22765)

The reporter provided a helpful sample stack that allowed us to test and confirm the problem quickly.
-->

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop-9.6` branch

Then try one of these:

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

- [Brian Milby](https://github.com/bwmilby)
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)* 
- *[runrevmark](https://github.com/runrevmark)* 


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Apple Transporter for iOS uploads?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg108524.html)

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
