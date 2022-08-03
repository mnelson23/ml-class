# CAP4770 Introduction to Data Mining

## Fall 2022

#### essentials

| \#  | Resource                                                                                                                       |
| ---:|:------------------------------------------------------------------------------------------------------------------------------ |
| 1   | [The current version of the syllabus](https://github.com/zacharski/ml-class)                                                   |
| 2   | [Welcome video](https://youtu.be/CT06ST4xLUk)                                                                                  |
| 3   | [What should you do the first week of the course](https://github.com/zacharski/ml-class/blob/master/jumpstart/readme.md)       |
| 4   | Instructor: Ron Zacharski, ron.zacharski@gmail.com, 575.680.4041                                                               |
| 5   | [Experience Point Sheet](https://docs.google.com/spreadsheets/d/1GKXvPqdZDsKotgjP6Vu2gcoFdvWgDfhrrs7u29yxMdQ/edit?usp=sharing) |
| 5   | the [FIU Deep Learning Slack workspace](https://fiu-deeplearning-team.slack.com)                                               |

## Course Catalog Description

Data mining applications, data preparation, data reduction and
various data mining techniques such as association, clustering, classification, anomaly
detection.

## Course Description

This course provides an introduction to practical machine learning tools for data mining with an emphasis on XGBoost and Deep Learning.

## Prerequisites

## An asynchronous online class

This class is asynchronous meaning there is no mandatory real-time interaction. You will be working through the [Inquiryum Machine Learning Fundamentals Course](http://inquiryum.com/machine-learning/). You can watch the videos anytime you want. You can play them at a faster speed, you can rewatch them or pause them. You can work on the course material in 20 minute blocks throughout a day, or devote a large contiguous block of time once per week. When you need help you can use the [FIU Deep Learning Slack workspace](https://fiu-deeplearning-team.slack.com/) to get assistance from me or your classmates.

The advantages of this approach is that it allows you great flexibility in when you want to work on the material and for how long. And, as described below under mastery learning, it allows you to work at your own pace.

### Optional Zoom Study Groups

See the description of the study groups on the [What to expect page](jumpstart/what_to_expect.md).

### Instructor availability

I will be sitting at my laptop on the Slack channel Tuesdays and Wednesdays from 11am until 2pm ET. This means that if you message me, I will respond within 5 minutes unless I am helping another student. Feel free to message me outside of those times. At times my response delay might be significant. Often I turn off Slack notifications at midnight. There may be times during Friday through Sunday when I don't have cell or wifi coverage and I will not be able to receive your message. Also, there may other times when I don't have cell coverage. In those cases I will post a message on Slack beforehand. The reason for this is that while I am based in Santa Fe I often go off exploring the Southwest in my van and sometimes lose cell phone coverage. If your questions require something that can be better addressed over Zoom, we can arrange a meeting time through Slack. I also encourage those in class to help others (see my honor code policy below)

The above hours may be subject to change if other times benefit more students. These changes will be announced in the Slack channel.

## Course Objectives

Students will gain hands-on experience with the following algorithms and libraries, learning when and how to apply them to problems in data mining:

* Numpy, Pandas, skLearn

* entropy and decision trees

* bagging and pasting

* random forest

* XGBoost

* deep learning basics

* Convolutional Neural Networks (CNN)

* Clustering

* Working with text

## Expected Outcomes

### Basic Machine Learning (ML) Techniques

Students should be able to

- architect a scalable ML pipeline
- run ML jobs on a GPU using Jupyter Notebooks in Colab
- evaluate different ML models
- determine the best ML algorithm to use for an application
- reduce the dimensionality of a dataset
- develop different linear models to solve classification problems
- communicate effectively about ML applications (terminology)

### XGBoost

Students should be able to

- apply decision tree algorithms to create a classifier
- use random forest techniques
- combine a number of weak classifiers into a strong one by using boosting.
- effectively use the XGBoost algorithm

### Deep Learning

Students should be able to

- build a simple deep learning system for image classification
- build CNNs for computer vision
- pre-process text datasets into a form usable for classification
- build CNN for text classification
- adjust hyperparameters to improve performance

## Labs and Projects

The majority of effort in the course is in working on labs and project, which have different levels of expected knowledge and independence.

### Labs

- In the form of Jupyter Notebook tutorials which provide detailed explanations and sample executable code.
- You are to:
  - write a small amount of code to complete the task
  - answer any non-coding questions the Notebook may ask.

### Projects

- Follows examples shown in the course videos and in the labs.
- Builds off of concepts and skills you learned completing the labs.
- Project definition provides
  - a dataset
  - a short problem description
- You are to
  - design and create the machine learning algorithm used to solve the problem.
  - write the code in a Jupyter Notebook
  - test and evaluate your solution.
  - save your notebook to Github..

## Mastery Learning

Traditional classes are time-based learning. You spend a specific amount of time on a topic and then you move on to the next topic. For example, in a traditional intro course on Python programming you might cover _for_ loops in week 5, take a quiz on them, and then move on to Python dictionaries in week 6. Suppose you got a 75% on that quiz in week 5. That means that you did not learn 25% of the material. Then perhaps in week 10 you take a test on list comprehensions and get an 80% (you did not master 20% of the material). These gaps in your mastery start adding up, and eventually, in either in some future class or on the job, you hit a wall because your current task requires that you are skilled in areas that you failed to master.

This class doesn't work like that.

In contrast to time-based learning, in mastery learning you stay on the topic until you master it. You work at your own pace. This online class is based on this approach. You stay on a topic until you master it. As I mentioned, the lectures are a set of videos (mostly screencasts) that you can watch at anytime. If the material is easy for you, you can speed up the videos and watch them at 1.5 speed. If you find the material challenging, you can rewatch the videos, google for more information, interact with other learners on the Slack channel, or in a study group.

Obviously, the work-at-your-own pace approach will collide with the end of the semester and there will be some material that you will not cover. The course is designed so that the essential core information is presented first, to enable you to develop solid foundational skills with no gaps.

### Mastery Learning Difficulties

This course is work at your own pace. Other courses you might be taking have fixed deadlines, So, for example, you might have a gnarly project for a programming class due this week and a big operating systems project due next week. It is likely that you will work on those projects since they have immediate deadlines and ignore working on this course. It is human nature. Just block out a regular time each week to work on the course and you will do fine. **Starting on week 8, there is a limit of 2 submissions per week**

## The course material

| Order | Lesson                 |
| -----:|:---------------------- |
| 1     | [JumpStart](jumpstart) |
| 2     | [Labs](labs)           |
| 3     | [Projects](projects)   |

Again, the class is work-at-your-own pace, but I provide a suggested schedule below.

## Week-by-Week

| Week | Date   | Unit        | Topics                                                       |
| ----:|:------ |:----------- |:------------------------------------------------------------ |
| 1    | 22 Aug | Intro       | Intro, Quickstart                                            |
| 2    | 29 Aug | basics      | Numpy, Pandas labs                                           |
| 3    | 5 Sep  | basics      | kNN, sklearn, kNN lab                                        |
| 4    | 12 Sep | basics      | entropy and decision trees                                   |
| 5    | 19 Sep | XGBoost     | working with data                                            |
| 6    | 26 Sep | XGBoost     | bagging and pasting                                          |
| 7    | 3 Oct  | XGBoost     | random forest,                                               |
| 8    | 10 Oct | DNN         | XGBoost - First Project                                      |
| 9    | 17 Oct | DNN         | our first neural network - classifying images                |
| 10   | 24 Oct | DNN         | Neural Network anatomy , a first look at text classification |
| 11   | 31 Oct | DNN         | Introduction to Convolutional Neural Networks (CNN)          |
| 12   | 7 Nov  | DNN         | using pretrained CNNs Project 2                              |
| 13   | 14 Nov | DNN         | CNNs and text classification                                 |
| 14   | 21 Nov | RL          | recurrent neural networks (RNN)                              |
| 15   | 28 Nov | RL          | reinforcement learning                                       |
| 16   | 5 Dec  | FINALS WEEK |                                                              |

Deadlines will be announced in the Slack channel.

## **Required materials**

**[Google Colab Cloud Account](https://colab.research.google.com/notebooks/intro.ipynb)**

**Laptop** 

[Inquiryum’s Machine Learning Fundamentals Course ](http://inquiryum.com/machine-learning)

No purchases (books or equipment) are required

## Slack

Slack is a work chat application that many tech companies use. We are going to be using Slack in a number of ways. If you have a particular programming question you can ask it in a general channel and hopefully you will get an answer or suggestion quickly from either myself or fellow learners.

[Sign up for Slack here](https://join.slack.com/t/newworkspace-9yq7551/shared_invite/zt-1dl3bvb7m-ANjWYb8YCGy5lYjxiB4thA).

## Okay but how do I pass?

Grading is based on a method developed by Professor Lee Sheldon at Indiana University. It is based on obtaining experience points (XP). The number of XP determines what level you are at. You start the class at Level Zero and with 0 XP. The level you obtain at the end of the semester determines your final grade. Here is the chart:

| Level | XP   | Grade |
|:-----:|:----:|:-----:|
| Zero  | 0    | F     |
| One   | 240  | D     |
| Two   | 340  | D+    |
| Three | 450  | C-    |
| Four  | 550  | C     |
| Five  | 650  | C+    |
| Six   | 750  | B-    |
| Seven | 850  | B     |
| Eight | 925  | B+    |
| Nine  | 1000 | A-    |
| Ten   | 1100 | A     |

Here are the ways of earning XP:

- there will be around 15 labs. On average each will be worth 22xp

- there are 5 machine learning projects. On average they are each worth 125xp

## **Accessibility Statement**

The Office of Disability Resources has been designated by the college as the primary office to guide, counsel, and assist students with disabilities. If you receive services through the Office of Disability Resources and require accommodations for this class, make an appointment with me as soon as possible to discuss your approved accommodation needs. Bring your accommodation letter, along with a copy of our class syllabus with you to the appointment. I will hold any information you share with me in strictest confidence unless you give me permission to do otherwise.

If you have not made contact with the Office of Disability Resources and have reasonable accommodation needs, (note taking assistance, extended time for tests, etc.), I will be happy to refer you. The office will require appropriate documentation of disability

## Title IX Statement

Floridal International University's faculty are committed to supporting students and upholding the University’s Policy on Sexual Harassment and Sexual Misconduct. Under Title IX and this Policy, discrimination based upon sex or gender is prohibited. If you experience an incident of sex or gender based discrimination, we encourage you to report it. While you may talk to me, understand that as a “Responsible Employee” of the University, I MUST report to FIU's Title IX Coordinator what you share. If you wish to speak to someone confidentially, please contact the confidential resources described on the []FIU Title IX webpage](https://dei.fiu.edu/crca/title-ix) They can connect you with support services and help you explore your options. You may also seek assistance from FIU’s Title IX Coordinator. 

#### 

## Honor Code Policy

[Computer Science Department Honor Code Policy](https://cas.umw.edu/computerscience/cpsc-department-honor-code-policy/)

The amendments to the Computer Science Department policy are as follows (the numbers related to the numbers in the policy):

1. In the last cell of any submitted Jupyter notebook and at the bottom of any text/markdown file, type _I hereby swear upon my word of honor that I have neither given nor received unauthorized aid on this work_ followed by your name.
2. I am more flexible than the policy "you are _not_ to communicate to others in any way about your assignment." My rule of thumb is What would a responsible adult do on the job? If you have a deadline on the job at a startup and didn't know how to do something, the responsible thing wouldn't be to sit at your workstation just getting more and more frustrated and depressed and missing the deadline. The responsible person would get whatever help was necessary to complete the task. On the other hand, a responsible person wouldn't let someone else do all the work and present it as his own. That would be a violation of this policy. (See the Slack section of the syllabus)
3. Regarding " Remember that _giving_ unauthorized help violates the Honor Code just as much as _receiving_ unauthorized help does." Again, I refer to the 'responsible adult' mentioned above. I would like people to help each other but yet do the work to learn the material. Sharing a complete assignment violates this point, but helping a person debug one cell of a notebook is fine.
4. Sadly, this contradicts what you want to do in your professional life. In your professional life, you want to post solutions to things you figured out as a way of helping people in the community. In fact, we are going to be using some material people posted in this class. However, to prevent plagiarism, you will only post your material to a private github repository. Sorry.
5. You should acknowledge the people that helped you in writing in your submission. For example, "Ann Mulkern helped me with the code to divide the dataset into training and testing sets"
6. All the rest of the conditions of the computer science policy hold as is.

### Avatar names, pseudonyms, noms de plume

During the first week of class you will need to fill out the [Avatar Form](https://forms.gle/GrBgG96H92NQP7kk9) for your avatar name, pseudonym, whatever. This is the name that will appear on the Experience Point Google Spreadsheet that will be viewable by everyone in the class. If you wish to remain anonymous, don’t share your avatar name with anyone. To further protect the anonymity of those who wish to remain anonymous, the spreadsheet will also be populated by fictitious avatar names.
