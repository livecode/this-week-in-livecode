---
layout: post
title:  "This Week In LiveCode 54"
date:   2016-10-10 14:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

* [lcCardLayoutToWeb](https://github.com/RichardHerz/lcCardLayoutToWeb): Design
  a stack and export its layout to HTML + CSS
* [revIgniter v1.9.2 released](http://revigniter.com/news/newsitem/revIgniter_v1.9.2_Released)
  with [updated TextMate bundles](http://revigniter.com/news/newsitem/TM_bundles_v1.4.5_Released)
* [Enabling USD debugging on Android Lollipop](http://forums.livecode.com/viewtopic.php?f=53&t=23146)

### Interesting discussions

* [Understanding `the defaultStack`](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg79242.html):
  There are quite a lot of subtleties to be aware of
* [dragData in LCB](http://forums.livecode.com/viewtopic.php?f=93&t=27680): How
  to drag a file onto a widget and grab the data for the widget to process

## Updates in the LiveCode open source project

86 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-10-03..2016-10-09&type=Issues&ref=searchresults).

### Notable changes

- A bunch of crash fixes got merged
- [Find Next/Previous in the SE respects current cursor location](https://github.com/livecode/livecode-ide/pull/1421):
  Better usability for the script editor interactive search
- [@seaniepie](https://github.com/seaniepie) is on a one-man mission to bury
  the language dev team in documentation pull requests

### Bug of the week

[Bug 18485 - 'Object' menu layer commands ungroup and regroup objects](http://quality.livecode.com/show_bug.cgi?id=18343)

This bug is a really interesting problem where the 'Object → Bring to front'
menu item (and other object ordering menu commands) can modify the group
structure of objects.

Each time the bug is reproduced using the sample stack, it's necessary to put
the sample stack back into its original configuration, including relayering and
regrouping the controls.  The reporter realised this and kindly included a
"Reset" button that makes preparing for testing the problem very easy!

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Inset the border path of the segmented control by the stroke width / 2 ](http://quality.livecode.com/show_bug.cgi?id=18319)
- (Easy) [Add a default script for scroll bars](http://quality.livecode.com/show_bug.cgi?id=17851)
- (Easy) [Document the scriptExecutionErrors property](http://quality.livecode.com/show_bug.cgi?id=18147)
- (Medium) [Teach the Project Browser to show parent behaviours](http://quality.livecode.com/show_bug.cgi?id=18176)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)

### Contributors this week

- [andrewferguson](https://github.com/andrewferguson)
- [asayd](https://github.com/asayd)
- [bhall2001](https://github.com/bhall2001)
- [seaniepie](https://github.com/seaniepie)
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[LiveCodeSteven](https://github.com/LiveCodeSteven)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*

## Upcoming events

- [16th October: LiveCode meeting in the Netherlands](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg79250.html)

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
