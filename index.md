---
layout: main-2021
title: Home
order: 1
collection: pages_2021
---
## Overview
Welcome to MRQA 2021!

We'll be taking questions via Sli.do. Please submit your questions to the speakers, and vote on questions (!) at [https://sli.do/mrqa2021](https://sli.do/mrqa2021)

**Update [24 Nov]: Thank you everyone for attending the workshop! Recorded talks and panels are now available [here](https://mrqa.github.io/#program).**

**Update [10 Nov 4:00PM AST]** We'd like to thank our brilliant speakers! We'll be closing out with our second Panel, on interpretability, starting in a few minutes

**Update: We have released [the workshop schedule](https://mrqa.github.io/#program)! The workshop will be hybrid.**
[](**We have extended our normal submission deadline to August 12. Please see our [Call for Papers](cfp).**)
[](**Deadline for the standard submissions has passed. We accept papers published elsewhere for the non-archival track (deadline: September 3). Please submit your work via the [google form](https://docs.google.com/forms/d/e/1FAIpQLSfPOCOr_4UiTVII29dZAL1GXkTFFvueQJa9gLaVK5TKh5R02A/viewform?usp=sf_link).**)

Machine Reading for Question Answering (MRQA) has become an important testbed for evaluating how well computer systems understand human language, as well as a crucial technology for industry applications such as search engines and dialogue systems. Successful MRQA systems must deal with a wide range of natural language phenomena, such as lexical semantics, paraphrasing/entailment, coreference, and pragmatic reasoning, to answer questions based on text. 

In recent years, the research community has achieved significant progress in both MRQA datasets and models. Novel datasets focus on different aspects of the problem, such as multi-hop reasoning, numerical reasoning, or commonsense reasoning. Models have also improved significantly in accuracy, and are now capable of retrieving evidence documents on the fly. However, most MRQA systems do not consider other important and diverse desiderata, such as interpretability and multilinguality, as they are predominantly evaluated by measuring accuracy on English benchmarks.

The goal of the 3rd MRQA workshop is to focus on these two emerging and crucial aspects of question answering models: interpretability and multilinguality. With recent advances in multilingual QA datasets, and the exploration and probing of large-scale pre-trained language models—that, furthermore, are increasingly incorporating multilingual data— it is timely to focus on these two topics. Towards this goal, we are structuring our workshop into two focused sessions, with dedicated speakers and panels for each of the highlighted themes. Furthermore, we are partitioning our call for papers into three primary tracks: a general research track, and one track for each theme. We expand on expectations for each track in greater detail below. 

#### Multilingual Track
Recent progress on question answering has been benchmarked mainly on English. While neural architectures are mostly language-agnostic, without using features such as named entity tags or part of speech tags, model design choices such as tokenizations are mainly driven by how it affects English. Thus, how existing MRQA models and datasets can support typologically diverse languages is unclear. In this track, we seek submissions in areas including, but not limited to:
- Modeling a unified MRQA system that can cover more than a single language.
- Improving generalization one language to another language, through data augmentation, parameter sharing and other methods.
- Developing datasets for multilingual and cross lingual MRQA. 
- Studying the tradeoff among desiderata for multilingual systems such as performance on low vs. high resource languages, compute efficiency, annotation budget.
- Evaluation methods for different languages: token-based F1 metrics, mostly suitable for English, have problems when applied to morphologically rich languages or languages without spacing. 

#### Interpretability Track
Prediction without justification or introspection has limited applicability, especially for high-stakes domains such as legal or medical text. Though many recent advances in MRQA systems have come from training expressive neural models powered by large-scale, pre-trained language models, these models still offer little transparency concerning how predictions are made. Interpretability offers a way for users to trust (or not trust) an otherwise black-box model’s predictions. Furthermore, interpretative methods can allow practitioners to diagnose critical modelling issues or dataset biases. In this track, we seek submissions in areas including, but not limited to:
- Rationales: Can models provide rationales for their predictions? What rationale format is most understandable to human users? Can we guarantee that a rationale is indeed faithful to the model’s prediction?
- Attention: In what ways can attention over the document be helpful? How does this extend to MRQA at scale, where the input documents are long, or retrieved from a large corpus?
- QA model analysis: What knowledge is stored in large-scale language models pre-trained over large, unstructured text corpora? How are facts manipulated by QA models during inference?

#### Research Track
We also seek submissions in broad areas relevant to MRQA, but do not fall within the scope of our two thematic tracks. Such topics include, but are not limited to, improving accuracy, generalization, scalability, and robustness. In addition to modeling, we also encourage submissions on the creation, analysis, and evaluation of MRQA-specific datasets.

## Registration
Workshop registration is included in [EMNLP 2021 registration](https://2021.emnlp.org/registration), along with access to the main conference, all workshops and tutorials. Note that our workshop is fully virtual.

## Speakers

**Multilingual QA**
- [Jon Clark](https://www.linkedin.com/in/jonhclark/), Google
- [Reut Tsarfaty](http://www.tsarfaty.com/), Bar-Ilan University & Allen Institute for AI
- [Yiming Cui](http://ymcui.github.io/), HIT & iFLYTEK Research

**Interpretability**
- [Hanna Hajishirzi](https://homes.cs.washington.edu/~hannaneh/), University of Washington & Allen Institute for AI
- [Jonathan Berant](https://www.cs.tau.ac.il/~joberant/),Tel Aviv University & Allen Institute for AI
- [Marco Tulio Ribeiro](https://homes.cs.washington.edu/~marcotcr/), Microsoft

## Program
The 3rd MRQA workshop will be held virtually on November 10, 2021 from 9AM to 5PM in Punta Cana Time (UTC-4).

<div id="schedule">
    <ul>
        <li>
            09:00-09:45 - Opening remark (a delayed start)
        </li>
        <li>
        	09:45-10:15 - Invited Talk 1:
        	<a href="http://www.tsarfaty.com/" target="_blank">Reut Tsarfaty</a> -- <b>Comprehensive and Inclusive Text Understanding</b> <em>(In-person)</em> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#reut-card" aria-expanded="false" aria-controls="reut-card">Abstract</button> <div class="collapse" id="reut-card">
            <div class="card card-body">Recent years have seen an all-times-peek in the performance of neural models on tasks that require natural language understanding, such as Question Answering (QA) and Natural language Inference. So much so that some recent media reports have quoted the "human" or "superhuman" performance of neural models on natural language understanding (NLU). However, in the face of such reports two questions emerge, namely: do these tasks indeed resemble human-like understanding? And, are these reports attainable in languages that are different from English?  In this talk I reflect on both of these questions, and discuss how we might want to proceed to make NLU more comprehensive and inclusive. The first work I present proposes a new task called Text-based NP Enrichment, in which we aim to predict the complete set of (NP, preposition, NP) relations that hold true in a text.  We present a novel and large-scale benchmark for the task that reflects understanding of non-trivial linguistic phenomena, both explicit and implicit, bypassing some common pitfalls of QA setups. We next present results from a completely different task, Sentence-Level Morphological Reinflection, which shed light on the difficulty to extract semantic arguments or answers from within morphologically-complex tokens. We conclude the talk by putting forward a list of desiderata for NLU assessment that would be both comprehensive and inclusive, and contemplate on tasks that could match these criteria.</div></div>
        </li>
        <li>
        	10:15-10:45 - Invited Talk 2:
        	<a href="https://www.linkedin.com/in/jonhclark/" target="_blank">Jon Clark </a> -- <b>Question Answering for All</b> <em>(Virtual)</em> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#jon-card" aria-expanded="false" aria-controls="jon-card">Abstract</button>
            <a href="https://drive.google.com/file/d/13rtG6O8aSWan_uTV6eY1B2igqQO0j3nR/view?usp=sharing" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="jon-card"><div class="card card-body">This talk advocates for a user-centric perspective on how to approach multilingual question answering systems. This perspective influences what research questions we pursue, what datasets we built, and ultimately how useful systems built with our methodologies will be to real people. We also discuss phenomena that make multilingual question answering both practically difficult and scientifically interesting including typological diversity, answer scarcity, and little supervised training data.</div></div>
        </li>
        <li>
        	10:45-11:15 - Invited Talk 3:
        	<a href="http://ymcui.github.io/" target="_blank">Yiming Cui</a> -- <b>Chinese Machine Reading Comprehension and Beyond</b> <em>(Virtual)</em> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#yiming-card" aria-expanded="false" aria-controls="yiming-card">Abstract</button> <div class="collapse" id="yiming-card">
            <a href="https://drive.google.com/file/d/11H1pYpmxuUyq31dLjMpJxX5D6_9TM8Ja/view?usp=sharing" class="btn btn-outline-info btn-xs">Video</a>
            <div class="card card-body">Machine Reading Comprehension has been widely studied in the context of English datasets. At the same time, it is also important to study non-English dataset and models to get a more comprehensive understanding in how machine understands human languages. In this talk, we will cover three main topics in dealing with non-English MRC scenarios. First, we will talk about the efforts that have been made in Chinese machine reading comprehension field. Next, we will move to multilingual and cross-lingual MRC studies, introducing a series of our work, discussing how these techniques improve the MRC system performance in Chinese and other languages. Lastly, we will try to analyze MRC models in a multilingual way and present our efforts in explainable MRC with new benchmarks and approaches.</div></div>
        </li>
        <li>
        	11:15-12:00 - Panel 1: Multilingual QA with Reut Tsarfaty, Jon Clark, Yiming Cui, <a href="https://www.cs.washington.edu/people/faculty/lsz" target="_blank">Luke Zettlemoyer</a> (University of Washington/Facebook AI Research) and <a href="http://users.umiacs.umd.edu/~jbg/" target="_blank">Jordan Boyd-Graber</a> (University of Maryland)
            <a href="https://drive.google.com/file/d/1ghj-OnzfzPFJBK9SIRoh17jqMN9WZthB/view?usp=sharing" class="btn btn-outline-info btn-xs">Video</a>
        </li>
        <li>
        	11:45-12:30 - Break (Lunch)
        </li>
        <li>
        	12:30-13:10 - Best paper talks <em>(Virtual)</em>
        	<ul style="padding-left: 40px;">
        		<li>Best paper: Maxime De Bruyn, Ehsan Lotfi, Jeska Buhmann and Walter Daelemans, <a href="https://mrqa.github.io/assets/papers/21_Paper.pdf" target="_blank">MFAQ: a Multilingual FAQ Dataset</a></li>
				<li>Honorable mention #1: Gregory Kell, Iain Marshall, Byron Wallace and Andre Jaun, <a href="https://mrqa.github.io/assets/papers/14_Paper.pdf" target="_blank">What Would it Take to get Biomedical QA Systems into Practice?</a></li>
				<li>Honorable mention #2: Martin Fajcik, Josef Jon and Pavel Smrz, <a href="https://mrqa.github.io/assets/papers/2_Paper.pdf" target="_blank">Rethinking the Objectives of Extractive Question Answering</a></li>
			</ul>
        </li>
        <li>
        	13:10-14:10 - Poster session <em>(Virtual)</em>
        </li>
        <li>
        	14:10-14:30 - Break
        </li>
        <li>
        	14:30-15:00 - Invited Talk 4:
        	<a href="https://www.cs.tau.ac.il/~joberant/" target="_blank">Jonathan Berant</a> -- <b>Is my QA model reasoning? Meaning representations and multi-task training for understanding QA models</b> <em>(In-person)</em> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#joberant-card" aria-expanded="false" aria-controls="joberant-card">Abstract</button> <div class="collapse" id="joberant-card">
            <a href="https://drive.google.com/file/d/1zKzV-GCQgHvF_Ja5bSKCYQNBxc0kUvCv/view?usp=sharing" class="btn btn-outline-info btn-xs">Video</a>
            <div class="card card-body">The discrepancy between the high performance of models on standard benchmarks, and their limitations when manually examined has led to wide interest in better evaluation of natural language understanding models. In this talk, I will discuss using structured meaning representations for automatically generating reasoning-focused "contrast sets" - given a question that requires reasoning over a set of contexts, we automatically generate additional question-answer pairs with minimal perturbations to the reasoning process. We show how this sheds light on the strengths and weaknesses of a wide range of models. In the second part of the talk, I will discuss how one can gain interpretability using multi-task training - by training a single model on a target task and an auxiliary task, we can use the outputs of the auxiliary task for better interpretation of the predictions of the model on the target task.</div></div>
        </li>
        <li>
        	15:00-15:30 - Invited Talk 5:
        	<a href="https://homes.cs.washington.edu/~marcotcr/" target="_blank">Marco Tulio Ribeiro</a> -- <b>Explanations and counterfactuals</b> <em>(In-person)</em> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#marcotcr-card" aria-expanded="false" aria-controls="marcotcr-card">Abstract</button>
            <a href="https://drive.google.com/file/d/12TO41xl4r9roUivuJp7Y3e4yQTQzdJUu/view?usp=sharing" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="marcotcr-card"><div class="card card-body">In this talk, I will present an overview of explanation methods through the lens of counterfactuals - which counterfactuals are used to create the explanation, how these counterfactuals are summarized, and what counterfactual predictions the explanation allows the user to make. In addition to being a helpful framework overall, I think this view highlights the drawbacks of most explanation methods applied to QA models, as well as potential research directions. Also, there should be fun explanations from a SOTA model trained on SQuAD 2.0.</div></div>
        </li>
        <li>
        	15:30-16:00 - Invited Talk 6:
        	<a href="https://homes.cs.washington.edu/~hannaneh/" target="_blank">Hanna Hajishirzi</a> -- <b>Knowledge-Rich and Robust Neural Text Comprehension and Reasoning</b> <em>(Virtual)</em> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#hanna-card" aria-expanded="false" aria-controls="hanna-card">Abstract</button>
            <a href="https://drive.google.com/file/d/1-85czn9w1C0b4kp5VhLGHtmKOHVm-IBH/view?usp=sharing" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="hanna-card"><div class="card card-body">Enormous amounts of ever-changing  knowledge are available online in diverse textual styles and diverse formats. Recent advances in deep learning algorithms and large-scale datasets are spurring progress in many Natural Language Processing (NLP) tasks, including question answering. Nevertheless, these models cannot scale up when task-annotated training data are scarce. This talk presents how to build robust models for textual comprehension and reasoning, and how to systematically evaluate them. First, I present general-purpose models for known tasks such as question answering in English and multiple languages that are robust to small domain shifts. Second, I discuss neuro-symbolic approaches that extend modern deep learning algorithms to elicit knowledge from structured data and language models to achieve strong performance in several NLP tasks. </div></div>
        </li>
        <li>
        	16:00-16:45 - Panel 2: Interpretability with
        	Jonathan Berant, Marco Tulio Ribeiro, Hanna Hajishirzi, <a href="https://dieuwkehupkes.nl/" target="_blank">Dieuwke Hupkes</a> (Facebook AI Research), <a href="http://www.cs.columbia.edu/~mcollins/" target="_blank">Michael Collins</a> (Google Research/Columbia University) and <a href="https://www.cis.upenn.edu/~danroth/" target="_blank">Dan Roth</a> (University of Pennsylvania)
            <a href="https://drive.google.com/file/d/1tte7AmWyU55ne0CxPopeLQWRjwKu623K/view?usp=sharing">Video</a>
        </li>
        <li>
        	16:45-17:00 - Closing remark
        </li>
     </ul>
</div>


## Organizing Committee
- [Adam Fisch](https://people.csail.mit.edu/fisch/), MIT
- [Alon Talmor](https://www.alontalmor.com/), Tel Aviv University
- [Danqi Chen](https://www.cs.princeton.edu/~danqic/), Princeton University
- [Eunsol Choi](https://www.cs.utexas.edu/~eunsol/), University of Texas at Austin
- [Minjoon Seo](https://seominjoon.github.io/), Facebook & KAIST
- [Patrick Lewis](https://www.patricklewis.io/), Facebook & University College London
- [Robin Jia](https://robinjia.github.io/), Facebook & University of Southern California
- [Sewon Min](https://shmsw25.github.io/), University of Washington


## Sponsors
![Baidu]({{ "/assets/images/baidu-logo.png" | absolute_url }})
![Facebook]({{ "/assets/images/facebook-logo.png" | absolute_url }})

