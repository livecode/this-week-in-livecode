---
layout: post
title:  "This Week In LiveCode 136"
date:   2018-07-09 15:00
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

- [When I assume ...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95790.html)
- [Deploying to Android from Linux](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95805.html)
- [Future support for Serial Coms](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95826.html)
- [WebDocMaker / Online Dictionary](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95829.html)
- [Capture Keystrokes & MouseMovements without being in focus?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95837.html)
- [odbc "information type out of range"](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95843.html)
- [LiveCode 6.6.3 crashing and saving only part of a stack file](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95848.html)
- [What are possible reasons for memory consumption going up on stack that isn't doing much?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95851.html)
- [Standalone in IDE Test Works; But Not From SA](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95854.html)
- [ScreenRect](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95858.html)
- [Unable to install LC 9 on Ubuntu 18.04](http://forums.livecode.com/viewtopic.php?t=31245&p=168833#p168833)


## Updates in the LiveCode open source project

7 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-07-01..2018-07-08&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 8.1.10](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94867.html) Note 8.1.10 STABLE is the last planned release in the 8.x series.
--->


### Notable changes

- [Fix crash in Mac player when changing filename repeatedly in a loop](https://github.com/livecode/livecode/pull/6607)
- [Do not split up .framework folders between MacOS and Resources/_MacOS…](https://github.com/livecode/livecode/pull/6606)
- [Fix crash on resume in commercial android engine](https://github.com/livecode/livecode/pull/6604)
- [Add stereo balance & panning properties to mac player](https://github.com/livecode/livecode/pull/6603)
- [Fix pattern to filter android externals](https://github.com/livecode/livecode/pull/6601)
- [Improve appearance of Motif theme disabled button text / icons](https://github.com/livecode/livecode/pull/6456)

### Bug of the week

- [Bug 21402 - AWSS3PutBucket fails when creating a bucket in a region other than us-east-1](http://quality.livecode.com/show_bug.cgi?id=21402)

The user provided useful info, a detailed recipe as well as a helpful sample stack that allowed us to test and confirm the problem quickly.

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

- [Trevor DeVore](https://github.com/trevordevore)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[montegoulding](https://github.com/montegoulding)*


<!---
## Other LiveCode News


This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Remote URL Not Available](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95626.html)
- [tsNet issues](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95696.html)
- [Mastering tsNet](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95770.html)
--->


## Upcoming events

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
