---
layout: post
title: In Depth Look at Luka Doncic's Performance
lang: en
lang-ref: doncic
url: doncic
---

Luka Dončić has arguably been rookie of the year thus far in 2018–19 season,
his performance is keeping Dallas Mavericks in the realistic possibility
of achieving this year's playoffs with currently standing only 5.5 games out of 8th seed.
He is putting up amazing numbers that match up with some of the all time greats and currently best active players.
I will touch on that in detail later on, for now there are some specific areas of his game which I want to explore.

<!--more-->

## Clutch Time is Luka Time

Whenever I went on to watch highlights of Luka's performances (I live in Croatia, Europe, so unfortunately
don't manage to catch on many games since they start late, especially those from west conference) I always notice
that Luka is the guy who handles all the sticks in Mavs' offense late in the game.

That made me look at his numbers in clutch time, and they were pretty impressive.
![image](https://i.imgur.com/4PCMADM.jpg)

On previous image you can view top 60 scorers in clutch time. On x axis are plotted total points and on y axis is the true shooting percentage. Along with Dončić, some other players which stand out are Oladipo (he is the dot above Dončić with much higher percentage) and top 3 players in total points (Kemba, Harden and Kyrie). But given the fact that Dončić is just a 19 year old rookie, these numbers are simply amazing. So that made me wonder how did rookies in past couple of years perform in clutch. I took clutch scoring since 2003-04 season (LeBron's first season) and got this chart.

![](https://i.imgur.com/5sOZb6B.jpg)

From that chart it's visible that Luka is one of best rookies during that range. The players with more points than him are (in this order) Brandon Jennings, Kevin Durant, Tyreke Evans and Derrick Rose. It's also worth noting that their stats are up to All Star game, so Dončić might bump up these numbers a bit in next couple of weeks. The rest of top 10 in total points are Lillard, Markkanen, Mitchell, Westbrook and Chris Paul, which is a really good company to be in.

## Dončić's shotcharts and play/shot type selection

Shot charts are my favourite things to create during analysis. For starters we have a regular shot chart.

![](https://i.imgur.com/OelhWuU.jpg)

The chart isn't really mind boggling but we can generally see that Luka is above average in almost all areas. And that he takes a lot of three pointers and doesn't settle for a lot of mid range jumpers (even though he is far from true *moreyball* shot chart).

To add to previous short clutch analysis, here is an shot chart of all Luka's shots in clutch time thus far.

![](https://i.imgur.com/E3lQ3Vo.jpg)

He is very effective from mid range even though most of the shots come from the three point area and under the basket of course.

NBA's tracking has several categories of plays to which they divide each shot a player takes. I tried to visualize which actions Dončić prefers and how he fares efficiency wise in those actions. Here is a chart which shows that.

![](https://i.imgur.com/w0oEGGz.jpg)

Important note here is that these aren't all field goals that Dončić made/attempted but only those which have some sort of classification, and if I'd had to assume what would those types of plays be they would probably represent something like catch and shoot and similar types of play. So even if we say that all other plays were catch and shoot, that would mean that he has in total 221 shots from catch and shoot plays. That would still leave us with a lot more shots which he has created for himself (either by driving, step back shots or normal pull up shots). This kind of kills the doubts that were had prior to the draft where experts questioned whether Dončić could create shots for himself given his average (if so) athleticism.

### Luka and (Step Back) Jump Shots

After that I took on visualizing types of jump shots Luka takes.

![](https://i.imgur.com/7ZHmv53.jpg)

Here is a chart which shows that. The shot type called just *Jump Shot* would represent Catch and Shoot type of play which I talked about earlier. From this chart we can see that Luka is already developing a signature move, Step Back Jump Shot. Which is quite complex move for sure. I wanted to check efficiency in Step Back Jump shots of all other players but unfortunately it would be really tough to get all data (due to problems with fetching data from nba api), so I just took a look at some players which should be good shooters and step back shooters with that.

![](https://i.imgur.com/ERYpP9P.jpg)

Here is an image with some of this year's top scorers (at least those who aren't scoring mostly from paint/close range) and Luka Dončić. He isn't actually that far off Kyrie, only 3 points per game. It is really interesting to see that even though he is rookie he is rather close to efficiency with all those players and even takes more step backs than all of them except Harden who is just taking an absurd number of step backs. To have such a powerful tool at age 19 is going to be huge advantage for Dončić.

To finish off this brief take on step back shots and Luka, here is shot chart containing all of the step back jumpers Luka has attempted this season.

![](https://i.imgur.com/EedfgtS.jpg)

## Assists

Along with great scoring capabilities Luka excels at having great court vision and finding tough passing lanes. He is averaging 5.4 assists per game, which is 2nd among rookies only behind Trae Young. His AST% (percentage of teammates' field goals which were assisted by that player, so 33% means that player x assisted 33% of other teammates field goals) is also quite high and almost at level of Trae Young (27.5% vs 36.5%) but given the fact that JJ Barea sustained an injury couple of games ago and he had league's highest AST% at 45%, Dončić's numbers might rise further through the season. During the stretch without Barea Dončić is averaging 8.8 assists (only 6 games however).

With that being said, I was interested to see who is his favourite target in team, and the results can be viewed on next image.

![](https://i.imgur.com/RujddcY.jpg).

Deandre is his favourite target and pretty much most of the assists ended up in a dunk. Barnes is the second favourite target and his field goals made from Dončić's assist were much more spread. I visualized that as well in this chart.

![](https://i.imgur.com/GEHkH23.jpg)

I omitted the three guys with least assisted field goals so that chart looks less squeezed. There are only 14 field goals which are mid range jumpers out of all assists by Dončić.

## Conclusion

Luka Dončić is having amazing season. I touched on just several aspects of his game and tried to explore some of the things which aren't that often mentioned (such as step back jumpers). I didn't even give out the basic statistics such as PTS/G, REB/G, AST/G but he ranks quite high in this among all players this year as well as among rookies in past couple of years.

One thing I didn't really mention that much is that his TS% is very high. And that should be worth mentioning because in three point era (1979/80 to present time) he is second among all rookies in 3PA at 6.7 per game and he is doing that at 35.5%.

The thing I didn't manage to visualize properly is Luka's BPM (Box Plus Minus). He currently sits at 3.7 which gives him 11th spot among all rookies during three point era. To be honest those advanced statistics are kind of iffy, I didn't go into details to study them, but in general I'd say that BPM is really good indicator of predicting who will develop into All-Star level player and more.


The entire code for generating all these charts can be found in [jupyter notebook](https://github.com/danchyy/Basketball_Analytics/blob/master/Scripts/2018_19_season/doncic_analysis/doncic_analysis.ipynb). I have more stuff about basketball analytics on my [github repository](https://github.com/danchyy/Basketball_Analytics).
