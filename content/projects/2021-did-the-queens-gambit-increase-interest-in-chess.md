---
title: Did The Queen's Gambit increase interest in Chess?
date: 2021-01-18T20:27:54.700Z
draft: true
categories: Podcast
tags:
  - Tableau
  - Excel
author: Chris Stayte
authorImage: uploads/chrisstayte_profilepic.jpg
comments: false
share: true
type: post
---
As many of you probably know, *The Office* was savagely taken off of Netflix on January 1st, 2021, leaving me and millions of other fans in the dust with nothing to watch other than about 4000 other shows and movies. The disappointment and sense of betrayal made it hard to look at Netflix in the screen. But eventually, after one whole day, I found forgiveness in my heart and decided to give the streaming service another chance. I logged in and started looking through the “Recommended for You” section when I stumbled upon *The Queen’s Gambit*. The show looked interesting and I had heard great things about it, so I decided to give it a spin.

*The Queen’s Gambit* follows a prodigious chess player named Elizabeth Harmon who rises up the ranks in the chess world while navigating through the struggles of substance abuse, a troubled past, and her personal relationships. The show is highly atmospheric and immaculately cast. I absolutely loved it and would recommend it to anyone who likes good things. I liked it so much, in fact, that I decided to give chess another try. This is a big deal, people. Hearing my history with chess is enough to put most people on antidepressants. I remember being a participant in the chess club in the 4th grade and losing every single game I played the entire year (ok, I got a draw in one game, but mentioning that would make my statement less impactful). 

Anyway, my newfound interest in chess made me curious if anyone else got interested in the game after watching the show too. In December of 2020, CNN reported that “a record 62 million households watched *The Queen’s Gambit* in its first month”. Surely, it’s plausible right the show garnered substantial interest in chess, right?

**I decided to measure interest in three different ways:** 

1. **Internet Searches:** Did more people make internet searches related to chess after the show was released?
2. **Chess Community Growth:** How did growth rates of popular chess-related subreddits change after the show was released?
3. **Online Chess Growth:** Did online chess websites and applications see user growth after the show was released?

To answer these questions, I found and created the necessary datasets, cleaned them in Excel, and finally transferred them into Tableau to make them look pretty.

### ***Internet Searches:***

To measure interest through internet searches, I used Google’s Trends Tool. I acquired data for the keywords “the queens gambit” and “chess”. The first step was to make sure that interest in these two keywords has similar growth patterns. Doing this would help me determine if there was a meaningful connection between the game and the show.

![](/images/uploads/screen-shot-2021-06-06-at-1.45.21-pm.png)

Before the show’s release, the average search interest indices in 2020 were 51.2 for “chess” and .93 for The Queen’s Gambit”. Significant increases in interest began around October 23rd, 2020, the Show’s release date. Within a month after release, the search interest index for “chess” and “the queens gambit” reached a maximum of 100. However, “the queens gambit” reached an interest index of 100 within a week of the Show’s release while “chess” took approximately a month to reach the same level of interest. 



While “the queens gambit” was about four times faster to reach maximum interest than “chess” was, interest in “the queens gambit” rapidly decreased between November and the end of December driving down the average interest index to 65.6. In this same period, “chess” maintained an average interest index of 87.2. By the end of December, “the queens gambit” had an interest index of 43 while “chess” maintained an interest index of 100.

 

These trends are mostly expected. Once individuals watch The Queen’s Gambit, they might move on to different shows, which would decrease the interest index. However, if they developed an interest in chess, they would likely keep coming back to the game, meaning that the interest index would remain high. In other words, individuals might not repeatedly watch The Queen's Gambit, but may repeatedly play games of chess. 

 

Next, I wanted to confirm that interest in the keywords came from similar regions. Doing this allowed me to confirm that the spike in chess' interest didn’t come from a country that had no interest in the show. If increases in interest for chess came from regions that didn’t have much interest in the show, it would suggest that something other than the release of the show was increasing interest in chess.