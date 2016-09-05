---
layout: post
title:  "This Week In LiveCode 49"
date:   2016-09-05 13:30
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

* [@PaulMacClernan](https://github.com/PaulMacClernan) shared a 
[LCB MIDI library](https://github.com/PaulMcClernan/community.livecode.library.GMIDILib)
he's working on.

### Interesting discussions

* [What's everyone working on this month](http://lists.runrev.com/pipermail/use-livecode/2016-September/thread.html#230352)
* Over on Facebook in the [LiveCode User Group](https://www.facebook.com/groups/livecodeusers/)
there's an interesting thread on assessing your coding efficiency and
productivity.

## Updates in the LiveCode open source project

27 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-08-29..2016-09-04&type=Issues&ref=searchresults).

### Notable changes

* [@asayd](https://github.com/asayd) continued his fine form with yet
more docs changes!
* [@jameshale](https://github.com/jameshale) came to the party with
*can-do spirit* by fixing his own bug report to improve the look of
the [PDF user guide](https://github.com/livecode/livecode/pull/4426).
* [@livecodeali](https://github.com/livecodeali) added his documentation editing helper stack which is
available from [here](https://github.com/livecode/livecode-ide/blob/develop/Documentation/Docs%20Helper.livecode)
* [@montegoulding](https://github.com/montegoulding) implemented a
[semantic versioning](http://semver.org/) library in LiveCode Script
which allows a version number to be tested against a version range. For
example, The range `1.2.7 || >=1.2.9 <2.0.0` would match the versions
`1.2.7`, `1.2.9`, and `1.4.6`, but not the versions `1.2.8` or `2.0.0`.
The library is available [here](https://github.com/livecode/livecode/tree/develop/extensions/script-libraries/semver) 

### Bug of the week

[Bug 18272 - Converting a password protected stack to script only doesn't save correctly](http://quality.livecode.com/show_bug.cgi?id=18272)

This bug is where after correctly removing a password from a password
protected stack and then setting the `scriptOnly` of the stack to true
the script still continues to be saved encrypted.

This is the bug of the week because its reporter provided a very 
helpful stack along with a reproducible recipe.

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

- [jameshale](https://github.com/jameshale)
- [asayd](https://github.com/asayd)
- *[runrevmark](https://github.com/runrevmark)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[peter-b](https://github.com/peter-b)*
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[montegoulding](https://github.com/montegoulding)*
- *[livecodepanos](https://github.com/livecodepanos)*

## Upcoming events

* [17th September: Make something cool with LiveCode!](http://www.meetup.com/The-THINQTANQ-Events-Meetups-and-More-in-Plymouth/events/226749341/)
