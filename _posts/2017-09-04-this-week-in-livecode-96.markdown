---
layout: post
title:  "This Week In LiveCode 96"
date:   2017-09-04 14:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community


### News & blog posts

- The Pittsburgh, Pennsylvania LiveCode Education Group held a recent meeting on August 24. We welcomed new member Cyril Pruszko, 
who is moving to the area. We discussed plans to offer opportunities to learn LiveCode in the region. Please get in touch with 
Claire Siskin, csiskin@edvista.com, if you would like to be involved in this initiative or to attend our next meeting.


### Interesting discussions

- [sms,MMS, and Push Notifications](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88459.html)
- [Couple of questions about the browser widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88507.html)
- [answer with...](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88524.html)
- [Developing first on android](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88548.html)
- [htaccess rewrite rule to https let my apps stop working](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88554.html)
- [lock screen gotcha revisited](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88587.html)
- [Daybed 2.0 - A Library for Apache CouchDB](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88594.html)
- [Keeping keys of an array in the order they came in?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88601.html)
- [Sending a message to users that floats above everything](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88627.html)
- [acceleratedRendering scope](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88655.html)
- [Paint tools and image creation](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88696.html)
- [Bad Crash on Attempt to Group Radio Buttons](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88739.html)
- [Search Values of Array in "One Go"](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88765.html)
- [Thoughts on BLOBs in SQLite](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88772.html)
- [Notifications system using "the files"? bad idea?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88791.html)
- [Sierra update --> Xcode install --> LC no provisioning profile](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88803.html)
- [Browser widget android local file problem](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88848.html)
- [webP and webM support in LiveCode](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88859.html)
- [Site won't load](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88887.html)
- [Video files not showing on my PC](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88915.html)
- [LiveCode changes image colors without being asked to do it](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89029.html)
- [Does exporting a snapshot from a rect work on mobile?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89045.html)
- [LC and OneSignal](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89092.html)
- [LC on Raspberry Pi3](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89122.html)
- [Print to PDF output dodgy on Windows](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89162.html)
- [Installing SDK and AVD and start Emulator from Command Line](http://forums.livecode.com/viewtopic.php?f=53&t=29714)
  
## Updates in the LiveCode open source project

104 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-08-14..2017-09-03&type=Issues).


### New LiveCode releases

- [LiveCode 8.1.6](https://downloads.livecode.com/livecode/#8_1_6):

Since the week beginning 21st August 2017, LiveCode iOS apps are being
rejected by iTunes Connect due to 'invalid binary'. It turns out that Apple
have upgraded the tools they use to analyse binaries, and this has shown an
error in the Mach-O structure of the 64-bit slice. The version of otool
with Xcode 6.x (on 10.9) does not show a problem, but newer versions do.

For this reason, we have built a new version of LiveCode 8.1.6 that
addresses this issue.

So if you have already installed the original LiveCode 8.1.6 and are
affected by this issue, please visit now

http://downloads.livecode.com/livecode/

and download the latest 8.1.6 (STABLE), released on the 31st of August.



### Notable changes

- [Ensure 'the engine folder' returns a LiveCode path](https://github.com/livecode/livecode/pull/5881)
- [Improve export/import snapshot from screen on iOS7+](https://github.com/livecode/livecode/pull/5880)
- [Check for DIB and DIBV5 clipboard formats](https://github.com/livecode/livecode/pull/5878): You can now paste from MS Paint to LC.
- [Fix crash when revsecurity didn't load](https://github.com/livecode/livecode/pull/5865)
- [Fix text selection not contiguous](https://github.com/livecode/livecode/pull/5862): A long standing issue is now hopefully fixed.
- [Fix crash on startup when resuming android app after quit](https://github.com/livecode/livecode/pull/5807): An annoying LC 8.x regression is now fixed.
- [SegmentedControl: Add toggleHilites property](https://github.com/livecode/livecode/pull/5793)
- [Non-LF line endings in script only stacks](https://github.com/livecode/livecode/pull/5792): Thanks @Brian Milby!
- [Fix crash when restoring taskbar visibility on exit](https://github.com/livecode/livecode/pull/5791)
- [Allow inspector to have smaller width](https://github.com/livecode/livecode-ide/pull/1711)
- [Handle BOM for Script-only stacks from URLs](https://github.com/livecode/livecode/pull/5780)
- [Fix crash when inserting large binary data to SQLite databases that aren't opened with the "binary" option](https://github.com/livecode/livecode/pull/5776)
- Plus tens of fixes in Dictionary entries, including correction of typos, broken links, malformed text etc. Thanks @Sam Norris!

### Bug of the week

- [Bug 20281 - Crash on closing a stack containing a player with dontUseQT false](http://quality.livecode.com/show_bug.cgi?id=20281)
- [Bug 20322 - Bad behavior of menu buttons](http://quality.livecode.com/show_bug.cgi?id=20322)

In both of these reports, the reporters attached a simple and helpful sample stack, and provided a detailed recipe that helped us to test and confirm the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [LC8 Dictionary Copy **using cmd+C** only works after Run Tool selected](http://quality.livecode.com/show_bug.cgi?id=17819)
- (Medium) [Dictionary auto-searches on first char freezing cursor](http://quality.livecode.com/show_bug.cgi?id=18739)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Bob Hall](https://github.com/bhall2001)
- [Brian Milby](https://github.com/bwmilby)
- [Devin Asay](https://github.com/asayd)
- [techstrategies](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodemichael](https://github.com/livecodemichael)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*

<!---
## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [Submitting to the #%^%#? App Store](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86577.html)
- [Augmented Earth now on the App Store!](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86655.html)
- [Oracle DB driver is now back in LiveCode Business Edition](https://github.com/livecode/livecode/pull/5636)
--->

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
