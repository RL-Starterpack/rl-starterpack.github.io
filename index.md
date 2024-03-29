## Authors

Alexander Kuhnle, Miguel Aroca-Ouellette, Anindya Basu, Murat Sensoy, John Reid, Dell Zhang

_{alexander.kuhnle, miguel.aroca, anindya.basu, murat.sensoy, john.reid, dell.zhang}[at]blueprism[dot]com_

![Logo](bp_ai_labs_logo.png)

## Description

There is strong interest in leveraging reinforcement learning (RL) for information retrieval (IR) applications including search, recommendation, and advertising. Just in 2020, the term "reinforcement learning" was mentioned in more than 60 different papers published by ACM SIGIR. It has also been reported that Internet companies like Google and Alibaba have started to gain competitive advantages from their RL-based search and recommendation engines. This full-day tutorial gives IR researchers and practitioners who have no or little experience with RL the opportunity to learn about the fundamentals of modern RL in a practical hands-on setting. Furthermore, some representative applications of RL in IR systems will be introduced and discussed. By attending this tutorial, the participants will acquire a good knowledge of modern RL concepts and standard algorithms such as REINFORCE and DQN. This knowledge will help them better understand some of the latest IR publications involving RL, as well as prepare them to tackle their own practical IR problems using RL techniques and tools.

This tutorial is featured in prestigious conferences [SIGIR-2021](https://sigir.org/sigir2021/tutorials/), [ECIR-2021](https://www.ecir2021.eu/tutorials/) and [SearchSolutions-2020](https://irsg.bcs.org/SearchSolutions/2020/ss2020tutorials.php).

## Materials

The complete repository for this tutorial can be found at [RL Starterpack](https://github.com/RL-Starterpack/rl-starterpack/).

### Quick Links:

##### Presentation Slides
* [RL Slides](https://github.com/RL-Starterpack/rl-starterpack/blob/main/slides/RL_Tutorial.pdf)
* [RL for IR Slides](https://github.com/RL-Starterpack/rl-starterpack/blob/main/slides/RL_Tutorial_IR.pdf)

##### Hands-on Exercises
* [Bandit Exercise](https://github.com/RL-Starterpack/rl-starterpack/blob/main/exercises/Bandits.ipynb)
* [TQL Exercise](https://github.com/RL-Starterpack/rl-starterpack/blob/main/exercises/TQL.ipynb)
* [DQN Exercise](https://github.com/RL-Starterpack/rl-starterpack/blob/main/exercises/DQN.ipynb)
* [PG Exercise](https://github.com/RL-Starterpack/rl-starterpack/blob/main/exercises/PG.ipynb)
* [AC Exercise](https://github.com/RL-Starterpack/rl-starterpack/blob/main/exercises/AC.ipynb)

## Schedule

As SIGIR 2021 is pre-recorded, once you have access to the tutorial video you can use the following timestamps to quickly navigate between sections:

* 	[0:00:00] Intro
* 	[0:05:18] RL Basics
* 	[0:14:50] Multi-armed Bandits
* 	[0:38:40] Tabular Q-Learning
* 	[1:00:37] Deep Q-Learning
* 	[1:15:23] IR applications using DQN
* 	[1:42:36] Policy Gradient (REINFORCE)
* 	[1:54:58] IR applications using REINFORCE
* 	[2:50:26] Actor-Critic
* 	[3:07:34] IR applications using Actor-Critic
* 	[3:21:09] Recent developments & outlook for research


## Contact

Questions? Feedback? Please reach out to one of the tutorial organisers using the emails listed at the top of this page.

## Additional Resources

##### Introductory Materials

- [Spinning Up in Deep RL (OpenAI)](https://spinningup.openai.com/en/latest/index.html)
- [Deep Reinforcement Learning Course (Thomas Simonini)](https://simoninithomas.github.io/Deep_reinforcement_learning_Course/)
- [Simple Reinforcement Learning with Tensorflow (Arthur Juliani)](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0)
- [Deep Reinforcement Learning: Pong from Pixels (Andrej Karpathy)](http://karpathy.github.io/2016/05/31/rl/)
- [An Outsider's Tour of Reinforcement Learning (Ben Recht)](http://www.argmin.net/2018/06/25/outsider-rl/)
- Lilian Weng:
    - [A (Long) Peek into Reinforcement Learning](https://lilianweng.github.io/lil-log/2018/02/19/a-long-peek-into-reinforcement-learning.html)
    - [Policy Gradient Algorithms](https://lilianweng.github.io/lil-log/2018/04/08/policy-gradient-algorithms.html)
    - [Implementing Deep Reinforcement Learning Models with Tensorflow + OpenAI Gym](https://lilianweng.github.io/lil-log/2018/05/05/implementing-deep-reinforcement-learning-models.html)
    - and more...

##### Critical Voices

- [Deep Reinforcement Learning Doesn't Work Yet (Alex Irpan)](https://www.alexirpan.com/2018/02/14/rl-hard.html)
- [The Policy of Truth (Ben Recht)](http://www.argmin.net/2018/02/20/reinforce/)
- [Lessons Learned Reproducing a Deep Reinforcement Learning Paper (Amid Fish)](http://amid.fish/reproducing-deep-rl)

##### Books

- [Reinforcement Learning - An Introduction (Sutton & Barto, 2018)](http://incompleteideas.net/book/RLbook2020.pdf)
- [An Introduction to Deep Reinforcement Learning (Francois-Lavet et al., 30 Nov 2018)](https://arxiv.org/abs/1811.12560)

##### Papers
- [DRN: A Deep Reinforcement Learning Framework for News Recommendation (WWW'18)](https://dl.acm.org/doi/10.1145/3178876.3185994)
- [Recommendations with Negative Feedback via Pairwise Deep Reinforcement Learning (KDD'18)](https://dl.acm.org/doi/10.1145/3219819.3219886)
- [Jointly Learning to Recommend and Advertise (KDD'20)](https://dl.acm.org/doi/10.1145/3394486.3403384)
- [Reinforcement Learning to Rank with Markov Decision Process (SIGIR'17)](https://dl.acm.org/doi/10.1145/3077136.3080685)
- [Adapting Markov Decision Process for Search Result Diversification (SIGIR'17)](https://dl.acm.org/doi/10.1145/3077136.3080775)
- [Multi Page Search with Reinforcement Learning to Rank (ICTIR'18)](https://dl.acm.org/doi/10.1145/3234944.3234977)
- [Reinforcement Learning to Rank with Pairwise Policy Gradient (SIGIR'20)](https://dl.acm.org/doi/10.1145/3397271.3401148)
- [A Reinforcement Learning Framework for Relevance Feedback (SIGIR'20)](https://dl.acm.org/doi/10.1145/3397271.3401099)
- [IRGAN: A Minimax Game for Unifying Generative and Discriminative Information Retrieval Models (SIGIR'17)](https://dl.acm.org/doi/10.1145/3077136.3080786)
- [Top-K Off-Policy Correction for a REINFORCE Recommender System (WSDM'19)](https://dl.acm.org/doi/10.1145/3289600.3290999)
- [Off-policy Learning in Two-stage Recommender Systems (WWW'20)](https://dl.acm.org/doi/10.1145/3366423.3380130)
- [Reinforcement Recommendation with User Multi-aspect Preference (WWW'21)](https://dl.acm.org/doi/10.1145/3442381.3449846)
- [Self-Supervised Reinforcement Learning for Recommender Systems (SIGIR'20)](https://dl.acm.org/doi/10.1145/3397271.3401147)

##### Workshops
- [DRL4IR Workshop at SIGIR](https://drl4ir.github.io/)
