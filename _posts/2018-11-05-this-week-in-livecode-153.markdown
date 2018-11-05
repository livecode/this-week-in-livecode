---
layout: post
title:  "This Week In LiveCode 153"
date:   2018-11-05 14:30
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

- [This month only: Get a Hacktoberfest t-shirt by contributing to LiveCode](https://hacktoberfest.digitalocean.com): Submit 5 pull requests and get a free Hacktoberfest T-shirt!
--->

### Interesting discussions

- [Mysteries of "Me"](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98756.html)
- [How to find the offset of the last instance of a repeating character	in a string?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98757.html)
- [Continual iOS Simulator Problems](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98779.html)
- [Interactive Tutorials - Where are they?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98786.html)
- [SSL with HTTPD Library?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98797.html)
- [Browser widget and mailto link](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98800.html)
- [tree view hide key](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98802.html)
- [LiveCode Pseudo Captcha?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98816.html)
- [Large files crash on Windows 10](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98814.html)
- [Tab between fields on mobile device](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98833.html)
- [Docset Reader released and updates to Make Docset and Livecode.Docset](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98834.html)
- [Re: How to find the offset of the last instance of a repeating character in a string? (Geoff Canyon)](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98836.html)
- [Sorting datagrid column with a tricκ?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98854.html)
- [problem with mobileSetKeyboardType](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98860.html)
- [How to update a css file when using the Browser widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98878.html)

## Updates in the LiveCode open source project

10 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-10-29..2018-11-04&type=Issues).

<!---
### New LiveCode releases

- [LiveCode 9.0.1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97854.html)
--->


### Notable changes

- [Fix emscripten loading capsule from file](https://github.com/livecode/livecode/pull/6769): A problem causing html5 standalones to fail to load when greater than 1MB is now fixed.
- [Fix early window synchronize when taking window](https://github.com/livecode/livecode/pull/6766)
- [Use numeric sort for keys in SE variables list](https://github.com/livecode/livecode-ide/pull/2008)
- [Fix crash when changing cards and acceleratedRendering=true](https://github.com/livecode/livecode/pull/6763)
- [Escape special characters in android standalone label](https://github.com/livecode/livecode/pull/6742)


### Bug of the week

- [Bug 21657 - focusedObject is empty when toggling browse/edit/browse mode breaking selectAll](http://quality.livecode.com/show_bug.cgi?id=21657)

The reporter provided a detailed recipe as well as a helpful simple sample stack that allowed us to test and confirm the problem quickly.



### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  

First read these posts from Trevor DeVore for detailed instructions on:

- [how to submit a pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98530.html)
- [how to add a bugfix note to the pull request](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98585.html)

Then try one of these:

- (Easy) [Docs: Mention that mobile player controller does not show if video file is missing or invalid](https://quality.livecode.com/show_bug.cgi?id=19631)
- (Easy) [Docs: Describe the behavior of stack title/label property](https://quality.livecode.com/show_bug.cgi?id=19660)
- (Easy) [Dictionary entry of the menu keyword is incorrectly formatted](https://quality.livecode.com/show_bug.cgi?id=20364)
- (Easy) [Docs say fullclipboarddata["image"] can be gif, png, or jpeg but BMP data can be present on Windows](https://quality.livecode.com/show_bug.cgi?id=20472)
- (Easy) [Docs: Livecode dictionary entry for videoClip](https://quality.livecode.com/show_bug.cgi?id=21156)
- (Easy) [Docs: specialFolderPath("resources") for stacks with empty filename is not documented](https://quality.livecode.com/show_bug.cgi?id=21183)
- (Easy) [Docs: Datagrid Deleteline and Deletelines commands are no longer synonymous in DG2](https://quality.livecode.com/show_bug.cgi?id=21576)
- (Easy) [Docs: Command line installation needs "-ui" instead of "noui" since LC 9 DP-5](https://quality.livecode.com/show_bug.cgi?id=21340)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Applescript "do script" missing from standalone](http://quality.livecode.com/show_bug.cgi?id=20993)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Medium) [Relayer control crashes livecode](https://quality.livecode.com/show_bug.cgi?id=21460)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)
- (Hard) [Case insensitive matchText returns incorrect result](https://quality.livecode.com/show_bug.cgi?id=15312)


### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- [Sean Cole](https://github.com/seaniepie)
- *[livecodepanos](https://github.com/livecodepanos)*  
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [using the map widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg98780.html)


## Upcoming events

* [LiveCode Global: 12 Months Streamed Live Around the Globe - Running every 2nd month throughout 2018!](https://livecode.com/global/)

Save the dates:

- 15th of November 2018

* [The next LiveCode Conference is in...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94801.html)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
