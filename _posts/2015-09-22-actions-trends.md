---
layout:     post
title:      Actions, Trends, and More!
summary:    Today we're releasing a few new features!
---

* Actions: How many times you issue a move command during a game?  Do your friends make use of Attack Move? 
  Get a complete breakdown of the command types each player issued during the game.  We also compute an APM (Actions Per Minute) stat based on this data.
* Trends: Want to see how you’ve progressed?  Get a look over time at any of a wide range of stats 
  (the same ones featured in the histograms, records, and compare tabs).  As with any player page, the data is fully filter/query-able with a wide range of 
  criteria.
* MMstats: See exactly how many people are looking for a match in your region at this time, and how those numbers have changed over the last 24 hours.
  Credit for RJacksonm1 for his original MMstats tool.
* Tooltips: We’ve gone through and added a ton of tooltips!  Wondering what went into your “Throw” stat?  Now you know! 
  (It’s the maximum gold advantage in a lost game).

We've also made a few other changes around the site:

* The Professional navbar item has been retired as it wasn’t very useful and showed only the last 100 matches with leagueid>0, which contained a lot of noise.
Pro matches continue to be automatically parsed, and you can find their match pages by putting their match ID into the matches URL.
* EFF@10 has been added as a histogram/record/trend/compare.
* Actions Per Min has been added as a histogram/record/trend/compare. (Will take some time to build data since this is a new stat!)
* The Totals player page has been split into “Sprees” and “Wardmap”, since “Totals” wasn’t really a descriptive name.

As usual, everything is open source and available at https://github.com/yasp-dota/yasp.  We love contributions and feedback!

To close, I'd just like to talk about the tremendous growth we've seen in our user base. It wasn't long ago that we saw 1,500 track players
and felt overwhelmed and amazed by the great reception we got for YASP. Today, we've crossed over 30,000 tracked players and over 35,000 parsed games
a day. We've scaled from one tiny web server to a small fleet.

And amazingly enough, contributions have scaled along with our expenditures! YASP only runs because of the generosity of our users and the
Dota 2 community as a whole. Want to contribute? Consider some [cheese](/carry). Thanks for your continued support!