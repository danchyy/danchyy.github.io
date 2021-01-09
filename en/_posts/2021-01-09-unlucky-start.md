---
layout: post
title: (Un)Luckiest Teams Based on Opponent's Wide Open FG3%
lang: en
lang-ref: unlucky-start-20-21
url: unlucky-start-20-21
twitter_img: /assets/unlucky_start/wide_open_table.jpg
---


![](/assets/unlucky_start/wide_open_table.png)

Some teams started the season surprisingly well, while others started rather badly. So if you glance over this table and then the real NBA standings you'll notice that teams which are on top here have really bad score (Washington 2-7, Denver 3-5 and Minny 2-6).

On the other hand, teams on bottom of this table have a solid score, Hawks currently sit at 4-4 while Knicks' score is 5-4.  

<!--more-->

## Wide Open shots

This table is all about Wide Open Shots. Shot is classified as wide open when the distance between the nearest defender and shooter is 6 Feet (or 1.8 meters). We can say that defender doesn't have a huge impact on these kind of shots because even if he contests the shot, the shooter will still have plenty of space and time to release the ball.

## Definition of Metrics/Statistics

#### WIDE OPEN OPP FG3% VS TARGET TEAM

I'll first explain ALLOWED WO FG3% column, since it is easier to explain it. That is basically **FG3% of opponent's wide open three pointers against target team**. If we observe Wizards only, they "allow" 49.3% (7.7 FG3M out of 15.6 FG3A) of opponent's wide open triples.

These numbers are identical to numbers on [this link](https://www.nba.com/stats/teams/opponent-shots-closest-defender/?Season=2020-21&SeasonType=Regular%20Season&CloseDefDistRange=6%2B%20Feet%20-%20Wide%20Open).

#### WIDE OPEN OPP FG3% VS ALL TEAMS

This metric is something else, and it is a bit tougher to explain, so I'll try to use Wizards as an example once again. Their opponents thus far have been: ORL (x2), MIN, CHI (x2), BOS, PHI (x2), BKN.

I'll take all of these opponents (but only once!) and sum up their MADE and ATTEMPTED wide open three point shots in the season thus far.

* ORL -> FG3M: 5.22, FG3A: 14.89
* MIN -> FG3M: 5.75, FG3A: 15.13
* CHI -> FG3M: 7.11, FG3A: 18.22
* PHI -> FG3M: 7.78, FG3A: 18.89
* BOS -> FG3M: 5.2, FG3A: 13.0
* BKN -> FG3M: 6.11, FG3A: 15.78

When we sum up these numbers we get FG3M: 37.17 i FG3A: 95.91 meaning that the average percentage of wide open shots of Wizards' opponents is `37.17 / 95.91 = 0.3876`, or rather `38.76%`.

So this metric shows **FG3% on wide open three pointers for Opposing teams of target team in all games thus far**

## Alternative to the table

Alternative to the table can be this *Scatter Plot*.

![](/assets/unlucky_start/wide_open_3pt_luck.png)

The diagonal line represents "ideal case", meaning that the values on x-axis and y-axis are identical (no luck involved at all). So you can see from this and the table above that there is absolutely no luck involved with Memphis, while Cleveland, Detroit, Boston and OKC are really close to "no-luck" effect as well.

But there are also some big extremes, the already mentioned Knicks and Hawks. They "allow" really small FG3% on Wide Open shots, even though their opponents generally shoot **okay** (the y-axis value) in all games thus far combined.

On the other side of the extreme are the Wizards (and Nuggets and Minny). Maybe Beal was wrong when he said that they [couldn't defend a parked car](https://bleacherreport.com/articles/2926076-bradley-beal-says-wizards-cant-guard-a-parked-car-after-loss-to-celtics) and they've just been unlucky? Or maybe there is something deeper in this story that makes Wizards' opponents go "Curry-like" versus them...


## Cooling Down

In the end here is another chart which paints the picture of Opponent's Wide Open triples through the seasons.

![](/assets/unlucky_start/mean_stddev_through_years.png)

Average at the level of entire league doesn't jump out that much this year. It is still around 39.5%-40% but the standard deviation is huge. If you aren't familiar with that term, standard deviation is a measure of the amount of variation or dispersion of a set of values. A low standard deviation indicates that the values tend to be close to the mean of the set, while a high standard deviation indicates that the values are spread out over a wider range.

But such high deviation is expected at the start of the season, as it normalizes as time goes on. Time does heal everything...

| Season | Starting deviation | Deviation through entire season |
| ------ | ------------------ | ------------------------ |
| 2013-14 | 0.05 | 0.02 |
| 2014-15 | 0.04 | 0.02 |
| 2015-16 | 0.04 | 0.02 |
| 2016-17 | 0.04 | 0.02 |
| 2017-18 | 0.03 | 0.01 |
| 2018-19 | 0.04 | 0.02 |
| 2019-20 | 0.04 | 0.02 |
| 2020-21 | 0.04 | ? |

## Conclusion

With all that was written here, we can expect that such big differences in opponent's wide open 3pt% will reduce, that Knicks and Hawks are going to regress and the Wizards should win a game or two in near future.
