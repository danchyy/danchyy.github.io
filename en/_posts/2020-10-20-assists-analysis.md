---
layout: post
title: Breaking down "Real" vs "Fake" Assists
lang: en
lang-ref: assists-analysis
url: assists-analysis
twitter_img: /assets/assist_analysis/top_20_assisters_description.png
---

What is assist? Assist is a pass that leads directly to a made basket. However, I realized that sometimes that *directly* means after a couple of dribbles, or after a pull up jump shoot, and so on... So in another words, assist is a relatively loose term when we observe NBA in comparison to basketball in Europe (FIBA actually).

That inspired me to take a look at play by play data at official NBA site and try to split the assists in two categories. "Real" vs "Fake" assists.

<!--more-->

Real assists are basically counted for baskets made [directly after a pass](https://videos.nba.com/nba/pbp/media/2019/10/28/0021900050/446/db082939-7c93-f57d-64c7-aa977203f60a_1280x720.mp4), or after one dribble. But they can be defined as "easy" shots as well. Based on NBA's classification of shot types, I considered these types of shot as the ones which came from "Real" assists:

    Alley Oop Dunk Shot,
    Alley Oop Layup shot,
    Cutting Dunk Shot,
    Cutting Finger Roll Layup Shot,
    Cutting Layup Shot,
    Dunk Shot,
    Jump Bank Shot,
    Jump Shot,
    Layup Shot,
    Hook Shot,
    Reverse Dunk Shot,
    Reverse Layup Shot,
    Running Alley Oop Dunk Shot,
    Running Alley Oop Layup Shot,
    Running Dunk Shot,
    Running Finger Roll Layup Shot,
    Running Jump Shot,
    Running Layup Shot,
    Running Pull-Up Jump Shot,
    Running Reverse Layup Shot

On the other hand, "Fake" assists are counted for baskets made after some "creation" after the pass. Meaning that often times, player [pulls up for a jumper](https://videos.nba.com/nba/pbp/media/2019/11/02/0021900079/607/1f7717bd-e2b2-375c-152e-85497758f717_1280x720.mp4) after a couple of dribbles or drives to the hoop after a dump off at the top of the key. These are the shot types which came from "Real" assists:

    Driving Dunk Shot,
    Driving Finger Roll Layup Shot,
    Driving Floating Bank Jump Shot,
    Driving Floating Jump Shot,
    Driving Hook Shot,
    Driving Layup Shot,
    Fadeaway Jump Shot,
    Floating Jump shot,
    Pullup Jump shot,
    Step Back Jump shot,
    Turnaround Fadeaway Bank Jump Shot,
    Turnaround Hook Shot,
    Turnaround Jump Shot

Now this data is often misclassified and not exact, but I figured it would be good enough for an approximation of who has more "real" or "fake" assists.

An example of data not being "that good" is this [pull up jumper](https://videos.nba.com/nba/pbp/media/2019/10/25/0021900025/40/d96001be-0b9b-ac60-05be-2a83caa3d0ac_1280x720.mp4) by Avery Bradley. Even though this is classified as Pull Up Jumper and hence placed in "fake" assist section, LeBron put in solid effort to "create" a shot for Bradley. That is the main purpose of this post, to *try to figure out* who creates the easiest shoot by looking at these "fake" and "real" assists.

The results can be visible in next chart.

![](/assets/assist_analysis/top_20_assisters_description.png)

The players included are top 20 players in assists per game in regular season. I think the results of the chart are expected. Jokić plays a lot with Murray and Harris who drive/pull up for shots. Same can be said for Brogdon (Oladipo + Warren) and Dame (CJ + Melo).

On the other side we have Russ, who creates a bunch of shots for players in corners, and those shots are usually just regular "Jump Shots", same can be said about Trae Young and Dončić who pull a lot of defending players on themselves, allowing them for easy dump off to cutting players or those on 3pt line.

PS. As mentioned multiple times through the post, data isn't exact and entirely correct, so all of this is approximation and shouldn't be taken that seriously, but it does give a nice look of how players/teams play around their main playmakers.

Data is from [stats.nba.com](https://stats.nba.com/).
