---
layout: post
title:  "This Week In LiveCode 47"
date:   2016-08-22 13:30
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

* [livecodepanos](https://github.com/livecodepanos) shares about his first conference on the [LiveCode Blog](https://livecode.com/my-first-livecode-conference/)
* [peter-b](https://github.com/peter-b) released an [Emacs major mode for LiveCode Builder](https://github.com/peter-b/lcb-mode)
* [angerangel](https://github.com/angerangel) released an update to the [livecodeExif library](https://github.com/angerangel/livecodeExif)

### Interesting discussions

* [Alex Tweedy continued The Joy of Removing Features series](hhttp://lists.runrev.com/pipermail/use-livecode/2016-August/thread.html#229972)
* [The wonders of trailing delimiters](http://lists.runrev.com/pipermail/use-livecode/2016-August/thread.html#230023)
* [Garbage collection](http://lists.runrev.com/pipermail/use-livecode/2016-August/thread.html#229935)

## Updates in the LiveCode open source project

70 pull requests were [merged since the last issue](https://github.com/search?l=&o=asc&s=created&type=Issues&utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-08-15..2016-08-21).

### Notable changes

* A huge effort this week from [@asayd](https://github.com/asayd) making
[17 patches to the documentation!](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-08-15..2016-08-21+author%3Aasayd&type=Issues&ref=searchresults)
* [Correct gray RGB values in "GrayX" colors](https://github.com/livecode/livecode/pull/4290) 
a great first contribution from [@meiradarocha](https://github.com/meiradarocha)!
* [New **minStackFileVersion** property for stacks](https://github.com/livecode/livecode/pull/4365):
  Check what minimum stack file version you can use without risking data loss.
* [Faster script formatting](https://github.com/livecode/livecode-ide/pull/1341)
* [Indicate script compilation errors on the project browser](https://github.com/livecode/livecode-ide/pull/1298)

### Bug of the week

[Bug 18227 - Wrong value for <field "name" of the target>](http://quality.livecode.com/show_bug.cgi?id=18227)

This bug details a regression in the behavior of the `target` function.

This is the bug of the week because its reporter provided both a very 
helpful stack illustrating the problem and a detailed, reproducible
recipe.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these!

- (Easy) [Make PDF user guide typography match dictionary view](http://quality.livecode.com/show_bug.cgi?id=18111)
- (Easy) [Document the scriptExecutionErrors property](http://quality.livecode.com/show_bug.cgi?id=18147)
- (Easy) [Add a note to the User Guide warning against giving objects numerical names](http://quality.livecode.com/show_bug.cgi?id=18043)
- (Medium) [Teach the Project Browser to show parent behaviours](http://quality.livecode.com/show_bug.cgi?id=18176)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)

### Contributors this week

- [meiradarocha](https://github.com/meiradarocha)
- [techstrategies](https://github.com/techstrategies)
- [asayd](https://github.com/asayd)
- *[peter-b](https://github.com/peter-b)*
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesebastien](https://github.com/livecodesebastien)*

## Upcoming events

* [17th September: Make something cool with LiveCode!](http://www.meetup.com/The-THINQTANQ-Events-Meetups-and-More-in-Plymouth/events/226749341/)
