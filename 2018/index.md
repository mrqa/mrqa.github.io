---
layout: main
title: Home
order: 1
---
Machine Reading for Question Answering (MRQA) has become an important testbed for 
evaluating how well computer systems understand human language,
as well as a crucial technology for industry applications such as search engines and dialog systems.
The research community has recently created a multitude of large-scale datasets 
over text sources such as 
Wikipedia ([WikiReading](http://www.aclweb.org/anthology/P16-1145), 
[SQuAD](https://aclweb.org/anthology/D16-1264),
[WikiHop](https://arxiv.org/pdf/1710.06481.pdf)), 
news and other articles ([CNN/Daily Mail](https://arxiv.org/pdf/1506.03340.pdf), 
[NewsQA](https://arxiv.org/pdf/1611.09830.pdf),
[RACE](http://aclweb.org/anthology/D17-1082)),
fictional stories ([MCTest](http://aclweb.org/anthology/D/D13/D13-1020.pdf), 
[CBT](https://arxiv.org/pdf/1511.02301.pdf),
[NarrativeQA](https://arxiv.org/pdf/1712.07040.pdf)), 
and general web sources ([MS MARCO](https://arxiv.org/pdf/1611.09268.pdf), 
[TriviaQA](http://www.aclweb.org/anthology/P17-1147), 
[SearchQA](https://arxiv.org/pdf/1704.05179.pdf)).
These new datasets have in turn inspired an even wider array of new question answering systems.

This workshop will gather researchers to address and discuss important research topics
surrounding MRQA, including:
- **Accuracy**: How can we make MRQA systems more accurate?
- **Interpretability**: How can systems provide rationales for their predictions?
- **Speed and Scalability**: How can systems scale to consider larger contexts, from long documents to the whole web?
- **Robustness**: How can systems generalize to other datasets and settings beyond the training distribution?
- **Dataset Creation**: What are effective methods for building new MRQA datasets?
- **Dataset Analysis**: What challenges do current MRQA datasets pose?
- **Error Analysis**: What types of questions or documents are particularly challenging for existing systems?

## Program
8:45--9:00   | Opening remarks<br> 
9:00--9:35   | [Phil Blunsom](https://www.cs.ox.ac.uk/people/phil.blunsom/), University of Oxford/Deepmind<br><b> - Data driven reading comprehension: successes and limitations  </b><button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">Abstract</button> <a href="./slides/phil.pdf" class="btn btn-outline-info btn-xs">Slides</a>
<div class="collapse" id="collapseExample">
    <div class="card card-body">The last three years has seen an explosion in interest in the application of large scale machine learning techniques to reading comprehension tasks. This interest has been driven by the availability of large datasets suitable for estimating data hungry supervised deep learning models. In this talk I will describe how our work at DeepMind has contributed to this trend and discuss whether this is the right approach for developing and evaluating natural language understanding systems.</div></div>
9:35--10:10  | [Sebastian Riedel](http://www.riedelcastro.org/), University College London<br><b> - Reading and Reasoning with Neural Program Interpreters  </b>
<button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#collapseExample0" aria-expanded="false" aria-controls="collapseExample">
    Abstract
  </button> <a href="./slides/sebastian.pdf" class="btn btn-outline-info btn-xs">Slides</a>
  <div class="collapse" id="collapseExample0">
    <div class="card card-body">We are getting better at teaching end-to-end neural models how to answer questions about content in natural language text. However, progress has been mostly restricted to extracting answers that are directly stated in text. In this talk, I will present our work towards teaching machines not only to read, but also to reason with what was read and to do this in a interpretable and controlled fashion. Our main hypothesis is that this can be achieved by a)  the development of neural abstract machines that follow the blueprint of program interpreters for real-world programming languages. We test this idea using two languages: an imperative (Forth) and a declarative (Prolog/Datalog) one. In both cases we implement differentiable interpreters that can be used for learning reasoning patterns. Crucially, because they are based on interpretable host languages, the interpreters also allow users to easily inject prior knowledge and inspect the learnt patterns. We will also present a data generation strategy to produce training sets for tasks that require reading and reasoning, and two datasets we have generated with it: Wikihop and Medhop.</div></div>
10:10--10:30 | Best paper talk: _A Systematic Classification of Knowledge, Reasoning, and Context within the ARC Dataset_<br>
10:30--11:00 | Morning coffee break<br>
11:00--11:35 | [Richard Socher](https://www.socher.org/), Salesforce Research<br><b> - The Natural Language Decathlon: Multitask Learning as Question Answering  </b><button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#collapseExample1" aria-expanded="false" aria-controls="collapseExample">
    Abstract
  </button>
  <div class="collapse" id="collapseExample1">
    <div class="card card-body">
Deep learning has improved performance on many natural language processing (NLP) tasks individually. However, general NLP models cannot emerge within a paradigm that focuses on the particularities of a single metric, dataset, and task. 
We introduce the Natural Language Decathlon (decaNLP), a challenge that spans ten tasks:
question answering, machine translation, summarization, natural language inference, sentiment analysis, semantic role labeling, zero-shot relation extraction, goal-oriented dialogue, semantic parsing, and commonsense pronoun resolution.
We cast all tasks as question answering over a context. Furthermore, we present a new Multitask Question Answering Network (MQAN) jointly learns all tasks in decaNLP without any task-specific modules or parameters in the multitask setting. MQAN shows improvements in transfer learning for machine translation and named entity recognition, domain adaptation for sentiment analysis and natural language inference, and zero-shot capabilities for text classification. We demonstrate that the MQAN's multi-pointer-generator decoder is key to this success and performance further improves with an anti-curriculum training strategy. Though designed for decaNLP, MQAN also achieves state of the art results on the WikiSQL semantic parsing task in the single-task setting. We release code for procuring and processing data, training and evaluating models, and reproducing all experiments for decaNLP. </div></div>
11:35--12:10 | [Jianfeng Gao](https://www.microsoft.com/en-us/research/people/jfgao/), Microsoft Research<br><b> - Multi-step reasoning neural networks for question answering </b><button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#collapseExample2" aria-expanded="false" aria-controls="collapseExample">
    Abstract
  </button> <a href="./slides/jianfeng.pdf" class="btn btn-outline-info btn-xs">Slides</a>
  <div class="collapse" id="collapseExample2">
    <div class="card card-body">In this talk, I review our recent work on developing multi-step reasoning neural network models for answering complex questions based on either text or knowledge graph (KG). For text-QA, we present a simple yet robust stochastic answer net (SAN) (Liu et al. 2018) that simulates multi-step reasoning for machine reading comprehension. SAN is unique in its use of a kind of stochastic prediction dropout on the answer module during training, which improves  robustness of the model. For KG-QA, we focus the discussion on the recently proposed reinforcement learning based approaches that explore multi-step paths in KGs. We describe in detail a graph-walking agent, called M-Walk (Shen et al. 2018), which consists of a RNN and Monte Carlo Tree Search, and has achieved new state of the art results on several graph-walking benchmarks.
</div></div>
12:10--13:45 | Lunch<br>
13:45--14:20 | [Sameer Singh](http://sameersingh.org/), University of California, Irvine<br><b> - Questioning Question Answering Answers </b><button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#collapseExample3" aria-expanded="false" aria-controls="collapseExample">
    Abstract
  </button> <a href="./slides/sameer.pdf" class="btn btn-outline-info btn-xs">Slides</a>
  <div class="collapse" id="collapseExample3">
    <div class="card card-body">Although existing QA systems are accurate on many benchmarks, they are often brittle and incorrect in ways that we don't fully understand. In this talk, I will introduce some of our recent tools for interpretability for black-box models, and present their application on SQuAD and VisualQA systems. In particular, I will show how different forms of explanations, such as word importance, sufficient conditions, and semantic adversaries, can be used to generate rationales, evaluate robustness, and analyze the errors of these complex, neural QA systems. (work with Marco Ribeiro and Carlos Guestrin)
</div></div>

14:20--15:30 | Poster session (with one-minute spotlight talks)<br>
15:30--16:00 | Afternoon coffee break<br>
16:00--17:00 | Panel discussion <br>
<b>[Annette Frank](http://www.cl.uni-heidelberg.de/~frank/), Jianfeng Gao, [Chris Manning](https://nlp.stanford.edu/manning/), Sebastian Riedel, Sameer Singh, Richard Socher</b><br>



## Important Dates
- ~~Deadline for submission: Monday, April 23, 2018~~  
- ~~Notification of acceptance: Tuesday, May 15, 2018~~  
- ~~Deadline for camera-ready version: Monday, May 28, 2018~~  
- ~~[Early registration deadline](https://acl2018.org/registration): June 4, 2018~~ 
- ~~Workshop Date: Thursday, July 19, 2018~~

All submission deadlines are 11:59 PM GMT -12 (anywhere in the world). 

## Organization
Steering Committee:
- [Antoine Bordes](https://research.fb.com/people/bordes-antoine/), Facebook AI Research
- [Percy Liang](https://cs.stanford.edu/~pliang/), Stanford University
- [Luke Zettlemoyer](https://www.cs.washington.edu/people/faculty/lsz), University of Washington

Organizing Committee:
- [Eunsol Choi](https://homes.cs.washington.edu/~eunsol/home.html), University of Washington
- [Minjoon Seo](https://seominjoon.github.io/), NAVER & University of Washington
- [Danqi Chen](http://cs.stanford.edu/people/danqi/), Stanford University
- [Robin Jia](http://stanford.edu/~robinjia/), Stanford University 
- [Jonathan Berant](http://www.cs.tau.ac.il/~joberant/), Tel-Aviv University

## Sponsors
![Naver]({{ "/assets/images/naver-logo.png" | absolute_url }})

![Facebook]({{ "/assets/images/facebook-logo.png" | absolute_url }})




