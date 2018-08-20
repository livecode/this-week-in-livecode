---
layout: post
title:  "This Week In LiveCode 142"
date:   2018-08-20 10:00
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

- [Help Support LiveCode - Open Source Needs You](https://mailchi.mp/57bd2132b4ac/support-livecode-open-source)
--->


### Interesting discussions

- [Cropping a referenced image](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96951.html)
- [Database data & emoji's](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96978.html)
- [Determine if device is a tablet](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96980.html)
- [Preview HTML of a field](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97010.html)
- [copying large string from clipboard is slooooow](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97033.html)
- [scaleFactor](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97040.html)
- [Not many people know this - Setting char-level styles](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97047.html)
- [Bluetooth detection and use?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97056.html)
- [filter list_of_files with REGEX xyz?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97079.html)
- [fullscreenmode and rect of a substack on mobile device?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97103.html)
- [Logging](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97105.html)
- [Split an Array to Numeric with 2 Dimensions](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97108.html)
- [Navigator 6.0 Alpha 4](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97111.html)
- [Socket questions](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97119.html)
- [Mac standalone size](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg97126.html)
- [Non sorted tree view display](http://forums.livecode.com/viewtopic.php?t=31411&p=170278#p170278)
- [Returning to LiveCode](http://forums.livecode.com/viewtopic.php?t=31404&p=170184#p170184)
- [encrypting content in standalone stack](http://forums.livecode.com/viewtopic.php?t=31401&p=170146#p170146)


## Updates in the LiveCode open source project

11 pull requests were [merged since the last issue](https://github.com/search?q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2018-08-14..2018-08-19&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 9.0.1 RC-1](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg95867.html) Get this new release that includes more than 90 bugfixes and performance improvements.
--->


### Notable changes

- [Ensure emscripten startup_script is suitable for capsule section](https://github.com/livecode/livecode/pull/6639): This fixes a recent regression where libURL did not work in html5 standalones
- [Fix automatic architecture detection on some Linux systems](https://github.com/livecode/livecode/pull/6635)
- [Fix crash on startup in iOS 12 beta](https://github.com/livecode/livecode/pull/6622)
- [Dirty rect even if layer id is 0](https://github.com/livecode/livecode/pull/6620): This fixes a regression when scrolling a group on Android with acceleratedRendering=true
- [Handle return correctly in fileds on Android](https://github.com/livecode/livecode/pull/6618)


### Bug of the week

- [Bug 21491 - pageHeights function returns erroneous values](http://quality.livecode.com/show_bug.cgi?id=21491)

The user provided a helpful stack and a detailed recipe that allowed us to test, confirm and fix the problem quickly.


### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Docs: The first example in mobileSetKeyboardType users an invalid parameter](https://quality.livecode.com/show_bug.cgi?id=21406)
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
- (Hard) [Case insensitive matchText returns incorrect result](https://quality.livecode.com/show_bug.cgi?id=15312)


### Contributors this week

- [andrewferguson](https://github.com/andrewferguson)
- [Brian Milby](https://github.com/bwmilby)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*


## Other LiveCode News

<!---
This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Tutorial for MAP widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg96771.html)
--->


## Upcoming events

* [LiveCode Global: 12 Months Streamed Live Around the Globe - Running every 2nd month throughout 2018!](https://livecode.com/global/) 

Save the dates:

- 20th of September 2018
- 15th of November 2018

* [The next LiveCode Conference is in...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg94801.html)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
