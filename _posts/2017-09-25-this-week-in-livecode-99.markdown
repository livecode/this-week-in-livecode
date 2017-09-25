---
layout: post
title:  "This Week In LiveCode 99"
date:   2017-09-25 14:00
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

- [NEW Autocomplete & Live Errors in LiveCode 8.2](https://livecode.com/new-autocomplete-live-errors-in-livecode-8-2/)
--->


### Interesting discussions

- [Constraining an input field's contents to be a single line](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89544.html)
- [SivaSiva iOS App Approved - Android Issues/AcceleratedRendering issues](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89547.html)
- [Behaviors](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89551.html)
- [Dash "Make DocSet" stack version 1.6. and non-Mac Dash readers](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89556.html)
- [= sign in script editor, Mac](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89561.html)
- [shell - c and java code](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89576.html)
- [Setting the acceleratedRendering to true on startup on Android 7 and	Android 8](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89585.html)
- [(Browser) Widget documentation](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89591.html)
- [Moving on from 8.* to 9.*](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89606.html)
- [Scrolling Groups on Mobile - Show a little of what is below](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89621.html)
- [Best way to copy from one stack to another](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89622.html)
- [How to to type bottom to up and right to left in a field](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89626.html)
- [HTML5 and Copy and Pasting of graphics?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89681.html)
- [How to offset placement of referenced images?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89682.html)
- [Developing Methods: Creating Scrolling groups larger than screen rect](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89696.html)
- [IPad Mini reports "not supported"](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89704.html)
- [LCB: Speed difference between LC 8 and LC 9?](http://forums.livecode.com/viewtopic.php?t=29793&p=158415#p158415)
- [LCB in LC 9: Speed difference between Business and Community?](http://forums.livecode.com/viewtopic.php?t=29794&p=158417#p158417)


## Updates in the LiveCode open source project

56 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-09-18..2017-09-24&type=Issues).


### New LiveCode releases

- [LiveCode 9.0.0 DP-9](https://downloads.livecode.com/livecode/#9_0_0)


### Notable changes

- [Fix issues with breakpoint movement on edit](https://github.com/livecode/livecode-ide/pull/1747)
- [Document android external special folder paths](https://github.com/livecode/livecode/pull/5950)
- [Fix dropped keystrokes on Windows](https://github.com/livecode/livecode/pull/5949)
- [Add android audio recorder library](https://github.com/livecode/livecode/pull/5941)
- [Merge automated prebuilts building into develop](https://github.com/livecode/livecode/pull/5948): This will save us some time and improve our build process.
- [Always add DIB format to clipboard for images](https://github.com/livecode/livecode/pull/5934): The previous "Bug of the week" is now fixed.
- ["Ask file" on Mac broken](https://github.com/livecode/livecode/pull/5909): Thanks @Brian Milby for discovering and fixing this (while building LC from source!) 
- [RevDB database types should be case insensitive](https://github.com/livecode/livecode/pull/5770): A LC 9.x regression in LC Server is now fixed.
- [Prevent crash on iOS if HealthKit is included](https://github.com/livecode/livecode/pull/5963)
- [breakpoints lag Editor scrolling](https://github.com/livecode/livecode-ide/pull/1703): Great to see community PRs and community comments in the PR :)
- Lots of fixes (regarding invalid links, malformed text) in various dictionary entries in LiveCode 9.x

### Bug of the week

- [Bug 20420 - Paste + undo in IDE leaves field LOOKING blank until next input](http://quality.livecode.com/show_bug.cgi?id=20420)

The reporter attached a simple and helpful sample stack, and provided a detailed recipe that helped us to test and confirm the problem quickly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Improvement in 'open socket' dictionary entry](http://quality.livecode.com/show_bug.cgi?id=19597)
- (Easy) [outputTextEncoding - parameter description format mixed up](http://quality.livecode.com/show_bug.cgi?id=19351)
- (Easy) [Info missing from mobileGetContactData entry](http://quality.livecode.com/show_bug.cgi?id=20359)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [LC8 Dictionary Copy **using cmd+C** only works after Run Tool selected](http://quality.livecode.com/show_bug.cgi?id=17819)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Dictionary: The LiveCode Script Guide cannot be searched](http://quality.livecode.com/show_bug.cgi?id=15957)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [Bob Hall](https://github.com/bhall2001)
- [Brian Milby](https://github.com/bwmilby)
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

- [Script Editor Autocomplete Optional?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89410.html)
- [Need a MergAV for dummies guide](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89401.html)
- [New license type](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89403.html)
- [Converting iOS app build to .ipa file - latest iTunes update stops you doing this](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89427.html)
- [tsNet - tsNetSmtpSync](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg89467.html)
--->


## Upcoming events

* [LiveCode Global: Our Next Conference in Your City](https://livecode.com/livecode-global-our-next-conference-in-your-city/): 48 hours of Conference content streamed live around the globe! Save the dates:

- 19th of October 2017
- 16th of November 2017

* [5th Oct : SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&t=29750)


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
