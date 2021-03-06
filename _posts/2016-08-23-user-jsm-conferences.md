---
layout: post
title: "useR and JSM 2016 conferences: a story in tweets"
description: "My reports on the useR and JSM conferences that I attended in summer 2016."
date: 2016-08-23 12:00:00 -0400
category: r
tags: [r, statistics]
comments: true
---



I was amused by a Guardian article last month that declared "[I'm a serious academic, not a professional Instagrammer](https://www.theguardian.com/higher-education-network/2016/aug/05/im-a-serious-academic-not-a-professional-instagrammer)," arguing that social media is a distraction for scientific research. This attitude was, to say the least, not popular on academic Twitter, which responded with the  [#seriousacademic](https://twitter.com/search?q=%23seriousacademic&src=tyah) hashtag.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">When someone tries to claim that a <a href="https://twitter.com/hashtag/seriousacademic?src=hash">#seriousacademic</a> should not use twitter... <a href="https://t.co/ocL753NFSw">pic.twitter.com/ocL753NFSw</a></p>&mdash; Kitty Kat, PhD. (@academickitty) <a href="https://twitter.com/academickitty/status/766349115710066688">August 18, 2016</a></blockquote>
<script async src="http://platform.twitter.com/widgets.js" charset="utf-8"></script>

One part of the article that struck me as especially misguided was the author's dismissal of conference tweeting:

> I see more and more of them live tweeting and hashtagging their way through events.... When did it become acceptable to use your phone throughout a lecture, let alone an entire conference? No matter how good you think you are at multitasking, you will not be truly focusing your attention on the speaker, who has no doubt spent hours preparing for this moment.

I personally haven't been a #seriousacademic in over a year, having since become a #sillydatascientist. So I felt no shame in live-tweeting the heck out of the two conferences I attended this summer: [userR](http://user2016.org/) and [JSM (Joint Statistical Meetings)](https://www.amstat.org/meetings/jsm/2016/).

There's a great analysis [here](https://earlyamericanists.com/2016/08/11/whats-livetweeting-for-anyway/) of why people tweet during conferences. For me Twitter best serves as sort of **"public diary"**- I'm not very good at taking notes, and tweeting lets me create a record of what I found most interesting that I can refer to later. So as the summer ends, I'm looking back at my "notes" from these two conferences, and sharing my thoughts.

(If you're a Serious Academic who is against live-tweeting of conferences, get out now, this post isn't going to get any better.)

### What I was up to at the conferences

At both conferences I gave a talk on my [broom package](https://github.com/dgrtwo/broom) for tidying model outputs. You can find the [slides here](http://varianceexplained.org/files/DavidRobinsonBroomUseR2016.pdf), along with the [useR video](https://channel9.msdn.com/Events/useR-international-R-User-conference/useR2016/broom-Converting-statistical-models-to-tidy-data-frames). I was especially impressed by the turnout for my talk at the useR conference, where I got to introduce broom to a large audience.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">&quot;Tidy data works until you start doing statistical modeling&quot; – <a href="https://twitter.com/drob">@drob</a> (creator of awesome &#39;broom&#39; package) <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> <a href="https://t.co/DGHwXIakFi">pic.twitter.com/DGHwXIakFi</a></p>&mdash; Mikhail Popov (@bearloga) <a href="https://twitter.com/bearloga/status/747951081959788545">June 29, 2016</a></blockquote>
<script async src="http://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Slides from my <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> talk yesterday are here: <a href="https://t.co/7brRt7eBV0">https://t.co/7brRt7eBV0</a> <a href="https://twitter.com/hashtag/rstats?src=hash">#rstats</a> <a href="https://t.co/24BOG0DHdl">pic.twitter.com/24BOG0DHdl</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/748222386697179136">June 29, 2016</a></blockquote>

At JSM I also got to present an e-poster about some of the analysis of software developers I've done at Stack Overflow:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> folks: come see my e-poster on what <a href="https://twitter.com/StackOverflow">@StackOverflow</a> data tells us about landscape of software development <a href="https://t.co/nkzcOYZsBK">pic.twitter.com/nkzcOYZsBK</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/759903941907931136">August 1, 2016</a></blockquote>
<script async src="http://platform.twitter.com/widgets.js" charset="utf-8"></script>

You can find the full slides [here](https://www.dropbox.com/s/erf2o5maa6ze6yn/DavidRobinsonJSMPoster.pdf?dl=0). The short version is that we can cluster programming languages based on which get used together:

![](http://varianceexplained.org/images/network_tags_cluster.png)

This also serves as a useful 2-dimensional layout for comparing technologies. For example, we could visualize which areas of the developer landscape are currently growing (red) or shrinking (blue), in terms of % of Stack Overflow questions:

![](http://varianceexplained.org/images/network_growth.png)

For instance, we can see that the data science cluster (including R and machine-learning) is growing in its share of Stack Overflow questions, while the C/C++ cluster below it is mostly shrinking.

### Education

Many of my favorite talks were about data science education. This included my single favorite talk of either session- Deborah Nolan's keynote address at useR on "Statistical Thinking in a Data Science Course" ([video here](https://channel9.msdn.com/Events/useR-international-R-User-conference/useR2016/Statistical-Thinking-in-a-Data-Science-Course)):

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Just imagine <a href="https://twitter.com/hashtag/stats?src=hash">#stats</a> course without simplified scenarios, canned data, non-coding, &amp; always normal distrib <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> <a href="https://t.co/qsm7qT4rf2">pic.twitter.com/qsm7qT4rf2</a></p>&mdash; Alice Data (@alice_data) <a href="https://twitter.com/alice_data/status/748554856827281408">June 30, 2016</a></blockquote>

I'd heard these problems with statistical education described before, but never with this much clarity and evidence.

But alongside that talk, the talks about education at both conferences were uniformly excellent.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/AmeliaMN">@AmeliaMN</a> shares an HS data science curriculum, including 400-page Introduction to Data Science doc. Wow! <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> <a href="https://t.co/Czh2ViaaF4">https://t.co/Czh2ViaaF4</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/747891505562456064">June 28, 2016</a></blockquote>

Some of the common themes included:

* **That programming should be taught alongside statistics, and not as an afterthought**- this was a nearly universal complaint among educators who have had to deal with statistics curricula.
* **That students should be able to do powerful things immediately**- many of the speakers focused on this point, and this is part of the foundation of my opinion that [instructors should teach ggplot2 first](http://varianceexplained.org/r/teach_ggplot2_to_beginners/). (Jeff Leek was also at JSM, where he doubled down on his dissenting opinion that [plotting should be either difficult or ugly](http://varianceexplained.org/r/why-I-use-ggplot2/)).
* **That we should teach permutation and boostrapping rather than normal theory**- this is a promising way to make statistics more intuitive and focus less on math early on. I did discuss with some people that this is a very frequentist approach to statistical education. What would be an equivalent math-lite Bayesian introduction?

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">&quot;Randomize, Repeat, Reject&quot;- Deborah Nolan suggests teaching permutation+bootstrap rather than normal theory <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/748558759924899840">June 30, 2016</a></blockquote>

* **That reproducible research should be a core part of education.** This brings me to another great set of talks:

### Reproducibility

Like much of the R community, I've internalized a lot of the lessons and practices of reproducible research. (For instance, these blog posts are reproducible from R markdown files in [this directory](https://github.com/dgrtwo/dgrtwo.github.com/tree/master/_R))). But it was still great to hear people communicate these messages well, and the reproducibility session chaired by Amelia McNamara was an all-star cast.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/minebocek">@minebocek</a> makes an important point- requiring reproducibility makes work easier for students, not harder <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> <a href="https://t.co/RU1CWHgbwy">pic.twitter.com/RU1CWHgbwy</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/760850027958919168">August 3, 2016</a></blockquote>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/kwbroman">@kwbroman</a>&#39;s colleague was &quot;sorry you did all that work on incomplete dataset&quot;- reproducibility for the win <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> <a href="https://t.co/cUTR2LRA1J">pic.twitter.com/cUTR2LRA1J</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/760838739866316800">August 3, 2016</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Jenny Bryan talked about her and Ritz FitzJohn's work on the [jailbreakr](https://github.com/rsheets/jailbreakr) package for reading warts-and-all Excel spreadsheets into R.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">. <a href="https://twitter.com/JennyBryan">@JennyBryan</a> encouraging empathy for spreadsheet users as always <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> <a href="https://t.co/Nu5omprsW3">pic.twitter.com/Nu5omprsW3</a></p>&mdash; Hilary Parker (@hspter) <a href="https://twitter.com/hspter/status/747864222017560576">June 28, 2016</a></blockquote>

(This is something [I've tried before](http://rpubs.com/dgrtwo/tidying-enron) but of which she and Ritz are the undisputed champions).

I particularly liked Yihui Xie's idea about teaching reproducibility:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/xieyihui">@xieyihui</a> had &quot;evil&quot; idea to teach reproducibility:<br><br>Week 1: Students analyze a dataset<br><br>Week 2: &quot;I updated the data, start over&quot;<a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/760857073122934784">August 3, 2016</a></blockquote>

(Interestingly, a number of responses were along the lines of "How is that evil, that's exactly what I've been doing!")

In the same session, Karthik Ram from rOpenSci described [JOSS](http://joss.theoj.org/), the Journal of Open Source Software. This is an excellent way to get citations and credit for software, and therefore for scientists to think of software packages (and not just papers) as units of research output.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/_inundata">@_inundata</a> promotes Journal of Open Source Software, w/ tidytext article by <a href="https://twitter.com/juliasilge">@juliasilge</a>+me as example 🎉🎉 <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> <a href="https://t.co/IOdF9Vt2hK">pic.twitter.com/IOdF9Vt2hK</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/760847306799349760">August 3, 2016</a></blockquote>

### Interactive Graphics

Many of my other favorite talks were about making online interactive visualizations.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Screw the dance party; after this <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> session I sorta want to spend tonight making interactive graphs <a href="https://twitter.com/hashtag/rstats?src=hash">#rstats</a> <a href="https://t.co/18otBYdgLP">pic.twitter.com/18otBYdgLP</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/760571353963630593">August 2, 2016</a></blockquote>
<script async src="http://platform.twitter.com/widgets.js" charset="utf-8"></script>

A lot of my knowledge about interactive graphics revolves around [Shiny](http://shiny.rstudio.com/). Shiny's a terrific tool, but it requires an R backend, which requires some effort and cost for deployment and scaling. I was excited to see what people were up to about building interactive graphics in R that could be deployed entirely in HTML and Javascript.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/jcheng">@jcheng</a> demos crosstalk <a href="https://twitter.com/hashtag/rstats?src=hash">#rstats</a> pkg for interactive web graphs- define in R, deploy in Javascript. Wow! <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> <a href="https://t.co/iyEwOBEiiJ">pic.twitter.com/iyEwOBEiiJ</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/760564295365197824">August 2, 2016</a></blockquote>
<script async src="http://platform.twitter.com/widgets.js" charset="utf-8"></script>

Ryan Hafen's [rbokeh](http://hafen.github.io/rbokeh/) package is really exciting and something I hadn't seen before (like others, I thought of Bokeh as a Python visualization package, but it turns out the backend is flexible). Since it plots in an HTML canvas it also doesn't need an R backend, and I appreciated how the syntax used the `%>%` pipe and followed the grammar of graphics.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/hafenstats">@hafenstats</a> trying 20 examples of rbokeh in 5 minutes <a href="https://t.co/EOWEfeFW0x">https://t.co/EOWEfeFW0x</a> <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> <a href="https://t.co/p2UWAEVqzj">pic.twitter.com/p2UWAEVqzj</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/748589269833261057">June 30, 2016</a></blockquote>

Carson's Sievert has taken the "make ggplot2 interactive" conversation to a whole new level, though, with the [plotly package](https://github.com/ropensci/plotly), an R interface to the popular [Plotly](https://plot.ly/) software that among other features includes conversion of ggplot2 objects into interactive plotly graphs.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Teaser for my <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> on interactive graphics with <a href="https://twitter.com/plotlygraphs">@plotlygraphs</a> <a href="https://twitter.com/hashtag/rstats?src=hash">#rstats</a> <a href="https://t.co/koAqMg7t8j">pic.twitter.com/koAqMg7t8j</a></p>&mdash; Carson Sievert (@cpsievert) <a href="https://twitter.com/cpsievert/status/760153512621637632">August 1, 2016</a></blockquote>

I think Yihui Xie might have won the day, though. He not only led a terrific discussion of the previous talks (packed with GIFs, as is his habit), but also demonstrated a [Shiny app](https://yihui.shinyapps.io/voice/) that does something I'd never seen before in R:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/xieyihui">@xieyihui</a> is customizing graphs with his voice and the room is Flipping. Out. <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> <a href="https://twitter.com/hashtag/rstats?src=hash">#rstats</a> <a href="https://t.co/HlFOL7rXGK">pic.twitter.com/HlFOL7rXGK</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/760572927947501568">August 2, 2016</a></blockquote>
<script async src="http://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/xieyihui">@xieyihui</a>: &quot;Change title to Make America Great Again&quot;, graph complies. Statistical applications are clear <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> <a href="https://t.co/1EhesE3s1D">https://t.co/1EhesE3s1D</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/760574342208036865">August 2, 2016</a></blockquote>

(Incidentally, I did end up going to the dance party, and *still* haven't had the chance to use these interactive graphics for more than toy problems. Looking forward to the right opportunity to use them!)

### RStudio

[RStudio](https://www.rstudio.com/) has been one of the most influential companies in the modern R world, not only developing the eponymous IDE but supporting many important open source packages, and the company was at both conferences in full force.

RStudio CEO J.J. Allaire talked about the new interactive notebook features of the RStudio IDE, analogous to Jupyter notebooks:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">comparison betw R markdown &amp; notebooks in JJ Allaire’s intro to <a href="https://twitter.com/rstudio">@RStudio</a>’s awesome new Rmd notebooks <a href="https://twitter.com/hashtag/UseR2016?src=hash">#UseR2016</a> <a href="https://t.co/4QFp8hhBuu">pic.twitter.com/4QFp8hhBuu</a></p>&mdash; Karl Broman (@kwbroman) <a href="https://twitter.com/kwbroman/status/748209635501318145">June 29, 2016</a></blockquote>

Hadley Wickham gave a useR keynote that pushed for a seismic shift in terminology:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">.<a href="https://twitter.com/hadleywickham">@hadleywickham</a> proposes we stop saying &quot;Hadleyverse&quot;, start saying &quot;tidyverse&quot; <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> <a href="https://twitter.com/hashtag/rstats?src=hash">#rstats</a> <a href="https://t.co/Z4zs4tw2Vn">pic.twitter.com/Z4zs4tw2Vn</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/748196885307920385">June 29, 2016</a></blockquote>

He also stepped in for Yihui Xie to introduce Yihui's terrific [bookdown](https://bookdown.org/yihui/bookdown/) package:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">The philosophy behind <a href="https://twitter.com/hashtag/rstats?src=hash">#rstats</a> bookdown: easy, community-written, freq updated <a href="https://twitter.com/hadleywickham">@hadleywickham</a> + <a href="https://twitter.com/xieyihui">@xieyihui</a> <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> <a href="https://t.co/WudsaLbHzY">pic.twitter.com/WudsaLbHzY</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/748575703025627137">June 30, 2016</a></blockquote>

I was inspired enough by this package that one week later Julia Silge and I started writing the book [Tidy Text Mining in R](https://github.com/dgrtwo/tidy-text-mining). Bookdown has been a real treat: it's solved so many of the hassles around creating HTML and PDF manuscripts from knitr.

I was excited to meet RStudio's Garrett Grolemund for the first time and talk statistics, education and R. He's the creator of an awesome set of cheat sheets ([available online](https://www.rstudio.com/resources/cheatsheets/)) on R, and grabbing some hard copies at the RStudio booth was a nice bonus.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> people: remember to stop by <a href="https://twitter.com/rstudio">@rstudio</a> booth to pick up awesome cheatsheets by <a href="https://twitter.com/StatGarrett">@StatGarrett</a> <a href="https://t.co/9KWE9J416S">pic.twitter.com/9KWE9J416S</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/748593622526750721">June 30, 2016</a></blockquote>

Finally, I was *crazy* excited that RStudio had printed my first set of broom hex stickers:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr"><a href="https://twitter.com/drob">@drob</a> i have this for you! <a href="https://t.co/8fpb2v738x">pic.twitter.com/8fpb2v738x</a></p>&mdash; Hadley Wickham (@hadleywickham) <a href="https://twitter.com/hadleywickham/status/747842262877380608">June 28, 2016</a></blockquote>

(The stickers are available on [stickermule](https://www.stickermule.com/user/1070448958/stickers), and I'll usually have some on hand at conferences and meetups if you run into me).

### Accessibility

There are a lot of important ongoing conversations about diversity and inclusion in the R community (e.g. the [TaskForce on Women in R](http://forwards.github.io/), which [presented on its findings at useR](https://rpubs.com/hturner/useR2016)). But Jonathan Godfrey, a lecturer at Massey University in New Zealand, alerted me to another dimension of diversity I hadn't considered before.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Jonathan Godfrey showing us how he uses a Braille keyboard to develop R code. Just amazing. <a href="https://twitter.com/hashtag/rstats?src=hash">#rstats</a> <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> <a href="https://t.co/zYUFOeJXmY">pic.twitter.com/zYUFOeJXmY</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/747687118680502272">June 28, 2016</a></blockquote>
<script async src="http://platform.twitter.com/widgets.js" charset="utf-8"></script>

Dr. Godfrey is blind, and along with teaching and consulting on statistics, he develops some tools for helping vision impaired statisticians work with R, such as an [in-progress e-book]([e-book](https://github.com/ajrgodfrey/LetsUseRNow)) and the [BrailleR](https://github.com/ajrgodfrey/BrailleR) package. One example of the BrailleR package is converting visualizations so that they could be understood by screen readers or Braille keyboards:


{% highlight r %}
library(BrailleR)

x <- rnorm(1000)

VI(hist(x))
{% endhighlight %}



{% highlight text %}
## This is a histogram, with the title: Histogram of x 
##  "x" is marked on the x-axis.
## Tick marks for the x-axis are at: -3, and 3 
## There are a total of 1000 elements for this variable.
## Tick marks for the y-axis are at: 0, 50, 100, and 150 
## It has 12 bins with equal widths, starting at -3 and ending at 3 .
## The mids and counts for the bins are:
## mid = -2.75  count = 8 
## mid = -2.25  count = 17 
## mid = -1.75  count = 46 
## mid = -1.25  count = 96 
## mid = -0.75  count = 154 
## mid = -0.25  count = 180 
## mid = 0.25  count = 182 
## mid = 0.75  count = 136 
## mid = 1.25  count = 114 
## mid = 1.75  count = 45 
## mid = 2.25  count = 17 
## mid = 2.75  count = 5
{% endhighlight %}

Talking to him made me realize what great strides had been made in statistics and programming for the blind ([here's more on that general topic](http://stackoverflow.com/questions/118984/how-can-you-program-if-youre-blind)), but also what obstacles remained for R in particular. I take RStudio for granted, but according to Jonathan it's effectively unusable for blind users (too many buttons, tabs and drop-down menus, which are difficult to navigate with a screenreader). Towards that goal he's been working on the [WriteR IDE](https://github.com/ajrgodfrey/WriteR) for accessible programming in R and R markdown:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Jonathan Godfrey talks WriteR: IDE accessible to blind. Looking for Python-savvy volunteers to contribute <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> <a href="https://t.co/HEYum541jE">pic.twitter.com/HEYum541jE</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/748248669854404608">June 29, 2016</a></blockquote>
<script async src="http://platform.twitter.com/widgets.js" charset="utf-8"></script>

(You can find the video of his talk on WriteR, and on the pitfalls of markdown for blind users, [here](https://channel9.msdn.com/Events/useR-international-R-User-conference/useR2016/R-markdown-Lifesaver-or-death-trap)).

I also asked him about the topic of [data sonification](https://en.wikipedia.org/wiki/Sonification) to replace visualization for blind scientists. Jonathan was very skeptical- among other issues, he pointed out that sight and sound often provide different but complementary channels of information, which is the reason sighted statisticians can find sonification useful. He also noted that he often works with at least one sighted collaborator, so there's still an opportunity for [visualization to surprise someone in ways a model cannot](http://www.johndcook.com/blog/2013/02/07/visualization-modeling-and-surprises/). I don't know much about the topic and I wonder if there are other perspectives.

### People

Probably my favorite part of visiting a conference is the people I got to see, whether meeting them for the first time or seeing them again.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Table of <a href="https://twitter.com/hashtag/useR2016?src=hash">#useR2016</a> folks, chatting, as one does, about how much fun it is to be called Dr. <a href="https://t.co/goxtTlmNcE">pic.twitter.com/goxtTlmNcE</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/748678832794705920">July 1, 2016</a></blockquote>
<script async src="http://platform.twitter.com/widgets.js" charset="utf-8"></script>

Aside from the people I've already mentioned (and many others), it was great to meet up with the Hopkins/ex-Hopkins Biostatistics crowd.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Four statisticians setting up an eposter<br><br>&quot;Does anyone know how to use Windows?&quot;<a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> <a href="https://twitter.com/jtleek">@jtleek</a> <a href="https://twitter.com/acfrazee">@acfrazee</a> <a href="https://twitter.com/hspter">@hspter</a> <a href="https://t.co/d1hfD4ElBi">pic.twitter.com/d1hfD4ElBi</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/759895655938678785">July 31, 2016</a></blockquote>

Hilary Parker chaired an excellent session on data science in industry. I missed Jeff Leek's talk since mine was at the same time, but our feud did make an appearance in his slides:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">😄😄😄 <a href="https://twitter.com/jtleek">@jtleek</a> s/o to <a href="https://twitter.com/drob">@drob</a> and the actual reasons people use methods <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> <a href="https://t.co/gRHXYgEbjh">pic.twitter.com/gRHXYgEbjh</a></p>&mdash; Hilary Parker (@hspter) <a href="https://twitter.com/hspter/status/760129814598602753">August 1, 2016</a></blockquote>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">I&#39;m OK with this analogy from <a href="https://twitter.com/jtleek">@jtleek</a>&#39;s talk because I get to be Batman <a href="https://twitter.com/hashtag/rstats?src=hash">#rstats</a> <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> <a href="https://t.co/nBpoW7qunx">pic.twitter.com/nBpoW7qunx</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/761239526270439425">August 4, 2016</a></blockquote>

I was happy to see my former colleague Chee Chen present at JSM on work he and I had done together:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Rather than defining 1 p-value threshold for FDR control, fFDR has threshold vary w/informative variable Z <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> <a href="https://t.co/HQAUAyRrPG">pic.twitter.com/HQAUAyRrPG</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/761216216388214784">August 4, 2016</a></blockquote>

And see my former adviser John, who has always been a compelling statistical communicator.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">This slide by <a href="https://twitter.com/johnstorey">@johnstorey</a> sets great example for math presentation- graphics help audience follow equations <a href="https://twitter.com/hashtag/JSM2016?src=hash">#JSM2016</a> <a href="https://t.co/svDULAXZyc">pic.twitter.com/svDULAXZyc</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/760140139611979776">August 1, 2016</a></blockquote>

Among the new people I got to meet were Amelia McNarama and Craig Citro, who gave me a run for my money at talking quickly:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">fast_talking_R_mafia &lt;- c(&quot; <a href="https://twitter.com/drob">@drob</a>&quot;, &quot;<a href="https://twitter.com/AmeliaMN">@AmeliaMN</a>&quot;, &quot;<a href="https://twitter.com/craigcitro">@craigcitro</a>&quot;)<a href="https://twitter.com/hashtag/User2016?src=hash">#User2016</a> <a href="https://t.co/jLrAzRiPrM">pic.twitter.com/jLrAzRiPrM</a></p>&mdash; Karthik Ram (@_inundata) <a href="https://twitter.com/_inundata/status/748681351864283136">July 1, 2016</a></blockquote>

There were so many other people and so many other talks I could have mentioned here (if you scroll through my twitter feed under #JSM2016 and #useR2016 you'd see a lot more). Overall I'm very glad I attended both, and that I had the chance to learn from and contribute to the great R and statistics communities. And I'm glad I wasn't too #serious to share that.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Story of how I once was a <a href="https://twitter.com/hashtag/seriousacademic?src=hash">#seriousacademic</a>, but Twitter turned me into a <a href="https://twitter.com/hashtag/sillydatascientist?src=hash">#sillydatascientist</a> <a href="https://t.co/QGZRJbOUZM">https://t.co/QGZRJbOUZM</a></p>&mdash; David Robinson (@drob) <a href="https://twitter.com/drob/status/761599542663979009">August 5, 2016</a></blockquote>
