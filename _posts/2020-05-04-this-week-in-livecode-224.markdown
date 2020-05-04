---
layout: post
title:  "This Week In LiveCode 224"
date:   2020-05-04 15:30
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community


### News & blog posts

- [Making the tiger roar](https://livecode.com/making-the-tiger-roar/)


### Interesting discussions

- [Counting unique items in a file](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107699.html)
- [Dark Mode support and iOS startup screens](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107711.html)
- [Can a stack know which standalone engine it's running on?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107713.html)
- [Quick IDE question](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107738.html)
- [Best relational database for IOS / Android](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107742.html)
- [Livecode HTML5 and SQL](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107747.html)
- [Spell Checker](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107762.html)
- [sqLite delete memory database](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107774.html)
- [FormattedHeight](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107779.html)
- [Script Only Behaviors](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107783.html)
- [DataView and DataView Tree Updates](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107791.html)
- [Group resizing](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107814.html)
- [Has anyone experience of GPS on iPhone?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107828.html)
- [system date](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107839.html)
- [the chosen folder is not a valid android sdk](http://forums.livecode.com/viewtopic.php?t=34010&p=191027#p191027)
- [App fails to launch when downloaded](http://forums.livecode.com/viewtopic.php?t=34007&p=191011#p191011)
- [mobilePickDate doesn't work on some iphones](http://forums.livecode.com/viewtopic.php?t=34005&p=191002#p191002)
- [Android emulator problem. Isn't there an easy way?](http://forums.livecode.com/viewtopic.php?f=7&t=34014&p=191217#p191217)

## Updates in the LiveCode open source project

11 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2020-04-27..2020-05-03&type=Issues).

<!---
### New LiveCode releases

- [Release 9.6.0 DP-4](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107407.html)
--->

### Notable changes

- [Improve performance of stackfile saving on Windows](https://github.com/livecode/livecode/pull/7342)
- [LifecycleListeners: Allow lcb widgets to register and listen for Android lifecycle events](https://github.com/livecode/livecode/pull/7339)
- [Add dark mode options for iOS launch screen](https://github.com/livecode/livecode-ide/pull/2130)
- [Load startup screen storyboard](https://github.com/livecode/livecode/pull/7308)
- [Fix bug in Win32 stdcall closure trampoline](https://github.com/livecode/livecode-thirdparty/pull/145)


### Bug of the week

- [Bug 22706 - DragDrop not dropping on intended target object](https://quality.livecode.com/show_bug.cgi?id=22706)

The reporter provided a detailed recipe and a helpful sample stack that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98611.html)

Note: Any new bug-fixing PRs should be submitted against `develop` branch

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

- *[livecodeian](https://github.com/livecodeian)*
- *[livecodemichael](https://github.com/livecodemichael)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*  
- *[runrevmark](https://github.com/runrevmark)* 


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [mergAV Select specific rear camera](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107763.html)
- [Most obscure HC question](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg107796.html)

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
