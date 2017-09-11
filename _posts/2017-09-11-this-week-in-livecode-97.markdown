---
layout: post
title:  "This Week In LiveCode 97"
date:   2017-09-11 14:00
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

- The Pittsburgh, Pennsylvania LiveCode Education Group held a recent meeting on August 24. We welcomed new member Cyril Pruszko, 
who is moving to the area. We discussed plans to offer opportunities to learn LiveCode in the region. Please get in touch with 
Claire Siskin, csiskin@edvista.com, if you would like to be involved in this initiative or to attend our next meeting.
--->

### Interesting discussions

- [Deploying to Android (Amazon Fire 7)](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89195.html)
- [customPropertyless](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89199.html)
- [Selections in Text Editor Revisited](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89252.html)
- [I just posted an Augmented Earth sample stack on LiveCode share](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89255.html)
- [DataGrid in group with backgroundbehavior?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89260.html)
- [Windows standalone seems double the file size in every version past 8.14](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89276.html)
- [Vector graphics, again](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89288.html)
- [replace and unicode?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89289.html)
- [private command gotcha](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89298.html)
- [script/engine broken when moved to 64bit server at JaguarPC](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89314.html)
- [Getting saucy](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89330.html)
- [Android Audio Playback & Recording](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89337.html)
- [Rotate text 90 degrees?](http://forums.livecode.com/viewtopic.php?t=29734&p=157985#p157985)

## Updates in the LiveCode open source project

44 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-09-04..2017-09-10&type=Issues).


### New LiveCode releases

- [LiveCode 8.1.7 RC-1](https://downloads.livecode.com/livecode/#8_1_7):


### Notable changes

- [Fix infinite loop](https://github.com/livecode/livecode-ide/pull/1725)
- [Backport spinner widget](https://github.com/livecode/livecode/pull/5920)
- [Ensure the IDE uses valid DB connections](https://github.com/livecode/livecode-ide/pull/1724)
- [Save script selection when updated](https://github.com/livecode/livecode-ide/pull/1721)
- [Mac folder dialog missing "add folder" button](https://github.com/livecode/livecode/pull/5915): A 8.1.7-rc-1 regression spotted and fixed by @Brian Milby.
- [Add natural int and float types](https://github.com/livecode/livecode/pull/5910)
- [Add aggregate support to LCB](https://github.com/livecode/livecode/pull/5904)
- [Fetch key codes of modifier keys in keysDown](https://github.com/livecode/livecode/pull/5899)
- [Fix crash when using file dialogs from browser widget](https://github.com/livecode/livecode/pull/5896)
- [Add thread affinity for iOS](https://github.com/livecode/livecode/pull/5724)

### Bug of the week

- [Bug 20336 - set the clipboardData["text"] does not produce real plain text but RTF text](http://quality.livecode.com/show_bug.cgi?id=20336)

The reporters attached a simple and helpful sample stack, and provided a detailed recipe that helped us to test and confirm the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Easy) [Info missing from mobileGetContactData entry](http://quality.livecode.com/show_bug.cgi?id=20359)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [LC8 Dictionary Copy **using cmd+C** only works after Run Tool selected](http://quality.livecode.com/show_bug.cgi?id=17819)
- (Medium) [Dictionary auto-searches on first char freezing cursor](http://quality.livecode.com/show_bug.cgi?id=18739)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- [macMikey](https://github.com/macMikey)
- [Martin Koob](https://github.com/MartinKoob)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [remote debugging just stopped being available?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89173.html)


## Upcoming events

* [LiveCode Global: Our Next Conference in Your City](https://livecode.com/livecode-global-our-next-conference-in-your-city/): 48 hours of Conference content streamed live around the globe! Save the dates:

- 21st of September 2017
- 19th of October 2017
- 16th of November 2017


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
