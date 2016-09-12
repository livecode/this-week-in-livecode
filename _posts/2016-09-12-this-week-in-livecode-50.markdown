---
layout: post
title:  "This Week In LiveCode 50"
date:   2016-09-12 13:30
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

This week's edition was edited by [montegoulding](https://github.com/montegoulding)
and [livecodepanos](https://github.com/livecodepanos).

## Updates from the LiveCode open source community

### News & blog posts

* LiveCode 8.1.0 RC 2 was released
* [@montegoulding](https://github.com/montegoulding) introduced the
[line chart widget](https://livecode.com/livecode-widgets-the-line-chart/)

### Interesting discussions

* Richard Gaskin has [called for community team members to help with an RPi build](http://forums.livecode.com/viewtopic.php?f=76&t=27912)
* [A question on threading](http://lists.runrev.com/pipermail/use-livecode/2016-September/thread.html#230525)
went waaaay off topic and ended up discussing script editor key
combinations
* [How to determine the version of a windows engine of an old standalone](http://lists.runrev.com/pipermail/use-livecode/2016-September/thread.html#230426)

## Updates in the LiveCode open source project

23 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-09-05..2016-09-11&type=Issues&ref=searchresults).

### Notable changes

* [@livecodefraser](https://github.com/livecodefraser) made a change to
the linux engine so it will tell users what required libraries are
missing if it [fails to load](https://github.com/livecode/livecode/pull/4453)
* [@PaulMcLernan](https://github.com/PaulMcLernan) added 
[docs](https://github.com/livecode/livecode/pull/4408) for 
`the currentCard of <stack>` 
* The team has been working on build tools and fixes for iOS 10 and
Xcode 8 along with some of the core components of the Infinite LiveCode
project.

### Bug of the week

[Bug 18343 - itemOffset returns 0 when wholeMatches is true](http://quality.livecode.com/show_bug.cgi?id=18343)

This bug occurs only under certain conditions and is the bug of the week
because the report made it easy for [livecodepanos](https://github.com/livecodepanos)
to determine those conditions.

To reproduce the bug the following conditions must be met:

- `the wholeMatches` must be true
- the string to search and the item searched for must not be unicode
- the item found must be the second item in the list where the first is
an empty item

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these!

- (Easy) [Inset the border path of the segmented control by the stroke width / 2 ](http://quality.livecode.com/show_bug.cgi?id=18319)
- (Easy) [Fix broken references in "filename of stack" dictionary entry](http://quality.livecode.com/show_bug.cgi?id=18297)
- (Easy) [Document the scriptExecutionErrors property](http://quality.livecode.com/show_bug.cgi?id=18147)
- (Medium) [Teach the Project Browser to show parent behaviours](http://quality.livecode.com/show_bug.cgi?id=18176)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)

### Contributors this week

- [PaulMcClernan](https://github.com/PaulMcClernan)
- [asayd](https://github.com/asayd)
- [jameshale](https://github.com/jameshale)
- [matthewmaier](https://github.com/matthewmaier)
- *[runrevmark](https://github.com/runrevmark)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[peter-b](https://github.com/peter-b)*
- *[livecodeali](https://github.com/livecodeali)*
- *[montegoulding](https://github.com/montegoulding)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodemichael](https://github.com/livecodemichael)*

## Upcoming events

* [17th September: Make something cool with LiveCode!](http://www.meetup.com/The-THINQTANQ-Events-Meetups-and-More-in-Plymouth/events/226749341/)
