---
layout: post
title:  "This Week In LiveCode 101"
date:   2017-10-09 14:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community


### News & blog posts

- [Testing 1, 2, 28534](https://livecode.com/testing-1-2-28534/): A very interesting blog post by @livecodeali, describing all the different sorts of tests we run.


### Interesting discussions

- [Size restrictions when cloning or create a control in script](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89854.html)
- [Segmented Control Bugs?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89865.html)
- [Scrollbar control and auto complete confusion](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89879.html)
- [LiveCode documentation set now available for Dash compatible readers](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89895.html)
- [How do I play sound files in HTML5?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89956.html)
- [Expanded dictionary in LC 9](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89964.html)
- [Grouping Controls in selectGroupedControls mode](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89967.html)
- [Atkinson dither algorithm](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89975.html)
- [How to define inclusions of a standalone by script?](http://forums.livecode.com/viewtopic.php?f=8&t=29943)
- [Multiple MouseEnter messages - crash](http://forums.livecode.com/viewtopic.php?f=8&t=29938)
- [Could not find plist template for device target](http://forums.livecode.com/viewtopic.php?f=49&t=29933)


## Updates in the LiveCode open source project

47 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-10-02..2017-10-08&type=Issues).


### New LiveCode releases

- [LiveCode 8.1.7 RC-3](https://downloads.livecode.com/livecode/#8_1_7)

LiveCode 8.1.7 RC-3 contains an important change:

Using Xcode 9 for building iOS standalones in LiveCode 8.1.7 RC-3 now
creates a universal binary, i.e. the binary contains both a 32bit slice and
a 64bit slice. This means that you can install it in older Apple devices
that have a 32bit chip (and thus require the app to have a 32bit slice),
such as iPhone 5, iPhone 5c and 4th gen iPad.

This was not possible in LiveCode 8.1.7 RC-2.


### Notable changes

- [Ensure effects popup palettes have correct height](https://github.com/livecode/livecode-ide/pull/1774): A LC 9 regression is now fixed.
- [Fixed bug causing crash on mouseEnter](https://github.com/livecode/livecode/pull/5990)
- [Fix optionKeyDown handler](https://github.com/livecode/livecode-ide/pull/1767)
- [Add emscripten deploy library](https://github.com/livecode/livecode/pull/5962): A list of all installed browsers will now appear under the "Test Target" button, when building a HTML5 standalone.
- [Fix unicode not showing in browser's htmlText](https://github.com/livecode/livecode/pull/5387)
- [Check order of buttons when returning answer dialog result](https://github.com/livecode/livecode/pull/5969)
- [Fix segmented control docs mismerge](https://github.com/livecode/livecode/pull/6021): A LC 9 regression is now fixed.
- Lots of fixes (regarding invalid links, malformed text) in various dictionary entries in LiveCode 8.2.x. Thanks @livecodesam :)

### Bug of the week

- [Bug 20507 - "read from socket X for 1" works in 6.1.1, not 8.1.6](http://quality.livecode.com/show_bug.cgi?id=20507)
- [Bug 20506 - Hilite color of list field in modal stack is gray when initially displayed](http://quality.livecode.com/show_bug.cgi?id=20506)

In both of these reports, the reporters attached a simple and helpful sample stack, and provided useful info and a detailed recipe that helped us to test and confirm the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [MouseEnter / MouseLeave infinite Loop trap - documentation enhancement](http://quality.livecode.com/show_bug.cgi?id=20529)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Easy) [Info missing from mobileGetContactData entry](http://quality.livecode.com/show_bug.cgi?id=20359)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [LC8 Dictionary Copy **using cmd+C** only works after Run Tool selected](http://quality.livecode.com/show_bug.cgi?id=17819)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Brian Milby](https://github.com/bwmilby)
- [James Hale](https://github.com/jameshale)
- [Josh Chiu](https://github.com/HedgeHao)
- *[livecodealex](https://github.com/livecodealex)*
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodemichael](https://github.com/livecodemichael)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

- [the dreaded "cannot connect to iTunes" - inapp purchase problem](http://forums.livecode.com/viewtopic.php?f=49&t=29923)

## Upcoming events

* [LiveCode Global: Our Next Conference in Your City](https://livecode.com/livecode-global-our-next-conference-in-your-city/): 48 hours of Conference content streamed live around the globe! Save the dates:

- 19th of October 2017
- 16th of November 2017

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
