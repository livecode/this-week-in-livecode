---
layout: post
title:  "This Week In LiveCode 85"
date:   2017-06-05 12:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

<!---
### News & blog posts

- [LiveCode: an inside perspective from the outside](https://livecode.com/livecode-an-inside-perspective-from-the-outside/)
-->



### Interesting discussions

- [Insanely long delays when moving several selected objects](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85373.html)
- [Forcing a number to be interpreted as a field name](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85378.html)
- [Using callbacks within LC and JS](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85394.html)
- [Livecode 9 and converting to Stack Behaviors](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85411.html)
- [iOS internet issue (url request timeout setting?)](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85419.html)
- [Rooting around in the Forum: destructors](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85464.html)
- [How to download an image](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85474.html)
- [Regex help](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85481.html)
- [HTML5 deployment: progress comes into sight](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85370.html)

  
## Updates in the LiveCode open source project

28 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-05-29..2017-06-04&type=Issues).


### New LiveCode releases

- [LiveCode 8.1.4-rc-3](https://downloads.livecode.com/livecode/#8_1_4)


### Notable changes

- [Only use LCD anti-aliasing in opaque contexts on Mac](https://github.com/livecode/livecode/pull/5547): Another regression caused by the update of Skia library is now fixed.
- [Make sure target stack is still valid before dispatching key focus event](https://github.com/livecode/livecode/pull/5544): This fixes a crash on Android when a stack is deleted shortly after switching to another stack.
- [LCB: Add ordinal binding for builtin modules](https://github.com/livecode/livecode/pull/5531): Another step closer to have widgets working in HTML5!
- [Fix relative path resolution of images in Mac standalones](https://github.com/livecode/livecode/pull/5524): A LC 8.1.4 regression is now fixed.
- [Remove legacy ink use from IDE](https://github.com/livecode/livecode-ide/pull/1597): Yet another regression caused by the update of Skia library is now fixed.
- [revDB: Fixed bug preventing all table names being retrieved](https://github.com/livecode/livecode/pull/5507)
- [Update Windows text rendering to use DirectWrite+Skia](https://github.com/livecode/livecode/pull/5496)
- [Expand range of 'random()' to 53-bits](https://github.com/livecode/livecode/pull/5473)
- [Add new set ops and into form](https://github.com/livecode/livecode/pull/5453): This patch adds difference and symmetric difference set operation commands, and adds an 'into' clause to all four.
- [LCB-Java: Convert to and from java string correctly](https://github.com/livecode/livecode/pull/5543)


### Bug of the week

- [Bug 19730 - Referenced images are broken](http://quality.livecode.com/show_bug.cgi?id=19730)

The reporter attached a helpful simple sample stack, and provided a detailed recipe as well as resource files that helped us to test, confirm and fix the problem quickly. 

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) [Dictionary entry for compositorType says OpenGL is iOS only](http://quality.livecode.com/show_bug.cgi?id=19496)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- *[livecodealex](https://github.com/livecodealex)*
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodeian](https://github.com/livecodeian)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[livecodesam](https://github.com/livecodesam)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*


<!---
## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

-->


## Upcoming events

* [LiveCode Global: Our Next Conference in Your City](https://livecode.com/livecode-global-our-next-conference-in-your-city/): 48 hours of Conference content streamed live around the globe! Save the dates:

- 15th of June 2017
- 13th of July 2017
- 17th of August 2017
- 21st of September 2017
- 19th of October 2017
- 16th of November 2017


## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
