---
layout: post
title:  "This Week In LiveCode 51"
date:   2016-09-19 12:00
categories: issue
---

Welcome to *This Week in LiveCode*!  This is a weekly summary of what's been
going on in the [LiveCode](https://livecode.com/) open source project and
community.  Want something mentioned?  Tweet
[@LiveCode](https://twitter.com/LiveCode) or
[send us an e-mail](mailto:opensource@livecode.com?subject=This Week in Livecode).

## Updates from the LiveCode open source community

### News & blog posts

* **[LiveCode 8.1: A major minor release](https://livecode.com/livecode-8-1-is-a-major-minor-release/)**
* [LiveCode Widgets: Modifying the line chart](https://livecode.com/livecode-widgets-modifying-the-line-chart/)
* [Accounting for new widget properties in an OnLoad handler](http://www.bluemangolearning.com/livecode/2016/09/accounting-for-new-widget-properties-in-an-onload-handler/)
* Bernd posted an experimental patch that enables [code folding in the script editor](http://lists.runrev.com/pipermail/use-livecode/2016-September/230949.html)
* ["Thread the Needle" Game](http://learninglivecode.blogspot.com/2016/09/lloyds-physics-simulation-prototype-2.html)
* Research presented at ICER2016 showed [lower overall cognitive load for LiveCode developers](https://twitter.com/icer2016/status/774099872152559617)

### Interesting discussions

* [Maintaining order in JSON imports](http://lists.runrev.com/pipermail/use-livecode/2016-September/230705.html): Exploring all the available ways of importing/exporting JSON data
* [Extending the IDE menu bar](http://lists.runrev.com/pipermail/use-livecode/2016-September/230675.html)
* [Why isn't the tsNet external open source?](https://www.facebook.com/groups/livecodeusers/permalink/1126326464072869/?comment_id=1126457430726439)

## Updates in the LiveCode open source project

47 pull requests were [merged since the last issue](https://github.com/search?utf8=%E2%9C%93&q=org%3Alivecode+is%3Apublic+is%3Apr+is%3Amerged+merged%3A2016-09-12..2016-09-18&type=Issues&ref=searchresults).

### New LiveCode releases

- **[LiveCode 8.1.0](https://downloads.livecode.com/livecode/#8_1_0)**

### Notable changes

* [Fix slow performance of `trueWord` chunk](https://github.com/livecode/livecode/pull/4507): [@runrevmark](https://github.com/runrevmark) managed to speed it up by a factor of 100 or so
* [Improve tokenisation of numbers and add hex and bin literals](https://github.com/livecode/livecode/pull/4494): Use `0xABCD` and `0x0010` literals in LCB source code
* [Allow newer JDKs to be used for Android builds](https://github.com/livecode/livecode/pull/4403): You no longer need to keep JDK 6 around for Android deployment

<!---
### Bug of the week
-->

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
- [PaulMcClernan](https://github.com/PaulMcClernan)
- [techstrategies](https://github.com/techstrategies)
- *[livecodeali](https://github.com/livecodeali)*
- *[livecodefraser](https://github.com/livecodefraser)*
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
