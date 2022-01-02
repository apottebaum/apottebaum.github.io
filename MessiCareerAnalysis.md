---
title: "Career Goals (and Assists): Understanding Lionel Messi's Offensive Greatness"
author: "Andy Pottebaum"
date: "January  1, 2022"
output:
  html_document:
    keep_md: true
---




### Introduction



<br>
Lionel Messi is one of the greatest athletes of all time. I aim to examine his truly "magisterial" ^1^ offensive prowess. I would like explore Messi's shooting and passing output to get a better understanding of his greatness. The data used for this analysis comes from Statsbomb, sports analytics company whose main expertise is in soccer (or football as it is commonly known). This particular data set (`MessiShotPassEvents`) is a compilation of all player events from La Liga, that is the top Spanish soccer league, games in which Messi has played in for FC Barcelona. I have pared it down to focus on shot and pass events specifically involving Lionel Messi. Two other ancillary data sets, `seasons` and `Matches`, are used to incorporate season and match info as necessary, and both come from Statsbomb as well.
<br>
<br>

### Goal Scoring

<br>
Messi is a world renown goal-scorer and the following table summarizes his goal-scoring output over his career in La Liga games.
<br>

<table class="table" style="width: auto !important; margin-left: auto; margin-right: auto;border-bottom: 0;">
 <thead>
  <tr>
   <th style="text-align:center;"> Season </th>
   <th style="text-align:center;"> Games Played </th>
   <th style="text-align:center;"> Goals </th>
   <th style="text-align:center;"> xG </th>
   <th style="text-align:center;"> Goals - xG </th>
   <th style="text-align:center;"> Goals/Game </th>
   <th style="text-align:center;"> XG/Game </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:center;"> 2004/2005 </td>
   <td style="text-align:center;"> 7 </td>
   <td style="text-align:center;"> 1 </td>
   <td style="text-align:center;"> 0.70 </td>
   <td style="text-align:center;"> 0.30 </td>
   <td style="text-align:center;"> 0.14 </td>
   <td style="text-align:center;"> 0.10 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2005/2006 </td>
   <td style="text-align:center;"> 17 </td>
   <td style="text-align:center;"> 6 </td>
   <td style="text-align:center;"> 5.50 </td>
   <td style="text-align:center;"> 0.50 </td>
   <td style="text-align:center;"> 0.35 </td>
   <td style="text-align:center;"> 0.32 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2006/2007 </td>
   <td style="text-align:center;"> 26 </td>
   <td style="text-align:center;"> 14 </td>
   <td style="text-align:center;"> 10.56 </td>
   <td style="text-align:center;"> 3.44 </td>
   <td style="text-align:center;"> 0.54 </td>
   <td style="text-align:center;"> 0.41 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2007/2008 </td>
   <td style="text-align:center;"> 28 </td>
   <td style="text-align:center;"> 10 </td>
   <td style="text-align:center;"> 9.84 </td>
   <td style="text-align:center;"> 0.16 </td>
   <td style="text-align:center;"> 0.36 </td>
   <td style="text-align:center;"> 0.35 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2008/2009 </td>
   <td style="text-align:center;"> 31 </td>
   <td style="text-align:center;"> 23 </td>
   <td style="text-align:center;"> 18.77 </td>
   <td style="text-align:center;"> 4.23 </td>
   <td style="text-align:center;"> 0.74 </td>
   <td style="text-align:center;"> 0.61 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2009/2010 </td>
   <td style="text-align:center;"> 35 </td>
   <td style="text-align:center;"> 34 </td>
   <td style="text-align:center;"> 24.73 </td>
   <td style="text-align:center;"> 9.27 </td>
   <td style="text-align:center;"> 0.97 </td>
   <td style="text-align:center;"> 0.71 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2010/2011 </td>
   <td style="text-align:center;"> 33 </td>
   <td style="text-align:center;"> 31 </td>
   <td style="text-align:center;"> 28.53 </td>
   <td style="text-align:center;"> 2.47 </td>
   <td style="text-align:center;"> 0.94 </td>
   <td style="text-align:center;"> 0.86 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2011/2012 </td>
   <td style="text-align:center;"> 37 </td>
   <td style="text-align:center;"> 50 </td>
   <td style="text-align:center;"> 39.64 </td>
   <td style="text-align:center;"> 10.36 </td>
   <td style="text-align:center;"> 1.35 </td>
   <td style="text-align:center;"> 1.07 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2012/2013 </td>
   <td style="text-align:center;"> 32 </td>
   <td style="text-align:center;"> 46 </td>
   <td style="text-align:center;"> 24.67 </td>
   <td style="text-align:center;"> 21.33 </td>
   <td style="text-align:center;"> 1.44 </td>
   <td style="text-align:center;"> 0.77 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2013/2014 </td>
   <td style="text-align:center;"> 31 </td>
   <td style="text-align:center;"> 28 </td>
   <td style="text-align:center;"> 27.83 </td>
   <td style="text-align:center;"> 0.17 </td>
   <td style="text-align:center;"> 0.90 </td>
   <td style="text-align:center;"> 0.90 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2014/2015 </td>
   <td style="text-align:center;"> 38 </td>
   <td style="text-align:center;"> 43 </td>
   <td style="text-align:center;"> 32.46 </td>
   <td style="text-align:center;"> 10.54 </td>
   <td style="text-align:center;"> 1.13 </td>
   <td style="text-align:center;"> 0.85 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2015/2016 </td>
   <td style="text-align:center;"> 33 </td>
   <td style="text-align:center;"> 26 </td>
   <td style="text-align:center;"> 24.86 </td>
   <td style="text-align:center;"> 1.14 </td>
   <td style="text-align:center;"> 0.79 </td>
   <td style="text-align:center;"> 0.75 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2016/2017 </td>
   <td style="text-align:center;"> 34 </td>
   <td style="text-align:center;"> 37 </td>
   <td style="text-align:center;"> 26.16 </td>
   <td style="text-align:center;"> 10.84 </td>
   <td style="text-align:center;"> 1.09 </td>
   <td style="text-align:center;"> 0.77 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2017/2018 </td>
   <td style="text-align:center;"> 36 </td>
   <td style="text-align:center;"> 34 </td>
   <td style="text-align:center;"> 25.49 </td>
   <td style="text-align:center;"> 8.51 </td>
   <td style="text-align:center;"> 0.94 </td>
   <td style="text-align:center;"> 0.71 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2018/2019 </td>
   <td style="text-align:center;"> 34 </td>
   <td style="text-align:center;"> 36 </td>
   <td style="text-align:center;"> 23.75 </td>
   <td style="text-align:center;"> 12.25 </td>
   <td style="text-align:center;"> 1.06 </td>
   <td style="text-align:center;"> 0.70 </td>
  </tr>
</tbody>
<tfoot>
<tr><td style="padding: 0; " colspan="100%"><span style="font-style: italic;">Note: </span></td></tr>
<tr><td style="padding: 0; " colspan="100%">
<sup></sup> xG (or expected goals) is defined as the probability that a shot will result in a goal based on the characteristics of that shot and the events leading up to it</td></tr>
</tfoot>
</table>

<br>
As you can see his prolific scoring totals emerged in the 2009/2010 season after a 34 goal campaign, and he has maintained his scoring scoring output with only a couple dips below the 30 goal mark. Another important stat to note from this table is his goal-scoring performance relative to xG (expected goal)^2^. xG is measured for each shot taken (see table note) and here it summarized as a total for all shots taken in a season. Looking at his performance against this standardized measurement of shot taking we see how Messi almost always expectations. 
<br>
<br>

<img src="MessiCareerAnalysis_files/figure-html/unnamed-chunk-3-1.png" style="display: block; margin: auto;" />

<br>
<br>




Clearly he has dominated La Liga opponents throughout the years. I would like to see which opponents in particular he as success against. Since he has scored against 4 different teams I have only included teams he has played 15 or more games against. Here we see how he has fared against such teams:
<br>
<br>

<img src="MessiCareerAnalysis_files/figure-html/unnamed-chunk-5-1.png" style="display: block; margin: auto;" />

<br>
He has perfomed quite well against the upper middle tier Spanish teams (e.g. Sevilla, Valencia, Atlético Madrid) . This probably due in part to the fact he has had a more opportunities to score against these opponents since they are competitive enough to maintain their place in the top Spanish league (Spain, like other European leagues uses a promotion/relegation system for professional soccer leagues). If we move down the list a bit we see lesser competitive teams, such as Osasuna, Levante, and Deportivo La Coruna. Arguably, Messi has posed a greater threat to these sides when you look at his goal-scoring rate on a per game basis. Interestingly, he has not performed as well against Barcelona's main rival, Real Madrid, but this makes sense as they too are one of the best clubs in the world. However, 18  goals in 25 games is nothing to scoff at.
<br>
<br>

Next, I would like to see how Messi's position on the field is related to the shot he takes overall and the shots in which result in a goal. Here we see a breakdown of all the shots and goals he has scored in La Liga and the location on the field the shot originated from.
<br>
<br>

<img src="MessiCareerAnalysis_files/figure-html/unnamed-chunk-6-1.png" style="display: block; margin: auto;" />

<br>
<br>
<br>

<img src="MessiCareerAnalysis_files/figure-html/unnamed-chunk-7-1.png" style="display: block; margin: auto;" />

<br>
Not surprisingly, we can see the bulk of his scoring has come from shots within the 18 yard box. He has converted these chances 27% of the time. His goal scoring rate declines a bit, as expected as he moves further from goal, but he still converts a more than respectable 8% of his chances from this distance. To give a little bit of context, a naive xG model (i.e. only considering position relative to goal as a factor) would predict an expected goal of .02-.05 from this range.
<br>
<br>

Looking at Messi's shots from an Outcome (Goal or Not Goal) standpoint we can try to see if there is a noticeable difference in location of the shots. 
<br>
<br>

<img src="MessiCareerAnalysis_files/figure-html/unnamed-chunk-8-1.png" style="display: block; margin: auto;" />

<br>
Using the average location of the shot, displayed by Shot Outcome group for each season, we can see that goals tend to come from closer shots. No surprise there. Also of note is the average location of the shots within the Shot Outcome groups stay pretty consistent over the years with a few outliers on the left side of the 18 yard box. These are from his first two seasons and a small sample size could play a role in these locations. It is worth mentioning that Lionel Messi is left-footed and most of his shots come from his dominant foot. So he could have been relying on moving to his left to shoot more in the formative stages of his career.
<br>
<br>

### Assisting Others

<br>
As far as great goal-scorers go, typically passing the ball to others in a goal-scoring situation doesn't come as easily. However, Messi's offensive greatness doesn't seem to be just confined to goal scoring. Another aspect of game is his ability to involve his teammates and make them better as well. Here is a look at his decision making in attacking or goal-scoring situations. Is he more likely to pass the ball to a teammate for a shot or take the shot himself?
<br>




<img src="MessiCareerAnalysis_files/figure-html/unnamed-chunk-10-1.png" style="display: block; margin: auto;" />

<br>
Clearly, he favors taking a shot over passing to a teammate, but his consistent outperformance of xG seems to justify this decision. He does seem to be developing into a more willing passer in these attacking situations though. We can see a downward trend in proportion of shots in more recent seasons, as well as an increase in number of shot assists.
<br>
<br>

Even though his preference is shooting it is also important to remember Messi's assist totals have consistent been among the La Liga leaders. The following table summarizes his Goal Assist and Shot Assists throughout his career.
<br>
<br>

<table class="table" style="width: auto !important; margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:center;"> Season </th>
   <th style="text-align:center;"> Games Played </th>
   <th style="text-align:center;"> Goal Assists </th>
   <th style="text-align:center;"> Shot Assists </th>
   <th style="text-align:center;"> Goal Assists/Game </th>
   <th style="text-align:center;"> Shot Assists/Game </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:center;"> 2004/2005 </td>
   <td style="text-align:center;"> 7 </td>
   <td style="text-align:center;"> 0 </td>
   <td style="text-align:center;"> 1 </td>
   <td style="text-align:center;"> 0.00 </td>
   <td style="text-align:center;"> 0.14 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2005/2006 </td>
   <td style="text-align:center;"> 17 </td>
   <td style="text-align:center;"> 1 </td>
   <td style="text-align:center;"> 12 </td>
   <td style="text-align:center;"> 0.06 </td>
   <td style="text-align:center;"> 0.71 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2006/2007 </td>
   <td style="text-align:center;"> 26 </td>
   <td style="text-align:center;"> 2 </td>
   <td style="text-align:center;"> 35 </td>
   <td style="text-align:center;"> 0.08 </td>
   <td style="text-align:center;"> 1.35 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2007/2008 </td>
   <td style="text-align:center;"> 28 </td>
   <td style="text-align:center;"> 12 </td>
   <td style="text-align:center;"> 28 </td>
   <td style="text-align:center;"> 0.43 </td>
   <td style="text-align:center;"> 1.00 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2008/2009 </td>
   <td style="text-align:center;"> 31 </td>
   <td style="text-align:center;"> 11 </td>
   <td style="text-align:center;"> 57 </td>
   <td style="text-align:center;"> 0.35 </td>
   <td style="text-align:center;"> 1.84 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2009/2010 </td>
   <td style="text-align:center;"> 35 </td>
   <td style="text-align:center;"> 10 </td>
   <td style="text-align:center;"> 49 </td>
   <td style="text-align:center;"> 0.29 </td>
   <td style="text-align:center;"> 1.40 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2010/2011 </td>
   <td style="text-align:center;"> 33 </td>
   <td style="text-align:center;"> 18 </td>
   <td style="text-align:center;"> 49 </td>
   <td style="text-align:center;"> 0.55 </td>
   <td style="text-align:center;"> 1.48 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2011/2012 </td>
   <td style="text-align:center;"> 37 </td>
   <td style="text-align:center;"> 16 </td>
   <td style="text-align:center;"> 74 </td>
   <td style="text-align:center;"> 0.43 </td>
   <td style="text-align:center;"> 2.00 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2012/2013 </td>
   <td style="text-align:center;"> 32 </td>
   <td style="text-align:center;"> 10 </td>
   <td style="text-align:center;"> 37 </td>
   <td style="text-align:center;"> 0.31 </td>
   <td style="text-align:center;"> 1.16 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2013/2014 </td>
   <td style="text-align:center;"> 31 </td>
   <td style="text-align:center;"> 11 </td>
   <td style="text-align:center;"> 60 </td>
   <td style="text-align:center;"> 0.35 </td>
   <td style="text-align:center;"> 1.94 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2014/2015 </td>
   <td style="text-align:center;"> 38 </td>
   <td style="text-align:center;"> 17 </td>
   <td style="text-align:center;"> 68 </td>
   <td style="text-align:center;"> 0.45 </td>
   <td style="text-align:center;"> 1.79 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2015/2016 </td>
   <td style="text-align:center;"> 33 </td>
   <td style="text-align:center;"> 15 </td>
   <td style="text-align:center;"> 59 </td>
   <td style="text-align:center;"> 0.45 </td>
   <td style="text-align:center;"> 1.79 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2016/2017 </td>
   <td style="text-align:center;"> 34 </td>
   <td style="text-align:center;"> 9 </td>
   <td style="text-align:center;"> 67 </td>
   <td style="text-align:center;"> 0.26 </td>
   <td style="text-align:center;"> 1.97 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2017/2018 </td>
   <td style="text-align:center;"> 36 </td>
   <td style="text-align:center;"> 13 </td>
   <td style="text-align:center;"> 71 </td>
   <td style="text-align:center;"> 0.36 </td>
   <td style="text-align:center;"> 1.97 </td>
  </tr>
  <tr>
   <td style="text-align:center;"> 2018/2019 </td>
   <td style="text-align:center;"> 34 </td>
   <td style="text-align:center;"> 13 </td>
   <td style="text-align:center;"> 78 </td>
   <td style="text-align:center;"> 0.38 </td>
   <td style="text-align:center;"> 2.29 </td>
  </tr>
</tbody>
</table>

<br>
Similar to his goal-scoring totals his assist totals seem to reach new levels a few years in to his career, and he has managed to maintain a double digit tally pretty much ever since.
<br>
<br>

I would be remiss if I didn't mention Messi's excellent supporting cast at Barcelona. As one of the top clubs in the world it has consistent developed and recruited some of the most talented coaches and players. Not only has Messi benefitted from this surplus of talent, so have his teammates. There have been many beneficiaries of Messi's passing, with 67 different players receiving a shot assist, and 35 different players receiving a goal asssist. Here are couple tables summarizing the top 5 recipients of Messi's passes in both categories:
<br>
<br>

<table class="table" style="width: auto !important; margin-left: auto; margin-right: auto;border-bottom: 0;">
 <thead>
  <tr>
   <th style="text-align:left;"> Shot Assist Recipient </th>
   <th style="text-align:right;"> Shot Assists Received </th>
   <th style="text-align:right;"> Seasons Receiving Assist </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Luis Alberto Suárez Díaz </td>
   <td style="text-align:right;"> 97 </td>
   <td style="text-align:right;"> 5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Andrés Iniesta Luján </td>
   <td style="text-align:right;"> 62 </td>
   <td style="text-align:right;"> 13 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Neymar da Silva Santos Junior </td>
   <td style="text-align:right;"> 55 </td>
   <td style="text-align:right;"> 4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Xavier Hernández Creus </td>
   <td style="text-align:right;"> 34 </td>
   <td style="text-align:right;"> 9 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> David Villa Sánchez </td>
   <td style="text-align:right;"> 32 </td>
   <td style="text-align:right;"> 3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Pedro Eliezer Rodríguez Ledesma </td>
   <td style="text-align:right;"> 32 </td>
   <td style="text-align:right;"> 6 </td>
  </tr>
</tbody>
<tfoot>
<tr><td style="padding: 0; " colspan="100%"><span style="font-style: italic;">Note: </span></td></tr>
<tr><td style="padding: 0; " colspan="100%">
<sup></sup> These shot assist recipients represent 42% of the total shot assists provided by Lionel Messi over his career.</td></tr>
</tfoot>
</table>

<br>
<br>

<table class="table" style="width: auto !important; margin-left: auto; margin-right: auto;border-bottom: 0;">
 <thead>
  <tr>
   <th style="text-align:left;"> Goal Assist Recipient </th>
   <th style="text-align:right;"> Goal Assists Received </th>
   <th style="text-align:right;"> Seasons Receiving Assist </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Luis Alberto Suárez Díaz </td>
   <td style="text-align:right;"> 23 </td>
   <td style="text-align:right;"> 5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Pedro Eliezer Rodríguez Ledesma </td>
   <td style="text-align:right;"> 13 </td>
   <td style="text-align:right;"> 4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Neymar da Silva Santos Junior </td>
   <td style="text-align:right;"> 12 </td>
   <td style="text-align:right;"> 3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Samuel Eto"o Fils </td>
   <td style="text-align:right;"> 12 </td>
   <td style="text-align:right;"> 4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> David Villa Sánchez </td>
   <td style="text-align:right;"> 10 </td>
   <td style="text-align:right;"> 2 </td>
  </tr>
</tbody>
<tfoot>
<tr><td style="padding: 0; " colspan="100%"><span style="font-style: italic;">Note: </span></td></tr>
<tr><td style="padding: 0; " colspan="100%">
<sup></sup> These shot assist recipients represent 42% of the total shot assists provided by Lionel Messi over his career.</td></tr>
</tfoot>
</table>


<br>
<br>

You would expect that as shot assist and goal assist to be relatively correlated season to season. However, that hasn't necessarily been the case.
<br>
<br>

<img src="MessiCareerAnalysis_files/figure-html/unnamed-chunk-14-1.png" style="display: block; margin: auto;" />

<br>
After initially rising together, shot assists have continued to grow while goal assists have remained relatively flat. This isn't necessarily an idictment on the quality of finishing Messi's passes, but does speak to his increasing willingness to create goal-scoring chances for his teammates. Assuming his incredible goal-scoring form eventually slows down this reliance on his teammates should serve him well as his career enters the final stages.
<br>
<br>


#### Footnotes:
^1^ As described by beIN Sports Commentator Ray Hudson  

^2^According to fbref.com the xG (or expected goals) is defined as the probability that a shot will result in a goal based on the characteristics of that shot and the events leading up to it. Some of these characteristics/variables include:

  * Location of shooter: How far was it from the goal and at what angle on the pitch?
  * Body part: Was it a header or off the shooter's foot?
  * Type of pass: Was it from a through ball, cross, set piece, etc?
  * Type of attack: Was it from an established possession? Was it off a rebound? Did the defense have time to get in position? Did it follow a dribble?
<br>  

#### References:
  
  Football Reference:
    https://fbref.com/en/
  
  StatsBomb:
    https://github.com/statsbomb/open-data/tree/master/doc
