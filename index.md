---
layout: main
title: Home
order: 1
collection: pages_2019
---

## Overview

Machine Reading for Question Answering (MRQA) has become an important testbed for evaluating how well computer systems understand human language, as well as a crucial technology for industry applications such as search engines and dialogue systems.
In a typical MRQA setting, a system must answer a question by reading one or more context documents.
Successful MRQA systems must understand a wide range of natural language phenomena, and a wide variety of question and document types.
While recent progress on benchmark datasets has been impressive, models are still primarily evaluated on in-domain accuracy.
It remains challenging to
build MRQA systems that generalize to new test distributions
([Chen et al., 2017](https://arxiv.org/pdf/1704.00051.pdf), [Levy et al., 2017](http://nlp.cs.washington.edu/zeroshot/zeroshot.pdf), [Yogatama et al., 2019](https://arxiv.org/pdf/1901.11373.pdf))
and are robust to test-time perturbations
([Jia and Liang, 2017](https://arxiv.org/pdf/1707.07328.pdf), [Ribeiro et al., 2018](https://homes.cs.washington.edu/~marcotcr/acl18.pdf)).

To promote research on MRQA, particularly related to generalization, we seek submissions in two tracks: [a research track](cfp) and [**a new shared task track**](shared).
Our shared task is specifically designed to test how well MRQA systems can generalize to new domains (see more details below).

## Program
8:50--9:00   | Opening remarks<br> 
9:00--9:35   | [Antoine Bordes](https://research.fb.com/people/bordes-antoine/), Facebook Artificial Intelligence Research<br>
<b>Better generation and knowledge fetching for long-form question answering</b>&nbsp;
<button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#antoine-card" aria-expanded="false" aria-controls="antoine-card">Abstract</button>
<a href="./assets/slides/antoine_bordes_mrqa2019.pdf" class="btn btn-outline-info btn-xs">Slides</a>
<div class="collapse" id="antoine-card"><div class="card card-body">
Long form question answering requires machines to provide long, complex answers, usually in the form of paragraphs&mdash;something that existing algorithms have not been challenged to do before. In this talk, we will outline the key opportunities and challenges that long-form QA entail. And we will present recent works that show that we can make promising advances towards machines that can generate complex answers to any question. Based on joint work with Angela Fan, Yacine Jernite, Chloe Braud, Michael Auli and Claire Gardent.
</div></div>
9:35--10:10  | [Matt Gardner](https://matt-gardner.github.io/), Allen Institute for Artificial Intelligence<br>
<b>How will we know when machines can read?</b>&nbsp;
<button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#matt-card" aria-expanded="false" aria-controls="matt-card">Abstract</button>
<a href="./slides/matt_gardner_mrqa2019.pdf" class="btn btn-outline-info btn-xs">Slides</a>
<div class="collapse" id="matt-card"><div class="card card-body">
The task of machine reading comprehension, asking a machine questions about a passage of text to probe its understanding, has seen a dramatic surge in popularity in recent years.  According to some metrics, we now have machines that perform as well as humans on this task.  Yet no serious researcher actually believes that machines can read, despite their performance on some reading comprehension benchmarks.  What would it take to convince ourselves that a machine understood a passage of text?  Can we devise a benchmark that would let us measure progress towards that goal?  In this talk I try to outline what such a benchmark might look like, and share some initial progress towards building one.
</div></div>
10:10--10:30 | Best paper talk I: _Multi-step Entity-centric Information Retrieval for Multi-Hop Question Answering_<br>
10:30--11:00 | Morning coffee break<br>

11:00--11:35  | [Jordan Boyd-Graber](http://users.umiacs.umd.edu/~jbg/), University of Maryland<br>
<b>What QA Researchers can Learn from Trivia Nerds</b>&nbsp;
<button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#jordan-card" aria-expanded="false" aria-controls="jordan-card">Abstract</button>
<!--<a href="./slides/jordan_boyd_graber_mrqa2019.pdf" class="btn btn-outline-info btn-xs">Slides</a>-->
<div class="collapse" id="jordan-card"><div class="card card-body">
In addition to the traditional task of getting machines to answer
questions, a major research question in question answering is creating
interesting, challenging questions that teach systems
how to answer questions and also reveal which systems are
best at answering those questions.  We argue that creating a
question answering dataset&mdash;and the ubiquitous leaderboard that
goes with it&mdash;closely resembles running a trivia tournament: you
write questions, have agents (either humans or machines) answer
the questions, and declare a winner.  However, the research
community has ignored the decades of hard-learned lessons from
decades of the trivia community creating vibrant, fair, and
effective question answering competitions.  After detailing
problems with existing QA datasets, we outline the key
lessons&mdash;removing ambiguity, discriminating skill, and
adjudicating disputes&mdash;that can transfer to QA research and
how they might be implemented for the QA community.  The talk
will also feature clips of Jordan Boyd-Graber making a fool of
himself on trivia competitions like Jeopardy! and actual trivia
whizzes taking on QA systems (and their take on QA research).
</div></div>
11:35--12:10 | Shared task overview and results<br>
12:10--12:30 | Shared task best system talk: _D-NET: A Pre-Training and Fine-Tuning Framework for Improving the Generalization of Machine Reading Comprehension_<br>
12:30--14:00 | Lunch<br>

14:00--14:20 | Best paper talk II: _Evaluating Question Answering Evaluation_<br>
14:20--14:55  | [Mohit Bansal](http://www.cs.unc.edu/~mbansal/), University of North Carolina at Chapel Hill<br>
<b>Interpretability and Robustness for Multi-Hop QA</b>&nbsp;
<button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#mohit-card" aria-expanded="false" aria-controls="mohit-card">Abstract</button>
<!--<a href="./slides/mohit_bansal_mrqa2019.pdf" class="btn btn-outline-info btn-xs">Slides</a>-->
<div class="collapse" id="mohit-card"><div class="card card-body">
In this talk, I will present some of our recent work in two important directions for multi-hop QA. First, we will discuss the value of interpretability and modularity, via our self-assembling neural modular networks and our explore+propose+assemble reasoning tree prediction models for multi-hop QA tasks. Next, I will present our work on robustness to adversaries and unseen scenarios for QA and dialogue models, including adversarial evaluation+training to avoid reasoning shortcuts in multi-hop QA, auto-augment based adversary-generation and self-robustification methods for dialogue models, robustness to new diverse questions via question generation for QA-augmentation, and robustness to missing commonsense/external knowledge in generative multi-hop QA.
</div></div>
14:55--16:30 | Poster session and afternoon coffee break<br>
16:30--17:30 | Panel discussion <br>
<!--<b>[Annette Frank](http://www.cl.uni-heidelberg.de/~frank/), Jianfeng Gao, [Chris Manning](https://nlp.stanford.edu/manning/), Sebastian Riedel, Sameer Singh, Richard Socher</b><br>-->

## Shared Task
This year, we are introducing a new MRQA Shared Task, which tests whether existing MRQA systems can generalize beyond the datasets on which they were trained.
A truly effective question answering system should do more than merely interpolate from the training set to answer test examples drawn from the same distribution: it should also be able to extrapolate to test examples drawn from different distributions.

Participants in the shared task will submit MRQA systems trained on a specified training dataset pooled from *six existing large-scale datasets*.
Systems will be evaluated on their *generalization to ten different test datasets.*
The test datasets will be in the same format as the training data, but may have different sources of document context (e.g., biology research papers) and questions (e.g., written by domain experts).
We will release development sets for five of the test datasets, while keeping the other five test datasets hidden.
This gives teams a way to measure progress during development, while discouraging them from designing specialized solutions for the particular test datasets we have chosen.

For more information, please see the [Shared Task page](shared).

## Research Track
Despite the rapid progress in MRQA, there is still much to understand about MRQA datasets and systems.
While in-domain model accuracy is rapidly improving on these datasets, generalization suffers when models are evaluated on new domains and datasets.
Focusing only on accuracy also obscures other important desiderata, including model interpretability, scalability, and robustness to perturbations.
Similarly, the diversity of recent datasets calls for an analysis of the various natural language phenomena (coreference, paraphrasing, entailment, multi-hop reasoning) that these datasets present.

This track is broad in scope and seeks submissions in areas including, but not limited to:
- Improving overall accuracy
- Interpretability
- Speed & Scalability
- Robustness
- Creation, analysis and evaluation of datasets
- Analysis of model predictions

For more information, please see [Call for Papers](cfp).

<!--
## Invited Speakers:
- [Mohit Bansal](http://www.cs.unc.edu/~mbansal/), UNC Chapel Hill
- [Antoine Bordes](https://research.fb.com/people/bordes-antoine/), Facebook AI Research
- [Jordan Boyd-Graber](http://users.umiacs.umd.edu/~jbg/), University of Maryland
- [Matt Gardner](https://matt-gardner.github.io/), Allen Institute for AI
-->

## Awards
This year, we have awarded three paper awards:
- An award of $500 for the shared task submission that achieves the highest final evaluation score.
- Two awards of $500 for the two best research papers at MRQA 2019.

<!--
## Financial Assistance
We can offer partial financial aid to student authors who demonstrate significant financial need.
Instructions on how to apply for financial assistance will be provided after paper acceptance decisions have been finalized.
-->

## Steering Committee:
- [Jonathan Berant](http://www.cs.tau.ac.il/~joberant/), Tel-Aviv University
- [Percy Liang](https://cs.stanford.edu/~pliang/), Stanford University
- [Luke Zettlemoyer](https://www.cs.washington.edu/people/faculty/lsz), University of Washington

## Organizing Committee:
- [Danqi Chen](https://www.cs.princeton.edu/~danqic/), Princeton University
- [Eunsol Choi](https://homes.cs.washington.edu/~eunsol/home.html), University of Washington
- [Adam Fisch](https://people.csail.mit.edu/fisch/), MIT
- [Robin Jia](http://stanford.edu/~robinjia/), Stanford University
- [Minjoon Seo](https://seominjoon.github.io/), NAVER & University of Washington
- [Alon Talmor](https://www.alontalmor.com/), Tel Aviv University

## Sponsors
![Baidu]({{ "/assets/images/baidu-logo.png" | absolute_url }})
![Facebook]({{ "/assets/images/facebook-logo.png" | absolute_url }})
![Naver]({{ "/assets/images/naver-logo.png" | absolute_url }})

Please see [Invitation to Sponsor MRQA](assets/docs/sponsorship.pdf) for sponsorship details.
