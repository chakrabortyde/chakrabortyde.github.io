---
title: "Exploring reinforcement learning techniques for discrete and continuous control tasks in the MuJoCo environment"
abstract: "We leverage the fast physics simulator, MuJoCo to run tasks in a continuous control environment and reveal details like the observation space, action space, rewards, etc. for each task. We benchmark value-based methods for continuous control by comparing Q-learning and SARSA through a discretization approach, and using them as baselines, progressively moving into one of the state-of-the-art deep policy gradient method DDPG. Over a large number of episodes, Qlearning outscored SARSA, but DDPG outperformed both in a small number of episodes. Lastly, we also fine-tuned the model hyper-parameters expecting to squeeze more performance but using lesser time and resources. We anticipated that the new design for DDPG would vastly improve performance, yet after only a few episodes, we were able to achieve decent average rewards. We expect to improve the performance provided adequate time and computational resources."
collection: publications
permalink: /publications/mujoco-control-tasks
date: "2023-07-20"
venue: "arXiv"
paperurl: "https://arxiv.org/pdf/2307.11166.pdf"
link: "https://doi.org/10.48550/arXiv.2307.11166"
code: "https://github.com/chakrabortyde/mujoco-control-tasks"
citation: "Vaddadi Sai Rahul & Chakraborty, D. (2023). Exploring reinforcement learning techniques for discrete and continuous control tasks in the MuJoCo environment. arXiv preprint. arXiv:2307.11166."
---