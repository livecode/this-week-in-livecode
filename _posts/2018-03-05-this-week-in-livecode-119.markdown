---
layout: post
title:  "This Week In LiveCode 119"
date:   2018-03-05 14:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community


### News & blog posts

- [Functional features in LiveCode – is it just a dream?](https://livecode.com/functional-features-in-livecode-is-it-just-a-dream/)




### Interesting discussions

- [IDE Cursor icon often hangs on windows](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93107.html)
- [Background color in an 'answer' dialog?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93111.html)
- [Size of screen diagonal?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93127.html)
- [Another server question (mixing node.js and LC)](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93131.html)
- [building deb packages](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93147.html)
- [Internet checking?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93149.html)
- ["Open in New Navigator" is back](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93153.html)
- [A suggestion for an in-memory database, following up on Richard’s experiment](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93157.html)
- [How to include files in an iOS-App?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93165.html)
- [Font name weirdness](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93172.html)
- [LC server and fonts](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93179.html)
- [Color a graphic on a datagrid](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93188.html)
- [Reverse 'pixelcoloring' and total amount of colors](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93222.html)
- [Hyphenator](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93224.html)


## Updates in the LiveCode open source project

23 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-02-26..2018-03-04&type=Issues).

<!---
### New LiveCode releases

- [LiveCode 8.1.9](https://downloads.livecode.com/livecode/#8_1_9)
--->


### Notable changes

- [Native HTML5 Button Widget](https://github.com/livecode/livecode/pull/6307)
- [Use selected font in android field and button widgets](https://github.com/livecode/livecode/pull/6297)
- [Fix library mapping for installed extensions](https://github.com/livecode/livecode-ide/pull/1915)
- [Ensure nested groups' scripts can be searched](https://github.com/livecode/livecode-ide/pull/1921) 
- [Fix installing extensions from local .lce files](https://github.com/livecode/livecode-ide/pull/1919)
- [Remove -S parameter trailing slash in aapt call](https://github.com/livecode/livecode/pull/6360): Fixes the problem of using a Map Widget on Android when building from Windows.
- [Tree view doesn't allow comma in keys](https://github.com/livecode/livecode-ide/pull/1918)
- [Fix rotated text rendering on Linux](https://github.com/livecode/livecode/pull/6359)
- [Fix font rendering appearance in HTML5](https://github.com/livecode/livecode/pull/6349)
- [Ensure malloc'd pointer is not incremented before free](https://github.com/livecode/livecode/pull/6347): Fixes a long standing crash when calling revDataFromQuery with ODBC databases.



### Bug of the week

- [Bug 21022 - IDE Search doesn't look in grouped groups](http://quality.livecode.com/show_bug.cgi?id=21022)

The reporter provided useful info, a detailed recipe as well as a helpful sample stack that allowed us to test, confirm and fix the problem quickly.


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
- (Medium) [Dragging Out Multiple Files (on Mac) Freezes LiveCode](http://quality.livecode.com/show_bug.cgi?id=20925)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [James Hale](https://github.com/jameshale)
- *[livecodealex](https://github.com/livecodealex)*
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodemiriam](https://github.com/livecodemiriam)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [tsNet Error Codes](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93214.html)
- [tsNet or not tsNet?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg93219.html)



## Upcoming events

* [LiveCode Global: 12 Months Streamed Live Around the Globe - Running every 2nd month throughout 2018!](https://livecode.com/global/) 

Save the dates:

- 15th of March 2018
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
