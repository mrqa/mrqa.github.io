---
layout: main-2021
title: Home
order: 1
collection: pages_2021
---
## Overview
**We have released our [Call for Papers](cfp)!**

Machine Reading for Question Answering (MRQA) has become an important testbed for evaluating how well computer systems understand human language, as well as a crucial technology for industry applications such as search engines and dialogue systems. Successful MRQA systems must deal with a wide range of natural language phenomena, such as lexical semantics, paraphrasing/entailment, coreference, and pragmatic reasoning, to answer questions based on text. 

In recent years, the research community has achieved significant progress in both MRQA datasets and models. Novel datasets focus on different aspects of the problem, such as multi-hop reasoning, numerical reasoning, or commonsense reasoning. Models have also improved significantly in accuracy, and are now capable of retrieving evidence documents on the fly. However, most MRQA systems do not consider other important and diverse desiderata, such as interpretability and multilinguality, as they are predominantly evaluated by measuring accuracy on English benchmarks.

The goal of the 3rd MRQA workshop is to focus on these two emerging and crucial aspects of question answering models: interpretability and multilinguality. With recent advances in multilingual QA datasets, and the exploration and probing of large-scale pre-trained language models—that, furthermore, are increasingly incorporating multilingual data— it is timely to focus on these two topics. Towards this goal, we are structuring our workshop into two focused sessions, with dedicated speakers and panels for each of the highlighted themes. Furthermore, we are partitioning our call for papers into three primary tracks: a general research track, and one track for each theme. We expand on expectations for each track in greater detail below. 


#### Interpretability Track
Prediction without justification or introspection has limited applicability, especially for high-stakes domains such as legal or medical text. Though many recent advances in MRQA systems have come from training expressive neural models powered by large-scale, pre-trained language models, these models still offer little transparency concerning how predictions are made. Interpretability offers a way for users to trust (or not trust) an otherwise black-box model’s predictions. Furthermore, interpretative methods can allow practitioners to diagnose critical modelling issues or dataset biases. In this track, we seek submissions in areas including, but not limited to:
- Rationales: Can models provide rationales for their predictions? What rationale format is most understandable to human users? Can we guarantee that a rationale is indeed faithful to the model’s prediction?
- Attention: In what ways can attention over the document be helpful? How does this extend to MRQA at scale, where the input documents are long, or retrieved from a large corpus?
- QA model analysis: What knowledge is stored in large-scale language models pre-trained over large, unstructured text corpora? How are facts manipulated by QA models during inference?


#### Multilingual Track
Recent progress on question answering has been benchmarked mainly on English. While neural architectures are mostly language-agnostic, without using features such as named entity tags or part of speech tags, model design choices such as tokenizations are mainly driven by how it affects English. Thus, how existing MRQA models and datasets can support typologically diverse languages is unclear. In this track, we seek submissions in areas including, but not limited to:
- Modeling a unified MRQA system that can cover more than a single language.
- Improving generalization one language to another language, through data augmentation, parameter sharing and other methods.
- Developing datasets for multilingual and cross lingual MRQA. 
- Studying the tradeoff among desiderata for multilingual systems such as performance on low vs. high resource languages, compute efficiency, annotation budget.
- Evaluation methods for different languages: token-based F1 metrics, mostly suitable for English, have problems when applied to morphologically rich languages or languages without spacing. 


#### Research Track
We also seek submissions in broad areas relevant to MRQA, but do not fall within the scope of our two thematic tracks. Such topics include, but are not limited to, improving accuracy, generalization, scalability, and robustness. In addition to modeling, we also encourage submissions on the creation, analysis, and evaluation of MRQA-specific datasets.



## Speakers
**Interpretability**
- [Hanna Hajishirzi](https://homes.cs.washington.edu/~hannaneh/), University of Washington & Allen Institute for AI
- [Jonathan Berant](https://www.cs.tau.ac.il/~joberant/),Tel Aviv University & Allen Institute for AI
- [Marco Tulio Ribeiro](https://homes.cs.washington.edu/~marcotcr/), Microsoft

**Multilingual QA**
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
