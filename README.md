# Awesome question answering, machine reading, and dialog datasets

## The (20) QA bAbI tasks
This dataset is constructed by [Facebook](https://research.fb.com/downloads/babi/). The tasks are described in detail in the paper:
Jason Weston, et. al,. [Towards AI Complete Question Answering: A Set of Prerequisite Toy Tasks](http://arxiv.org/abs/1502.05698).



## SQuAD 
Stanford Question Answering Dataset (SQuAD) is a reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage, or the question might be unanswerable.

This dataset is created by [Pranav Rajpurkar](Pranav Rajpurkar), and can be download from the author's [github page](https://rajpurkar.github.io/SQuAD-explorer/).


## The (6) dialog bAbI tasks
This dataset contains six tasks and each task is used to test a unique aspect of dialog. Tasks are designed to complement the set of 20 bAbI tasks for story understanding of the previous section.

For each task, there are 1000 dialogs for training, 1000 for development and 1000 for testing. For tasks 1-5, we also include a second test set (with suffix -OOV.txt) that contains dialogs including entities not present in training and development sets.

The detail description can be find in the paper:
Antoine Bordes, Y-Lan Boureau, Jason Weston, [Learning End-to-End Goal-Oriented Dialog](https://research.fb.com/publications/learning-end-to-end-goal-oriented-dialog/).



## The Movie Dialog dataset
Movie Dialog dataset (MDD) is designed to measure how well models can perform at goal and non-goal orientated dialog centered around the topic of movies (question answering, recommendation and discussion). Details and baseline results on this dataset can be found in the paper:

Jesse Dodge, Andreea Gane, Xiang Zhang, Antoine Bordes, Sumit Chopra, Alexander Miller, Arthur Slam, Jason Weston. [Evaluating Prerequisite Qualities for Learning End-to-End Dialog Systems](http://arxiv.org/abs/1511.06931) and the [page](https://research.fb.com/publications/evaluating-prerequisite-qualities-for-learning-end-to-end-dialog-systems/).

The file format is again the same as in the bAbI tasks. The IDs for a given dialog start at 1 and increase. Each ID consists of one turn for each speaker (an “exchange”), which are tab separated. When the IDs in a file reset back to 1 you can consider the following sentences as a new conversation.

## 


## 


## 


## 


## 