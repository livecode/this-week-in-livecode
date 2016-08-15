---
layout: post
title:  "This Week In LiveCode 46"
date:   2016-08-15 13:30
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

This week's edition was edited by [peter-b](https://github.com/peter-b) and
[livecodepanos](https://github.com/livecodepanos).

## Updates from the LiveCode open source community

### News & blog posts

* Max Vessi reports that the [LiveCode Wiki](http://livecode.wikia.com/wiki/Livecode_Wiki) has reached 300 pages
* Digital Pomegranate have released
  [livecode-piwik](https://github.com/digitalpomegranate/livecode-piwik), a
  wrapper library for the Piwik analytics platform's API.

### Interesting discussions

* [Giving multiple behaviors to a single object](http://lists.runrev.com/pipermail/use-livecode/2016-August/thread.html#229799)
* [Combining multiple arrays](http://lists.runrev.com/pipermail/use-livecode/2016-August/thread.html#229799)
* [Building a message scheduler by sending messages in 0 milliseconds](https://www.facebook.com/groups/livecodeusers/permalink/1088621854509997/?comment_id=1088641581174691):
  Are you likely to need 65000 pending messages?

## Updates in the LiveCode open source project

33 pull requests were [merged since the last issue](https://github.com/search?l=&o=asc&s=created&type=Issues&utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-08-08..2016-08-14).

### Notable changes

[@montegoulding](https://github.com/montegoulding) was on fire this week, and
added lots of cool new toys!

* [New **scriptStatus** property for objects](https://github.com/livecode/livecode/pull/4326):
  Check if an object's script compiled properly.
* [Keyboard navigation in the Project Browser](https://github.com/livecode/livecode-ide/pull/1302)
* [Make **group** return the long id of the new group](https://github.com/livecode/livecode/pull/4338):
  The **group** command now sets `it` like other object-creation commands.
* [Implement filtering keys/elements of arrays](https://github.com/livecode/livecode/pull/4343):
  The **filter** command now works on arrays.

### Bug of the week

[Bug 18129 - matchChunk returns wrong offset after high Unicode codepoints](http://quality.livecode.com/show_bug.cgi?id=18129)

This bug is regards the `matchChunk()` function, which searches for a regular
expression in a target string and returns the range of characters that matched.
LiveCode was returning the wrong range of characters when used with a string
containing Unicode Supplementary Multilingual Plane characters.

This is the bug of the week because its reporter provided both a very helpful
stack illustrating the problem and a detailed recipe.  This allowed the bug to
be fixed within days.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these!

- (Easy) [Add a note to the User Guide warning against giving objects numerical names](http://quality.livecode.com/show_bug.cgi?id=18043)
- (Medium) [Teach the Project Browser to show parent behaviours](http://quality.livecode.com/show_bug.cgi?id=18176)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)

### Contributors this week

- [techstrategies](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*

## Upcoming events

* [17th September: Make something cool with LiveCode!](http://www.meetup.com/The-THINQTANQ-Events-Meetups-and-More-in-Plymouth/events/226749341/)
