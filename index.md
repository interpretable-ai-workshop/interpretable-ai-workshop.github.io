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
    - text: December 15, 2024 | Vancouver, Canada
  background_image:
    src: /assets/images/home_img.png
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

.article__header {
    margin: 0 0 0 0;
}

.article__header h1 {
    display: inline;
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
    content:"December 15, 2024 | Vancouver, Canada";
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

Note: All deadlines are 11:59PM UTC-12:00 <b>Anywhere on Earth (AoE)</b>.

### Paper Submission
- Submission open on OpenReview: August 9, 2024
- Submission Deadline: August 30, 2024
- Notification of Acceptance: October 9, 2024
- Camera-ready Deadline: November 15, 2024

### Workshop Event

<b>Date:</b> December 15, 2024

## Accepted Papers
<button class="toggle-button" onclick="togglePapers('papers')">Show Papers</button>
<div id="papers" class="papers-container" style="display:none;">		
  <div>Paper ID: 58 - <a href="https://openreview.net/forum?id=0w7JBZibDc" target="_blank"> "What do we even know about interpretability?"</a></div>
  <div>Paper ID: 40 - <a href="https://openreview.net/forum?id=OPQZa8e6E4" target="_blank"> "Interpretable AI in Human-Machine Systems: Insights from Human-in-the-Loop Product Recommendation Engines"</a></div>
  <div>Paper ID: 56 - <a href="https://openreview.net/forum?id=Ce8hCJWO2s" target="_blank"> "Isometry pursuit"</a></div>
  <div>Paper ID: 68 - <a href="https://openreview.net/forum?id=r4BofYylBt" target="_blank"> "Subgroup Discovery with the Cox Model"</a></div>
  <div>Paper ID: 83 - <a href="https://openreview.net/forum?id=ywxDNmQ2jV" target="_blank"> "A Theory of Interpretable Approximations"</a></div>
  <div>Paper ID: 19 - <a href="https://openreview.net/forum?id=bT69IJ5Br5" target="_blank"> "Bivariate Decision Trees: Smaller, Interpretable, More Accurate"</a></div>
  <div>Paper ID: 43 - <a href="https://openreview.net/forum?id=vcySq1WUeL" target="_blank"> "PCNN: Probable-Class Nearest-Neighbor Explanations Improve Fine-Grained Image Classification Accuracy for AIs and Humans"</a></div>
  <div>Paper ID: 37 - <a href="https://openreview.net/forum?id=0HOHJuNpZl" target="_blank"> "GAMformer: Exploring In-Context Learning for Generalized Additive Models"</a></div>
  <div>Paper ID: 70 - <a href="https://openreview.net/forum?id=vr5VRKq09l" target="_blank"> "Residual Stream Analysis with Multi-Layer SAEs"</a></div>
  <div>Paper ID: 74 - <a href="https://openreview.net/forum?id=a78CZ8g85n" target="_blank"> "ConceptDrift: Uncovering Biases through the Lens of Foundational Models"</a></div>
  <div>Paper ID: 77 - <a href="https://openreview.net/forum?id=6VGkENHc1J" target="_blank"> "Can sparse autoencoders be used to decompose and interpret steering vectors?"</a></div>
  <div>Paper ID: 6 - <a href="https://openreview.net/forum?id=zJFvjdW9JS" target="_blank"> "How Do Training Methods Influence the Utilization of Vision Models?"</a></div>
  <div>Paper ID: 67 - <a href="https://openreview.net/forum?id=tmpMQLxVHh" target="_blank"> "Measuring the Reliability of Causal Probing Methods: Tradeoffs, Limitations, and the Plight of Nullifying Interventions"</a></div>
  <div>Paper ID: 14 - <a href="https://openreview.net/forum?id=zjjtn7P8IG" target="_blank"> "Clustering and Alignment: Understanding the Training Dynamics in Modular Addition"</a></div>
  <div>Paper ID: 64 - <a href="https://openreview.net/forum?id=K1lmElBhNo" target="_blank"> "SignAttention: On the Interpretability of Transformer Models for Sign Language Translation"</a></div>
  <div>Paper ID: 65 - <a href="https://openreview.net/forum?id=OvmW8HnGzK" target="_blank"> "Interpretability as Compression: Reconsidering SAE Explanations of Neural Activations"</a></div>
  <div>Paper ID: 23 - <a href="https://openreview.net/forum?id=Wzav8fesTL" target="_blank"> "A is for Absorption: Studying Sparse Autoencoder Feature Splitting and Absorption in Spelling Tasks"</a></div>
  <div>Paper ID: 39 - <a href="https://openreview.net/forum?id=jT1WiYTIHR" target="_blank"> "Words in Motion: Interpreting Motion Forecasting Transformers by Controlling Representations"</a></div>
  <div>Paper ID: 53 - <a href="https://openreview.net/forum?id=l2qgijevG0" target="_blank"> "You can remove GPT2's LayerNorm by fine-tuning"</a></div>
  <div>Paper ID: 55 - <a href="https://openreview.net/forum?id=jYl7kM1oK0" target="_blank"> "Towards scientific discovery with dictionary learning: Extracting biological concepts from microscopy foundation models"</a></div>
  <div>Paper ID: 79 - <a href="https://openreview.net/forum?id=3JEHX31Yy6" target="_blank"> "A Mechanism for Storing Positional Information Without Positional Embeddings"</a></div>
  <div>Paper ID: 76 - <a href="https://openreview.net/forum?id=8XuiwERO2A" target="_blank"> "Your Theory Is Wrong: Using Linguistic Frameworks for LLM Probing"</a></div>
  <div>Paper ID: 48 - <a href="https://openreview.net/forum?id=Teect8Hlkk" target="_blank"> "CoS: Enhancing Personalization and Mitigating Bias with Context Steering"</a></div>
  <div>Paper ID: 63 - <a href="https://openreview.net/forum?id=x6ZM5Is2Po" target="_blank"> "Competence-Based Analysis of Language Models"</a></div>
  <div>Paper ID: 13 - <a href="https://openreview.net/forum?id=dIOLgr7nda" target="_blank"> "Error-controlled interaction discovery in deep neural networks"</a></div>
  <div>Paper ID: 18 - <a href="https://openreview.net/forum?id=yNgYYzimDb" target="_blank"> "Enhancing patient stratification and interpretability through class-contrastive and feature attribution techniques"</a></div>
  <div>Paper ID: 35 - <a href="https://openreview.net/forum?id=cftKAMCl2h" target="_blank"> "Evaluating Machine Learning Models with NERO: Non-Equivariance Revealed on Orbits"</a></div>
  <div>Paper ID: 17 - <a href="https://openreview.net/forum?id=SG78tZG9kv" target="_blank"> "A Concept-Based Explainability Framework for Large Multimodal Models"</a></div>
  <div>Paper ID: 24 - <a href="https://openreview.net/forum?id=sBPRqxPrWh" target="_blank"> "Exploiting Interpretable Capabilities with Concept-Enhanced Diffusion and Prototype Networks"</a></div>
  <div>Paper ID: 28 - <a href="https://openreview.net/forum?id=IxWm8majsV" target="_blank"> "Interactive Semantic Interventions for VLMs: A Human-in-the-Loop Approach to Interpretability"</a></div>
  <div>Paper ID: 30 - <a href="https://openreview.net/forum?id=OeRxyWGO4k" target="_blank"> "Model Reconstruction Using Counterfactual Explanations: A Perspective From Polytope Theory"</a></div>
  <div>Paper ID: 57 - <a href="https://openreview.net/forum?id=3xMGHSJkXf" target="_blank"> "Policy-shaped prediction: improving world modeling through interpretability"</a></div>
  <div>Paper ID: 71 - <a href="https://openreview.net/forum?id=xP1ROUJoyt" target="_blank"> "ProtoS-ViT: Visual foundation models for sparse self-explainable classifications"</a></div>
  <div>Paper ID: 44 - <a href="https://openreview.net/forum?id=mZkShMbCaS" target="_blank"> "Disentangling Mean Embeddings for Better Diagnostics of Image Generators"</a></div>
  <div>Paper ID: 27 - <a href="https://openreview.net/forum?id=0EUYnGIp4F" target="_blank"> "The effect of whitening on explanation performance"</a></div>
  <div>Paper ID: 61 - <a href="https://openreview.net/forum?id=dQR1CSGfog" target="_blank"> "Aligning Characteristic Descriptors with Images for Human-Expert-like Explainability"</a></div>
  <div>Paper ID: 4 - <a href="https://openreview.net/forum?id=qvsRFOmB6Z" target="_blank"> "Explainable AI-based analysis of human pancreas sections detects traits of type 2 diabetes"</a></div>
  <div>Paper ID: 16 - <a href="https://openreview.net/forum?id=HmuMTOWdiK" target="_blank"> "Right on Time: Revising Time Series Models by Constraining their Explanations"</a></div>
  <div>Paper ID: 51 - <a href="https://openreview.net/forum?id=oZLbD3p11a" target="_blank"> "Explainable Concept Generation through Vision-Language Preference Learning"</a></div>
  <div>Paper ID: 75 - <a href="https://openreview.net/forum?id=RUictASiLY" target="_blank"> "Riemann Sum Optimization for Accurate Integrated Gradients Computation"</a></div>
  <div>Paper ID: 12 - <a href="https://openreview.net/forum?id=TfrQgdcVlm" target="_blank"> "Deep quantum graph dreaming: deciphering neural network insights into quantum experiments"</a></div>
  <div>Paper ID: 36 - <a href="https://openreview.net/forum?id=bXMjIjaKtP" target="_blank"> "This Looks Like Those: Illuminating Prototypical Concepts Using Multiple Visualizations"</a></div>
  <div>Paper ID: 78 - <a href="https://openreview.net/forum?id=BpJK5lFzfM" target="_blank"> "From Flexibility to Manipulation: The Slippery Slope of Parameterizing Interpretability Evaluation"</a></div>
  <div>Paper ID: 20 - <a href="https://openreview.net/forum?id=uojwi6W25V" target="_blank"> "Latent Concept-based Explanation of NLP Models"</a></div>
  <div>Paper ID: 72 <b>(Position)</b> - <a href="https://openreview.net/forum?id=FHScolo0WA" target="_blank"> "In Defense of Post-hoc Explainability"</a></div>
  <div>Paper ID: 5 <b>(Position)</b> - <a href="https://openreview.net/forum?id=g0I1h8JmtE" target="_blank"> "XAI needs formal notions of explanation correctness"</a></div>         
</div>          


## Schedule

<table>
    <tr>
        <th>Time</th>
        <th>Event</th>
        <th>Additional Information</th>
    </tr>
    <tr>
        <td class="time">8:50 - 9:00 AM</td>
        <td>Opening Remarks</td>
        <td></td>
    </tr>
    <tr>
        <td class="time">9:00 - 9:30 AM</td>
        <td>IT1: Cynthia Rudin</td>
        <td> </td>
    </tr>
    <tr>
        <td class="time">9:30 - 10:00 AM</td>
        <td>IT2: Rich Caruana</td>
        <td> </td>
    </tr>
    <tr>
        <td class="time">10:00 - 11:15 AM</td>
        <td>Poster Session 1 + Coffee Break</td>
        <td>
        </td>
    </tr>
    <tr>
        <td class="time">11:15 - 12:00 AM</td>
        <td>Panel Discussion</td>
        <td><strong>Moderator:</strong> David Bau. <strong>Panelists:</strong> Cynthia Rudin, Rich Caruana, and Victor Veitch.</td>
    </tr>
    <tr>
        <td class="time">12:00 - 1:00 PM</td>
        <td>Lunch</td>
        <td></td>
    </tr>
    <tr>
        <td class="time">1:00 - 1:30 PM</td>
        <td>Contributed Talks 1</td>
        <td> 
          <button class="toggle-button" onclick="togglePapers('orals1')">Show Papers</button>
          <div id="orals1" class="papers-container" style="display:none;">
          <div>Paper ID: 56 - <a href="https://openreview.net/forum?id=Ce8hCJWO2s" target="_blank"> "Isometry pursuit"</a></div>
          <div>Paper ID: 37 - <a href="https://openreview.net/forum?id=0HOHJuNpZl" target="_blank"> "GAMformer: Exploring In-Context Learning for Generalized Additive Models"</a></div>
          <div>Paper ID: 24 - <a href="https://openreview.net/forum?id=sBPRqxPrWh" target="_blank"> "Exploiting Interpretable Capabilities with Concept-Enhanced Diffusion and Prototype Networks"</a></div>
          </div>
        </td>
    </tr>
    <tr>
        <td class="time">1:30 - 2:00 PM</td>
        <td>IT3: Jiaxin Zhang</td>
        <td> </td>
    </tr>
    <tr>
        <td class="time">2:00 - 2:30 PM</td>
        <td>IT4: Tong Wang</td>
        <td> </td>
    </tr>
    <tr>
        <td class="time">2:30 - 3:00 PM</td>
        <td>Coffee Break</td>
        <td>
        </td>
    </tr>	
    <tr>
        <td class="time">3:00 - 3:30 PM</td>
        <td>IT5: Neel Nanda</td>
        <td> </td>
    </tr>    
    <tr>
        <td class="time">3:30 - 4:00 PM</td>
        <td>Contributed Talks 2</td>
        <td>
          <button class="toggle-button" onclick="togglePapers('orals2')">Show Papers</button>
          <div id="orals2" class="papers-container" style="display:none;">
          <div>Paper ID: 65 - <a href="https://openreview.net/forum?id=OvmW8HnGzK" target="_blank"> "Interpretability as Compression: Reconsidering SAE Explanations of Neural Activations"</a></div>
          <div>Paper ID: 67 - <a href="https://openreview.net/forum?id=tmpMQLxVHh" target="_blank"> "Measuring the Reliability of Causal Probing Methods: Tradeoffs, Limitations, and the Plight of Nullifying Interventions"</a></div>
          <div>Paper ID: 55 - <a href="https://openreview.net/forum?id=jYl7kM1oK0" target="_blank"> "Towards scientific discovery with dictionary learning: Extracting biological concepts from microscopy foundation models"</a></div>
          </div>
        </td>
    </tr>
    <tr>
        <td class="time">4:00 - 4:45 PM</td>
        <td>Poster Session 2</td>
        <td></td>
    </tr>	  
    <tr>
        <td class="time">4:45 - 5:00 PM</td>
        <td>Concluding Remarks</td>
        <td></td>
    </tr>	
</table>


_All times are in Canada/Pacific Time_  

## Speakers and panelists


<div style="display:inline; width:900px; vertical-align: top;">

<a href="https://users.cs.duke.edu/~cynthia/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/Cynthia.png" alt="Cynthia Rudin">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Cynthia Rudin</p>
<p style="margin:0 0 0 10px; font-size:10px;">Distinguished Professor<br>Duke University</p>
</div>
</div>
</a>




<a href="https://www.microsoft.com/en-us/research/people/rcaruana/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/Rich.png" alt="Rich Caruana">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Rich Caruana</p>
<p style="margin:0 0 0 10px; font-size:10px;">Senior Principal Researcher<br>Microsoft Research</p>
</div>
</div>
</a>

<a href="https://tongwang-ai.github.io/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="/assets/images/speakers/Tong.png" alt="Tong Wang" />
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Tong Wang</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor of Marketing <br />Yale University</p>
</div>
</div>
</a>

<a href="https://www.neelnanda.io/about" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/Neel.png" alt="Neel Nanda">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Neel Nanda</p>
<p style="margin:0 0 0 10px; font-size:10px;">Lead of <br>Google DeepMind Mechanistic Interpretability</p>
</div>
</div>
</a>



<a href="https://jxzhangjhu.github.io/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/Jiaxin.png" alt="Jiaxin Zhang">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Jiaxin Zhang</p>
<p style="margin:0 0 0 10px; font-size:10px;">Staff Research Scientst <br>Intuit AI Research</p>
</div>
</div>
</a>

<a href="https://baulab.info/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/david_bau.png" alt="David Bau">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">David Bau</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor<br>Northeastern University</p>
</div>
</div>
</a>

<a href="https://scholar.google.com/citations?user=xkn_XZgAAAAJ&hl=en" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/vicotr_veitch.png" alt="Victor Veitch">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Victor Veitch</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor<br>University of Chicago</p>
</div>
</div>
</a>



</div>


## Organisers


<div style="display:inline; width:900px; vertical-align: top;">

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

<a href="https://users.cs.duke.edu/~lesia/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/Lesia.png" alt="Chhavi Yadav">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Lesia Semenova</p>
<p style="margin:0 0 0 10px; font-size:10px;">Postdoctoral researcher at Microsoft Research, her research focuses mainly on interpretable machine learning and AI in healthcare.</p>
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

<a href="https://scholar.google.com/citations?user=gzRuY4cAAAAJ&hl=en" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/AXAI_workshop_valentyn.png" alt="Valentyn Boreiko">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Valentyn Boreiko</p>
<p style="margin:0 0 0 10px; font-size:10px;">PhD student at the University of Tübingen, his research focuses on development of interpretability technique for vision classifiers</p>
</div>
</div>
</a>

<a href="https://sites.google.com/view/vinayakabrol/home" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/vabrol.png" alt="Zico Kolter">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Vinayak Abrol</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor at IIIT Delhi, his research focuses on the design and analysis of numerical algorithms for information-inspired applications</p>
</div>
</div>
</a>


<a href="https://www.linkedin.com/in/bitya-neuhof/?originalSubdomain=il" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/Bitya.png" alt="Bitya Neuhof">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Bitya Neuhof</p>
<p style="margin:0 0 0 10px; font-size:10px;">PhD student at the Hebrew University of Jerusalem, exploring the stability and reliability of explainable AI methods</p>
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

</div>


# Contact information

- Email: interpretable.ai.neurips.workshop [AT] gmail.com


## Sponsors

<div class="sponsor-logos">
    <img src="{{ site.baseurl }}/assets/images/sponsors/Google_2015_logo.svg.png" alt="Google Logo">
    <img src="{{ site.baseurl }}/assets/images/sponsors/intuit-logo.png" alt="Intuit Logo">
</div>

## Organizers' Institutions

<div class="sponsor-logos">
    <img src="{{ site.baseurl }}/assets/images/sponsors/bosch_logo.png" alt="Bosch Logo">
    <img src="{{ site.baseurl }}/assets/images/sponsors/ebay_logo.png" alt="eBay Logo">
    <img src="{{ site.baseurl }}/assets/images/sponsors/ucsd_logo.png" alt="UCSD Logo">
    <img src="{{ site.baseurl }}/assets/images/sponsors/harvard_logo.png" alt="Harvard Logo">
    <img src="{{ site.baseurl }}/assets/images/sponsors/microsoft_logo.png" alt="Microsoft Logo">
    <img src="{{ site.baseurl }}/assets/images/sponsors/tubingen_logo.png" alt="Tübingen Logo">
    <img src="{{ site.baseurl }}/assets/images/sponsors/infosys_logo.jpg" alt="Infosys Logo">
    <img src="{{ site.baseurl }}/assets/images/sponsors/huji_logo.jpg" alt="HUJI Logo">
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
