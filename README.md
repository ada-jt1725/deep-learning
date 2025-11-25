# Deep Learning Module 2025

This repository and README contains relevant information regarding the Deep Learning module, please read it all carefully. 

The machine learning framework we will use is [PyTorch](https://pytorch.org/).

# Table of contents
1. [Objectives](#objectives)
2. [Course contents](#coursecontents)
3. [Assessments](#assessments)
4. [Recap sessions and unassessed quizzes](#q&a)
5. [Primer materials and bibliography](#primer)
6. [Lecture materials](#lectures)
7. [Google Colab](#colab)
8. [Teaching team](#team)
9. [Learning outcomes](#outcomes)


## Objectives <a name="objectives"></a>

The objective of this module is to equip you with a solid foundation to understand the basic principles of deep learning (DL).

Despite the humongous size of the deep-learning research landscape, and the impossibility to cover all the topics it encompasses, 
this course will provide you with all the fundamental concepts, building blocks, and mathematical methods that are used in the majority 
of modern complex applications, preparing you to develop your professional careers in this field.

## Course contents <a name="coursecontents"></a>

During the course we will cover the following topics:

1. Introduction to Deep Learning
2. Basic DL concepts (backprop, regularisation, etc).
3. PyTorch primer
4. Feed-forward Networks (FFNs)
5. Convolutional neural networks (CNNs)
6. Probability for DL
7. Generative models:
	- Variational autoencoders (VAEs)
	- Generative adversarial networks (GANs)
	- Diffusion models
8. Recurrent neural networks (RNNs) and long short-term memory networks (LSTMs)
10. Transformers
11. Other DL methods, architectures, and strategies (informative session, **not assessed**):

The contents will be delivered using jupyter notebooks that contain both theory and practical implementations.

Most days will be structured as follows:

| time  | session |
|---------------|-----------------------------------------------------------------------|
| 9:00h-12:00h  | theory and implementation |
| 14:00h-17:00h | exercise session |


with a few exceptions:

- On Wednesday afternoons we will not have any sessions.

- Other dates that will not follow the morning-lecture/afternoon-exercise structure will be:

| session  | activity |
|---------------|-----------------------------------------------------------------------|
| Thursday 11 Dec (morning) | Q&A and review session before coursework |
| Thursday 11 Dec (afternoon) & Friday 12 Dec (all day) | coursework release and working time |


## Assessments <a name="assessments"></a>

The module assessment is based on one coursework.

| **COURSEWORK** | **Date and time** |
| :------------------ | :---: |
| *Release* | Thursday 11 Dec 14:00h |
| *Due (deadline)* | Friday 12 Dec 18:00h |


## Recap sessions and unassessed quizzes <a name="q&a"></a>

We will have three recap sessions, one at the end of each teaching block. At the beginning of each of these sessions, 
we will conduct an **unassessed** quiz that will help you understand what concepts might need more attention.

| **RECAP & QUIZ 1** | **Date and time** |
| :------------------ | :---: |
| *Theory recap & quiz* | Monday 1 Dec 09:00-12:00 |
| *Exercise recap* | Monday 1 Dec 14:00-17:00 |


| **RECAP & QUIZ 2** | **Date and time** |
| :------------------ | :---: |
| *Theory recap & quiz* | Friday 5 Dec 09:00-12:00 |
| *Exercise recap* | Friday 5 Dec 14:00-17:00 |


| **RECAP & QUIZ 3** | **Date and time** |
| :------------------ | :---: |
| *Theory recap & quiz* | Thursday 11 Dec 09:00-12:00 |


## Primer materials and bibliography <a name="primer"></a>

It is NOT mandatory to read (or view) any of the materials in this section.

### Introductory videos

To help prepare for the course, it is recommended to watch these four short (15-20 mins) videos which provide a good introduction to Machine Learning:

1. [But what is a Neural Network? | Deep learning, chapter 1](https://www.youtube.com/watch?v=aircAruvnKk)  
2. [Gradient descent, how neural networks learn | Deep learning, chapter 2](https://www.youtube.com/watch?v=IHZwWFHWa-w&t=11s)   
3. [What is backpropagation really doing? | Deep learning, chapter 3](https://www.youtube.com/watch?v=Ilg3gGewQ5U)  
4. [Backpropagation calculus | Deep learning, chapter 4](https://www.youtube.com/watch?v=tIeHLnjs5U8)  

Probability introductory videos:

1. [Binomial distribution](https://www.youtube.com/watch?v=8idr1WZ1A7Q&list=RDCMUCYO_jab_esuFRV4b17AJtAw&index=2)
2. [Normal distribution](https://www.khanacademy.org/math/statistics-probability/modeling-distributions-of-data/more-on-normal-distributions/v/introduction-to-the-normal-distribution) 
3. [Bayes theorem](https://www.youtube.com/watch?v=HZGCoVF3YvM) 

### Bibliography

- [Pattern recognition and Deep Learning (Christopher M. Bishop)](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
- [Deep Learning (Ian Goodfellow, Yoshua Bengio, Aaron Courville)](https://www.deeplearningbook.org/)


## Lecture materials <a name="lectures"></a>

The table below contains the course materials and their scheduled dates. Lecture slides/notebooks will be released two days before the start of the lectures. Two notebooks will be provided for each session (morning or afternoon):

- **Codealong**/**Exercises notebook**: Template with some code provided and empty blocks to work on the implementation during the lecture (**Codealong**) or during the afternoon exercises (**Exercise**).
- **Solutions notebook**: Practical/Exercise notebook completed with model solutions for the tasks done during the lecture or to be completed during the afternoon exercises.

We encourage you to work on the **Codealong/Exercise notebook** and try to implement the tasks proposed during the lectures, but at the same time we want to provide the delivery of the module contents in a complete format to accomodate 
different learning styles. In particular, some people prefer to focus their attention on the lecture before attempting to implement code themselves, and this is why we provide solutions beforehand.

*\[The numbers in the table (01:, 02:, etc), notebook names, and other materials, corresponds to the day of the course (from 01 to 15).\]*


| Session   |   Date <br> Time | Codealong/Exercises | Solutions     |
|-----------|:-------------------|-----------------------|----------------------------|
| Day01 morning - **Intro, Colab, and FFNs**     |   Nov 24 <br> 09:00-12:00  |  [lecture](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day01-Intro_DL_FFNs_and_Colab/Day01-Intro_DL_FFNs_and_Colab_morning_codealong.ipynb) <br> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day01-Intro_DL_FFNs_and_Colab/Day01-Intro_DL_FFNs_and_Colab_morning_codealong.ipynb)                     |     [solutions](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day01-Intro_DL_FFNs_and_Colab/Day01-Intro_DL_FFNs_and_Colab_morning_solutions.ipynb) <br> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day01-Intro_DL_FFNs_and_Colab/Day01-Intro_DL_FFNs_and_Colab_morning_solutions.ipynb)       | 
| Day01 afternoon - **Intro, Colab, and FFNs**   |   Nov 24 <br> 14:00-17:00  |  [exercises](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day01-Intro_DL_FFNs_and_Colab/Day01-Intro_DL_FFNs_and_Colab_afternoon_exercises.ipynb) <br> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day01-Intro_DL_FFNs_and_Colab/Day01-Intro_DL_FFNs_and_Colab_afternoon_exercises.ipynb)                     | [solutions](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day01-Intro_DL_FFNs_and_Colab/Day01-Intro_DL_FFNs_and_Colab_afternoon_solutions.ipynb) <br> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day01-Intro_DL_FFNs_and_Colab/Day01-Intro_DL_FFNs_and_Colab_afternoon_solutions.ipynb)| 
||
| Day02 morning - **DL_concepts**   |   Nov 25 <br> 09:00-12:00  |  [lecture](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-DL_concepts_morning_codealong.ipynb) <br> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-DL_concepts_morning_codealong.ipynb)                     | [solutions](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-DL_concepts_morning_solutions.ipynb) <br> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-DL_concepts_morning_solutions.ipynb)| 
| Day02 afternoon - **PyTorch**     |   Nov 25 <br> 14:00-17:00  |    [lecture](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-Intro_to_Pytorch_afternoon_codealong.ipynb) <br>  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-Intro_to_Pytorch_afternoon_codealong.ipynb)   |      [solutions](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-Intro_to_Pytorch_afternoon_solutions.ipynb) <br>  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-Intro_to_Pytorch_afternoon_solutions.ipynb)    | 
||
| Day03 morning - **PyTorch**     |   Nov 26 <br> 09:00-12:00  |    [exercises](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day03-PyTorch/Day03-Intro_to_Pytorch_morning_exercises.ipynb) <br>  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day03-PyTorch/Day03-Intro_to_Pytorch_morning_exercises.ipynb)   |      [solutions](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day03-PyTorch/Day03-Intro_to_Pytorch_morning_solutions.ipynb) <br>  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day03-PyTorch/Day03-Intro_to_Pytorch_morning_solutions.ipynb)    | 
| Day03 *additional* - **DL_concepts**   |   Nov 26 <br> not taught  |  [exercises](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-DL_concepts_additional_exercises.ipynb) <br> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-DL_concepts_additional_exercises.ipynb)                     | [solutions](https://github.com/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-DL_concepts_additional_solutions.ipynb) <br> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025/blob/master/Day02-DL_concepts_and_PyTorch/Day02-DL_concepts_additional_solutions.ipynb)| 
||
| Day04 morning - **CNNs (1)**    |   Nov 27 <br> 09:00-12:00  |    [lecture](https://github.com/ese-ada-lovelace-2025/DL_Module_2025_Teaching/blob/master/Day04-CNNs(1)/Day04-CNNs(1)_morning_codealong.ipynb) <br>  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025_Teaching/blob/master/Day04-CNNs(1)/Day04-CNNs(1)_morning_codealong.ipynb)   |      [solutions](https://github.com/ese-ada-lovelace-2025/DL_Module_2025_Teaching/blob/master/Day04-CNNs(1)/Day04-CNNs(1)_morning_solutions.ipynb) <br>  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025_Teaching/blob/master/Day04-CNNs(1)/Day04-CNNs(1)_morning_solutions.ipynb)     | 
| Day04 afternoon - **CNNs (1)**  |   Nov 27 <br> 14:00-17:00  |   [exercises](https://github.com/ese-ada-lovelace-2025/DL_Module_2025_Teaching/blob/master/Day04-CNNs(1)/Day04-CNNs(1)_afternoon_exercises.ipynb) <br>  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025_Teaching/blob/master/Day04-CNNs(1)/Day04-CNNs(1)_afternoon_exercises.ipynb)   |      [solutions](https://github.com/ese-ada-lovelace-2025/DL_Module_2025_Teaching/blob/master/Day04-CNNs(1)/Day04-CNNs(1)_afternoon_solutions.ipynb) <br>  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ese-ada-lovelace-2025/DL_Module_2025_Teaching/blob/master/Day04-CNNs(1)/Day04-CNNs(1)_afternoon_solutions.ipynb)     | 
||
| Day05 morning - **CNNs (2)**    |   Nov 28 <br> 09:00-12:00  |     <hr>     |     <hr>        |
| Day05 afternoon - **CNNs (2)**  |   Nov 28 <br> 14:00-17:00  |     <hr>     |     <hr>        |
||
| Day06 morning - **Recap (1) and Quiz (1)**    |   Dec 1 <br> 09:00-12:00  |     <hr>     |     <hr>        |
| Day06 afternoon - **Excercises Recap (1)**    |   Dec 1 <br> 14:00-17:00  |       <hr>       |   <hr>       |
||
| Day07 morning - **VAEs**    |   Dec 2 <br> 09:00-12:00  |     <hr>     |     <hr>        |
| Day07 afternoon - **VAEs**    |   Dec 2 <br> 14:00-17:00  |     <hr>     |     <hr>        |
||
| Day08 morning - **GANs**    |   Dec 3 <br> 09:00-12:00  |     <hr>     |     <hr>        |
| Day08 *additional* - **GANs**   | Dec 3 <br> not taught |     <hr>     |     <hr>        |
||
| Day09 morning - **Diffusion Models**    |  Dec 4 <br> 09:00-12:00  |     <hr>     |     <hr>        |
| Day09 afternoon - **Diffusion Models**    |   Dec 4 <br> 14:00-17:00  |     <hr>     |     <hr>        |
||
| Day10 morning - **Recap (2) and Quiz (2)**    |   Dec 5 <br> 09:00-12:00  |     <hr>     |     <hr>        |
| Day10 afternoon - **Excercises Recap (2)**    |   Dec 5 <br> 14:00-17:00  |       <hr>       |   <hr>       |
||
| Day11 morning - **RNNs & LSTMs**    |   Dec 8 <br> 09:00-12:00  |     <hr>     |     <hr>        |
| Day11 afternoon - **Transformers primer**    |   Dec 8 <br> 14:00-17:00  |     <hr>     |     <hr>        |
||
| Day12 morning - **Transformers**  |   Dec 9 <br> 09:00-12:00  |     <hr>     |     <hr>        |
| Day12 afternoon - **Transformers** |  Dec 9 <br> 14:00-17:00 |     <hr>     |     <hr>        |
||
| Day13 morning - **Latest developments**  |   Dec 10 <br> 09:00-12:00  |     <hr>     |     <hr>        |
| Day13 *additional* - **Deep RL** |  Dec 10 <br> not taught |     <hr>     |     <hr>        |
||
| Day14 morning - **Recap (3) and Quiz (3)**    |   Dec 11 <br> 09:00-12:00  |     <hr>     |     <hr>        |
| Day14 afternoon - **Coursework Release**    |   Dec 11 <br> 14:00  |      <hr>          |     <hr>      |
||
| Day15 all day - **Coursework**    |   Dec 12 <br> ***deadline 18:00h***  |     <hr>     |     <hr>        |


###### The links in the table will become active as we progress during the course.


## Google Colab <a name="colab"></a>

All the coding will be done using Google Colab. It is also possible to use your own computer and run the jupyter notebooks locally, if you prefer, but limited support will be available to help you set up your local system.

There will be an introductory session on how to use Google Colab on Day 01 (24 Nov). We will also provide a Google Colab Pro licence for each of you on Day 13 (10 Dec), for that we will have a live session during class to set up the Colab Pro with provided virtual credit cards.

#### **Do not buy any Colab Pro license as they will provided in class**

#### **A new google account will be created on the first day of the module, which will be a dedicated account for the course. Do NOT use your existing google account for this because the payment system provided could be extended to any personal payment details you have in your personal account**


## Teaching team <a name="team"></a>

- Carlos Cueto [(email)](mailto:c.cueto@imperial.ac.uk) - ***module coordinator***
- Debbie Pelacani Cruz
- Ben Moseley
- Jack Ma
- Wenhao Zheng
- Janice Zhao
- Kun Wang
- Di Xu
- Ida Caspari
- Weihao Lyu
- Yixuan Jiang
- Davide Staub


## Learning outcomes <a name="outcomes"></a>

#### Over the next three weeks, you will be able to go from here:

<img src="https://imgs.xkcd.com/comics/machine_learning.png" alt="drawing" width="300"/> <br>
[XKCD 1838](https://xkcd.com/1838/)

#### to understanding complex network architectures, how and why they work, and when to use them:

<img src="https://miro.medium.com/max/407/1*o0pS0LbXVw7i41vSISrw1A.png" alt="drawing" width="300"/> <br>
[Transformers](https://arxiv.org/pdf/1706.03762.pdf)








