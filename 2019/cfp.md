---
layout: main-2019
title: Call for Papers
order: 4
collection: pages_2019
---

# Call for Papers
Machine Reading for Question Answering (MRQA) has become an important testbed for
evaluating how well computer systems understand human language,
as well as a crucial technology for industry applications such as search engines and dialog systems.
Successful MRQA systems must deal with a wide range of important phenomena,
including syntactic attachments, coreference links, and entailment.
Recognizing the potential of MRQA as a comprehensive language understanding benchmark,
the research community has recently created a multitude of large-scale datasets
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

Despite this rapid progress, there is much to understand about these datasets and systems.
While in-domain test accuracy has been improving rapidly on these datasets,
systems struggle to generalize gracefully when tested on new domains and datasets.
The ideal MRQA system is not only accurate on in-domain data, but
is also interpretable, robust to distributional shift,
able to abstain from answering when there is no adequate answer,
and capable of making logical inferences (e.g., via entailment and multi-sentence reasoning).
Meanwhile, the diversity of recent datasets calls for an analysis of the
various natural language phenomena (e.g., coreference, paraphrase, entailment, multi-step reasoning)
these datasets present.

We seek submissions on the following topics:
- **Accuracy**: How can we make MRQA systems more accurate?
- **Interpretability**: How can systems provide rationales for their predictions?
To what extent can cues such as attention over the document be helpful,
compared to direct explanations?  Can models generate derivations that justify their predictions?
- **Speed and Scalability**: Can models scale to consider multiple, lengthy documents, or the entire web as information source?  Similarly, can they scale to consider richer answer spaces, such as sets of spans or entities instead of a single answer one?
- **Robustness**: How can systems generalize to other datasets and settings beyond the training distribution?
Can we guarantee good performance on certain types of questions or documents?
- **Dataset Creation**: What are effective methods for building new MRQA datasets?
- **Dataset Analysis**: What challenges do current MRQA datasets pose?
- **Error Analysis**: What types of questions or documents are particularly challenging for existing systems?

## Submission Guidelines
We seek submissions of at least 4 and at most 8 pages, not including citations.
All submissions will be reviewed in a single track, regardless of length.
Please format your papers using the [standard ACL style files](https://www.emnlp-ijcnlp2019.org/calls/papers#formatting-requirements).
Submission is electronic via the [Softconf START system](https://www.softconf.com/emnlp2019/ws-MRQA/).

We accept two types of submissions:
 1. Archival: original work that will be included in the workshop proceedings. It needs to be anonymized and goes through double-blind review process.
 2. Non-archival: work published elsewhere. It won't be included in the proceedings.
 The authors should clearly indicate the original venue,
and will be accepted if the organizers think the work will benefit from exposure to the audience of this workshop.
It does not need to be anonymized.

#### Dual submissions
We allow submissions that are also under review in other venues, but please note that many conferences do not allow it, so make sure that you do not violate their policy as well.

#### Anonymity period
We do not enforce anonymity period. We do not restrict posting on preprint servers such as arXiv at any point of time.

## Important Dates
- **August 19, 2019**: Deadline for submission
- **September 16, 2019**: Notification of acceptance
- **September 30, 2019**: Deadline for camera-ready version

All submission deadlines are 11:59 PM GMT -12 (anywhere in the world).
