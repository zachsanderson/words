---
layout: post
title:  "Orioles baseball hackathon"
date:   2016-02-05
categories: projects
featured: yes
excerpt_separator: <!-- more -->

images:

    -   url: /images/orioleshackathon-1600.jpg
        alt: Flyer advertising the 2016 Orioles baseball hackathon
    -   url: /images/hackathonposter-1600.jpg
        alt: Flyer advertising the 2016 Orioles baseball hackathon
    -   url: /images/miltpappasteam-1600.jpg
        alt: Alex, Aaron and Zach around Frank Robinson's jersey
        caption: Alex, Aaron and I with our favorite Red, er, Oriole
    -   url: /images/miltpappasandbats-1600.jpg
        alt: Milt Pappas' baseball card, his bat amongst other Oriole bats
        caption: We took a few liberties with one of Milt's baseball cards. And then found his bat hanging on the wall at Camden Yards.
    -   url: /images/expectedoutcomescards-1600.jpg
        alt: Alex, Aaron and Zach's baseball cards
        caption: I couldn't find these in Beckett's
    -   url: /images/situationalpitching-1600.jpg
        alt: Screenshot of Situational Pitching data visualization
        
---

My friend Aaron emailed me with a link that had a couple of my favorite words in it: [baseball and hackathon](https://www.eventbrite.com/e/baseball-analytics-hackathon-registration-20112410762 "Orioles baseball hackathon").

Aaron and I can have 5 hour long conversations, but there were no other words in his email. None necessary. I emailed back "Road trip?"

{% assign image = page.images[1] %}
{% include image.html image=image %}

What the Orioles were proposing was a data analytics hackathon with a baseball angle to it. There really wasn't much more info besides it was going to be hosted by the Orioles at Camden Yards. I didn't need any more than that.

They were looking for teams of 3-6. I knew [Aaron](http://aaronjlehr.com "Aaron Lehr") would be a great candidate and his girlfriend [Alex](https://duchessofdata.wordpress.com/ "Alex Duke"), an even better one. I felt pretty good about putting together a sales pitch for the three of us. I still tried to manage my hopes and confidence. As a college baseball fan, I see how deep the draft goes and how few actually make it.

The application requirements fit us pretty well. They asked us to answer three questions: our baseball experience, our data experience and our web experience. Although each of us had good answers for all three, we were able to each share a specialty in one. We hit on Aaron's experience obsessing over baseball and things like sabermetrics. We hit on Alex's job and experience at [Slalom](https://www.slalom.com/ "Slalom Consulting"), a consulting firm where she presents data all day, not to mention her Tableau community experience. And I was Web Guy.

{% assign image = page.images[2] %}
{% include image.html image=image %}

We sprinkled in some overall baseball love from the three of us and decided to go with an obscure Orioles reference for the team name: Milt Pappas and the Expected Outcomes. We explained: 

> As Reds fans and sympathizers, Alex Duke, Aaron Lehr and Zach Sanderson couldn't help but wonder if Bill DeWitt hosted a baseball analytics hackathon in 1965, maybe Milt would have stayed an Oriole and Frank Robinson a Red.

We assumed the Orioles knew the history of Milt. Aaron, the more seasoned Reds fan, explained [his significance to me](https://en.wikipedia.org/wiki/Milt_Pappas#Cincinnati_Reds "Milt Pappas traded to the Reds").

{% assign image = page.images[3] %}
{% include image.html image=image %}

I had some hackathon experience, but most of that came from [hosting one](https://www.flickr.com/photos/zachsanderson/albums/72157664829044063 "Dev/Iowa Hackathon") and not participating. I also knew that every hackathon is different, so my experience didn't mean much. Based on the feel of the room when we first came in, I thought this would be a pretty technical competition. The Orioles ended up providing us a huge data dump of Pitch F/X data and asking us to come up with something creative, actionable and functional for the front office to use.

We worked to our strengths. I'll just say now though: mine were limited. The hackathon is 8 hours and though I've done some data work with large hospital datasets, "rapid" was never in the vocabulary. I definitely filled a more administrative role for the team.

Aaron's strengths were definitely useful. I'd say he came out as our Opinions Guy. Sure, pretty pictures of numbers are great, but Aaron was able to best articulate why it mattered. Aaron and I talk about this stuff all the time, so I kind of knew where he stood.

But Alex, Alex was insane. I of course don't know her as well as a guy I've known since kindergarten. I've seen links to her Tableau visualizations and certainly saw their quality, but I'd never seen her work in real time. About 6 hours in she had put together a fantastic dashboard-esque visualization in Tableau. And then she and Aaron had a moment of doubt. "This isn't saying anything."

At that point, my argument, as been-to-a-hackathon-before guy, was "Who cares. We need to ship it." That's the antithesis of me in real life. I'm constantly trying to battle my perfectionism and what better place to do it than a hackathon with the clock ticking. They overruled my vote and completely ripped the engine out. With 90 minutes left.

I honestly did not come in looking to win any prizes. I knew the event itself would be fun. They were saying, "We're not going to win if we aren't saying anything." My response (mostly internal) was, "Oh well. Then we didn't win. Still fun though."

{% assign image = page.images[4] %}
{% include image.html image=image %}

In the last hour, I put together a slide deck and handled some administrative-y communication stuff with the hackathon staff while Aaron and Alex put the engine back together.

Aaron was our presenter and was going to go off of bullet points that he and I put in the slideshow. We started with a brief overview of our initial plans. Aaron presented it really well. Even squeezed a laugh out of the room. To me this had all the trappings of a good "Well this is what we were going for," white flag-type hackathon presentation.

Our last bit was to present what we ended up with. Alex was sitting next to me on the floor and took over the mouse as Aaron walked through some scenarios on the dashboard. When Alex started mousing around, it was really my first time seeing it in an hour or two, since I was getting the presentation ready. I hope the judges weren't looking because I'm sure I was visibly surprised. I had no idea what she had put together in the final minutes. Every idea or suggestion Aaron said, she just hovered over or clicked and that information was presented.

{% assign image = page.images[5] %}
{% include image.html image=image %}

[Go to the Tableau page to see the final interactive visualization](https://public.tableau.com/profile/alexandria4237#!/vizhome/ExpectedOutcomes/Dashboard1 "The final product")

Aaron's explanation was perfect. Alex's demonstration was perfect. I even advanced the slides at the right time.

I was a lot more confident when we finished, but I didn't know how the judges would see it. 

When they came out to announce the winners, one of the judges prefaced the awards with emphasis on the ability to present your findings. He really hammered on this. This made the guy inside me who wishes he knew more R feel like he was getting punched, but it made the guy who was riding on Alex and Aaron's coattails feel even more confident.

There was one team I was especially worried about. They presented on the success rates of consecutive pitch types. That idea was just too perfect and I turned to Aaron and said "Winner."

I was right. They ended up with 1st but we got 2nd. As we packed up, we talked with members of the Orioles front office and the event sponsor, Booz Allen Hamilton. Alex spent most of the time explaining "Yes, you can do that with Tableau."

It was an awesome experience. We won killer tickets to a future Orioles game. I'm hoping the Orioles had a good enough experience to host it again. It's cool to see a MLB team and a big corporate partner get behind events like this.

Aaron wrote up [his thoughts](http://aaronjlehr.com/home/hacking-in-baltimore "Aaron Lehr's Orioles hackathon experience") as well. The [Baltimore Sun](http://www.baltimoresun.com/sports/bal-for-orioles-hackathon-participant-an-impossibly-complex-task-make-sense-of-data-20160209-story.html "Baltimore Sun on the hackathon") picked up the story from Aaron's blog too.

Here's our slidedeck:

<iframe src="//www.slideshare.net/slideshow/embed_code/key/xdxSdcKteK9Qt2" width="725" height="550" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>