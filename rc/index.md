---
layout: main-rc
title: Home
order: 1
collection: pages_2019_rc
---

## Overview

Machine Reading for Question Answering (MRQA) has become an important testbed for evaluating how well computer systems understand human language, as well as a crucial technology for industry applications such as search engines and dialogue systems. Successful MRQA systems must deal with a wide range of natural language phenomena, such as lexical semantics, paraphrasing/entailment, coreference, and pragmatic reasoning, to answer questions based on text.

Recognizing the potential of MRQA as a comprehensive language understanding benchmark, the research community has recently created a multitude of large-scale datasets over text sources such as Wikipedia, news articles, fictional stories, and general web sources. These new datasets have in turn inspired an even wider array of new question answering systems.

Despite this rapid progress, there is still much to understand about these datasets and systems. While in-domain model accuracy is rapidly improving on these datasets, generalization suffers when models are evaluated on new domains and datasets. Focusing only on accuracy also obscures other important desiderata, including model interpretability, scalability, and robustness to perturbations. Similarly, the diversity of recent datasets calls for an analysis of the various natural language phenomena (coreference, paraphrasing, entailment, multi-hop reasoning) that these datasets present.

Towards this goal, this year we will seek submissions in two tracks: a research track and a new shared task track. Our shared task is specifically designed to test the generalization abilities of MRQA systems (see more details below).


## Shared Task

This year, we are introducing a new MRQA Shared Task, which tests whether existing MRQA systems can generalize beyond the datasets on which they were trained. 
A truly effective question answering system should do more than merely interpolate from the training set to answer test examples drawn from the same distribution: it should also be able to extrapolate to test examples drawn from different distributions.

Participants in the shared task will submit MRQA systems trained on a specified training dataset pooled from six existing datasets. 
Systems will be evaluated on their generalization to ten different test datasets. 

For more information, please see the [Shared Task page](shared).

## Research Track

This track is broad in scope and seeks submissions in areas including, but not limited to:
- Accuracy
- Interpretability
- Speed / Scalability
- Robustness
- Creation, analysis and evaluation of datasets
- Analysis of model predictions

For more information, please see the [Research Track's call for paper](research).




## Invited Speakers:
- [Antoine Bordes](https://research.fb.com/people/bordes-antoine/), Facebook AI Research
- [Jordan Boyd-Graber](http://users.umiacs.umd.edu/~jbg/), University of Maryland
- [Kyunghyun Cho](http://www.kyunghyuncho.me/), New York University
- [Hannaneh Hajishirzi](https://homes.cs.washington.edu/~hannaneh/), University of Washington
- [Ruslan Salakhutdinov](http://www.cs.cmu.edu/~rsalakhu/), Carnegie Mellon University

## Steering Committee:
- [Jonathan Berant](http://www.cs.tau.ac.il/~joberant/), Tel-Aviv University
- [Percy Liang](https://cs.stanford.edu/~pliang/), Stanford University
- [Luke Zettlemoyer](https://www.cs.washington.edu/people/faculty/lsz), University of Washington

## Organizing Committee:
- [Danqi Chen](http://cs.stanford.edu/people/danqi/), Stanford University & Princeton University
- [Eunsol Choi](https://homes.cs.washington.edu/~eunsol/home.html), University of Washington
- [Adam Fisch](https://people.csail.mit.edu/fisch/), MIT
- [Robin Jia](http://stanford.edu/~robinjia/), Stanford University
- [Minjoon Seo](https://seominjoon.github.io/), NAVER & University of Washington
- [Alon Talmor](https://www.alontalmor.com/), Tel Aviv University
