---
layout: post
title:  "This Week In LiveCode 124"
date:   2018-04-09 14:00
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

- [Audio recording fails when trying to record video](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93793.html)
- [memory databases fail in Windows](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93799.html)
- [Odd Name Resolution](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93808.html)
- [v9 experience grinds to a halt. non-functioning breakpoints.](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93820.html)
- [configuring a Windows Installer for a Standalone](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93854.html)
- [commandine standalone using 100% of core on doing what?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93868.html)
- [Understanding numberformat](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93897.html)
- [formatForPrinting](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93907.html)
- [Project Browser Goes Blank - How To Refresh](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93928.html)
- [RevMail - Status in 9.0](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93929.html)
- [Widget User Defined Properties](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93934.html)
- [Android Can't Find Path to Web folder](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93940.html)

## Updates in the LiveCode open source project

10 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-04-03..2018-04-08&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 9 is out, read all about it here](https://us7.campaign-archive.com/?u=8404b344b09103bf489dd8a9a&id=c574bcb9b3)
--->


### Notable changes

- [Make sure stack and pending stack limit are the same](https://github.com/livecode/livecode/pull/6472)
- [Fixed errors when setting textFont/textSize on Android native button](https://github.com/livecode/livecode/pull/6470)
- [Enhance TreeView numeric sort to sort non-numbers](https://github.com/livecode/livecode/pull/6464) Thanks @BrianMilby
- [Prevent index errors when expanding TreeView buffer](https://github.com/livecode/livecode/pull/6463)
- [Prevent TreeView chunk out of range error on Linux](https://github.com/livecode/livecode/pull/6461)
- [Update windowBoundingRect](https://github.com/livecode/livecode-ide/pull/1954)
- [Add default points for polygon graphic](https://github.com/livecode/livecode-ide/pull/1947)
- [Detect missing dependencies when installing package](https://github.com/livecode/livecode-ide/pull/1945)
- [Allow tab in text property of PI](https://github.com/livecode/livecode-ide/pull/1943)
- [Skip tracing resizeControl](https://github.com/livecode/livecode-ide/pull/1935)


### Bug of the week

- [Bug 21137 - (Styled Text) line height incorrect when fixedLineHeight = false](http://quality.livecode.com/show_bug.cgi?id=21137)

The reporter provided useful info, a detailed recipe as well as a helpful sample stack that allowed us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

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
- *[livecodemichael](https://github.com/livecodemichael)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [tsnet on Mac doesn't follows htaccess rewrite rule](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93834.html)



## Upcoming events

* [LiveCode Global: 12 Months Streamed Live Around the Globe - Running every 2nd month throughout 2018!](https://livecode.com/global/) 

Save the dates:

- 17th of May 2018
- 19th of July 2018
- 20th of September 2018
- 15th of November 2018


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
