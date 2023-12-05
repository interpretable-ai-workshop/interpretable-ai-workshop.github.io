---
layout: article
title: "XAI in Action: Past, Present, and Future Applications"
excerpt: NeurIPS 2023 Workshop
menu: true
show_info: true
titles:
  en      : &EN       Home
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
key: page-home
article_header:
  type: overlay
  theme: dark
  align: left
  actions:
    - text: December 16, 2023 | New Orleans, USA 
  background_image:
    src: /assets/images/Slide6.png
#    gradient: 'linear-gradient(135deg, rgba(52, 140, 96, 0.4), rgba(136, 73, 107, 0.4))'
---

<style>
.schedule-table-heading {
    display: inline;
    font-weight: bold;
    font-size: 20px;
    color: #999999;
    padding:0 0 20px 0;
}

.schedule-table-timecol {
    padding:0 50px 0 50px;
    display:inline;
}

.schedule-table-eventcol {
    display:inline;
    display:inline-block;
    inline-size: 300px;
}

.schedule-table-contentcol {
    display:inline;
    display:inline-block;
    inline-size: 250px;
    font-size:14px;
    line-height: normal;
}

.schedule-table-row-even {
    display:block;
    width:800px;
    background-color: #EEEEEE;
    padding:10px;
}

.schedule-table-row-odd {
    display:block;
    width:800px;
    padding:10px;
}

.article__header--overlay .overlay {
    min-height: 36rem;
    padding-top: 5rem;
    padding-bottom: 5rem;
}

.article__header {
    margin: 0 0 0 0;
}

.article__header h1 {
    display: inline;
    font-family: sans-serif;
    font-size: 2.5em;
    letter-spacing: -0.04em;
    line-height: 0.9;
    color: lightyellow;
    text-shadow: -20px -8px 17px rgb(0 0 0 / 90%);
    -webkit-text-stroke: 2px black; /* width and color */
    word-wrap: break-word;
}

.overlay__excerpt {
    margin: 20px 0 0 0;
    font-family: sans-serif;
    color: black;
    text-shadow: -20px -8px 17px rgb(0 0 0 / 90%);
}

ul.menu li::after {
    color: black;
    text-shadow: -20px -8px 17px rgb(0 0 0 / 90%);
    content:"December 16, 2023 | New Orleans, USA";
}

ul.menu a {
    display: none;
}

.pc-column {
    width:270px;
    display:inline-block;
    vertical-align: top;
}

.pc_list_item {
    display:inline-block;
    width:200px;
}

.organiser_profile {
    font-weight:normal;
    color: black;
}

.organiser_profile a:link a:visited a:hover a:active {
    font-weight:normal;
    color: #000000;
}

.organiser_profile p {
    font-weight:normal;
    color: #000000;
}

.logos-organizers {
    display: flex;
    align-items: center;
    flex-direction: row;
    flex-wrap: nowrap;
}

.img-fluid {
    max-width: 100%;
    height: auto;
}

img {
    vertical-align: middle;
    border-style: none;
}

  .reviewers-container {
    display: flex;
    flex-wrap: wrap;
  }

  .reviewers-container > div {
    padding: 5px;
    background-color: #f0f0f0;
    border-radius: 5px;
    margin: 5px;
  }
  
</style>


<script>
  var x = setInterval(function() {
    var d = new Date();
    var n = d.toLocaleTimeString("en-US", {timeZone: "America/New_York", hour: '2-digit', minute:'2-digit', hour12: false})
    document.getElementById("edt").innerHTML = n
  }, 1000);
</script>

<script>
  var x = setInterval(function() {
    var d = new Date();
    var n = d.toLocaleTimeString("en-US", {timeZone: "Europe/Vienna", hour: '2-digit', minute:'2-digit', hour12: false})
    document.getElementById("cet").innerHTML = n
  }, 1000);
</script>

<script>
  {%- include scripts/lib/swiper.js -%}
  var SOURCES = window.TEXT_VARIABLES.sources;
  window.Lazyload.js(SOURCES.jquery, function() {
    $('.swiper-demo').swiper();
  });
</script>

<script>

  var countDownDate = new Date("Feb 15, 2022 23:59:59 UTC").getTime();  
  countDownDate = countDownDate + 1000 * 3600 * 12


  var x = setInterval(function() {


    var now = new Date().getTime();


    var distance = countDownDate - now;


    var days = Math.floor(distance / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);


    var countdown = days + "d " + hours + "h " + minutes + "m " + seconds + "s ";


    if (distance < 0) {
      clearInterval(x);
      countdown = "(expired)";  
    }

    document.getElementById("countdown").innerHTML = countdown

  }, 1000);
</script>

<br>

## About

As AI models continue to advance in complexity and sophistication, understanding how they work and make decisions is becoming increasingly challenging. This challenge has prompted a surge of research into developing methods and tools that can enhance the transparency and explainability of these models. Nowadays, there are many such methods available, to the point that their specific applications have become somewhat unclear.

This workshop will specifically explore the diverse applications of explainable artificial intelligence (XAI) methods in various areas. The areas will include, but not limited to XAI in Healthcare, Natural Science, Auditing, Fairness, Natural Language Processing and Law. By examining the use of XAI in these fields, the workshop will provide attendees with insights into the latest trends and challenges within the different domains. 

The workshop discussions aim to delve into the latest advancements in applied XAI and devise ways to further progress the field. The objective is to foster an open and productive dialogue that enhances our understanding of the potential opportunities and constraints of XAI and its impact across different domains. The purpose of this discourse is to identify strategies that can extend the frontiers of applied XAI and make notable progress in this rapidly evolving area. Specifically, the workshop aims to:


### Topics covered

<div>
<div style="width:49%; display:inline-block; font-size:14px; vertical-align:top">
<ul>
<li>Examine various applications of XAI from the past and present </li>
<li>Discuss potential applications of XAI in the future</li>
<li>Identify the obstacles that hinder progress in each use case and how can we overcome them</li>
<li>Explore the necessary methodological requirements for applying XAI</li>
</ul>
</div>
<div style="width:49%; display:inline-block; font-size:14px; vertical-align:top">
<ul>
<li>Identify new domains where XAI can be useful in the future</li>
<li>Understand the inherent limitations of XAI</li>
<li>Explore whether insights gained from one use case can be transferred to other use cases</li>
</ul>
</div>
</div>

The workshop will provide a valuable learning opportunity for researchers, practitioners, and students seeking to apply XAI in their work, as it will feature presentations by experts in the field, as well as interactive discussions and insights into the latest trends and future directions in applied XAI. By bringing together a diverse group of participants with a shared interest in XAI, the workshop aims to foster collaboration, innovation, and knowledge sharing in this rapidly growing field.

## Accepted Papers

A full list of accepted papers can be found [here](https://openreview.net/group?id=NeurIPS.cc/2023/Workshop/XAIA&referrer=%5BHomepage%5D(%2F)#tab-accept).

### Highlighted Reviewers

<div class="reviewers-container">
  <div>Sichao Li</div>
  <div>Bardh Prenkaj</div>
  <div>Arnaud Pannatier</div>
  <div>Kyle Matoba</div>
  <div>Amir Akbarnejad</div>
  <div>Nari Johnson</div>
  <div>Davin Hill</div>
  <div>Eike Peterson</div>
  <div>Karel D'Oosterlinck</div>
  <div>Bitya Neuhof</div>
  <div>Sebastian Bordt</div>
</div>

### All Reviewers

<div class="reviewers-container">
  <div>Sahib Singh</div>
  <div>Shah Nawaz</div>
  <div>Raj Korpan</div>
  <div>Zhenjie Zhao</div>
  <div>Sichao Li</div>
  <div>Eike Petersen</div>
  <div>Kiet Van Nguyen</div>
  <div>Rakshit Naidu</div>
  <div>Sukriti Verma</div>
  <div>Chris Lin</div>
  <div>Gabriel Kasmi</div>
  <div>Kilian Kluge</div>
  <div>Pulkit Verma</div>
  <div>Jacopo Teneggi</div>
  <div>Wei Qiu</div>
  <div>Muhammad Usman Shahid Khan</div>
  <div>Bardh Prenkaj</div>
  <div>Gökhan Özbulak</div>
  <div>Daniel Barrejon</div>
  <div>Fan Feng</div>
  <div>Hangzhi Guo</div>
  <div>Debarpan Bhattacharya</div>
  <div>Zeming Wei</div>
  <div>Sagnik Dakshit</div>
  <div>Arnav Wadhwa</div>
  <div>Beepul Bharti</div>
  <div>Sukrut Rao</div>
  <div>Pouya Khani</div>
  <div>Satyapriya Krishna</div>
  <div>Akshay R. Kulkarni</div>
  <div>Nitsan Soffair</div>
  <div>Bhawesh Kumar</div>
  <div>Yuri Feldman</div>
  <div>Lenka Tětková</div>
  <div>Wenbo Zhang</div>
  <div>Vinitra Swamy</div>
  <div>Sree Harsha Tanneru</div>
  <div>Daniel Flores Araiza</div>
  <div>Vidhya Kamakshi</div>
  <div>Goutham Rajendran</div>
  <div>Aditya Bhattacharya</div>
  <div>Swagatam Haldar</div>
  <div>Leonardo Lucio Custode</div>
  <div>Jaakko Suutala</div>
  <div>Changjian Shui</div>
  <div>Sasikanth Kotti</div>
  <div>Nan Wu</div>
  <div>Amir Akbarnejad</div>
  <div>Ido Ben-Shaul</div>
  <div>Kenza Amara</div>
  <div>Zeyu Qin</div>
  <div>Leonard Tang</div>
  <div>Raghav Singhal</div>
  <div>Mustafa Cavus</div>
  <div>Laura O'Mahony</div>
  <div>Canyu Chen</div>
  <div>Alex Oesterling</div>
  <div>Srishti Gautam</div>
  <div>Usha Bhalla</div>
  <div>Francesco Croce</div>
  <div>Alexander Meinke</div>
  <div>Christian Schlarmann</div>
  <div>Gal Yona</div>
  <div>Dana Arad</div>
  <div>Natalie Shapira</div>
  <div>Katelyn Morrison</div>
  <div>Maksym Andriushchenko</div>
  <div>Sunnie S. Y. Kim</div>
</div>

### Area Chairs

<div class="reviewers-container">
  <div>Suraj Srinivas</div>
  <div>Valentyn Boreiko</div>
  <div>Chhavi Yadav</div>
  <div>Aounon Kumar</div>
  <div>Cyrus Rashtchian</div>
  <div>Michal Moshkovitz</div>
  <div>Nave Frost</div>
</div>


## Dates

Note: all deadlines are in <b>Anywhere on Earth (AoE)</b>.

### Paper Submission

Submission deadline - ~~September 22~~ October 2 (23:59 AoE), 2023 \
Author notification - ~~October 20~~ October 27 (23:59 AoE), 2023 \
Camera ready deadline -  November 22 (23:59 AoE), 2023

### Workshop Event

<b>Date:</b> December 16, 2023

## Schedule

|       Time        | Event                                             |
|:-----------------:|:--------------------------------------------------|
| **8:50 - 9:00 AM**  | Opening Remarks                                   |
| **9:00 - 9:30 AM**  | IT1: Sameer Singh                                 |
| **9:30 - 10:00 AM** | IT2: Ulrike von Luxburg ※                             |
| **10:00 - 10:30 AM**| Coffee Break & Interactive Games                  |
| **10:30 - 11:00 AM**| IT3: Su-In Lee                                    |
| **11:00 - 12:00 PM**| Panel Discussion (featuring Shai Ben David, moderated by Kamalika Chaudhuri)                          |
| **12:00 - 1:30 PM** | Lunch                                 |
| **1:30 - 2:00 PM**  | IT4: Julius Adebayo                         |
| **2:00 - 3:00 PM**  | Poster Session 1          |
| **3:00 - 3:30 PM**  | Coffee Break & Interactive Games                 |
| **3:30 - 4:00 PM**  | IT5: Leilani Gilpin                              |
| **4:00 - 4:30 PM**  | Contributed Talks             |
| **4:30 - 5:30 PM**  | Poster Session 2          |

※ Indicates virtual participation

_All times are in Central Standard Time_  

<!---
Friday, 22 July, 2022. All times are in Eastern Daylight Time (EDT). Current time is <span id="edt"></span>.

<div style="display:block; width:900px; padding:20px; border:solid 4px #CCCCCC;">
<div class="schedule-table-heading" style="margin-left:57px; display:inline-block; inline-size:100px;">Time</div>
<div class="schedule-table-heading" style="display:inline-block; inline-size:295px;">Event</div>
<div class="schedule-table-heading">Content</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol">08:50</div>
<div class="schedule-table-eventcol">Welcome</div>
<div class="schedule-table-contentcol">Opening Remarks</div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">09:00</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/david_held.png" alt="David Held">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">David Held</p>
<p style="margin:0 0 0 10px; font-size:10px;">CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987747/selfsupervised-3d-perception-for-autonomous-driving?ref=folder-105306" target="_blank"><i>Self-supervised learning for autonomous driving</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">09:30</div>
<div class="schedule-table-eventcol">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/melanie_zeilinger.png" alt="Melanie Zeilinger">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Melanie Zeilinger</p>
<p style="margin:0 0 0 10px; font-size:10px;">ETH Zürich</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987741/learning-for-high-performance-yet-safe-control?ref=folder-105306"><i>Learning for High Performance yet Safe Control</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol">10:00</div>
<div class="schedule-table-eventcol">Social + Poster Session</div>

<div class="schedule-table-contentcol"><b>Gathertown</b> and in-person displays</div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol">11:00</div>
<div class="schedule-table-eventcol">Spotlight Talks</div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Zijian Guo</p>
<p style="margin:0 0 0 10px; font-size:10px;">CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a target="_blank" href="https://slideslive.com/38987752/constrained-modelbased-reinforcement-learning-via-robust-planning?ref=folder-105306"><i>#16: Constrained Model-based Reinforcement Learning via Robust Planning</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Linrui Zhang</p>
<p style="margin:0 0 0 10px; font-size:10px;">Tsinghua University</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a target="_blank" href="https://slideslive.com/38987764/saferlkit-evaluating-efficient-reinforcement-learning-methods-for-safe-autonomous-driving?ref=folder-105306"><i>#12: SafeRL-Kit: Evaluating Efficient Reinforcement Learning Methods for Safe Autonomous Driving</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">11:30</div>
<div class="schedule-table-eventcol">Autonomous Racing Virtual Challenge: Contributed Talks</div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Shivansh Beohar</p>
<p style="margin:0 0 0 10px; font-size:10px;">IIIT Allahabad</p>
</div>
</div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">James Bockman</p>
<p style="margin:0 0 0 10px; font-size:10px;">U Adelaide</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a target="_blank" href="https://slideslive.com/38987768/the-edge-of-disaster-a-battle-between-autonomous-racing-and-safety?ref=folder-105306"><i>#14: The Edge of Disaster: A Battle Between Autonomous Racing and Safety</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol">12:00</div>
<div class="schedule-table-eventcol">Lunch Break</div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">13:30</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/peter_stone.png" alt="Peter Stone">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Peter Stone</p>
<p style="margin:0 0 0 10px; font-size:10px;">UT Austin; Sony AI</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987742/reward-misdesign-for-autonomous-driving-and-accumulating-safety-rules-from-catastrophic-action-effects?ref=folder-105306"><i>Reward (Mis)design for Autonomous Driving and Accumulating Safety Rules from Catastrophic Action Effects</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol">14:00</div>
<div class="schedule-table-eventcol">Spotlight Talks</div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Weiran Yao</p>
<p style="margin:0 0 0 10px; font-size:10px;">CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a target="_blank" href="https://slideslive.com/38987757/distributionaware-goal-prediction-and-conformant-modelbased-planning-for-safe-autonomous-driving?ref=folder-105306"><i>#23: Distribution-aware Goal Prediction and Conformant Model-based Planning for Safe Autonomous Driving</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Zuxin Liu</p>
<p style="margin:0 0 0 10px; font-size:10px;">CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a target="_blank" href="https://slideslive.com/38987751/on-the-robustness-of-safe-reinforcement-learning-under-observational-perturbations?ref=folder-105306"><i>#15: On the Robustness of Safe Reinforcement Learning under Observational Perturbations</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">14:30</div>
<div class="schedule-table-eventcol">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/todd_hester.png" alt="Todd Hester">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Todd Hester</p>
<p style="margin:0 0 0 10px; font-size:10px;">Amazon Scout</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987743/multimodal-sensor-fusion-for-the-amazon-scout-robot?ref=folder-105306"><i>Multi-modal sensor fusion for the Amazon Scout robot</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">15:00</div>
<div class="schedule-table-eventcol">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/chelsea_finn.png" alt="Chelsea Finn">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Chelsea Finn</p>
<p style="margin:0 0 0 10px; font-size:10px;">Stanford + Google Brain</p>
</div>
</div>
</div>


<div class="schedule-table-row-odd">
<div class="schedule-table-timecol">15:30</div>
<div class="schedule-table-eventcol">Social + Poster Session</div>

<div class="schedule-table-contentcol"><b>Gathertown</b> and in-person displays</div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">16:30</div>
<div class="schedule-table-eventcol">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/andrea_bajcsy.png" alt="Andrea Bajcsy">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Andrea Bajcsy</p>
<p style="margin:0 0 0 10px; font-size:10px;">UC Berkeley / CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987745/practical-safety-assurances-for-dynamic-humanrobot-interactions?ref=folder-105306"><i>Practical Safety Assurances for Dynamic Human-Robot Interactions</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">17:00</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/jeff_schneider.png" alt="Jeff Schneider">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Jeff Schneider</p>
<p style="margin:0 0 0 10px; font-size:10px;">Carnegie Mellon University</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987746/safety-and-reinforcement-learning-for-selfdriving-cars?ref=folder-105306"><i>Reinforcement Learning for self-driving cars</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">17:30</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/sergey_levine.png" alt="Sergey Levine">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Sergey Levine</p>
<p style="margin:0 0 0 10px; font-size:10px;">UC Berkeley</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987748/learning-plannable-representations-and-planning-with-learnable-skills?ref=folder-105306"><i>Learning Plannable Representations and Planning with Learnable Skills</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol">18:00</div>
<div class="schedule-table-eventcol">Conclusion</div>
<div class="schedule-table-contentcol">Closing Remarks</div>
</div>

</div>

--->

## Speakers


<div style="display:inline; width:900px; vertical-align: top;">

<a href="https://juliusadebayo.com/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/AXAI_workshop_julius.png" alt="Julius Adebayo">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Julius Adebayo</p>
<p style="margin:0 0 0 10px; font-size:10px;">Postdoctoral Fellow<br>Prescient Design</p>
</div>
</div>
</a>




<a href="https://people.ucsc.edu/~lgilpin/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/AXAI_workshop_leilani.png" alt="Leilani Gilpin">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Leilani Gilpin</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor<br>UC Santa Cruz</p>
</div>
</div>
</a>

<a href="https://aims.cs.washington.edu/su-in-lee" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="/assets/images/speakers/AXAI_workshop_Lee.png" alt="Su-In Lee" />
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Su-In Lee</p>
<p style="margin:0 0 0 10px; font-size:10px;">Professor<br />Paul G. Allen School of Computer Science & Engineering</p>
</div>
</div>
</a>

<a href="https://www.tml.cs.uni-tuebingen.de/team/luxburg/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/AXAI_workshop_ulrike.png" alt="Ulrike von Luxburg">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Ulrike von Luxburg</p>
<p style="margin:0 0 0 10px; font-size:10px;">Professor<br>University of Tübingen </p>
</div>
</div>
</a>


<a href="https://sameersingh.org/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/AXAI_workshop_sameer.png" alt="Sameer Singh">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Sameer Singh</p>
<p style="margin:0 0 0 10px; font-size:10px;">Associate Professor<br>University of California, Irvine</p>
</div>
</div>
</a>



</div>


## Organisers


<div style="display:inline; width:900px; vertical-align: top;">

<a href="https://www.chhaviyadav.org" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/AXAI_workshop_chhavi.png" alt="Chhavi Yadav">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Chhavi Yadav</p>
<p style="margin:0 0 0 10px; font-size:10px;">PhD student at UCSD, her interests lie in XAI, Secure Verification, Auditing and societal impacts of deep generative models</p>
</div>
</div>
</a>

<a href="https://sites.google.com/view/michal-moshkovitz" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/AXAI_workshop_michal.png" alt="Michal Moshkovitz">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Michal Moshkovitz </p>
<p style="margin:0 0 0 10px; font-size:10px;">Machine Learning Research Scientist at Bosch Research, she has been focused on developing the foundations of explainable machine learning</p>
</div>
</div>
</a>

<a href="https://www.linkedin.com/in/bingqing-chen-631b754a/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/bingqing_chen.png" alt="Bingqing Chen">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Bingqing Chen</p>
<p style="margin:0 0 0 10px; font-size:10px;">Machine Learning Research Scientist at Bosch Research, her research lies at the intersection of machine learning and energy systems</p>
</div>
</div>
</a>

<a href="https://www.linkedin.com/in/nave-frost/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/AXAI_workshop_nave.png" alt="Nave Frost">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Nave Frost</p>
<p style="margin:0 0 0 10px; font-size:10px;">Research Scientist at eBay Research, his research interests focus on supplying explanations for data science applications</p>
</div>
</div>
</a>

<a href="https://suraj-srinivas.github.io" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/AXAI_workshop_suraj.png" alt="Suraj Srinivas">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Suraj Srinivas</p>
<p style="margin:0 0 0 10px; font-size:10px;">Postdoctoral research fellow at Harvard University, his research focuses on developing the foundations for interpretable machine learning</p>
</div>
</div>
</a>

<a href="https://scholar.google.com/citations?user=gzRuY4cAAAAJ&hl=en" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/AXAI_workshop_valentyn.png" alt="Valentyn Boreiko">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Valentyn Boreiko</p>
<p style="margin:0 0 0 10px; font-size:10px;">PhD student at the University of Tübingen and a sabbatical student at Bosch Research, his research focuses on development of interpretability technique for vision classifiers</p>
</div>
</div>
</a>

<a href="https://himalakkaraju.github.io" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/AXAI_workshop_hima.png" alt="Hima Lakkaraju">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Hima Lakkaraju</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor at Harvard University who focuses on the algorithmic and applied aspects of explainability, fairness, robustness, and privacy of machine learning models</p>
</div>
</div>
</a>


<a href="http://zicokolter.com" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/AXAI_workshop_zico.png" alt="Zico Kolter">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Zico Kolter</p>
<p style="margin:0 0 0 10px; font-size:10px;">Aassociate Professor at CMU, and chief scientist at Bosch Research, his work spans the intersection of machine learning and optimization</p>
</div>
</div>
</a>

<a href="https://scholar.google.co.il/citations?user=zhQaFaMAAAAJ&hl=en" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/AXAI_workshop_dotan.png" alt="Dotan Di Castro">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Dotan Di Castro</p>
<p style="margin:0 0 0 10px; font-size:10px;">Research scientist and lab manager at Bosch Research, his research focuses on Reinforcement Learning and Computer Vision</p>
</div>
</div>
</a>

<a href="https://cseweb.ucsd.edu/~kamalika/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/AXAI_workshop_kamalika.png" alt="Kamalika Chaudhuri">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Kamalika Chaudhuri</p>
<p style="margin:0 0 0 10px; font-size:10px;">Associate Professor at UCSD and a Research Scientist at Meta AI, her research interests lie in the foundations of trustworthy machine learning</p>
</div>
</div>
</a>

</div>


# Contact information

- Email: appliedXAI.neurips2023 [AT] gmail.com
- Twitter: [@XAI_in_Action](https://twitter.com/XAI_in_Action)


<!--
## Program Committee

<!-- column 1 -->
<!--
<div class="pc-column">
<ul>
<li>Arav Agarwal (<b>ER</b>, <b>TR</b>)</li>
<li>Eren Aksoy</li>
<li>Raghuram Mandyam Annasamy</li>
<li>Tiago Cortinhal</li>
<li>Xiaoxiao Du (<b>TR</b>)</li>
<li>Isht Dwivedi</li>
<li>Hesham Eraqi</li>
<li>Xiangyu Gao</li>
<li>Sahika Genc (<b>ER</b>)</li>
<li>S. Alireza Golestaneh (<b>TR</b>)</li>
</ul>
</div>
-->

<!-- column 2 -->
<!--
<div class="pc-column" style="margin:0 30px 0 0;">
<ul>
<li>David Held (<b>SMR</b>)</li>
<li>Todd Hester (<b>SMR</b>)</li>
<li>Zehao Huang</li>
<li>Fabian Hüger</li>
<li>Arec Jamgochian (<b>TR</b>)</li>
<li>Rowan McAllister (<b>SMR</b>)</li>
<li>Kunal Menda</li>
<li>Aarati Noronha</li>
<li>Praveen Palanisamy</li>
<li>João Pinho (<b>ER</b>)</li>
</ul>
</div>
-->


<!-- column 3 -->
<!--
<div class="pc-column">
<ul>
<li>Daniele Reda</li>
<li>Nazmus Sakib</li>
<li>Pranjay Shyam</li>
<li>Mark Schutera</li>
<li>Zhaoen Su</li>
<li>Ram Vasudevan</li>
<li>Yujie Wei</li>
<li>Weiran Yao</li>
</ul>
</div>
-->

---
<!--
<b>ER</b> — <i>Recognises PC member who served ("+" additionally) as an Emergency Reviewer.</i><br>
<b>TR</b> — <i>Recognises PC member who, according to Chair ratings, ranked in the Top 15% of Reviewers.</i><br>
<b>SMR</b> — <i>Recognises PC member who agreed to provide their services as a Senior Meta-Reviewer.</i>
-->

## Sponsors

<img src="{{ site.baseurl }}/assets/images/sponsors/bosch_logo.png">
