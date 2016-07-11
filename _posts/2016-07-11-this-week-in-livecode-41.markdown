---
layout: post
title:  "This Week In LiveCode 41"
date:   2016-07-11 12:15
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

- Digital Pomegranate released the source code of
  [livecode-wp-restapi](https://github.com/digitalpomegranate/livecode-wp-restapi),
  a set of WordPress integration REST API libraries
- [LiveCode + WordPress = Infinite Possibilities Webinar](https://www.youtube.com/watch?v=D_6b04AltTQ)
- [Lloyd's physics simulation: prototype 1](https://learninglivecode.blogspot.co.uk/2016/07/lloyds-physics-simulation-prototype-1.html)

### Interesting discussions

- [WP REST API and creating sample apps](http://thread.gmane.org/gmane.comp.ide.revolution.user/228104)
- [Front/backscripts on mobile, and working with native scrollers](http://thread.gmane.org/gmane.comp.ide.revolution.user/227977)
- [Parsing a PDF file](http://thread.gmane.org/gmane.comp.ide.revolution.user/228148)

## Updates in the LiveCode open source project

38 pull requests were [merged since the last issue](https://github.com/search?l=&o=asc&s=created&type=Issues&utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-07-04..2016-07-10).

### New LiveCode releases

- [LiveCode 8.0.2-rc-3](https://downloads.livecode.com/livecode/#8_0_2)

### Notable changes

- [List directories without changing "the defaultFolder"](https://github.com/livecode/livecode/pull/4237)
- [Fix rendering of rotated text on Windows](https://github.com/livecode/livecode/pull/4232)
- [Make sure action of "return for" is local to the caller](https://github.com/livecode/livecode/pull/4233)
- [Ensure "iconGravity" is preserved when copying buttons](https://github.com/livecode/livecode/pull/4234)

### Bug of the week

[Bug 17884 - windowShape issues on Windows](http://quality.livecode.com/show_bug.cgi?id=17884)

This bug is bug of the week this week because:

- the reporter tested in earlier versions of LiveCode
- the bug includes results of testing on **all** desktop platforms (and on
  Raspberry Pi)
- there's an excellent sample stack to use for reproducing the issue
- the report points out the exact line of code that causes the problem
- the report even includes a workaround!

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these!

- (Easy) Change IDE to use `files(<folder>)` instead of setting `the defaultFolder`
- (Medium) [Improve the script editor's menubar layout on Linux](http://quality.livecode.com/show_bug.cgi?id=17398)
- (Medium) [Change "bundled" IDE plugins to use publish/subscribe mechanism](http://quality.livecode.com/show_bug.cgi?id=17686)
- (Hard) [Replace MCMoviePlayerController with AVPlayer on iOS](http://quality.livecode.com/show_bug.cgi?id=15834)

### Contributors this week

- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*

## Upcoming events

* [2nd-4th August: LiveCode Conference 2016](https://livecode.com/edinburgh-2016/)
* [17th September: Make something cool with LiveCode!](http://www.meetup.com/The-THINQTANQ-Events-Meetups-and-More-in-Plymouth/events/226749341/)
