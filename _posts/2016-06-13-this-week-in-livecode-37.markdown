---
layout: post
title:  "This Week In LiveCode 37"
date:   2016-06-13 14:00
categories: issue
---

Welcome to *This Week in LiveCode*!  [LiveCode](https://livecode.com/) is a
high-level language with an easy-to-learn English-like syntax.  This is a
weekly summary of what's been going on in the LiveCode open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).
Want to get involved?
[We welcome contributions](https://github.com/livecode/livecode).

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).

This week's edition was edited by [peter-b](https://github.com/peter-b) and [livecodepanos](https://github.com/livecodepanos).

## Updates from the LiveCode open source community

### News & blog posts

- [LiveCode Widgets: SVG Path](https://livecode.com/livecode-widgets-svg-path/)
- Two new LiveCode Builder widgets by PaulMcClernan:
  - [five stars control](https://github.com/PaulMcClernan/livecode.widget.fivestars)
  - [knob control with 10 states](https://github.com/PaulMcClernan/community.livecode.pgmcclernan.tennotchknob)
- macMikey has published two new script libraries:
  - [csvToText](https://github.com/macMikey/csvToText), a CSV parser library
  - v1.12 of the [phxDropboxLib](https://github.com/macMikey/phxDropboxLib) library

### Interesting discussions

- [hasMemory() and why it can't be reliable](http://thread.gmane.org/gmane.comp.ide.revolution.user/227307)
- [Using GPIO on the Raspberry Pi](http://thread.gmane.org/gmane.comp.ide.revolution.user/227298)
- [Why doesn't the "startup" message work in the IDE?](http://thread.gmane.org/gmane.comp.ide.revolution.user/227247)

## Updates in the LiveCode open source project

66 pull requests were [merged since the last issue](https://github.com/search?l=&o=asc&s=created&type=Issues&utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-06-06..2016-06-12).

### Notable changes

- [Improve GPS timestamps on Android](https://github.com/livecode/livecode/pull/4085)
- [Add "vectorDotProduct" function](https://github.com/livecode/livecode/pull/4109)
- **Windows player:**
  - [Fix MP3 support (etc.)](https://github.com/livecode/livecode/pull/4107)
  - [Fix frame seeking](https://github.com/livecode/livecode/pull/4117)
  - [Fix overflow of large player position values](https://github.com/livecode/livecode/pull/4064): Ensure sensible behaviour with really long videos
  - [Pause player when entering edit mode](https://github.com/livecode/livecode/pull/4095)
  - [Remove the "load QT at startup preference"](https://github.com/livecode/livecode-ide/pull/1215): Fixes crashes with some combinations of Windows and Quicktime
  - [Make "dontUseQT" true by default](https://github.com/livecode/livecode/pull/4103)
- **Big LiveCode Builder improvements!**
  - [Lexical scope for variables](https://github.com/livecode/livecode/pull/4113)
  - [Bytecode blocks](https://github.com/livecode/livecode/pull/4097): Embed raw LCB bytecode in LCB source code
  - [String and manifest encoding correctness fixes](https://github.com/livecode/livecode/pull/4084): Safely use any character in LCB `metadata` declarations

### Bug report of the week

[Bug 17802 - filter with/without is wrong with a left bracket in input string](http://quality.livecode.com/show_bug.cgi?id=17802)

- Very descriptive and self-explanatory sample stack. It has the recipe on a
  stack field as well, so no need to switch between Bugzilla and LiveCode when
  trying to reproduce it
- "Beautiful" stack, because all the buttons, fields are layered very nicely.
  There is an input field on the left, some buttons with actions in the centre,
  and an output field on the right.  The buttons are equally spaced, they have
  labels where necessary. It is obvious that the submitter has spent time on
  making it both functional _and_ good-looking, and that's greatly appreciated

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these!

- (Easy) [Swapped labels in the Project Browser](http://quality.livecode.com/show_bug.cgi?id=17768)
- (Easy) Remove the `p_is_debug_message` argument from `MCObject::message()`
- (Easy) [Script editor find & replace geometry missing](http://quality.livecode.com/show_bug.cgi?id=17146)
- (Easy) Remove "web" platform from dictionary entries
- (Medium) [Navbar widget doesn't generate unique item names](http://quality.livecode.com/show_bug.cgi?id=17687)
- (Medium) [Engine doesn't parse some ProxyServer formats correctly](http://quality.livecode.com/show_bug.cgi?id=17803)
- (Medium) [Modify "answer color" to use the correct color profile data on OS X](http://quality.livecode.com/show_bug.cgi?id=14308)
- (Hard) [Correct rendering of multicolor fonts](http://quality.livecode.com/show_bug.cgi?id=17395)

### Contributors this week

- [techstrategies](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevelanor](https://github.com/runrevelanor)*
- *[runrevmark](https://github.com/runrevmark)*

## Upcoming events

* [7th July](http://forums.livecode.com/viewtopic.php?f=50&t=27433): SoCal LiveCode Group meetup
* [2nd-4th August: LiveCode Conference 2016](https://livecode.com/edinburgh-2016/)
