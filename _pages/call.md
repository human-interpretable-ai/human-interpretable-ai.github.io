---
layout: default
permalink: /call/
title: Call For Papers
nav: true
nav_order: 1
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
</style>

<script src="https://code.jquery.com/jquery-3.6.1.min.js" integrity="sha256-o88AwQnZB+VDvE9tvIXrMQaPlFFSUTR+nldQm1LuPXQ=" crossorigin="anonymous"></script>
<script src="https://icml.cc/static/core/js/jquery.countdown.min.js"  charset="utf-8"></script>

# Call for Papers

We invite researchers working on topics related to Human-Interpretable AI (HI-AI)
to submit short research papers describing new contributions or positions. Below,
we describe topics within HI-AI for which we will accept submissions, as well as
the submission format and instructions. Please read this page carefully before
submitting to ensure your submission is aligned with this workshop’s objectives
and guidelines.

## Important Dates

Following are the proposed important dates for the workshop. All deadlines are
due 11:59 pm Anywhere on Earth (AOE).

<table class="table table-condensed datesummary">
    <col width="auto">
        <tr class="gray">
            <td>
                <b>Paper submission deadline</b>
            </td>
            <td>
                <span class='gray'>May 28th, 2024</span>
            </td>
            <td>
                <span class="submission-countdown"></span>
                <script >
                    if ("submission" != "") {
                            var submission = "2024/05/28 23:59:59 UTC";
                        $('.submission-countdown').countdown(submission, function (event) {
                        $(this).html(event.strftime('%w weeks %d days %H:%M:%S'));

                        });
                    }
                </script>
            </td>
        </tr>
        <tr class="gray">
            <td>
                <b>Review period begins</b>
            </td>
            <td>
                <span class='gray'> May 29th, 2024</span>
            </td>
            <td>
                <span class="reviewbegins-countdown"></span>
                <script >
                    if ("reviewbegins" != "") {
                            var reviewbegins = "2024/05/29 23:59:59 UTC";
                        $('.reviewbegins-countdown').countdown(reviewbegins, function (event) {
                        $(this).html(event.strftime('%w weeks %d days %H:%M:%S'));

                        });
                    }
                </script>
            </td>
        </tr>
        <tr class="gray">
            <td>
                <b>Review period ends</b>
            </td>
            <td>
                <span class='gray'> June 27th, 2024</span>
            </td>
            <td>
                <span class="reviewends-countdown"></span>
                <script >
                    if ("reviewends" != "") {
                            var reviewends = "2024/06/27 23:59:59 UTC";
                        $('.reviewends-countdown').countdown(reviewends, function (event) {
                        $(this).html(event.strftime('%w weeks %d days %H:%M:%S'));

                        });
                    }
                </script>
            </td>
        </tr>
        <tr class="gray">
            <td>
                <b>Notification of decision</b>
            </td>
            <td>
                <span class='gray'> June 28th, 2024</span>
            </td>
            <td>
                <span class="decision-countdown"></span>
                <script >
                    if ("decision" != "") {
                            var decision = "2024/06/28 23:59:59 UTC";
                        $('.decision-countdown').countdown(decision, function (event) {
                        $(this).html(event.strftime('%w weeks %d days %H:%M:%S'));

                        });
                    }
                </script>
            </td>
        </tr>
        <tr class="gray">
            <td>
                <b>Camera-ready paper due</b>
            </td>
            <td>
                <span class='gray'> July 27th, 2024</span>
            </td>
            <td>
                <span class="camera-countdown"></span>
                <script >
                    if ("camera" != "") {
                            var camera = "2024/07/27 23:59:59 UTC";
                        $('.camera-countdown').countdown(camera, function (event) {
                        $(this).html(event.strftime('%w weeks %d days %H:%M:%S'));

                        });
                    }
                </script>
            </td>
        </tr>
</table>

## Topics of interest

In this workshop, we welcome contributions focused on a variety of topics
related to interpretability. The following is a non-exhaustive list of possible
contributions. If you believe your paper is still related to interpretability,
but it does not fit in any of the following topics, please send it anyway, we
will then evaluate whether it may be still considered.

- <b>Explainable-by-design models</b>, novel approaches designing machine learning and deep learning models that are intrinsically interpretable. Also, papers showing novel characteristics (i.e. higher trustworthiness, robustness, causality, etc.) of existing models or extending them to novel domains are appreciated.
- <b>Post-hoc methods for Interpretable AI</b>, novel approaches on post-hoc interpretable AI. These include but are not limited to approaches working on higher-level features such as concepts. As for explainable-by-design models, papers showing novel characteristics of existing models or extensions to novel domains are welcome.
- <b>Theoretical analyses</b> of existing methods, showing from a theoretical point of view what existing interpretable methods can achieve both from an explanation and a generalization point of view.
- <b>Knowledge integration & Reasoning</b> methods injecting domain knowledge or integrating expert systems and reasoning methods into deep learning models to enhance their interpretability and performance.
- <b>Ethical AI</b> papers analysing implications of interpretable AI methods, discussing topics such as fairness, accountability, transparency, and bias mitigation in AI systems.
- <b>Human-machine Interaction</b> studies on innovative human-machine interaction system successfully exploiting interpretable AI models in their capability to provide both standard and counter-factual explanations.
- <b>Position papers on XAI</b> discussing the possible evolutions of the XAI field or speculating potential interpretable system and applications with their implications.
- <b>Applications in Medicine and Healthcare</b> applications of interpretable AI methods in medical diagnosis, treatment planning, and healthcare decision-making. Case studies demonstrating the clinical utility of interpretable AI models are welcome.
- <b>AI in Industry</b> practical applications of interpretable AI methods in various safety-critical industrial sectors, such as transportation, finance and retail. We welcome case studies, as well as discussions on the challenges of integrating interpretable AI technologies into existing decision-making processes.
- <b>Legal and Regulatory dissertations</b> discussing and providing analysis of the legal challenges associated with interpretable AI, including compliance with data protection laws, liability issues, and existing regulatory requirements for transparent and accountable AI systems.

## Submission Guidelines

Authors are invited to submit short papers, limited to <b>six pages excluding
references and an optional appendix</b>. Submissions include <b>new research
papers</b> presenting novel findings and/or theoretical analyses, as well as
<b>position papers</b> aimed at starting an active discussion on topics related
to HI-AI. We also welcome summaries of <b>already published papers</b> from
A-conferences and Q1-journals within the field.

The optional Appendix has no page limit, but we encourage authors to use this
space sparingly. This appendix may discuss reproducibility details, proofs,
pseudo-code, additional results, etc. Nevertheless, the paper's main body (i.e.,
the first six pages before references) should be entirely self-contained, and
reviewers may only read through part of the Appendix.

For papers presenting novel empirical results, we kindly ask authors to
provide access to the code and data underpinning their work (when possible) to
ensure reproducibility.
All paper submissions should follow the CEUR-WS format of the HI-AI workshop that you can find [here](https://github.com/human-interpretable-ai/human-interpretable-ai.github.io/tree/master/latex-template/HI-AI-template.zip).

<div style="text-align: center; margin: auto; padding-top: 3%; padding-bottom: 3%;">
    <button class="button-submit" role="button" type="submit" onclick="window.open('https://openreview.net/group?id=KDD.org/2024/Workshop/HI-AI', '_blank')">Submit your paper</button>
</div>

### Review Process

All submissions will be peer-reviwed through a double-blinded process. Therefore,
authors must ensure that their submissions are <b>properly anonymized</b>.
To fascilitate with this process, we will use OpenReview to manage the
submission and review process, guaranteeing that final decisions are made without
any conflicts of interest.


## Publication

All papers accepted for the workshop will be published on the official workshop
website, ensuring they remain available and accessible beyond the duration of
the conference. <b>For the authors interested in an archival version</b>,
arrangements have been made with the external editor CEUR.WS to provide this
service. This, however, is optional, and authors may opt out of having their
paper included in these proceedings if they wish to submit part of their
submission to future archived venues. Furthermore, we will consider an extension
of some of the top accepted papers for a special issue on the workshop's topic.

## Attendance

For each accepted paper, at least one author must attend the conference to
present a poster for the paper. Moreover, a small number of papers will be given
the opportunity to be presented as a short contributing talk in
our workshop.
