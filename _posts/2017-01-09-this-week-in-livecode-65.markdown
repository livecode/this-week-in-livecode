---
layout: post
title:  "This Week In LiveCode 65"
date:   2017-01-09 15:15
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

Happy new year LiveCoders!

<!---
### News and blog posts
-->

### Interesting discussions

- [SQLite and single quote characters](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81229.html)
- [Building LiveCode from source using git](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81505.html)
- [Vaccination simulation using LiveCode by MaxV](https://www.facebook.com/groups/livecodeusers/permalink/1235044569867724/)

## Updates in the LiveCode open source project

30 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-12-19..2017-01-08&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 8.1.2](https://downloads.livecode.com/livecode/8_1_2)
- [LiveCode 9.0.0 DP 4](https://downloads.livecode.com/livecode/9_0_0)

### Notable changes

- [Copy target string in replaceText/matchText](https://github.com/livecode/livecode/pull/4990):
  Now the target string is copied when used in `replaceText` or `matchText`, ensuring that the original string is not
  force converted to unicode internally. This results in a dramatic performance increase in subsequent calls of `replaceText` or `matchText`.
- [Improve efficiency of regex cache](https://github.com/livecode/livecode/pull/4989):
  Another performance improvement.
- [Send standalone messages at correct time](https://github.com/livecode/livecode/pull/4871)
- [Delete substacks of stack before deleting mainstack](https://github.com/livecode/livecode/pull/5023):
  This prevents a crash when deleting a stack with an open substack.


### Bug of the week

[Bug 19020 -  The hotspot of an image is cropped if a hotspot coordinate is set to a value > 16](http://quality.livecode.com/show_bug.cgi?id=19020)

The reporter has noticed that although the cursor can be set to an image of size greater than 16x16, the hotspot of an image can not be greater than (16,16).
The simple and self-explanatory example stack nicely demonstrates the problem.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [dunbarx](https://github.com/dunbarx)
- [techstrategies](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*


## Upcoming events

- [Greater Toronto Area LiveCode Meetup Jan 25, 2017](http://forums.livecode.com/viewtopic.php?t=28620&p=150027#p150027)
- [International LiveCode Mini Conference, organised by Mark Schonewille](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81544.html)

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
