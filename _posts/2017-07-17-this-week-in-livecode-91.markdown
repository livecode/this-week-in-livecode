---
layout: post
title:  "This Week In LiveCode 91"
date:   2017-07-17 14:00
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

- [Using Infinite LiveCode for Android to Create Native Controls and Wrap OS APIs](https://livecode.com/using-infinite-livecode-for-android-to-create-native-controls-and-wrap-os-apis/)
--->


### Interesting discussions

- [No screenshot from LC video possible](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86844.html)
- [Refreshing question](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86903.html)
- [Server Basics Everyone Should Do](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86868.html)
- [Set the tooltip of a datagrid](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86879.html)
- [north widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86900.html)
- [Native Livecode Pinch and Zoom](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86901.html)
- [dgToolTip Snippet](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86945.html)
- [Codesigning fail LC 8.1.5, Xocde 8.3.3](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86947.html)
- [Finding errors in a standalone](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86970.html)
- ["Silly" fun for the weekend](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86977.html)
- [intersect . . . invisible images](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg86978.html)
- [High Sierra & LC](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87006.html)
- [Correct img format for browser widget](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87027.html)
- [Bug? ResizeControl Triggers From Outside of CustomControl with Assigned Behavior](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87037.html)
- [Mobile - missing? files added in copy files pane of standalone builder](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87046.html)
- [Weird variable thing in 8.1.5](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87060.html)
- [Help Testing Small Script Editor Enhancement](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87064.html)

  
## Updates in the LiveCode open source project

30 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-07-10..2017-07-16&type=Issues).


### New LiveCode releases

- [LiveCode 8.1.5](https://downloads.livecode.com/livecode/#8_1_5)
- [LiveCode 8.1.6 RC-1](https://downloads.livecode.com/livecode/#8_1_6)
- [LiveCode 9.0.0 DP-8](https://downloads.livecode.com/livecode/#9_0_0)



### Notable changes

- [Fix up all dictionary 'message' entries](https://github.com/livecode/livecode/pull/5693): The parameter names of the default handlers can no longer be a reserved name
- [LCB: Fix image from resource path](https://github.com/livecode/livecode/pull/5690): A LC-9 regression is now fixed
- [LCB: Add basic support for Objective-C FFI](https://github.com/livecode/livecode/pull/5688): A Mac native button widget is now added in the LC's widget collection
- [Fixed: Inline Docs parsing incorrect when handler spans over \ delimited lines](https://github.com/livecode/livecode/pull/5683)
- [Statically link libstdc++ in Android shared libs](https://github.com/livecode/livecode/pull/5678): This fixes a crash on startup on Android if some externals are included
- [Add a QR Generator library](https://github.com/livecode/livecode/pull/5671): The public domain licensed QR Code Generator Library (sQuiRt) by John Craig has been added to the community repository for ease of maintenance and use
- [Add a list of default handlers associated with the object in the Script Editor](https://github.com/livecode/livecode-ide/pull/1656)
- [Add Edit Behavior Script contextual menu](https://github.com/livecode/livecode-ide/pull/1648)
- [Add android native field widget](https://github.com/livecode/livecode/pull/5647)
- [Allow accessing Image/Object Library from LC menubar](https://github.com/livecode/livecode-ide/pull/1655): A LC-8 regression is now fixed

### Bug of the week

- [Bug 19997 - The printPaperRectangle is set to the printRectangle ](http://quality.livecode.com/show_bug.cgi?id=19997)

The reporter not only provided a detailed recipe that helped us to test and confirm the problem quickly, but also identified the LiveCode version where this bug was introduced .

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
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

* [3rd August - Pasadena: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=29460)

* [LiveCode Global: Our Next Conference in Your City](https://livecode.com/livecode-global-our-next-conference-in-your-city/): 48 hours of Conference content streamed live around the globe! Save the dates:

- 17th of August 2017
- 21st of September 2017
- 19th of October 2017
- 16th of November 2017


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
