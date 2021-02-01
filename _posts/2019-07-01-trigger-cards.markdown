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

The objective of this feature is to improve Hintigo's engagement with its readers within its website. Adclick came in with an idea of including small polls in articles - similar to the one represented in <a href="#flow" class="ref">1</a> - and wanted to know if it could be successful.

<figure>
    <img id="group" src="/imgs/trigger-cards/example.png" alt="">
    <figcaption><strong>Fig. 1</strong> Example of a quiz card - <a href="http://actionbutton.org" target="_blank">Action Button</a> - used in an <a href="https://www.papermag.com/nasa-cancels-all-female-spacewalk-2632865651.html" target="_blank">online magazine</a> (retrieved Feb'21)</figcaption>
</figure>

The first step taken was to learn more about Hintigo, social quizzes and polls (their format, their uses and purposes) and also about microinteractions.

<figure>
    <img src="/imgs/trigger-cards/structure.jpg" alt="">
    <figcaption><strong>Fig. 2</strong> Identifying the common elements in popular polls and quizzes.</figcaption>
    <!-- : https://apester.com, https://help.twitter.com/en/using-twitter/twitter-polls; https://about.instagram.com/blog/announcements/introducing-polls-in-instagram-stories ; etc -->
</figure>

Next, I started to define this feature. I called it “TriggerCard” because the objective is to _trigger_ a reaction from the reader: it asks a question to the reader, the reader answers it, and according to that answer the card can suggest an action the reader should take - like read another article on the topic or even suggest a related service or product (<a href="#flow" class="ref">3</a>).

<figure>
    <img id="flow" class="md-img" src="/imgs/trigger-cards/idea.png" alt="Diagram of the main behaviour of the TriggerCard">
    <figcaption><strong>Fig. 3</strong> Example of the main behaviour of the TriggerCard.</figcaption>
</figure>

Then I started drawing some wireframes and mockups, following Hintigo's image guidelines. After a short usability test, one functional prototype was developed. 

[That prototype](https://inxsvf.github.io/cards/) was used for a series of face-to-face semi-structured interviews with potential users (<a href="#test" class="ref">4</a>). After using the prototype they also filled a SUS questionnarie.
Many questions were raised during these tests:
- How does the topic of the article and the interest of its readers influence the interaction with the TriggerCard?
- How is the position at the end of the article suitable for its purpose?
- Can the TriggerCard be mistaken with an Ad?
- What if another type of TriggerCard interaction is more appealing (e.g. using a slider)?

<figure>
    <img id="test" src="/imgs/trigger-cards/tests/tasks.png" alt="">
    <figcaption><strong>Fig. 4</strong> Some screens used in the semi-structured interview. The participants were asked to read and interact with an Hintigo article (a) that included a <em>TriggerCard</em>. The objective was to see if they answered the quiz presented (b) and clicked the article recomended (b).</figcaption>
</figure>


## Conclusion and Learning Points

Due to time constraints, as it was an academic assigment, the project ended at this stage. These questions were left unanswered, but they still help guide the way for future tests and development. This project had a troubled journey, two of the main difficulties are explained next.

<p class="li-highlight">Finding my research question before starting prototyping</p>

It was hard to understand the relevance of user research as a first step to take. The feature proposed was:
- very small;
- most of it was more or less defined by the client;
- it had a very low prototyping cost

To clarify the doubts and assumptions I had, I thought I would need an artifact first I could iterate upon.

<!-- <i class="fas fa-hand-point-right"></i> -->

<p class="li-highlight"> Not viewing the feature - the TriggerCard - as a part of a greater system - the Hintigo website</p>

I was only considering the interaction between the user and the TriggerCard, with the user already inside the Hintigo article. I should had learned the reading behaviours of Hintigo users (how much they read, scan, what attracts them, ..) - i.e. to create Hintigo's user journey.

Developing a user journey could have helped:
- understanding every step and interaction that the user could perform, and
- finding my research questions.

<div class="row no-gutters card-cstm">
    <div class="col-md-4">
        <img src="/imgs/trigger-cards/qrcode.png" alt="The beautiful MDN logo.">
    </div>
    <div class="col-md-8">
        <div class="card-body">
            <p class="card-text">Use your smartphone to scan this QR Code and access the prototype or just click the button bellow.</p>
            <a href="https://inxsvf.github.io/cards/" class="btn btn-primary">View TriggerCard</a>
        </div>
    </div>
</div>