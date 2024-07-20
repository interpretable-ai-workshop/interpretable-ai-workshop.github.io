---
layout: article
title: "Interpretable AI: Past, Present and Future"
excerpt: NeurIPS 2024 Workshop
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
    - text: December 14 or December 15, 2024 | Vancouver, Canada
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
    content:"December 14 or December 15, 2024 | Vancouver, Canada";
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





  


   body {
  font-family: 'Arial', sans-serif;
  line-height: 1.6;
  color: #333;
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

  .sponsor-logos img {
    width: 150px; /* Adjust this value as needed */
    margin-right: 20px; /* Space between images */
}

/* Remove margin from the last image */
.sponsor-logos img:last-child {
    margin-right: 0;
}


  .toggle-button {
    background-color: #007bff; /* Blue background */
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    outline: none;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.toggle-button::after {
    content: ' ▼'; /* Down arrow by default */
}

.toggle-button.active::after {
    content: ' ▲'; /* Up arrow when the section is visible */
}


/* Optional: Style for paper titles */
.paper-title {
    font-weight: bold;
}

/* Optional: Style for authors */
.authors {
    font-style: italic;
}

table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }

       .time {
            font-weight: bold;
            text-align: center;
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

Interpretability in machine learning revolves around constructing models that are _inherently_ transparent and insightful for human end users. As the scale of machine learning models increases and the range of applications expands across diverse fields, the need for interpretable models is more crucial than ever. The significance of interpretability becomes particularly evident in scenarios where decisions carry substantial real-world consequences, influencing human lives in areas such as healthcare, criminal justice, and lending, where understanding the machine learning process is essential. Interpretability can aid in auditing, verification, debugging, bias detection, ensure safety, and align models more effectively with human intentions. Post-hoc explanations may be unfaithful and thereby unreliable in some applications, which is why it is essential to design inherently interpretable models that provide truthful and complete explanations by default. Motivated by this, researchers have studied interpretability, resulting in a spectrum of distinct approaches.

On one end of the spectrum, classical interpretability methods designed for small-scale and tabular datasets often use rule-based models (e.g., decision trees, risk scores) and linear models (e.g., sparse linear models, generalized linear models) that are deemed inherently transparent. On the other end, modern interpretability methods for large-scale foundation models involve incorporating interpretable components into deep neural networks while not being fully interpretable, spawning novel research areas such as mechanistic interpretability.

In the workshop we aim to connect researchers working on different sub-fields of _interpretability_, such as rule-based interpretability, attribution-based interpretability, mechanistic interpretability, applied interpretable ML for various domains (e.g. healthcare, earth, material sciences, physics), and AI regulation. We will pose several key questions to foster discussion and insights:

- What interpretability approaches are best suited for large-scale models and foundation models? 
- How to incorporate domain knowledge and expertise when designing interpretable models?
- How can we assess the quality and reliability of interpretable models?
- How to choose between different interpretable models?
- When is it appropriate to use interpretable models or post-hoc explainability methods
- What are the inherent limitations of interpretability, and how can we address them?
- What are the diverse applications of interpretability across different domains?
- What will the future landscape of interpretability entail?
- Is there a legal need for interpretable models, and when should they be enforced?
## Dates

Note: all deadlines are in <b>Anywhere on Earth (AoE)</b>.

### Paper Submission

Submission deadline - ~~September 22~~ October 2 (23:59 AoE), 2023 \
Author notification - ~~October 20~~ October 27 (23:59 AoE), 2023 \
Camera ready deadline -  November 22 (23:59 AoE), 2023

### Workshop Event

<b>Date:</b> December 14 or December 15, 2024

## Schedule

To be announced

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

- Email: interpretable.ai.neurips.workshop [AT] gmail.com
- Twitter: [@XAI_in_Action](https://twitter.com/XAI_in_Action)


## Sponsors

<div class="sponsor-logos">
    <img src="{{ site.baseurl }}/assets/images/sponsors/bosch_logo.png" alt="Bosch Logo">
    <img src="{{ site.baseurl }}/assets/images/sponsors/Google_2015_logo.svg.png" alt="Google Logo">
</div>

<script>
 document.addEventListener('DOMContentLoaded', function() {

   // Toggle for Oral Papers
    var toggleHighlighted = document.getElementById('toggle-oral-papers');
    toggleHighlighted.addEventListener('click', function() {
        var div = document.getElementById('oral-papers-list');
        var isVisible = div.style.display === 'block';
        div.style.display = isVisible ? 'none' : 'block';
        toggleHighlighted.classList.toggle('active', !isVisible);
    });

   
    // Toggle for Highlighted Reviewers
    var toggleHighlighted = document.getElementById('toggle-highlighted');
    toggleHighlighted.addEventListener('click', function() {
        var div = document.getElementById('highlighted-reviewers-list');
        var isVisible = div.style.display === 'block';
        div.style.display = isVisible ? 'none' : 'block';
        toggleHighlighted.classList.toggle('active', !isVisible);
    });

    // Toggle for All Reviewers
    var toggleAll = document.getElementById('toggle-all');
    toggleAll.addEventListener('click', function() {
        var div = document.getElementById('all-reviewers-list');
        var isVisible = div.style.display === 'block';
        div.style.display = isVisible ? 'none' : 'block';
        toggleAll.classList.toggle('active', !isVisible);
    });

    // Toggle for Area Chairs
    var toggleAreaChairs = document.getElementById('toggle-area-chairs');
    toggleAreaChairs.addEventListener('click', function() {
        var div = document.getElementById('area-chairs-list');
        var isVisible = div.style.display === 'block';
        div.style.display = isVisible ? 'none' : 'block';
        toggleAreaChairs.classList.toggle('active', !isVisible);
    });
});


  function toggleAbstract(abstractId) {
        var abstract = document.getElementById(abstractId);
        if (abstract.style.display === "none") {
            abstract.style.display = "block";
        } else {
            abstract.style.display = "none";
        }
    }

  function togglePapers(papersId) {
    var papersDiv = document.getElementById(papersId);
    papersDiv.style.display = (papersDiv.style.display === "none") ? "block" : "none";
}
</script>
