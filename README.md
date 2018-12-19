# Awesome question answering, machine reading, and dialog datasets


## SQuAD 
Stanford Question Answering Dataset (SQuAD) is a reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage, or the question might be unanswerable.

This dataset is created by [Pranav Rajpurkar](Pranav Rajpurkar), and can be download from the author's [github page](https://rajpurkar.github.io/SQuAD-explorer/).


## NarrativeQA: The NarrativeQA Reading Comprehension Challenge
[paper](https://arxiv.org/pdf/1712.07040.pdf)

Reading comprehension (RC)—in contrast to
information retrieval—requires integrating information and reasoning about events, entities, and their relations across a full document.
Question answering is conventionally used to
assess RC ability, in both artificial agents and
children learning to read. However, existing
RC datasets and tasks are dominated by questions that can be solved by selecting answers
using superficial information (e.g., local context similarity or global term frequency); they
thus fail to test for the essential integrative aspect of RC. To encourage progress on deeper
comprehension of language, we present a new
dataset and set of tasks in which the reader
must answer questions about stories by reading
entire books or movie scripts. These tasks are
designed so that successfully answering their
questions requires understanding the underlying narrative rather than relying on shallow
pattern matching or salience. We show that although humans solve the tasks easily, standard
RC models struggle on the tasks presented here.
We provide an analysis of the dataset and the
challenges it presents.


## RACE: Large-scale ReAding Comprehension Dataset From Examination
[paper](http://aclweb.org/anthology/D17-1082)

We present RACE, a new dataset for
benchmark evaluation of methods in the
reading comprehension task. Collected
from the English exams for middle and
high school Chinese students in the age
range between 12 to 18, RACE consists of near 28,000 passages and near
100,000 questions generated by human
experts (English instructors), and covers a variety of topics which are carefully designed for evaluating the students’
ability in understanding and reasoning.
In particular, the proportion of questions
that requires reasoning is much larger
in RACE than that in other benchmark
datasets for reading comprehension, and
there is a significant gap between the
performance of the state-of-the-art models (43%) and the ceiling human performance (95%). We hope this new dataset
can serve as a valuable resource for research and evaluation in machine comprehension. The dataset is freely available at [CMU](http://www.cs.cmu.edu/~glai1/data/race/) and the code is
available at [Github](https://github.com/qizhex/RACE_AR_baselines)


## TriviaQA: A Large Scale Distantly Supervised Challenge Dataset for Reading Comprehension
[paper](http://www.aclweb.org/anthology/P17-1147)

We present TriviaQA, a challenging
reading comprehension dataset containing over 650K question-answer-evidence
triples. TriviaQA includes 95K question-answer pairs authored by trivia enthusiasts and independently gathered evidence
documents, six per question on average,
that provide high quality distant supervision for answering the questions. We
show that, in comparison to other recently
introduced large-scale datasets, TriviaQA
(1) has relatively complex, compositional
questions, (2) has considerable syntactic
and lexical variability between questions
and corresponding answer-evidence sentences, and (3) requires more cross sentence reasoning to find answers. We also
present two baseline algorithms: a featurebased classifier and a state-of-the-art neural network, that performs well on SQuAD
reading comprehension. Neither approach
comes close to human performance (23%
and 40% vs. 80%), suggesting that TriviaQA is a challenging testbed that is worth
significant future study.1


## WikiHop: Constructing Datasets for Multi-hop Reading Comprehension Across Documents
[paper](https://arxiv.org/pdf/1710.06481.pdf)

Most Reading Comprehension methods limit
themselves to queries which can be answered
using a single sentence, paragraph, or document. Enabling models to combine disjoint
pieces of textual evidence would extend the
scope of machine comprehension methods,
but currently no resources exist to train and
test this capability. We propose a novel task to
encourage the development of models for text
understanding across multiple documents and
to investigate the limits of existing methods.
In our task, a model learns to seek and combine evidence – effectively performing multihop, alias multi-step, inference. We devise a
methodology to produce datasets for this task,
given a collection of query-answer pairs and
thematically linked documents. Two datasets
from different domains are induced, 
and we
identify potential pitfalls and devise circumvention strategies. We evaluate two previously proposed competitive models and find
that one can integrate information across documents. However, both models struggle to select relevant information; and providing documents guaranteed to be relevant greatly improves their performance. While the models outperform several strong baselines, their
best accuracy reaches 54.5% on an annotated
test set, compared to human performance at
85.0%, leaving ample room for improvement.


## SearchQA
[paper](https://arxiv.org/pdf/1704.05179.pdf)

We publicly release a new large-scale
dataset, called SearchQA, for machine
comprehension, or question-answering.
Unlike recently released datasets, such as
DeepMind CNN/DailyMail and SQuAD,
the proposed SearchQA was constructed
to reflect a full pipeline of general
question-answering. That is, we start not
from an existing article and generate a
question-answer pair, but start from an existing question-answer pair, crawled from
J! Archive, and augment it with text snippets retrieved by Google. Following this
approach, we built SearchQA, which consists of more than 140k question-answer
pairs with each pair having 49.6 snippets
on average. Each question-answer-context
tuple of the SearchQA comes with additional meta-data such as the snippet’s
URL, which we believe will be valuable
resources for future research. We conduct
human evaluation as well as test two baseline methods, one simple word selection
and the other deep learning based, on the
SearchQA. We show that there is a meaningful gap between the human and machine performances. This suggests that
the proposed dataset could well serve as
a benchmark for question-answering.


## WIKIREADING:  A Novel Large-scale Language Understanding Task over Wikipedia
[paper](http://www.aclweb.org/anthology/P16-1145)

We present WIKIREADING, a large-scale
natural language understanding task and
publicly-available dataset with 18 million
instances. The task is to predict textual
values from the structured knowledge base
Wikidata by reading the text of the corresponding Wikipedia articles. The task
contains a rich variety of challenging classification and extraction sub-tasks, making it well-suited for end-to-end models
such as deep neural networks (DNNs).
We compare various state-of-the-art DNNbased architectures for document classification, information extraction, and question answering. We find that models supporting a rich answer space, such as word
or character sequences, perform best. Our
best-performing model, a word-level sequence to sequence model with a mechanism to copy out-of-vocabulary words, obtains an accuracy of 71.8%.


## NewsQA:
[paper](https://arxiv.org/pdf/1611.09830.pdf)

We present NewsQA, a challenging machine comprehension dataset of over 100,000
human-generated question-answer pairs. Crowdworkers supply questions and answers based on a set of over 10,000 news articles from CNN, with answers consisting of spans of text from the corresponding articles. We collect this dataset through
a four-stage process designed to solicit exploratory questions that require reasoning.
A thorough analysis confirms that NewsQA demands abilities beyond simple word
matching and recognizing textual entailment. We measure human performance
on the dataset and compare it to several strong neural models. The performance
gap between humans and machines (0.198 in F1) indicates that significant progress
can be made on NewsQA through future research. The dataset is freely available at
https://datasets.maluuba.com/NewsQA.


## MS MARCO
[paper](https://arxiv.org/pdf/1611.09268.pdf)

We introduce a large scale MAchine Reading COmprehension dataset, which we
name MS MARCO. The dataset comprises of 1,010,916 anonymized questions—
sampled from Bing’s search query logs—each with a human generated answer and
182,669 completely human rewritten generated answers. In addition, the dataset
contains 8,841,823 passages—extracted from 3,563,535 web documents retrieved
by Bing—that provide the information necessary for curating the natural language
answers. A question in the MS MARCO dataset may have multiple answers or no
answers at all. Using this dataset, we propose three different tasks with varying
levels of difficulty: (i) predict if a question is answerable given a set of context
passages, and extract and synthesize the answer as a human would (ii) generate
a well-formed answer (if possible) based on the context passages that can be
understood with the question and passage context, and finally (iii) rank a set of
retrieved passages given a question. The size of the dataset and the fact that the
questions are derived from real user search queries distinguishes MS MARCO from
other well-known publicly available datasets for machine reading comprehension
and question-answering. We believe that the scale and the real-world nature of this
dataset makes it attractive for benchmarking machine reading comprehension and
question-answering models.


## The (6) dialog bAbI tasks
This dataset contains six tasks and each task is used to test a unique aspect of dialog. Tasks are designed to complement the set of 20 bAbI tasks for story understanding of the previous section.

For each task, there are 1000 dialogs for training, 1000 for development and 1000 for testing. For tasks 1-5, we also include a second test set (with suffix -OOV.txt) that contains dialogs including entities not present in training and development sets.

The detail description can be find in the paper:
Antoine Bordes, Y-Lan Boureau, Jason Weston, [Learning End-to-End Goal-Oriented Dialog](https://arxiv.org/pdf/1605.07683.pdf) and [Facebook](https://research.fb.com/publications/learning-end-to-end-goal-oriented-dialog/).


## CNN/Daily Mail: 
[paper](https://arxiv.org/pdf/1506.03340.pdf)

Teaching machines to read natural language documents remains an elusive challenge. Machine reading systems can be tested on their ability to answer questions
posed on the contents of documents that they have seen, but until now large scale
training and test datasets have been missing for this type of evaluation. In this
work we define a new methodology that resolves this bottleneck and provides
large scale supervised reading comprehension data. This allows us to develop a
class of attention based deep neural networks that learn to read real documents and
answer complex questions with minimal prior knowledge of language structure.


## The Movie Dialog dataset
Movie Dialog dataset (MDD) is designed to measure how well models can perform at goal and non-goal orientated dialog centered around the topic of movies (question answering, recommendation and discussion). Details and baseline results on this dataset can be found in the paper:

Jesse Dodge, Andreea Gane, Xiang Zhang, Antoine Bordes, Sumit Chopra, Alexander Miller, Arthur Slam, Jason Weston. [Evaluating Prerequisite Qualities for Learning End-to-End Dialog Systems](http://arxiv.org/abs/1511.06931) and the [page](https://research.fb.com/publications/evaluating-prerequisite-qualities-for-learning-end-to-end-dialog-systems/).

The file format is again the same as in the bAbI tasks. The IDs for a given dialog start at 1 and increase. Each ID consists of one turn for each speaker (an “exchange”), which are tab separated. When the IDs in a file reset back to 1 you can consider the following sentences as a new conversation.


## CBT
[paper](https://arxiv.org/pdf/1511.02301.pdf)

We introduce a new test of how well language models capture meaning in children’s books. Unlike standard language modelling benchmarks, it distinguishes
the task of predicting syntactic function words from that of predicting lowerfrequency words, which carry greater semantic content. We compare a range of
state-of-the-art models, each with a different way of encoding what has been previously read. We show that models which store explicit representations of long-term
contexts outperform state-of-the-art neural language models at predicting semantic content words, although this advantage is not observed for syntactic function
words. Interestingly, we find that the amount of text encoded in a single memory
representation is highly influential to the performance: there is a sweet-spot, not
too big and not too small, between single words and full sentences that allows the
most meaningful information in a text to be effectively retained and recalled. Further, the attention over such window-based memories can be trained effectively
through self-supervision. We then assess the generality of this principle by applying it to the CNN QA benchmark, which involves identifying named entities in
paraphrased summaries of news articles, and achieve state-of-the-art performance.


## The (20) QA bAbI tasks
This dataset is constructed by [Facebook](https://research.fb.com/downloads/babi/). The tasks are described in detail in the paper:
Jason Weston, et. al,. [Towards AI Complete Question Answering: A Set of Prerequisite Toy Tasks](http://arxiv.org/abs/1502.05698).


## MCTest
[paper](http://aclweb.org/anthology/D/D13/D13-1020.pdf)

We present MCTest, a freely available set of
stories and associated questions intended for
research on the machine comprehension of
text. Previous work on machine comprehension (e.g., semantic modeling) has made great
strides, but primarily focuses either on limited-domain datasets, or on solving a more restricted goal (e.g., open-domain relation
extraction). In contrast, MCTest requires machines to answer multiple-choice reading
comprehension questions about fictional stories, directly tackling the high-level goal of
open-domain machine comprehension. Reading comprehension can test advanced abilities
such as causal reasoning and understanding
the world, yet, by being multiple-choice, still
provide a clear metric. By being fictional, the
answer typically can be found only in the story itself. The stories and questions are also
carefully limited to those a young child would
understand, reducing the world knowledge
that is required for the task. We present the
scalable crowd-sourcing methods that allow
us to cheaply construct a dataset of 500 stories
and 2000 questions. By screening workers
(with grammar tests) and stories (with grading), we have ensured that the data is the same
quality as another set that we manually edited,
but at one tenth the editing cost. By being
open-domain, yet carefully restricted, we hope
MCTest will serve to encourage research and
provide a clear metric for advancement on the
machine comprehension of text.


# MRQA 2018: Machine Reading for Question Answering, Workshop at ACL 2018
[page](https://mrqa2018.github.io/)

This workshop will gather researchers to address and discuss important research topics surrounding MRQA, including:

Accuracy: How can we make MRQA systems more accurate?
Interpretability: How can systems provide rationales for their predictions?
Speed and Scalability: How can systems scale to consider larger contexts, from long documents to the whole web?
Robustness: How can systems generalize to other datasets and settings beyond the training distribution?
Dataset Creation: What are effective methods for building new MRQA datasets?
Dataset Analysis: What challenges do current MRQA datasets pose?
Error Analysis: What types of questions or documents are particularly challenging for existing systems?


