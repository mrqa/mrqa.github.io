---
layout: main-2021
title: Home
order: 1
collection: pages_2021
---
## Overview
Machine Reading for Question Answering (MRQA) has become an important testbed for evaluating how well computer systems understand human language, as well as a crucial technology for industry applications such as search engines and dialogue systems. Successful MRQA systems must deal with a wide range of natural language phenomena, such as lexical semantics, paraphrasing/entailment, coreference, and pragmatic reasoning, to answer questions based on text. 

Recognizing the potential of MRQA as a comprehensive language understanding benchmark, the research community has recently created a multitude of large-scale datasets over text sources such as Wikipedia, news articles, fictional stories, and general web sources. These new datasets have in turn inspired an even wider array of new question answering systems.

Despite this rapid progress, there is still much to understand about these datasets and systems. Though in-domain model accuracy has progressed dramatically over the past few years with the introduction of large-scale pre-trained language models, many open and important research questions remain. Focusing only on accuracy also obscures other important desiderata, including model interpretability, multi-lingual extensions, scalability, and robustness to perturbations. Similarly, the diversity of recent datasets and pre-trained language model backbones calls for an analysis of the various natural language phenomena (coreference, paraphrasing, entailment, multi-hop reasoning) that these datasets present. 

To discuss the progress and limitations of MRQA, we hosted the 1st Workshop for MRQA at ACL 2018. With 99 official registrants and 16 accepted papers from 25 submissions, it served as a central venue for discussing machine reading related topics. The 2nd MRQA Workshop, hosted at EMNLP 2019, continued this discussion with a special focus on out-of-domain generalization, in conjunction with a new shared task. The goal of the 3rd MRQA workshop is to continue to highlight recent advances across the field, and in particular, focus on two key, emerging and complementary topics: multilinguality and interpretability. Towards this goal, this year we are structuring our workshop into two focused sessions, with dedicated speakers and panels for each of the highlighted themes. Furthermore, we are partitioning our call for papers into three primary tracks: a general research track, a multilingual track, and an interpretability track. We expand on the expectations for each track in greater detail below.

## Research Track
This track is broad in scope and seeks submissions in areas including, but not limited to:
- Accuracy: How can we improve overall accuracy on MRQA?
- Speed / Scalability: Can models scale to consider multiple, lengthy documents, or the entire web as an information source?  Similarly, can they scale to consider richer answer spaces, such as sets of spans or entities, instead of a single answer one?
- Robustness: Can models guarantee good performance on certain types of questions or documents? Can they behave reliably and consistently on similar examples?
- Creation, analysis and evaluation of datasets: What kinds of datasets do we need? How can we create them efficiently? Can we quantify the challenges posed by each dataset?

## Interpretability Track
Our first theme of the workshop is interpretability. Prediction without justification or introspection has limited applicability. Though many recent state-of-the-art advances in MRQA systems have come from training expressive neural models powered by large-scale, pre-trained language models, these models still offer little transparency concerning how predictions are made. Interpretability offers a way for users to trust (or not trust) an otherwise black-box model’s predictions. Furthermore, interpretative methods can allow practitioners to diagnose critical modelling issues or dataset biases. In this track, we seek submissions in areas including, but not limited to:
- Rationales: Can models provide rationales for their predictions? What rationale format is most understandable to human users? Can we guarantee that a rationale is indeed faithful to the model’s prediction?
- Attention: In what ways can attention over the document be helpful? How does this extend to MRQA at scale, where the input documents are long, or numerous—i.e., retrieved from a large corpus?
- Language model analysis: What knowledge is stored in large-scale language models pre-trained over large, unstructured text corpora? How is it manipulated by LMs fine-tuned for QA? 

## Multilingual Track
Our second theme of the workshop is multilingual and cross lingual question answering. Recent progress on question answering has been benchmarked mainly on English. While neural architectures are mostly language-agnostic, without using features such as named entity tags or part of speech tags, model design choices such as tokenizations are mainly driven by how it affects English. Thus, how existing MRQA models and datasets can support typologically diverse languages is unclear. In this track, we seek submissions in areas including, but not limited to:
- Modeling a unified MRQA system that can cover more than a single language.
- Improving generalization one language to another language, through data augmentation, parameter sharing and other methods.
- Developing datasets for multilingual and cross lingual MRQA. 
- Studying the tradeoff among desiderata for multilingual systems such as performance on low resource language vs. high resource language, compute efficiency, annotation budget.


## Speakers
#### Interpretability
- [Hanna Hajishirzi](https://homes.cs.washington.edu/~hannaneh/), University of Washington & Allen Institute for AI
- [Jonathan Berant](https://www.cs.tau.ac.il/~joberant/),Tel Aviv University & Allen Institute for AI
- [Marco Tulio Ribeiro](https://homes.cs.washington.edu/~marcotcr/), Microsoft

#### Multilingual QA
- [Jon Clark](https://www.linkedin.com/in/jonhclark/), Google
- [Reut Tsarfaty](http://www.tsarfaty.com/), Bar-Ilan University
- [Yiming Cui](http://ymcui.github.io/), HIT & iFLYTEK Research


## Organizing Committee
- [Adam Fisch](https://people.csail.mit.edu/fisch/), MIT
- [Alon Talmor](https://www.alontalmor.com/), Tel Aviv University
- [Danqi Chen](https://www.cs.princeton.edu/~danqic/), Princeton University
- [Eunsol Choi](https://www.cs.utexas.edu/~eunsol/), University of Texas at Austin
- [Minjoon Seo](https://seominjoon.github.io/), Naver & KAIST
- [Patrick Lewis](https://www.patricklewis.io/), Facebook & University College London
- [Robin Jia](https://robinjia.github.io/), Facebook & University of Southern California
- [Sewon Min](https://shmsw25.github.io/), University of Washington




