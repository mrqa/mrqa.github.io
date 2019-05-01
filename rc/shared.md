---
layout: main-rc
title: Shared Task
order: 2
collection: pages_2019_rc
permalink: /rc/shared
---
## Shared Task Overview
The 2019 MRQA Shared Task focuses on **generalization**.
We release an official training dataset containing examples from existing QA datasets, and evaluate submitted models on ten hidden QA test datasets.
Train and test datasets may differ in some of the following ways:
- **Passage distribution**: Test examples may involve passages from different sources (e.g., science, news, novels, medical abstracts, etc) with pronounced syntactic and lexical differences.
- **Question distribution**: Test examples may emphasize different styles of questions (e.g., entity-centric, relational, other tasks reformulated as QA, etc) which may come from different sources (e.g., crowdworkers, domain experts, exam writers, etc.)
- **Joint distribution**: Test examples may vary according to the relationship of the question to the passage (e.g., collected independent vs. dependent of evidence, multi-hop, etc)

Both train and test datasets have the same format and are *extractive*.
That is, given a question and context passage, systems must find the word or the phrase in the document that best answers the question.
While this format is somewhat restrictive, it allows us to leverage many existing datasets, and its simplicity helps us focus on out-of-domain generalization, instead of other important but orthogonal challenges.

Each participant will submit a single QA system trained on the provided training data.
We will then privately evaluate each system on the hidden test data.


## Training Datasets

All participants are required to use our official training corpus (see our [GitHub repository](https://github.com/mrqa/MRQA-Shared-Task-2019) for details),
which consists of examples pooled from the following datasets:
- [SQuAD](https://arxiv.org/abs/1606.05250) (Rajpurkar et al., 2016)
- [NewsQA](https://arxiv.org/abs/1611.09830) (Trischler et al., 2016)
- [TriviaQA](https://arxiv.org/abs/1705.03551) (Joshi et al., 2017)
- [SearchQA](https://arxiv.org/abs/1704.05179) (Dunn et al., 2017)
- [HotpotQA](https://arxiv.org/abs/1809.09600) (Yang, Qi, Zhang, et al., 2018)
- [NaturalQuestions](https://ai.google/research/pubs/pub47761) (Kwiatkowski et al., 2019)

**No other question answering data may be used for training.**
We allow and encourage participants to use off-the-shelf tools for linguistic annotation (e.g. POS taggers, syntactic parsers),
as well as any publicly available unlabeled data and models derived from these (e.g. word vectors, pre-trained language models).


## Dev & Test Datasets

For development, we will release development datasets for **five** out of the ten test datasets:
- TBA on May 13

We will keep the other five test datasets hidden until the conclusion of the shared task.
We hope this will prevent teams from building solutions that are specific to our test datasets,
but do not generalize to other datasets.

Note: while the development data can be used for model selection,
**participants should not train models directly on the development data**.


## Evaluation

Systems will first be evaluated using automatic metrics: exact match score (EM) and word-level F1-score (F1).
EM only gives credit for predictions that exactly match the gold answer(s),
whereas F1 gives partial credit for partial word overlap with the gold answer(s).
We define a system’s Overall Automatic Score (OAS) to be the (macro-) average F1 score across the ten test datasets.

Time and resources permitting, we plan to run human evaluation on the top few systems with the highest overall score.
Human evaluators will directly judge whether top systems’ predictions are good answers to the test questions.


## Data Format and Submission Instructions

We detail data format and submission instructions, along with our baseline models,
in this [GitHub repository](https://github.com/mrqa/MRQA-Shared-Task-2019).
For any inquiry about the shared task and the submission, please make a new **issue** in the repository.


## Important Dates

- **May 1, 2019**: Training datasets released [[link](https://github.com/mrqa/MRQA-Shared-Task-2019#training-data)]
- **May 13, 2019**: Development datasets released
- **July 29, 2019**: Deadline for model submission
- **August 12, 2019**: Test results announced
- **August 30, 2019**: System description paper submission deadline
- **September 16, 2019**: Acceptance notification and reviews shared with authors
- **September 30, 2019**: System description paper camera-ready deadline

All submission deadlines are 11:59 PM GMT -12 (anywhere in the world).
