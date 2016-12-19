---
layout: post
title:  "This Week In LiveCode 64"
date:   2016-12-19 14:15
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

*This Week in LiveCode* will be taking a couple of weeks off, and will return
on 9th January!

### News & blog posts

- [When C uninitialised variables and misleading whitespace combine](http://blog.peter-b.co.uk/2016/12/when-uninitialised-variables-whitespace-combine.html): The anatomy of a bug in the LiveCode engine
- [LiveCode 8.1.3 will include Xcode 8.2 support](https://www.mail-archive.com/use-livecode@lists.runrev.com/msg81061.html)

### Interesting discussions

- [Why regular expressions made subsequent statements run slowly](http://forums.livecode.com/viewtopic.php?f=104&t=28513)
- [Using `wait until <condition> with messages` for parallel code](https://www.facebook.com/groups/livecodeusers/permalink/1209310985774416/)

## Updates in the LiveCode open source project

42 pull requests were [merged since the last issue](https://github.com/search?utf8=✓&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-12-12..2016-12-18&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 8.1.2 rc 3](https://downloads.livecode.com/livecode/8_1_2)

### Notable changes

- Documentation and code style guide updates
  - [Updated C++ style](https://github.com/livecode/livecode/pull/4991): The
    new C++ coding style makes use of C++11 features and changes the
    indentation style
  - [Documentations style guide](https://github.com/livecode/livecode/pull/3521):
    Detailed guidance on the writing style for LiveCode documentation
- [revvideograbber: Remove from Mac OS X builds](https://github.com/livecode/livecode/pull/4999):
  LiveCode 9 no longer supports Mac OS X 10.8 and below, so it isn't possible
  to compile the revvideograbber external for Mac any more
- [Check for script-only stacks in objchunk url resolution](https://github.com/livecode/livecode/pull/4998):
  It is now possible to load script-only stacks with `go url <stackUrl>`
- [Add 'Select All' as a built-in field action](https://github.com/livecode/livecode/pull/4963):
  LiveCode fields now respond to &lt;Cmd+A&gt; or &lt;Ctrl+A&gt; by default

### Bug of the week

[Bug 18970 - Datagrid doesn't respond to mouseDown handler on Android](http://quality.livecode.com/show_bug.cgi?id=18970)

The reporter documents a surprising difference in the way the datagrid works on
Android platforms vs desktop platforms.  The simple and self-explanatory
example stack nicely demonstrates the problem.

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

- [asayd](https://github.com/asayd)
- [BerndN](https://github.com/BerndN)
- [seaniepie](https://github.com/seaniepie)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodepanos](https://github.com/livecodepanos)*
- *[montegoulding](https://github.com/montegoulding)*
- *[peter-b](https://github.com/peter-b)*
- *[runrevmark](https://github.com/runrevmark)*

<!---
## Upcoming events
-->

## Contribute!

*This Week in LiveCode* is openly developed
[on GitHub](https://github.com/livecode/this-week-in-livecode).
If you find any errors in this issue, please
[file an issue](https://github.com/livecode/this-week-in-livecode/issues) or
[submit a pull request](https://github.com/livecode/this-week-in-livecode/pulls).
