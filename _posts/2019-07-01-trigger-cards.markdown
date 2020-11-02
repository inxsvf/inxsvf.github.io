---
layout: post
title:  "Trigger Cards"
subtitle: "A widget developed for a publishing company"
date:   2019-07-01 21:11:24 +0000
categories: jekyll update
type: project


company: (Assignment) UX Project
tags: ["Web Widget", "Prototyping", "Testing", "Web Programming"]
---

This was an academic project proposed by an external entity - Adclick - where I was the sole designer.

> [Adclick](https://www.adclick.pt) is a digital marketing company focused on creating and improving audiences for their clients.

The _TriggerCards_ are a quiz-like feature to be included in an information website called Hintigo[^1]. Hintigo shares advice with its readers, about a large range of topics - from _how to choose a microwave_ to _how to fill taxes_. Most of its readers reach Hintigo from Google searches or via a Facebook post.

[^1]: Currently, Hintigo consists of different websites that in the future will converge into just one. One of these websites is [https://www.e-konomista.pt](https://www.e-konomista.pt).

<figure>
    <img id="group" src="/imgs/trigger-cards/example.png" alt="">
    <figcaption><strong>Fig. 1</strong> Example of a quiz card - <a href="http://actionbutton.org" target="_blank">Action Button</a> - used in an <a href="https://www.papermag.com/nasa-cancels- all-female-spacewalk-2632865651.html" target="_blank">online magazine</a> (retrieved Sep’20)</figcaption>
</figure>

The objective of this feature is to improve Hintigo’s engagement with its readers within its website. Adclick came in with an idea of including small polls in articles (similar to the one represented in 1) and wanted to know if it could be successful.

The first step taken was to learn more about Hintigo, social quizzes and polls (their format, their uses and purposes) and also about microinteractions.

<figure>
    <img src="/imgs/trigger-cards/structure.jpg" alt="">
    <figcaption><strong>Fig. 2</strong> Identifying the common elements in popular polls and quizzes.</figcaption>
</figure>

Next, I started to define this feature. I called it “TriggerCard” because the objective is to trigger a reaction from the reader: it asks a question to the reader, the reader answers it, and according to that answer the card can suggest an action the reader should take - like read another article on the topic; suggest a service or product <a href="#flow" class="ref">3</a>.

<figure>
    <img id="flow" class="md-img" src="/imgs/trigger-cards/idea.png" alt="">
    <figcaption><strong>Fig. 3</strong> Example of the main behaviour of the TriggerCard.</figcaption>
</figure>

Then I started drawing some wireframes and mockups, following Hintigo’s image. After a short usability test, one functional prototype was developed. This prototype was used for a series of face-to-face semi-structured interviews with potential users. After using the prototype they filled a SUS questionnarie.
Many questions were raised during these tests <a href="#test" class="ref">4</a>:
- How does the topic of the article and the interest of its readers influence the interaction with the TriggerCard?
- How is the position at the end of the article suitable for its purpose?
- Can the TriggerCard be mistaken with an Ad?
- What if another type of TriggerCard interaction is more
appealing (e.g. using a slider)?

<figure>
    <img id="test" src="/imgs/trigger-cards/tests/tasks.png" alt="">
    <figcaption><strong>Fig. 4</strong> Some screens used in the semistructured interview. The participants were asked to read and interact with an Hintigo article that included a TriggerCard (a). The objective was that they answered the quiz presented (b) and clicked the article recomended (b).</figcaption>
</figure>

## Conclusion and Learning Points

Due to time constraints, as it was an academic assigment, the project ended at this stage. These questions were left unanswered, but they help guide the way for future tests and development. This project had a troubled journey, two of the main difficulties were the following:

<p class="li-highlight">Finding my research question before starting prototyping</p>

It was hard to understand the relevance of user research as a first step to take. The feature proposed was:
- very small;
- most of it was more or less defined by the client;
- it had a very low prototyping cost

To clarify the doubts and assumptions I had, I thought I would need an artifact first I could iterate upon.

<!-- <i class="fas fa-hand-point-right"></i> -->

<p class="li-highlight"> Not viewing the feature - the TriggerCard - as a part of a greater system - the Hintigo website</p>

I was only considering the interaction between the user and the TriggerCard, with the user already inside the Hintigo article. I should have learned the reading behaviours of Hintigo users (how much they read, scan, what attracts them, ..) - i.e. create Hintigo’s user journey.

Developing a user journey could have helped:
- understanding every step and interaction that the user
could perform, and
- finding my research questions.

<div class="row no-gutters card-cstm">
    <div class="col-md-4">
        <img src="/imgs/trigger-cards/qrcode.png" alt="The beautiful MDN logo.">
    </div>
    <div class="col-md-8">
        <div class="card-body">
            <p class="card-text">Use your smartphone to scan this QR Code and access the prototype</p>
            <a href="https://inxsvf.github.io/cards/" class="btn btn-primary">View TriggerCard</a>
        </div>
    </div>
</div>