---
layout: post
title:  "This Week In LiveCode 62"
date:   2016-12-12 11:15
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

* [LiveCode Widgets: The "Spinner" Activity Indicator](https://livecode.com/livecode-widgets-the-spinner-activity-indicator/)
* [LiveCode is on Gitter](https://gitter.im/LiveCode/)
* [Support LiveCode open source with OSS Membership](https://livecode.org/membership/)

### Interesting discussions

* [Installer software](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80954.html)
* [Behaviors and the message path](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80949.html)
* [Compiler not catching bad exit within routine](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg80906.html)

## Updates in the LiveCode open source project

30 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-12-04..2016-12-11&type=Issues&ref=searchresults).

### Notable changes

- [Show up to 10 nested behaviors in the Project Browser](https://github.com/livecode/livecode-ide/pull/1508):
  This PR was submitted on behalf of [BerndN](https://github.com/BerndN), and it allows up to 10 nested behaviors to be shown in the PB. 
- [Reinstate text props and graphic effects to DataGrid Property Inspector](https://github.com/livecode/livecode-ide/pull/1509):
  The LC-8 DataGrid Property Inspector was missing some text props and graphic effects. Now they are back :)
- [LCB modules can declare Android app permissions and features](https://github.com/livecode/livecode/pull/4969):
  LCB module metadata is now checked for Android permissions which will be added to the manifest when building for Android.
- [Set the maximum text length for an iOS native (single-line) input field](https://github.com/livecode/livecode/pull/4975):
  It is now possible to set/get the maximum number of characters that can be entered into an ios native single-line field, using the new "maximumTextLength" property
- [Support multi-module assemblies in "load extension"](https://github.com/livecode/livecode/pull/4970)
- [Make sure CMYK images display correctly on Mac](https://github.com/livecode/livecode/pull/4950)

### Bug of the week

[Bug 18924 - Mobile scroller misaligned when setting vScroll](http://quality.livecode.com/show_bug.cgi?id=18927)

When setting the initial vScroll for a newly created native scroller on Android, the resulting scroll is misaligned,
causing incorrect (or sometimes no) scrolling behavior.

The reporter of this bug provided a clear, detailed recipe and a helpful
sample stack that demonstrates the problem.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) [Add a default script for scroll bars](http://quality.livecode.com/show_bug.cgi?id=17851)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [asayd](https://github.com/asayd)
- [BerndN](https://github.com/BerndN)
- [trevordevore](https://github.com/trevordevore)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*

<!---
## Upcoming events
-->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
