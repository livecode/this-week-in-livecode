---
layout: post
title:  "This Week In LiveCode 52"
date:   2016-09-26 13:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

🎂 *This Week in LiveCode* is one year old!

Here are some highlights from our first year, in no particular order:

* [Script Only Stacks](https://livecode.com/script-only-stacks/)
* [Triangulation 235](https://twit.tv/shows/triangulation/episodes/235): Bill Fernandez (Apple employee #4) on LiveCode as the child of HyperCard
* [Report from the Conference on Higher Education Pedagogy at Virginia Tech](https://learninglivecode.blogspot.co.uk/2016/02/livecode-report-from-conference-on.html)
* [brimEng](http://edvista.com/claire/apps/brimeng.html) is a smartphone app for English language learning developed at Daffodil University, Dhaka
* [Bézier Line Demo](http://tactilemedia.com/blog/2015/12/06/livecode-bezier-line-demo/)
* [Exam results for students using LiveCode in Norway](http://thread.gmane.org/gmane.comp.ide.revolution.user/227578)
* [Interactive Tutorials](https://livecode.com/livecode-interactive-tutorials/)
* [What is "Open Language"?](http://lists.runrev.com/pipermail/use-livecode/2015-October/thread.html#220332)
* [Bluetooth Controlled Lighted Gong](http://www.projectiveart.com/gong/): installation art with LiveCode
* Research presented at ICER2016 showed [lower overall cognitive load for LiveCode developers](http://dx.doi.org/10.1145/2960310.2960321)

### Interesting discussions

- [LiveCode interface to SCORM /LIT](http://lists.runrev.com/pipermail/use-livecode/2016-September/231030.html): Building a Learning Management System with LiveCode
- [Export PNG with alpha channel/mask ](http://lists.runrev.com/pipermail/use-livecode/2016-September/231135.html)
- [use "" as an array key](http://lists.runrev.com/pipermail/use-livecode/2016-September/231145.html), and the difference between an empty string and "no value"

## Updates in the LiveCode open source project

47 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-09-19..2016-09-25&type=Issues&ref=searchresults).

### New LiveCode releases

- [LiveCode 8.1.1-rc-1](https://downloads.livecode.com/livecode/#8_1_1): Includes Xcode 8 deployment support

### Notable changes

- [Encode/decode HTML text transferred on the clipboard](https://github.com/livecode/livecode/pull/4525)
- [Include `tabAlign` in `htmlText` and `styledText` field properties](https://github.com/livecode/livecode/pull/4543)
- [lc-compile: Print contextual information for each warning or error](https://github.com/livecode/livecode/pull/4518): Including the source line and an indication of exactly where the problem was found

### Bug of the week

[Bug 18254 - Low performance of byte comparison in LiveCode 8.1](http://quality.livecode.com/show_bug.cgi?id=18254)

The reporter found that some comparisons involving raw binary data values were
much slower in LiveCode 7+ than in LiveCode 6.7.  The report contained a simple,
helpful sample stack, a detailed recipe for reproducing the problem, and some
results of comparison with previous versions of LiveCode.  This made it possible
to fix the problem promptly.

### Help needed!

Want to get involved in the LiveCode open source project but don't know where
to start?  Try one of these!

- (Easy) [Inset the border path of the segmented control by the stroke width / 2 ](http://quality.livecode.com/show_bug.cgi?id=18319)
- (Easy) [Add a default script for scroll bars](http://quality.livecode.com/show_bug.cgi?id=17975)
- (Easy) [Document the scriptExecutionErrors property](http://quality.livecode.com/show_bug.cgi?id=18147)
- (Medium) [Teach the Project Browser to show parent behaviours](http://quality.livecode.com/show_bug.cgi?id=18176)
- (Medium) [Make guide outlines in the Dictionary expand/collapse with repeated clicks](http://quality.livecode.com/show_bug.cgi?id=18184)
- (Medium) [Reduce whitespace in Dictionary](http://quality.livecode.com/show_bug.cgi?id=18278)

### Contributors this week

- [asayd](https://github.com/asayd)
- [trevordevore](https://github.com/trevordevore)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
- *[livecodeian](https://github.com/livecodeian)*
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
