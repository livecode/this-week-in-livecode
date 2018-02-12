---
layout: post
title:  "This Week In LiveCode 116"
date:   2018-02-12 15:00
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

- [LiveCode 9 - The final preview](https://livecode.com/livecode-9-the-final-preview/)
--->



### Interesting discussions

- [How to calm down the Standalone Builder?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg92603.html)
- [SE: restore default handlers?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg92609.html)
- [Delete imported audioclips?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg92627.html)
- [update to Mkvmerger](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg92654.html)
- [how to format text for copy-pasting as a spreadsheet table](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg92656.html)
- [Execute multiple MySQL commands](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg92657.html)
- [representing this character from a pdf](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg92670.html)
- [LC-Magick #10](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg92717.html)
- [Put URL into variable and textEncoding](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg92718.html)
- [Navigator Update -- Drag and Drop!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg92719.html)
- [Stack for recompiling widgets when switching between LC 8-9](http://forums.livecode.com/viewtopic.php?f=104&t=30433&p=163580#p163582): See attached stack by BerndN ("bn") in post no 9.


## Updates in the LiveCode open source project

10 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-02-05..2018-02-11&type=Issues).

### New LiveCode releases

- [LiveCode 8.1.9](https://downloads.livecode.com/livecode/#8_1_9)


### Notable changes

- [Remove 32bit slice from Mac externals if we build for 64bit only](https://github.com/livecode/livecode/pull/6321) 
- [Clipboard always converts plain text to styled text](https://github.com/livecode/livecode/pull/6293) Thanks @BrianMilby
- [Serialize behavior in script-only-stack format](https://github.com/livecode/livecode/pull/6290) This patch allows setting the behavior of a script-only stack when the script-only stack is loaded.
- [Ensure colors round-trip correctly through styledText](https://github.com/livecode/livecode/pull/6287)
- [Make 'encoding' analyse the specified range of text](https://github.com/livecode/livecode/pull/6254/)
- [Fixed bug that causes crash with bad range chunk](https://github.com/livecode/livecode/pull/6316)

### Bug of the week

- [Bug 20957 - While dragging from a field with a horizontal scrollbar, dragging below/to the right causes bad mouseRelease message](http://quality.livecode.com/show_bug.cgi?id=20957)

The reporter provided useful info, a detailed recipe as well as a helpful sample stack that helped us to test and confirm the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Dictionary: Mention that in ReplaceText function you might need to escape RegExp metacharacters, if the "replacementString" is the char itself (e.g. ".")](http://quality.livecode.com/show_bug.cgi?id=20943)
- (Easy) [Dictionary: Improve documentation for launch URL & specialFolderPath for Android](http://quality.livecode.com/show_bug.cgi?id=20722)
- (Easy) [Dictionary: Mention that iPhone X does not support "portrait upside down" orientation](http://quality.livecode.com/show_bug.cgi?id=20640)
- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [MouseEnter / MouseLeave infinite Loop trap - documentation enhancement](http://quality.livecode.com/show_bug.cgi?id=20529)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Easy) [Info missing from mobileGetContactData entry](http://quality.livecode.com/show_bug.cgi?id=20359)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Medium) [Dragging Out Multiple Files (on Mac) Freezes LiveCode](http://quality.livecode.com/show_bug.cgi?id=20925)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- *[livecodealex](https://github.com/livecodealex)*
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[runrevmark](https://github.com/runrevmark)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [iOS app Error ITMS-90529 submitting to app store via Application	Loader](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg92707.html)



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
