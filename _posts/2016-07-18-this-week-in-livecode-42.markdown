---
layout: post
title:  "This Week In LiveCode 42"
date:   2016-07-18 15:00
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

Are you interested in helping to run the [livecode.org](https://livecode.org/)
community website? Contribute to the [planning discussion ](http://forums.livecode.com/viewtopic.php?f=108&t=27610) in the forums!

### News & blog posts

- [Faff-free files function](https://livecode.com/faff-free-files-function/)
- [New "FontLab" plugin for the IDE](http://thread.gmane.org/gmane.comp.ide.revolution.user/228363)

### Interesting discussions

- [Application Transport Security deadline for iOS apps](http://thread.gmane.org/gmane.comp.ide.revolution.user/228243): Use HTTPS wherever possible!
- [What's the best way to share stacks with other users?](http://thread.gmane.org/gmane.comp.ide.revolution.user/228378)

## Updates in the LiveCode open source project

26 pull requests were [merged since the last issue](https://github.com/search?l=&o=asc&s=created&type=Issues&utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-07-11..2016-07-17).

### Notable changes

- [Allow global handlers to be overridden by scripted handlers](https://github.com/livecode/livecode/pull/4265)
- [Workaround for IDE hang when tracing resizeStack & moveStack](https://github.com/livecode/livecode-ide/pull/1273): [montegoulding](https://github.com/montegoulding) addressed an extremely-longstanding IDE issue
- [Add markerStyles and showLines properties to line graph widget](https://github.com/livecode/livecode/pull/4266)

### Bug of the week

[Bug 17905 - Resizing LiveCode Builder widgets can get into a mode where the width and height seem to be unclear](http://quality.livecode.com/show_bug.cgi?id=17905)

This  bug is about non-smooth resizing of widgets that can result in distorted
rendering  when they hit some particular (but not the same between launches)
values of (width, height).  It's our bug of the week because:

1. Initially the user provided a video of the bug, since he could not find a
   concrete recipe and the core dev team couldn't reproduce it
2. The video was enough to confirm the bug -- but the reporter didn't give up!
3. He created an amazing-yet-simple stack, that automatically resizes the
   widget over a set of all possible values of width and height, and logs the
   "bad" combinations.

Thanks to his persistence, the bug is now reproducible and that will make it
much easier to find and fix the problem.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these!

- (Easy) [Document the alignments available with the `fill text` command in LCB](http://quality.livecode.com/show_bug.cgi?id=17655)
- (Medium) [Add support for the "tabAlign" property to the property inspector](http://quality.livecode.com/show_bug.cgi?id=17978)
- (Hard) Add basic HTTP support on HTML5 platform

### Contributors this week

- *[livecodeali](https://github.com/livecodeali)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*

## Upcoming events

* [2nd-4th August: LiveCode Conference 2016](https://livecode.com/edinburgh-2016/)
* [4th August: SoCal LiveCode Group meetup](http://forums.livecode.com/viewtopic.php?f=50&27600)
* [17th September: Make something cool with LiveCode!](http://www.meetup.com/The-THINQTANQ-Events-Meetups-and-More-in-Plymouth/events/226749341/)
