---
layout: page
permalink: /fall2020/project/
title: Course Project
description: Guidelines and suggestions for course projects
---

Your class project is an opportunity for you to explore an interesting problem in the context of a real-world data sets.
Projects should be done in teams of three students.
Each project will be assigned a TA as a project consultant/mentor; instructors and TAs will consult with you on your ideas, but of course the final responsibility to define and execute an interesting piece of work is yours. Your project will be worth 46% of your final class grade, and will have 4 deliverables:

1. **Proposal** : 2 pages excluding references (10%)
2. **Midway Report** : 5 pages excluding references (20%)
3. **Presentation** : poster presentation (20%)
4. **Final Report** : 8 pages excluding references (50%)

All write-ups should use the [ICML style](https://media.neurips.cc/Conferences/ICML2019/Styles/icml2019_style.zip).

***

* (The list will be replaced with the table of contents.)
{:toc}

***

### Team Formation

You are responsible for forming project teams of 3-4 people.
In some cases, we will also accept teams of 2, but a 3-4-person group is preferred.
Once you have formed your group, please send one email per team to the class instructor list with the names of all team members.
If you have trouble forming a group, please send us an email and we will help you find project partners.

### Dataset Preferences

The dataset preferences are due at **11:59 PM on Tuesday, Sept 8th**, and must be submitted via [Gradescope](https://www.gradescope.com/courses/36025).

### Project Pre-proposal

You must turn in a brief project proposal that provides an overview of your idea and also contains a brief survey of related work on the topic.
We will provide a list of suggested project ideas for you to choose from, though you may discuss other project ideas with us, whether applied or theoretical.
Note that even though you can use datasets you have used before, **you cannot use work that you started prior to this class as your project**.

Proposals should be approximately **two pages long**, and should include the following information:

- Project title and list of group members.
- Overview of project idea. This should be approximately half a page long.
- A short literature survey of 4 or more relevant papers. The literature review should take up approximately one page.
- Description of potential data sets to use for the experiments.
- Plan of activities, including what you plan to complete by the midway report and how you plan to divide up the work.

The grading breakdown for the proposal is as follows:

- 40% for clear and concise description of proposed method
- 40% for literature survey that covers at least 4 relevant papers
- 10% for plan of activities
- 10% for quality of writing

The project proposal will be due at **11:59 PM on Wednesday, Sept 16th**, and should be submitted via [Gradescope](https://www.gradescope.com/courses/36025).

### First Assignment

The project midterm report will be due at **11:59 PM on Sunday, Oct 11th**, and must be submitted via [Gradescope](https://www.gradescope.com/courses/36025).

### Midterm Assignment

The midterm report will serve as a check-point at the halfway mark of your project.
It should be about **5 pages long**, and should be formatted like a conference paper, with the following sections: introduction, background & related work, methods, experiments, conclusion.
The introduction and related work sections should be in their final form; the section on the proposed methods should be almost finished; the sections on the experiments and conclusions will have the results you have obtained, perhaps with place-holders for the results you plan/hope to obtain.

The grading breakdown for the midterm report is as follows:

- 20% for introduction and literature survey
- 40% for proposed method
- 20% for the design of upcoming experiments and revised plan of activities (in an appendix, please show the old and new activity plans)
- 10% for data collection and preliminary results
- 10% for quality of writing

The project midterm report will be due at **11:59 PM on Sunday, Nov 14th**, and must be submitted via [Gradescope](https://www.gradescope.com/courses/36025).

### Final Assignment

Your final report is expected to be **8 pages excluding references**, in accordance with the length requirements for an ICML paper. It should have roughly the following format:

- Introduction: problem definition and motivation
- Background & Related Work: background info and literature survey
- Methods
-- Overview of your proposed method
-- Intuition on why should it be better than the state of the art
-- Details of models and algorithms that you developed
- Experiments
-- Description of your testbed and a list of questions your experiments are designed to answer
-- Details of the experiments and results
- Conclusion: discussion and future work

The grading breakdown for the final report is as follows:

- 10% for introduction and literature survey
- 30% for proposed method (soundness and originality)
- 30% for correctness, completeness, and difficulty of experiments and figures
- 10% for empirical and theoretical analysis of results and methods
- 20% for quality of writing (clarity, organization, flow, etc.)

The project final report will be due at **11:59 PM on Sunday, Dec 13th** (tentative), and must be submitted via [Gradescope](https://www.gradescope.com/courses/36025).

### Presentation

All project teams will present their work at the end of the semester.
We will have a 2-3-hour long poster session held in NSH atrium on April 30.
Each team should prepare a poster (similar in style to a conference poster) and present it during the allocated time.
If applicable, live demonstrations of your software are highly encouraged.

## Project Suggestions

If you are interested in a particular project, please contact the respective *contact person* to get further ideas or details.
We may add more project suggestions down the road.

***

#### Deep generative models for video, text, and audio generation
**Contact person:** [Paul Liang](https://www.cs.cmu.edu/~pliang/){:target="\_blank"}

Generative models are important for probabilistic reasoning within graphical models. Recent advancements in parameterizing these models using deep neural networks and optimizating using gradient-based techniques have enabled large scale modeling of high-dimensional, real-world data. Deep generative models have been successfully been applied for image, text, and audio generation.
You can explore new applications of deep generative models, improve the theoretical understanding and empirical optimization of deep generative models, design metrics for improved evaluation of deep generative models, and other new directions. 

**References:**

1. [IJCAI Tutorial on Deep Generative Models by Aditya Grover and Stefano Ermon](https://ermongroup.github.io/generative-models/){:target="\_blank"}.
2. [ICML Workshop on Deep Generative Models](https://sites.google.com/view/tadgm/home){:target="\_blank"}.
3. Brock et al., [Large Scale GAN Training for High Fidelity Natural Image Synthesis](https://arxiv.org/abs/1809.11096){:target="\_blank"}. ICLR 2019.
4. Hu et al., [Toward Controlled Generation of Text](https://arxiv.org/pdf/1703.00955.pdf){:target="\_blank"}. ICML 2017.
5. van den Oord et al., [WaveNet: A Generative Model for Raw Audio](https://arxiv.org/abs/1609.03499){:target="\_blank"}. arXiv 2016.

***

#### Deep generative models for disentangled representation learning
**Contact person:** [Paul Liang](https://www.cs.cmu.edu/~pliang/){:target="\_blank"}

Disentangled representation learning involves learning a set of latent variables that each capture individual factors of variation in the data.
For example, when we learn a generative model for shapes, it would be ideal if each latent variables would correspond to the shapes pose, shadow, rotations, lighting etc.
This improves interpretability of our learned representations and allows flexible generation from latent variables.
You can explore new methods of learning disentangled representations in both supervised and unsupervised settings (i.e. whether information about pose, shadow, rotations are given or not), design metrics for improved evaluation of disentanglement in models, as well as new applications of disentangled representation learning to improve performance on NLP, vision, and multimodal tasks.

**References:**

1. [Papers in NIPS 2017 workshop on disentangled representation learning](https://sites.google.com/view/disentanglenips2017){:target="\_blank"}.
2. Denton et al., [Unsupervised Learning of Disentangled Representations from Video](https://papers.nips.cc/paper/7028-unsupervised-learning-of-disentangled-representations-from-video){:target="\_blank"}. NIPS 2017.
3. Chen et al., [InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets](https://arxiv.org/abs/1606.03657){:target="\_blank"}. NIPS 2016.
4. Kulkarni et al., [Deep Convolutional Inverse Graphics Network](https://arxiv.org/abs/1503.03167){:target="\_blank"}. NIPS 2015.

***
