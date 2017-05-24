---
layout: post
title:  "This Week In LiveCode 83"
date:   2017-05-24 12:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community


### News & blog posts

- [LiveCode: an inside perspective from the outside](https://livecode.com/livecode-an-inside-perspective-from-the-outside/)


### Interesting discussions

- [Dispatching Messages to Closed Stacks Which Are Not in Memory](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84851.html)
- [Identical and similar blend modes](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84887.html)
- [Writing Extensions](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84913.html)
- [Android policy update](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84944.html)
- [Sort so that "Hello" is always before "hello"](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84969.html)
- [browser print?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg84992.html)
- [Which port is beeing used with get URL?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85017.html)
- [Sql problem](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85058.html)
- [How are URL / libUrl / tsNet related?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85061.html)
- [Which Externals does a standalone load?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85065.html)
- [Best Practice for updating the screen?](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85072.html)
- [breakpoint on parameter](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg85078.html)
  
## Updates in the LiveCode open source project

40 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2017-05-15..2017-05-23&type=Issues).


<!---
### New LiveCode releases

- [LiveCode 8.1.4-rc-2](https://downloads.livecode.com/livecode/#8_1_4)
-->


### Notable changes

- [Relative file support for stackfiles](https://github.com/livecode/livecode-ide/pull/1502)
- [SkiaUpdate: Reinstate stipple effect](https://github.com/livecode/livecode/pull/5457)
- [SkiaUpdate: Reinstate diamond, spiral, XY and sqrtXY gradients](https://github.com/livecode/livecode/pull/5458)
- [Overhaul message box execution](https://github.com/livecode/livecode-ide/pull/1587)
- [Ensure platform player is destroyed on close](https://github.com/livecode/livecode/pull/5468): This patch ensures that system resources do not get used whilst the player is not being used.
- [Changed confusing dependency instructions in linux build doc](https://github.com/livecode/livecode/pull/5471)
- [Fixed bug preventing users to select txt of length 65535](https://github.com/livecode/livecode/pull/5476)
- [Restore lockIdleTimer's value when camera is dismissed](https://github.com/livecode/livecode/pull/5479)
- [Fix various Project Browser update issues](https://github.com/livecode/livecode-ide/pull/1591)
- [Fixed bug causing crash with undoChanged](https://github.com/livecode/livecode/pull/5489): Previous Bug of the Week is now fixed.


### Bug of the week

- [Bug 19670 - "effective working screenrect" does not take the keyboard into account on Android if status bar is hidden](http://quality.livecode.com/show_bug.cgi?id=19670)

The reporter attached a helpful sample stack, and provided a detailed recipe as well as a useful observation that helped us to test and confirm the problem quickly. 

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these:

- (Easy) [Update & complete documentation for `the processor`](http://quality.livecode.com/show_bug.cgi?id=17974)
- (Easy) ["width" property dictionary entry missing words "lockLocation property" in description](http://quality.livecode.com/show_bug.cgi?id=19727)
- (Easy) [Dictionary entry for compositorType says OpenGL is iOS only](http://quality.livecode.com/show_bug.cgi?id=19496)
- (Medium) [Add info on manipulating field contents to the User Guide](http://quality.livecode.com/show_bug.cgi?id=18990)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)
- (Hard) [Allow Windows line endings in script-only stacks](http://quality.livecode.com/show_bug.cgi?id=17810)
- (Hard) [Create a LiveCode Community build for Raspberry Pi](http://forums.livecode.com/viewtopic.php?f=76&t=27912)

### Contributors this week

- [MartinKoob](https://github.com/MartinKoob)
- [mwieder](https://github.com/mwieder)
- [trevordevore](https://github.com/trevordevore)
- *[livecodealex](https://github.com/livecodealex)*
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodemichael](https://github.com/livecodemichael)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[runrevmark](https://github.com/runrevmark)*


## Other LiveCode News

This section brings you other interesting news from across the LiveCode universe over the last week. This section may include non OSS projects.

Staff changes: Welcome to Chris and Alex and goodbye to Peter.

We’d love to welcome two new staff members who have just joined the team: Alex Brisan and Chris Colman. 
Alex has joined the development team and Chris is helping out with marketing. We're delighted to have them and you'll get to know them as they settle in and learn the ropes.
You can read Alex's introductory blog post [here](https://livecode.com/livecode-an-inside-perspective-from-the-outside/), and Chris will be making one soon!

Peter Brett has sadly left us for pastures new, we wish him all the best in his new post and he will of course be missed. 
Our thanks for his sterling contribution to advancing LiveCode over the last few years.



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
