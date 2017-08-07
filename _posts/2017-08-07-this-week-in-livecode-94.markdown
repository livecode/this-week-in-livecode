---
layout: post
title:  "This Week In LiveCode 94"
date:   2017-08-07 14:00
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

- [revHTTP](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87765.html)
- [OT: Hackintosh](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87798.html)
- [httpd library and missed opportunity](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87808.html)
- [Can't use double finger scroll on mac for grouped controls](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87811.html)
- [App Rejected: IPv6 network?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87834.html)
- [Made with . . .](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87838.html)
- [how to get the value of a custom property if the name of the	cProperty is in a variable?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87856.html)
- [merge() only evaluating first expression?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87865.html)
- [Android device speed](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87909.html)
- [MouseDown sent to button in group, but MouseUp sent to card](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87922.html)
- [How to remove from a group](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87947.html)
- [OT-ish: Updating MacBook from El Capitan to Sierra to install Xcode 8.3+](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87955.html)
- [set the clipboarddata["image"] not compatible with Adobe Photoshop](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87978.html)
- [menuHistory & menuPick](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg87989.html)
- [preOpenStack problem](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88000.html)
- [Understanding LiveCode Source - BOM Issue with livecodescript URLs](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg88008.html)
  
## Updates in the LiveCode open source project

25 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-07-31..2017-08-06&type=Issues).


### New LiveCode releases

- [LiveCode 8.1.6](https://downloads.livecode.com/livecode/#8_1_6)


### Notable changes

- [Backport of faster script search](https://github.com/livecode/livecode-ide/pull/1706)
- [Keep android button enabled property in sync](https://github.com/livecode/livecode/pull/5753): A "known issue" affecting the Native Android Button widget is now fixed.
- [Ensure `the controlNames` works with grouped controls too](https://github.com/livecode/livecode/pull/5748)
- [Missing AppleScript Dictionary](https://github.com/livecode/livecode/pull/5743): Brian Milby keeps fixing bugs! Thank you Brian.
- [Ensure import paint into group respects the (parent) group](https://github.com/livecode/livecode/pull/5740): A previous "Bug of the Week" is now fixed
- [Search dictionary with $](https://github.com/livecode/livecode-ide/pull/1695)
- [Sort API Dictionaries](https://github.com/livecode/livecode-ide/pull/1693)
- [Make mac installer dmg image horizontal](https://github.com/livecode/livecode/pull/5710)
- [Fix memory leak in obj-c action proxies](https://github.com/livecode/livecode/pull/5723)
- [Enable control-tab on Mac OS](https://github.com/livecode/livecode-ide/pull/1682)

### Bug of the week

- [Bug 20235 - Offset function hits a limit and stops reporting matching data, but works as expected if stack is saved as legacy 5.5. format](http://quality.livecode.com/show_bug.cgi?id=20235)

The reporter attached a nice and helpful sample stack, and provided a detailed recipe that helped us to test and confirm the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [LC8 Dictionary Copy **using cmd+C** only works after Run Tool selected](http://quality.livecode.com/show_bug.cgi?id=17819)
- (Medium) [Dictionary auto-searches on first char freezing cursor](http://quality.livecode.com/show_bug.cgi?id=18739)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Bob Hall](https://github.com/bhall2001)
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
