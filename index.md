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

## Invited Speakers:
- [Mohit Bansal](http://www.cs.unc.edu/~mbansal/), UNC Chapel Hill
- [Antoine Bordes](https://research.fb.com/people/bordes-antoine/), Facebook AI Research
- [Jordan Boyd-Graber](http://users.umiacs.umd.edu/~jbg/), University of Maryland
<!-- - [Kyunghyun Cho](http://www.kyunghyuncho.me/), New York University
- [Hannaneh Hajishirzi](https://homes.cs.washington.edu/~hannaneh/), University of Washington -->
- [Matt Gardner](https://matt-gardner.github.io/), Allen Institute for AI
- [Ruslan Salakhutdinov](http://www.cs.cmu.edu/~rsalakhu/), Carnegie Mellon University

## Awards
This year we will give two awards, one for each track:
- An award of $500 for the shared task submission that achieves the highest final evaluation score.
- An award of $500 for the best research paper at MRQA 2019.

## Financial Assistance
We can offer partial financial aid to student authors who demonstrate significant financial need.
Instructions on how to apply for financial assistance will be provided after paper acceptance decisions have been finalized.

## Steering Committee:
- [Jonathan Berant](http://www.cs.tau.ac.il/~joberant/), Tel-Aviv University
- [Percy Liang](https://cs.stanford.edu/~pliang/), Stanford University
- [Luke Zettlemoyer](https://www.cs.washington.edu/people/faculty/lsz), University of Washington

## Organizing Committee:
- [Danqi Chen](http://cs.stanford.edu/~danqi), Princeton University
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
