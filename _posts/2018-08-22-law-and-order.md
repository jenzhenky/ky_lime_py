---
title: 'Law & Order SVU: Investigating the Cast'
header:
  teaser: /assets/images/svu-opening-teaser.jpg
---
*How often do actors appear on SVU?*

{% include figure image_path="/assets/images/svu-opening.jpg" alt="SVU Opening Credits" caption="SVU opening credits via [Wikipedia](https://en.wikipedia.org/wiki/Law_%26_Order:_Special_Victims_Unit#/media/File:SVUopening.jpg)" %}

One of my guilty pleasures is binge-watching *Law & Order: Special Victims Unit* (SVU). I find its repetitive nature to be meditative and it's fun to recognize the New York sights. But I've also recognized a lot of familiar faces and wondered: how often do actors actually reappear on the show?

There are a lot of episodes (one season per year since 1999), so this seemed like a great introductory Python project. In this post, I gathered data with web scraping, cleaned data sets, and analyzed data to delve into some of my questions about SVU. 

*Check out my code for this project [here](https://github.com/jenzhenky/SVU).*

### Gathering the (data) evidence

I used a web scraping package, Scrapy, to scrape the episode information and cast list for all 434 episodes. Next, I cleaned up the raw data to create a list of actors and their roles. Finally, I created a dataframe with each unique actor-role combination and the episodes in which they appeared. There were 7,839 unique actor-role combinations and 6,330 unique actors over 19 seasons - a prolific list for a prolific show!

### How often do actors appear on the show?

No surprise: Mariska Hargitay who plays Detective Olivia Benson has been in every episode of SVU. The runner-up is Ice-T as Detective Odafin Tutuola (Fin) who was in 412 of 434 episodes. Interestingly, the distribution of actor appearances on the show was very skewed to one-timers and there were fewer core cast members than I had expected. Only 10 actors had appeared on over 100 episodes, 20 had appeared in 20 to 100 episodes, and 97% of the actors on the show appeared in fewer than 5 episodes.

{% include figure image_path="/assets/images/svu_actor_dist.png" alt="Distribution of actor appearances" caption="SVU is heavily skewed towards actors who have appeared on the show fewer than 10 times. Note: over 6000 actors have appeared on the show fewer than 5 times and were excluded from this chart to show the remaining distribution." %}

### Who's the low-key MVP of SVU?

The unsung hero of the show is [James Zeiss](https://www.imdb.com/name/nm6079503/). According to IMDb, he is the actor with the most unique roles on the show at a whopping 16 (though they are uncredited roles). He appeared in seasons 15 to 19 in roles such as "Atlanta Detective" and "Courtroom Reporter". SVU must have a special place in his heart because it is the show in which he most frequently appeared, followed by 10 episodes of *Blue Bloods*.

### Fun fact - Celebrity Edition
<figure class="half">
	<a href="/assets/images/biden-svu.jpg"><img src="/assets/images/biden-svu.jpg"></a>
   	<a href="/assets/images/chainz-svu.jpg"><img src="/assets/images/chainz-svu.jpg"></a>
	<figcaption>Joe Biden and 2 Chainz on SVU via <a href="http://time.com/4513184/joe-biden-svu-cameo/">Time</a> and <a href="https://www.spin.com/2013/04/2-chainz-law-and-order-svu-mariska-hargitay-instagram/">SPIN</a></figcaption>
</figure>
What do 2 Chainz and Joe Biden have in common? They have both appeared on SVU! 2 Chainz appeared in Season 14 Episode 22, "Poisoned Motive." His scene opens with an Asian massage (because he has "sciatica") and ends with Olivia and Fin shaking him down for information on a cop killer. Here's a thorough [list of every line he uttered](https://www.complex.com/music/2013/05/heres-every-line-that-2-chainz-said-on-law-and-order-svu-last-night). 

While in office, Joe Biden appeared on Season 18 Episode 2, "Making a Rapist," to speak about the country's backlog of untested rape kits. And here's [Ice-T on what it was liking working with the vice president](https://www.huffingtonpost.com/entry/joe-biden-ice-t-svu_us_57ec33eee4b0c2407cdba44f): “You know I got a lot of friends, but I’m like, ‘Yo, show up at my job,’ and they’re like, ‘Nah, I ain’t that close to you, homie…And to be able to get a vice president to actually arrange his schedule to do TV, c’mon, be serious.” 

Be serious, indeed, Ice-T.
