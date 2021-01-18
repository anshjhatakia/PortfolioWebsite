---
title: Test Article
date: 2021-01-18T04:18:53.641Z
draft: false
categories: Podcast
author: Chris Stayte
authorImage: uploads/chrisstayte_profilepic.jpg
comments: true
share: true
type: post
---
As many of you probably know, *The Office* was savagely taken off of Netflix on January 1st, 2021, leaving me and millions of other fans in the dust with nothing to watch other than about 4000 different shows and movies. The disappointment and sense of betrayal made it hard to look at Netflix in the screen. But eventually, after 1 whole day, I found forgiveness in my heart and decided to give the streaming service another chance. I logged in and started looking through the “Recommended for You” section when I stumbled upon *The Queen’s Gambit*. The show looked interesting and I had heard great things about, so I decided to give it a spin.

*The Queen’s Gambit* follows a prodigious chess player named Elizabeth Harmon who rises up the ranks in the chess world while navigating through the struggles of substance abuse, a troubled past, and her personal relationships. The show is highly atmospheric, immaculately cast, and reminds me of the rare brilliance that I saw in *Master of None,* my favorite show of all time. I absolutely loved it and would recommend it to anyone who likes good things. I liked it so much, in fact, that I decided to give chess another try. This is a big deal, people. Hearing my history with chess is enough to put most people on antidepressants. I remember being a participant in the chess club in the 4th grade and losing every single game I played the entire year (ok, I got a draw in one game, but mentioning that would make my statement less impactful). It was basically like Rocky III if the movie ended after Rocky’s first fight with Clubber Lang.

Anyway, my newfound interest in Chess made me curious if anyone else got interested in the game after watching the show too. In December 2020, CNN reported that “a record 62 million households watched *The Queen’s Gambit* in its first month”. Surely, it’s plausible right the show garnered a substantial interest in chess, right? Well, ya boy went on the interwebs to find out. And find out I did. And that’s what this project is about.

**I decided to measure interest in 4 different ways:**

<!--\\[if !supportLists]-->1.     <!--\\[endif]-->\*\*Internet Searches:\*\* Did more people make internet searches related to the game after the show was released?

<!--\\[if !supportLists]-->2.     <!--\\[endif]-->\*\*Chess Community Growth:\*\* How did growth rates of popular chess-related subreddits change after the show was released?

<!--\\[if !supportLists]-->3.     <!--\\[endif]-->\*\*Online Chess Growth:\*\* Did online chess websites applications see user growth after the show was released?

<!--\\[if !supportLists]-->4.     <!--\\[endif]-->\*\*Online Market Searches:\*\* Did the number of chess-related keyword searches on Amazon.com increase after the show was released?

Solid methodology, I know. To answer these questions, I found and created the necessary datasets, cleaned them in Excel, and slapped them into Tableau to make them look pretty.

<!--\\[if !supportLists]-->\*\*1.\*\*     <!--\\[endif]-->\*\*Internet Searches:\*\*

To measure interest through internet searches, I used Google’s Trends Tool. I acquired data for the keywords “the queens gambit” and “chess”. The first step was to make sure that interest in these two keywords have similar growth patterns. Doing this would help me determine if there was a meaningful connection between the game and the show.

INSERT GS GRAPH HERE

There’s a connection alright. The above graph shows that the interest index for both keywords shot up to 100 right around the show’s release. The data used for this graph is weekly, so I unfortunately could not get a more specific date for when the jump occurred. However, given that there were no major chess-related events around this time, I’d venture to hypothesize that the jump for both keywords happened close to October 23rd, 2020, the show’s release date.

Next, I wanted to confirm that interest in the keywords came from similar regions. Doing this allows me to confirm that the spike in the interest in chess didn’t come from a country that had no interest in the show.

INSERT FIRST MAP CHART

INSERT SECOND MAP CHART

The map charts above show that worldwide interest in the two keywords did indeed come from similar locations. Interest in “the queens gambit” generally comes from areas where there is a preexisting interest in “chess”. Also, more regions of the world had an interest in “chess” than they did in “the queens gambit”. India is a good example of this with a max interest in “chess” of 43 and a max interest in “the queens gambit” of 2.

Kinda cool, right?

Trends shown by the graphs above helped me confirm plausibility behind the notion that a rise in chess’s popularity after the show’s release can be at least partially attributed to the show garnering interest in the game.

<!--\\[if !supportLists]-->\*\*2.\*\*     <!--\\[endif]-->\*\*Chess Community Growth:\*\*

There are a lot of chess communities out there. I decided to utilize data on popular chess-related subreddits because of Reddit’s accessibility to newcomers. There’s a good chance that many new chess players are already familiar and acquainted with Reddit, so joining a chess related subreddit would be a natural choice for them.

The subreddits I decided to focus on are r/AnarchyChess, r/chess, r/chessbeginners, and r/chessvariants. I picked them because they are the top four most popular chess-related subreddits. The graphs below show monthly growth in 2020 for each subreddit.

INSERT ANARCHYCHESS GRAPH

INSERT CHESS GRAPH

INSERT CHESSBEGINNERS GRAPH

INSERT CHESSVARIANTS GRAPH

All four of the subreddits investigated reported above average growth in the months after *The Queen’s Gambit* released. It should be noted that the show released at the end of October, which very likely played a part in truncating the number of new subscribers from the month. Here’s a graph of the total number of subscribers in each subreddit over 2020.

INSERT TOTAL SUBSCRIBER GRAPH

While r/chessvariants seemingly shows a flat growth line, it should be noted that the subreddit is growing and has grown at a faster rate ever since the show release, as indicated by the earlier bar graphs. The flat line is a product of the scale and the comparative monstrosity that the other subreddits are.

The graphs above show that there was a rise in the growth rate of each subreddit around *The Queen’s Gambit’s* time of release. This is potentially indicative of a positive impact on chess interest from the show.

confounding variable variance change average subscribers per month, % of yearly subscribers before and after

<!--EndFragment-->