---
layout: home
title: Home
home_title: KDD Workshop on Human-Interpretable AI
subtitle:
nav_title: Home
permalink: /
description:
---

<style>
    .button-submit {
    align-items: center;
    appearance: none;
    background-color: #3EB2FD;
    background-image: linear-gradient(1deg, #4F58FD, #149BF3 99%);
    background-size: calc(100% + 20px) calc(100% + 20px);
    border-radius: 100px;
    border-width: 0;
    box-shadow: none;
    box-sizing: border-box;
    color: #FFFFFF;
    cursor: pointer;
    display: inline-flex;
    font-family: CircularStd,sans-serif;
    font-size: 1rem;
    height: auto;
    justify-content: center;
    line-height: 1.5;
    padding: 6px 20px;
    position: relative;
    text-align: center;
    text-decoration: none;
    transition: background-color .2s,background-position .2s;
    user-select: none;
    -webkit-user-select: none;
    touch-action: manipulation;
    vertical-align: top;
    white-space: nowrap;
    }

    .button-submit:active,
    .button-submit:focus {
    outline: none;
    }

    .button-submit:hover {
    background-position: -20px -20px;
    }

    .button-submit:focus:not(:active) {
    box-shadow: rgba(40, 170, 255, 0.25) 0 0 0 .125em;
    }
    .logo-row {
    display: flex;
    flex-wrap: wrap;
    padding: 0 20px;
    text-align: center;
    margin-left: auto;
    margin-right: auto;
    justify-content: center;
    align-items: center;     /* vertical centering   */
    }

    /* Create four equal columns that sits next to each other */
    .logo-column {
    flex: 25%;
    max-width: 40%;
    padding: 0 20px;
    }

    .logo-column img {
    margin-top: 8px;
    vertical-align: middle;
    width: 100%;
    }

    /* Responsive layout - makes a two column-layout instead of four columns */
    @media screen and (max-width: 800px) {
    .logo-column {
        flex: 50%;
        max-width: 50%;
    }
    }

    /* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
    @media screen and (max-width: 600px) {
    .logo-column {
        flex: 100%;
        max-width: 100%;
    }
    }
</style>

<div style="margin: auto; text-align: center;">
  Held in conjunction with <a href="https://kdd2024.kdd.org/">KDD 2024</a><br>

  Centre de Convencions Internacional de Barcelona, Spain<br>

  August 26<sup>th</sup>, 2024<br>

  Call for papers deadline: June 14<sup>th</sup>, 2024<br><br>
</div>

## Introduction and Goals

As deep neural networks have become a fundamental building block in recent Artificial Intelligence (AI) systems, there has been a sharp increase in attempts to explain these notoriously opaque models. Human-Interpretable AI (HI-AI), a sub-field in explainable AI (XAI), is emerging as a promising direction where methods aim to construct explanations using representations that are aligned to high-level
human-understandable concepts or symbols rather than low-level representations (e.g., pixels/saliency maps). This workshop aims to spearhead research on topics within HI-AI by:

- providing a general overview of the key aspects of HI-AI to equip all researchers with the necessary background and definitions.
- running a call for papers for researchers in fields related to HI-AI to present their works as part of our poster session and have the opportunity to include these works in workshop proceedings (details can be found in our [call for papers](/call)).
- creating a space for active researchers in HI-AI to share and discuss novel ideas through invited keynote talks and contributing talks from a selected number of accepted papers.

We welcome contributions covering novel post-hoc explainability or interpretable-by-design approaches and theoretical analysis of existing works. Additionally, position contributions speculating on the future potential of this field are highly encouraged. Finally, we welcome contributions from related fields such as ethical AI, knowledge-driven machine learning, human-machine interaction, applications in medicine and industry, and analyses from regulatory experts.

## Key Details

The following are key details and dates for this workshop:

- **Workshop Date**: This workshop will be held on August 26<sup>th</sup>, 2024 from 8:50 am to 12:20 am CEST.
- **Conference**: The 30th ACM SIGKDD Conference on [Knowledge Discovery and Data Mining (KDD)](https://kdd2024.kdd.org/).
- **Location**: [Centre de Convencions Internacional de Barcelona, Barcelona, Spain](https://ccib.es/).
- **Modality**: In-person half-day event.
- **Paper Submission Deadline**: All papers for our call must be submitted by <s>May 28th, 2024</s> <b>June 14th, 2024</b>, 11:59 pm Anywhere on Earth (AOE). Please refer to our official [Call for Papers](/call) for details.

<div style="text-align: center; margin: auto; padding-top: 3%; padding-bottom: 3%;">
    <button class="button-submit" role="button" type="submit" onclick="window.open('https://openreview.net/group?id=KDD.org/2024/Workshop/HI-AI', '_blank')">Submit your paper</button>
</div>

## Attending the Workshop

The workshop is organized as a part of the 30<sup>th</sup> ACM SIGKDD
[Conference on Knowledge Discovery and Data Mining (KDD)](https://kdd2024.kdd.org/)
that will be held in Barcelona, Spain <b>from Sunday 25<sup>th</sup> of August 2024
until Thursday 29<sup>th</sup> of August 2024</b>. To attend the workshop you will need
a single day registration for the day of the workshop (August 26<sup>th</sup>)
or a full conference registration. Please look at registration details, including
costs, on the [official registration site](https://kdd2024.kdd.org/registration/).

We recommend potential attendees to register early to the conference as
(1) the "early bird" registration price ends on July 10<sup>th</sup> AoE, and
(2), if you need a Schengen visa, it is recommended to apply for this visa as
early as possible to guarantee the visa's arival before the workshop start date.
Notice that you <b>do not need to submit a paper to attend our workshop</b>!

## Keynote Speakers

<div class="row projects pt-1 pb-1">
    <div class="col-sm-4">
        {% include people.html name="Andrea Passerini" affiliation="University of Trento" url="https://disi.unitn.it/~passerini/" img="/assets/img/people/passerini.jpg" %}
    </div>
    <div class="col-sm-4">
        {% include people.html name="Abbas Rahimi" affiliation="IBM Research Europe" url="https://research.ibm.com/people/abbas-rahimi" img="/assets/img/people/abbas.JPG" %}
    </div>
    <div class="col-sm-4">
        {% include people.html name="Sonali Parbhoo" affiliation="Imperial College London" url="https://sites.google.com/view/sonali-parbhoo/home" img="/assets/img/people/sonali.jpg" %}
    </div>
</div>

## General Chairs
  <div class="row projects pt-1 pb-1">
      <div class="col-sm-4">
          {% include people.html name="Gabriele Ciravegna" affiliation=" Politecnico di Torino" url="https://dbdmg.polito.it/dbdmg_web/gabriele-ciravegna/" img="/assets/img/people/gabriele.jpeg" %}
      </div>
      <div class="col-sm-4">
          {% include people.html name="Mateo Espinosa Zarlenga" affiliation="University of Cambridge" url="https://mateoespinosa.github.io/" img="/assets/img/people/mateo_2.jpg" %}
      </div>
      <div class="col-sm-4">
        {% include people.html name="Pietro Barbiero" affiliation="Università della Svizzera Italiana" url="https://www.pietrobarbiero.eu/" img="/assets/img/people/pietro.jpeg" %}
      </div>
      <div class="col-sm-4">
          {% include people.html name="Zohreh Shams" affiliation="Builder.ai / University of Cambridge" url="https://zohrehshams.com/" img="/assets/img/people/zohreh-resized.jpg" %}
      </div>
      <div class="col-sm-4">
          {% include people.html name="Francesco Giannini" affiliation="Scuola Normale Superiore <br> Consorzio Interuniversitario Nazionale per l'Informatica" url="https://www.francescogiannini.eu/" img="/assets/img/people/francesco.jpeg" %}
      </div>
      <div class="col-sm-4">
          {% include people.html name="Damien Garreau" affiliation="Julius-Maximilians-Universität Würzburg" url="https://sites.google.com/view/damien-garreau/home" img="/assets/img/people/damien-resized.jpeg" %}
      </div>
      <div class="col-sm-4">
          {% include people.html name="Mateja Jamnik" affiliation="University of Cambridge" url="http://www.cl.cam.ac.uk/~mj201" img="/assets/img/people/mateja-resized.jpeg" %}
      </div>
      <div class="col-sm-4">
          {% include people.html name="Tania Cerquitelli" affiliation="Politecnico di Torino" url="https://www.polito.it/en/staff?p=tania.cerquitelli" img="/assets/img/people/tania.jpg" %}
      </div>
  </div>

## Sponsors
We are proud and grateful to have the following organizations as sponsors of our workshop:

<div class="logo-row">
    <div class="logo-column">
        <a href="https://tailor-network.eu/" rel="external nofollow noopener" target="_blank"><img src="/assets/img/logo_TAILOR.jpeg"></a>
    </div>
    <div class="logo-column">
         <a href="https://fondazione-fair.it/en/" rel="external nofollow noopener" target="_blank"><img src="/assets/img/logo_FAIR_cropped.jpeg"></a>
    </div>
    <div class="logo-column">
         <a href="https://about.google/intl/en-GB/" rel="external nofollow noopener" target="_blank"><img src="/assets/img/logo_google.png"></a>
    </div>
</div>
<br>
In particular, we would like to acknowledge that this workshop has been partially
supported by <b>TAILOR project funded by EU Horizon 2020 under GA No 952215</b>. This workshop has also been partially
supported by the <b>Partnership Extended PE00000013 - “FAIR - Future Artificial Intelligence Research” -
Spoke 1 “Human-centered AI”</b>.


## Contact
For any questions, please do not hesitate to contact us at
[human.interpretable.ai@gmail.com](mailto:human.interpretable.ai@gmail.com).
