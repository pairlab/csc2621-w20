---
id: calendar
name: Calendar
heading: Calendar
subheading: Calendar&#58;
image: ""
---

This a draft schedule and is subject to change.  

|Schedule           | Broad Area                | Reading List | Slides
|-----------|------------------------|---------|-----
|**Week 1 Jan 7** | Course Overview & Intro to RL	|[Human Learning in Atari](https://core.ac.uk/download/pdf/141473125.pdf)|[Lecture 1 Slides (Animesh Garg)](assets/slides/lec1.pdf)|
||||[Presentation Template Slides](assets/slides/template.pptx)|
|**Week 2 Jan 14** | 	Imitation Learning: supervised	|**Core readings**||
|||[An Invitation To Imitation](https://www.ri.cmu.edu/publications/an-invitation-to-imitation/),<br />[Dagger: A reduction of imitation learning and structured prediction to no-regret online learning](https://arxiv.org/pdf/1011.0686.pdf)|[Lecture 2 Slides (Animesh Garg)](assets/slides/lec2.pdf)
|||[End to End Learning for Self-Driving Cars](https://arxiv.org/abs/1604.07316)| [Slides (Dylan Turpin)](assets/slides/lec2_endtoend.pdf)
|||[Behavioral Cloning from Observation](https://www.ijcai.org/proceedings/2018/0687.pdf)| [Slides (Tingwu Wang)](assets/slides/lec2_behaviorcloning.pdf)|
|||**Optional**|
|||[ALVINN: An autonomous land vehicle in a neural network](https://papers.nips.cc/paper/95-alvinn-an-autonomous-land-vehicle-in-a-neural-network.pdf)|
|||[ChauffeurNet: Learning to Drive by Imitating the Best and Synthesizing the Worst](https://arxiv.org/abs/1812.03079)|
|||[Apprenticeship Learning via Inverse Reinforcement Learning](https://ai.stanford.edu/~ang/papers/icml04-apprentice.pdf)|
|**Week 3 Jan 21** | 	Policy Gradients	|**Core readings**||
|||[Policy Gradient Methods for Reinforcement Learning with Function Approximation](https://papers.nips.cc/paper/1713-policy-gradient-methods-for-reinforcement-learning-with-function-approximation.pdf)|[Slides (Silviu Pitis)](assets/slides/lec3_pgm.pdf)|
|||[Trust region policy optimization: deep RL with natural policy gradient and adaptive step size](https://arxiv.org/pdf/1502.05477) (TRPO)||
|||[Continuous control with deep reinforcement learning](https://arxiv.org/abs/1509.02971) (DDPG)||
|||[Variance Reduction for Policy Gradient with Action-Dependent Factorized Baselines](https://arxiv.org/pdf/1803.07246.pdf)|[Slides (Animesh Garg)](assets/slides/lec3.pdf)|
|||**Optional**|
|||SB Ch: 13||
|||[Reinforcement learning of motor skills with policy gradients](https://www.sciencedirect.com/science/article/pii/S0893608008000701)|
|**Week 4 Jan 28** | 	Actor-Critic Methods+ Value Based methods	| **Core readings**||
|||[Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/abs/1602.01783)|[Slides (Adelin Travers)](assets/slides/lec4_actorcritic.pdf)|
|||[Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor](https://arxiv.org/abs/1801.01290),<br />[Soft Actor-Critic Algorithms and Applications](https://arxiv.org/abs/1812.05905)|[Slides (Zikun Chen, Minghan Li)](assets/slides/lec4_sac.pdf)|
|||[IMPALA: Scalable Distributed Deep-RL with Importance Weighted Actor-Learner Architectures](https://arxiv.org/abs/1802.01561)||
|||[High-confidence error estimates for learned value functions](https://arxiv.org/abs/1808.09127)||
|||**Optional**||
|||SB Ch: 13||
|**Jan 28** | 	(before class)	| **<span style="color:#b32425">Project Proposal Due</span>**|
|**Week 5 Feb 4** | Q-Value based RL| **Core papers**||
|||[Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602) (DQN)||
|||[Deep Reinforcement Learning with Double Q-learning](https://arxiv.org/abs/1509.06461) (Double DQN),<br />[Dueling Network Architectures for Deep Reinforcement Learning](https://arxiv.org/abs/1511.06581) (Dueling DQN)|[Slides (Haoping Xu)](assets/slides/lec5_ddqn.pdf)|
|||[QT-Opt: Scalable Deep Reinforcement Learning for Vision-Based Robotic Manipulation](https://arxiv.org/abs/1806.10293) (Qt-Opt), <br />[Quantile QT-Opt for Risk-Aware Vision-Based Robotic Grasping](https://arxiv.org/abs/1910.02787)| [Slides (Vismay Modi)](assets/slides/lec5_qtopt.pdf)|
|||[Bridging the Gap Between Value and Policy Based Reinforcement Learning](https://arxiv.org/abs/1702.08892) (PCL), <br />[Trust-PCL: An Off-Policy Trust Region Method for Continuous Control](https://arxiv.org/pdf/1707.01891.pdf)|[Slides (Michael Pham-Hung)](assets/slides/lec5_pcl.pdf)|
|||[Rainbow - Combining Improvements in Deep Reinforcement Learning](https://arxiv.org/abs/1710.02298),<br />[Impala](https://arxiv.org/abs/1802.01561)|[Slides (Mohan Zhang)](assets/slides/lec5_rainbow.pdf)|
|||**Optional**||
|||[Rainbow is all you need](https://github.com/Curt-Park/rainbow-is-all-you-need) (step-by-step Rainbow tutorial)||
|||[Addressing Function Approximation Error in Actor-Critic Methods](https://arxiv.org/abs/1802.09477) (TD3)||
|||[Prioritized Experience Replay](https://arxiv.org/abs/1511.05952)||
|**Week 6 Feb 11** | 	Distributional RL ||[Intro Slides (Animesh Garg)](assets/slides/lec6_distributional.pdf)|
|||**Core papers**||
|||[A Comparative Analysis of Expected and Distributional Reinforcement Learning](https://arxiv.org/abs/1901.11084)||
|||[Implicit Quantile Networks for Distributional Reinforcement Learning](https://arxiv.org/abs/1806.06923)||
|||[Statistics and Samples in Distributional Reinforcement Learning](https://arxiv.org/abs/1902.08102)||
|||[Value Function in Frequency Domain and the Characteristic Value Iteration Algorithm](https://papers.nips.cc/paper/9620-value-function-in-frequency-domain-and-the-characteristic-value-iteration-algorithm)||
|||[An analysis of categorical distributional reinforcement learning](https://arxiv.org/abs/1802.08163)||
|||**Optional**||
|||[Reinforcement learning with Gaussian processes](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.81.6420&rep=rep1&type=pdf)||
|||[Nonparametric return distribution approximation for reinforcement learning](https://pdfs.semanticscholar.org/1ec2/6e05c2577154213e1668ddd374e4da663309.pdf)||
|||[A Distributional Perspective on Reinforcement Learning](https://arxiv.org/pdf/1707.06887.pdf) (C51)||
|||[Distributed Distributional Deterministic Policy Gradients](https://arxiv.org/abs/1804.08617) (D4PG)||
|**Week 7 Feb 18** | 	Model-Based RL	|**Core papers**||
|||[PILCO: Probabilistic Inference for Learning COntrol](http://mlg.eng.cam.ac.uk/carl/pilco/)||
|||[Algorithmic Framework for Model-based Deep Reinforcement Learning with Theoretical Guarantees](https://arxiv.org/abs/1807.03858) (SLBO)||
|||[Model-Based Reinforcement Learning via Meta-Policy Optimization](https://arxiv.org/abs/1809.05214) (MB-MPO)||
|||[Dream to Control: Learning Behaviors by Latent Imagination](https://arxiv.org/abs/1912.01603)|[Slides (Haotian Cui)](assets/slides/lec7_dreamtocontrol.pdf)|
|||[Iterative Value-Aware Model Learning](https://papers.nips.cc/paper/8121-iterative-value-aware-model-learning.pdf) (refer to [supplement](https://papers.nips.cc/paper/8121-iterative-value-aware-model-learning-supplemental.zip) as well)||
|||[Intro to ILQR](https://homes.cs.washington.edu/~todorov/papers/LiICINCO04.pdf)||
|||**Optional**||
|||[Benchmarking Model-Based Reinforcement Learning](https://arxiv.org/abs/1907.02057)||
|||[Learning Latent Dynamics for Planning from Pixels](https://arxiv.org/abs/1811.04551) (PlaNet)||
|||[Embed to Control: A Locally Linear Latent Dynamics Model for Control from Raw Images](https://arxiv.org/abs/1506.07365)(E2C)||
|||[Robust locally-linear controllable embedding](https://arxiv.org/abs/1710.05373)(RCE)||
|||[World Models](https://worldmodels.github.io/)||
|||[Deep Reinforcement Learning in a Handful of Trials using Probabilistic Dynamics Models](https://arxiv.org/abs/1805.12114) (PETS)||
|**Week 8 Feb 25** | 	Imitation: Inverse RL	|**Core papers**||
|||[Generative Adversarial Imitation Learning](https://arxiv.org/abs/1606.03476)||
|||[Maximum Entropy Inverse Reinforcement Learning](https://www.aaai.org/Papers/AAAI/2008/AAAI08-227.pdf)||
|||[Provably Efficient Imitation Learning from Observation Alone](https://arxiv.org/abs/1905.10948)||
|||[Off-Policy Evaluation via Off-Policy Classification](https://arxiv.org/abs/1906.01624)||
|||[Inverse KKT: Learning cost functions of manipulation tasks from demonstrations](https://journals.sagepub.com/doi/abs/10.1177/0278364917745980)||
|||**Optional**||
|||[Imitation from Observation: Learning to Imitate Behaviors from Raw Video via Context Translation](https://arxiv.org/abs/1707.03374)||
|||[Neural Task Graphs: Generalizing to unseen tasks from a single video demonstration](https://arxiv.org/abs/1807.03480)||
|**Feb 28** | 	(released Friday 9:00AM)	| **<span style="color:#b32425">Take Home Midterm Released (24 hours to turn-in)</span>**|
|**Feb 28** | 	(due Friday 11:59PM)	|**<span style="color:#b32425">Mid-Term Project Report Due</span>**|
|**Week 9 Mar 3** | Exploration in RL	|**Core papers**||
|||[Deep Exploration via Bootstrapped DQN](https://arxiv.org/abs/1602.04621)||
|||[Vime: Variational information maximizing exploration](https://arxiv.org/abs/1605.09674)||
|||[Incentivizing Exploration In Reinforcement Learning With Deep Predictive Models](https://arxiv.org/abs/1507.00814)||
|||[Large-Scale Study of Curiosity-Driven Learning Episodic Curiosity through Reachability](https://arxiv.org/abs/1808.04355)||
|||[Approximate Exploration through State Abstraction](https://arxiv.org/abs/1808.09819),<br /> [Go-Explore: a New Approach for Hard-Exploration Problems](https://arxiv.org/abs/1901.10995)||
|||**Optional**||
|||[Parameter Space Noise for Exploration](https://arxiv.org/abs/1706.01905)||
|||[Hindsight Experience Replay](https://arxiv.org/abs/1707.01495)||
|||[Exploration by Random Network Distillation](https://arxiv.org/abs/1810.12894)||
|**Week 10 Mar 10** | 	Bayesian RL	| **Core papers**||
|||[Bayesian Reinforcement Learning: A Survey](https://arxiv.org/abs/1609.04436)||
|||[VariBAD: A Very Good Method for Bayes-Adaptive Deep RL via Meta-Learning](https://arxiv.org/abs/1910.08348)||
|**Week 11 Mar 17** | 	Hierarchical RL	|**Core papers**||
|||[Building Portable Options: Skill Transfer in Reinforcement Learning](https://www.ijcai.org/Proceedings/07/Papers/144.pdf)||
|||[Between MDPs and Semi-MDPs: A Framework for Temporal Abstraction in Reinforcement Learning](https://www.sciencedirect.com/science/article/pii/S0004370299000521)||
|||Variational Option Discovery Algorithms|
|**Week Mar 24** | 	Project Presentation	||
|**Week Mar 31** | 	Project Presentation	||
|**Week Apr 7** | [Buffer]	||
|**Week Apr 7** | Tues 11:59 pm	|**<span style="color:#b32425">Final Project Report Due</span>**|
