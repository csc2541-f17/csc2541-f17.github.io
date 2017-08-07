---
id: info
name: Course Information
heading: Course Information
subheading: Course Information&#58; 
image: ""
---

**Instructor:** [Roger Grosse](http://www.cs.toronto.edu/~rgrosse)

**Email:** rgrosse at cs dot toronto dot edu (put CSC2541 in the subject line)

**Lecture:** Friday, 2-4pm, in Bahen 1200

**Office Hours:** Tuesday, 2-4pm, in Pratt 290F (that's the D. L. Pratt Building, not the E. J. Pratt Library!)

### Overview

Over the last 5 years or so, neural networks have driven rapid progress in applications as diverse as vision, language understanding, speech understanding, robotics, chemistry, and game playing. But a major challenge remains: modeling uncertainty, i.e. knowing what one doesn't know. Good models of uncertainty are crucial whenever an algorithm needs to manage exploration, i.e. decide how and when to acquire new information. The topic of uncertainty also rears its head in the context of adversarial examples, a recently discovered phenomenon which originally seemed like a curiosity, but now seems to be a serious security vulnerability for modern ML systems which has so far resisted all attempts to defeat it.

The first half of the course will cover a set of algorithmic tools for modeling uncertainty: Gaussian processes, Bayesian neural nets, and variational inference. We will focus on continuous models and the setting of function approximation, in order to avoid overlap with other iterations of this course (see below). I.e., we will have little if any coverage of generative models or discrete latent variables. The second half of the course will cover applications of uncertainty modeling: neural net sparsification, active learning, black-box optimization, reinforcement learning, and adversarial robustness. 


### Prerequisites

This course is designed to bring students to the current frontier of knowledge on these methods, so that ideally, their course projects can make a novel contribution. A previous background in machine learning such as CSC411 or ECE521 is strongly recommended. Linear algebra, basic multivariate calculus, basics of working with probability, and programming skills are required.

### Relationship with other courses

Since uncertainty is a central topic in machine learning, it's unsurprising that there are lots of courses at UofT focusing on it. Several departments offer core courses focused on probabilistic machine learning, with varying emphases:

* [CSC412, Probabilistic Learning and Reasoning](https://www.cs.toronto.edu/~duvenaud/courses/csc412/index.html)
* [STA414, Statistical Methods for Machine Learning](https://duvenaud.github.io/sta414/)
* [ECE521, Inference Algorithms and Machine Learning](https://ece521.github.io/)

Those courses are all lecture-based, and aim to give broad coverage of probabilistic modeling techniques. They focus on principles which are pretty well understood.

By contrast, CSC2541 is a topics course which aims to bring you to the research frontier on certain topics. Many of the topics have not yet been distilled in an easily accessible form, and a lot of the key experimental findings are still open to multiple interpretations. While the core courses listed above cover a variety of techniques, here we focus on a smaller set (mostly Gaussian processes, Bayesian neural nets, and variational inference) and look at how they can be applied in situations that depend on accurate uncertainty modeling.

CSC2541 is a topics course which is offered repeatedly but with different topics. I'm only planning to offer this version of the course once. David Duvenaud recently taught a [version of 2541](https://www.cs.toronto.edu/~duvenaud/courses/csc2541/index.html) focused on generative models, and this coming winter, he'll be teaching a topics course focused on learning discrete structure. I've tried to minimize the overlap with those courses, so if you've taken 2541 before, you should be able to take it again without being bored. Hence, this course doesn't have much material on generative models or discrete latent variables. I think there are roughly 2 weeks of overlap with last year's iteration of 2541: variational inference and model-based reinforcement learning.

### Tentative course structure

The course will roughly follow the following structure, but the details are subject to change.

After the first two lectures, each week a different student, or pair of students, will present on an aspect of these methods, using a couple of papers as reference. I'll provide guidance about the content of these presentations.

In-class discussion will center around:

* Understanding the strengths and weaknesses of these methods.
* Understanding the relationships between these methods, and with previous approaches.
* Extensions or applications of these methods.
* Experiments that might better illuminate their properties.

The hope is that these discussions will lead to actual research papers, or resources that will help others understand these approaches.

Grades will be based on:

* Class presentations - 20%
* Project proposal - 20% - Due Oct 14th
* Project presentation - 20% - Nov 18th and 25th
* Project report and code - 40% - Dec 10th

### Project

The project will follow roughly the following structure, but the details are subject to change.

Students can work on projects individually, in pairs, or even in triplets. The grade will depend on the ideas, how well you present them in the report, how clearly you position your work relative to existing literature, how illuminating your experiments are, and well-supported your conclusions are.

Each group of students will write a short (around 2 pages) research project proposal, which ideally will be structured similarly to a standard paper. It should include a description of a minimum viable project, some nice-to-haves if time allows, and a short review of related work. You don't have to do what your project proposal says - the point of the proposal is mainly to have a plan and to make it easy for me to give you feedback.

Towards the end of the course everyone will present their project in a short, roughly 5 minute, presentation.

At the end of the class you'll hand in a project report (around 4 to 8 pages), ideally in the format of a machine learning conference paper such as NIPS.

