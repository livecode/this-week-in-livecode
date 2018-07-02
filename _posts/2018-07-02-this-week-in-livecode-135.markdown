---
layout: post
title:  "This Week In LiveCode 135"
date:   2018-07-02 15:00
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

- [Datagrid Behaviors Moved??](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95606.html)
- [What exactly does the status pending in Livecode Quality Control	Center mean](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95614.html)
- [iOS 12 compatibility](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95630.html)
- [Behaviors not honoring script local variables??](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95637.html)
- [Tessellated hexagonal grid?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95654.html)
- [Grabbing a widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95661.html)
- [Array Column Subset Revisited](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95700.html)
- [Sort IP List](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95709.html)
- [LCB Foreign LC9.0.0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95724.html)
- [bitwise shifts gone?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95742.html)
- [MouseMove and HTML5](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95743.html)
- [WooCommerce API Manager & Livecode](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95759.html)
- [Field entry cursor](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95767.html)
- [Stripping styling from the clipboard...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95558.html)
- [How to get the dimensions of an image with LC server?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95560.html)
- [Translation Service Deepl.com](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95585.html)
- [Top Bottom Left Right](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95592.html)

## Updates in the LiveCode open source project

14 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-06-25..2018-07-01&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 8.1.10](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94867.html) Note 8.1.10 STABLE is the last planned release in the 8.x series.
--->


### Notable changes

- [Set clipsToBounds of native container layer](https://github.com/livecode/livecode/pull/6598)
- [Redraw the entire stack before hiding bitmap view](https://github.com/livecode/livecode/pull/6596)
- [Ensure device can register for and receive remote notifications on Android](https://github.com/livecode/livecode/pull/6593)
- [Use app platform 16 with target sdk 26](https://github.com/livecode/livecode/pull/6588)
- [Android: Add support to thirdparty libs for additional CPU architectures](https://github.com/livecode/livecode-thirdparty/pull/116)
- [Clear unshared data when compacting stack](https://github.com/livecode/livecode/pull/6560)

### Bug of the week

- [Bug 21386 - Browser widget out of grouped rect on iOS](http://quality.livecode.com/show_bug.cgi?id=21386)

The user provided useful info, a detailed recipe as well as a helpful sample stack that allowed us to test, confirm and fix the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Docs: Command line installation needs "-ui" instead of "noui" since LC 9 DP-5](https://quality.livecode.com/show_bug.cgi?id=21340)
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
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*



## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Remote URL Not Available](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95626.html)
- [tsNet issues](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95696.html)
- [Mastering tsNet](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95770.html)


## Upcoming events

* [5th of July : SoCal LiveCode Group meetup - Pasadena](http://forums.livecode.com/viewtopic.php?f=50&t=31125)

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
