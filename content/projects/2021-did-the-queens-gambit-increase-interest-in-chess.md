---
title: Did The Queen's Gambit increase interest in Chess?
date: 2021-01-18T22:11:23.120Z
draft: false
categories: Podcast
tags:
  - Tableau
author: Chris Stayte
authorImage: uploads/chrisstayte_profilepic.jpg
comments: true
share: true
type: post
---
As many of you probably know, The Office was savagely taken off of Netflix on January 1st, 2021, leaving me and millions of other fans in the dust with nothing to watch other than about 4000 other shows and movies. The disappointment and sense of betrayal made it hard to look at Netflix in the screen. But eventually, after one whole day, I found forgiveness in my heart and decided to give the streaming service another chance. I logged in and started looking through the “Recommended for You” section when I stumbled upon The Queen’s Gambit. The show looked interesting and I had heard great things about it, so I decided to give it a spin.

The Queen’s Gambit follows a prodigious chess player named Elizabeth Harmon who rises up the ranks in the chess world while navigating through the struggles of substance abuse, a troubled past, and her personal relationships. The show is highly atmospheric and immaculately cast. I absolutely loved it and would recommend it to anyone who likes good things. I liked it so much, in fact, that I decided to give chess another try. This is a big deal, people. Hearing my history with chess is enough to put most people on antidepressants. I remember being a participant in the chess club in the 4th grade and losing every single game I played the entire year (ok, I got a draw in one game, but mentioning that would make my statement less impactful). 

Anyway, my newfound interest in chess made me curious if anyone else got interested in the game after watching the show too. In December of 2020, CNN reported that “a record 62 million households watched The Queen’s Gambit in its first month”. Surely, it’s plausible right the show garnered substantial interest in chess, right?

**I decided to measure interest in three different ways:** 

1. **Internet Searches:** Did more people make internet searches related to chess after the show was released?
2. **Chess Community Growth:** How did growth rates of popular chess-related subreddits change after the show was released?
3. **Online Chess Growth:** Did online chess websites and applications see user growth after the show was released?

To answer these questions, I found and created the necessary datasets, cleaned them in Excel, and finally transferred them into Tableau to make them look pretty.

### ***Internet Searches:***

To measure interest through internet searches, I used Google’s Trends Tool. I acquired data for the keywords “the queens gambit” and “chess”. The first step was to make sure that interest in these two keywords has similar growth patterns. Doing this would help me determine if there was a meaningful connection between the game and the show.

![](/images/uploads/goodsc.png)

Before the show’s release, the average search interest indices in 2020 were 51.2 for “chess” and .93 for The Queen’s Gambit”. Significant increases in interest began around October 23rd, 2020, the Show’s release date. Within a month after release, the search interest index for “chess” and “the queens gambit” reached a maximum of 100. However, “the queens gambit” reached an interest index of 100 within a week of the Show’s release while “chess” took approximately a month to reach the same level of interest. 

While “the queens gambit” was about four times faster to reach maximum interest than “chess” was, interest in “the queens gambit” rapidly decreased between November and the end of December driving down the average interest index to 65.6. In this same period, “chess” maintained an average interest index of 87.2. By the end of December, “the queens gambit” had an interest index of 43 while “chess” maintained an interest index of 100. 

These trends are mostly expected. Once individuals watch The Queen’s Gambit, they might move on to different shows, which would decrease the interest index. However, if they developed an interest in chess, they would likely keep coming back to the game, meaning that the interest index would remain high. In other words, individuals might not repeatedly watch The Queen's Gambit, but may repeatedly play games of chess.  

Next, I wanted to confirm that interest in the keywords came from similar regions. Doing this allowed me to confirm that the spike in chess' interest didn’t come from a country that had no interest in the show. If increases in interest for chess came from regions that didn’t have much interest in the show, it would suggest that something other than the release of the show was increasing interest in chess.

![](/images/uploads/screen-shot-2021-01-26-at-9.38.03-am.png)

![](/images/uploads/screen-shot-2021-01-26-at-9.34.27-am.png)

The map charts above show that worldwide interest in the two keywords did indeed come from similar locations. Interest in “the queens gambit” generally comes from areas where there is a preexisting interest in “chess”. Also, more regions of the world had an interest in “chess” than they did in “the queens gambit”.  For example, in India, “chess” had a max developed a maximum interest of 43 while “the queens gambit” developed a maximum interest of 2. A similar trend is seen in Russia. 

Trends shown by the graphs above helped me confirm plausibility behind the notion that a rise in chess’s popularity after the show’s release can be at least partially attributed to the show garnering interest in the game. 

It should be noted that no major events in the chess community (tournaments, big announcements, etc.) took place around the release of the show, meaning that there was nothing prominent enough to have created this large influx of chess period in this period.

### ***Online Chess Community Growth:***   

There are a lot of online chess communities out there. I decided to analyze growth in different chess-related subreddits. There’s a good chance that many new chess players are already familiar and acquainted with Reddit, so joining a chess-related subreddit would be a natural starting point for them to become part of the community. The subreddits I decided to focus on are r/chess, r/AnarchyChess, r/chessbeginners, and r/chessvariants. I picked these subreddits because they are the top four most popular chess-related subreddits. The graphs below show monthly growth in 2020 for each subreddit.

![](/images/uploads/screen-shot-2021-01-26-at-9.36.21-am.png)

![](/images/uploads/screen-shot-2021-01-26-at-9.38.49-am.png)

![](/images/uploads/screen-shot-2021-01-26-at-9.38.16-am.png)

![](/images/uploads/screen-shot-2021-01-26-at-9.35.31-am.png)

All four of the subreddits reported above-average growth in the months after The Queen’s Gambit was released. Between January and September, r/chess grew by a total of 62,484 subscribers. Between October and December, the subreddit grew by 61,592 subscribers. The subscriber growth between October and December accounted for approximately 50 percent of the r/chess’s annual growth! The same period accounted for about 54 percent of r/chessbeginners’s growth, 43 percent of r/AnarchyChess’s annual growth, and 48 percent of r/chessvariant’s growth.  

It should be noted that the show was released at the end of October, which very likely a reason why subreddit growth in October wasn’t too substantial. 



![](/images/uploads/screen-shot-2021-01-26-at-9.36.45-am.png)

While r/chessvariants seemingly shows a flat growth line, it should be noted that the subreddit is growing and has grown at a faster rate ever since the show release, as indicated by the earlier bar graphs. The flat line is a product of the graph’s scale and the comparative monstrosities that the other subreddits are.

The graphs above universally show that there was a rise in the growth rate of each subreddit around The Queen’s Gambit’s time of release. This is potentially indicative of a positive impact on chess interest from the show.

### ***Online Chess Growth:*** 

The most accessible way to get into chess in the modern age is through online chess. With millions of players all around the world, no fees, and without the need for a physical board, there are very few barriers to entry for online chess. Growth in online chess around the time of the show’s release is an ideal indicator of the show’s impact on interest in the game. Below is a chart depicting the growth of popular chess websites over time. Sites shown in the figures below show up on the first page of Google searches under the search keys “online chess” and “learn chess”. 

![](/images/uploads/chesssite2.png)

![](/images/uploads/chesssite1.png)

As shown in the charts, the average monthly growth for all websites was universally above average in October. However, this monthly increase tapered off in November. In some cases, such as chess.org, chess24.com, and chesskid.com, monthly traffic actually decreases.

The real winner here is chess.com. This is no surprise. Chess.com is the largest, most noticeable, online chess website in the world. They also attract some of the world’s most popular chess streamers such as Alexandra Botez and Hikaru Nakamura. Their outreach efforts and popularity make them an ideal place for new chess players to start playing.

Between October and December, chess.com’s monthly traffic increased by approximately 16.1 million people (60.1 percent increase). In second place was chess24.com, which only had a monthly traffic increase of approximately 450,000 people (43 percent increase).

Since chess.com is an extremely popular online chess platform, another indicator of the show’s impact on online growth can be seen through chess.com app store rankings.

 

![](/images/uploads/screen-shot-2021-01-26-at-9.38.34-am.png)

On October 20th, 2020, the Chess.com app was ranked around 1000 for both iPhone and iPad. Less than a week after the Show's release, the app was ranked around 410 for both platforms. This means that the app rose up by about 490 ranks in less than a week! Unfortunately, I could not gather data for the Play Store in the same period. However, the other data I was able to gather for the Play Store showed similar rankings. 

Given that there were no major events in the Chess community during the period of the show’s release, it’s reasonable to think that the show had some impact on the stark rise of chess’s popularity in that period.

Between 2009 and 2016, the OECD surveyed individuals in 32 countries around the world and found that the average individual watches TV or listens to the radio for 118 minutes per day. Television plays an important part in shaping our views and interests. So, when The Queen’s Gambit was released, I became curious about whether the Show increased interest in the game.

The data I found suggests that The Queen’s Gambit certainly had an interest in chess interest. After the show’s release, chess-related Google searches garnered massive interest, online chess communities and servers grew at above-average rates.

I’m curious to see how permanent this increase in interest is. Will it taper off throughout 2021 as people move to bigger and better things? Will the game continue to grow in popularity? The answers to these questions could provide good insight as to how media affects different hobbies or activities.