---
layout: post
title:  "Best Record in Baseball"
subtitle: "Visualization in D3"
date:   2016-04-13
categories: projects
featured: yes
excerpt_separator: <!-- more -->

images:

    -   url: /images/bestrecord
        extension: png
        alt: Best Record in Baseball data visualization screenshot

---

I've been wanting to learn and use D3 for data visualization. I'd done the typical (for me at least) Reading the First Half of a Programming Book. I also took a D3 Lynda course so I had *something* to show even if it was the standard Follow What The Dude Did On A Screen.

Although I still had a bunch of questions, I thought it'd be best to get my hands dirty and search for answers as I went. I've maintained a list of ideas for visualizations for some time but to get started, I wanted to focus more on the tool and less on the design, so I decided to go with [an existing one](http://www.flipflopflyin.com/flipflopflyball/info-bestrecord.html "The Best Record in Baseball by Craig Robinson") that I've always wanted to improve on.

Craig Robinson (Flip Flop Fly Ball) is great. He's a great artist and baseball fan. He's a dude who is from England, discovered baseball while visiting the US with his job in Germany, then watched the Blue Jays while living in Toronto and now lives in Mexico City. I've grown up around baseball and compared to Craig's history, watching it for me was pretty effortless.

I've followed Craig's work for some time, and I love seeing what I saw as a 4 year old through the eyes of an adult discovering it for the first time. Plus, as an artist, Craig is able to visually articulate thoughts I've had but couldn't get out of my brain. I'll admit even as an adult I dream about cool locations for ball fields. Occasionally Craig would just throw up a sketch of a ball field and I'm just like "That's it! That's a ball field I want to see!"

Here are a few of his sketches:

* [An Island Where a Baseball-Like Sport is Played](http://www.fangraphs.com/not/an-island-where-a-baseball-like-sport-is-played/ "An Island Where a Baseball-Like Sport is Played")
* [Fibonacci Fields](http://www.fangraphs.com/not/fibonacci-fields/ "Fibonacci Fields")
* [Cardinals' spring training at a quarry](http://www.flipflopflyin.com/flipflopflyball/art-stlquarry.html "Cardinals' spring training at a quarry")
* I'd give good money for these last three to exist/belong to me:
    * [Perfect life](http://www.flipflopflyin.com/flipflopflyball/art-perfectlife.html "Perfect life")
    * [Baseball field near a cliff](http://www.flipflopflyin.com/flipflopflyball/art-cliff.html "Baseball field near a cliff")
    * [Ballpark in the forest](http://www.flipflopflyin.com/flipflopflyball/art-forestsketch.html "Ballpark in the forest") - I've thought about this since I was 4

Besides his sketches, Craig also has really unique ideas on the other medium of choice for baseball fans: numbers. He doesn't do necessarily the deep number crunching of a sabermetrician but comes up with some very clear thoughts on things that stand out in baseball.

For "The Best Record in Baseball", the one I linked at the top, Craig has visualized an interesting issue that highlights the effect of wild cards and divisions on the outcome of the Playoffs and World Series. Craig's design is a clean but static one. As I've learned about D3 and started seeing clean visuals being made with it, I always thought this would be a great target.

So it's not an original idea but I thought it would first, be good practice for me in learning D3 and second, would allow me to expand on it with some features that let you dig a little deeper into each team/season.

Here's [my current progress](http://zachsanderson.com/data/bestrecord "Best Record in Baseball"). And here's [the git repository](https://github.com/zachsanderson/viz "Git for data visualizations"). But more to come.

#### Some to-dos

* Add large tooltip on hover to dive into each team
* Tweak color scheme and add legend to explain what the hell the colors mean
* Blend tied teams' blocks together much like Craig did
* Incorporate scaling to allow for additional seasons/different browser sizes more easily