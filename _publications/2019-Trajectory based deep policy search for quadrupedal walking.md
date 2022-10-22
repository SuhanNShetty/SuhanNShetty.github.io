---
title: "Trajectory based deep policy search for quadrupedal walking"
collection: publications
permalink: /publication/2019-Trajectory based deep policy search for quadrupedal walking

excerpt: 'In this paper, we explore a specific form of deep reinforcement learning (D-RL) technique for quadrupedal
walking—trajectory based policy search via deep policy networks. Existing approaches determine optimal policies for each time step, whereas we propose to determine an optimal policy for each walking step. We justify our approach based on the fact that animals including humans use “low” dimensional trajectories at the joint level to realize walking. We will construct these trajectories by using Bezier polynomials, with the coefficients being determined by a parameterized policy. In order to maintain smoothness of the trajectories during step transitions, hybrid invariance conditions are also applied. The action is computed at the beginning of every step, and a linear PD control law is applied to track at the individual joints. After each step, reward is computed, which is then used to update the new policy parameters for the next step. After learning an optimal policy, i.e., an optimal walking gait for each step, we then successfully play them in a custom built quadruped robot, Stoch 2, thereby validating our approach.'
date: 2019
# venue: 'Vibroengineering PROCEDIA, Vol. 26'
# website: 'https://sites.google.com/view/ttgo/home'
paperurl: 'https://ieeexplore.ieee.org/document/8956369'
citation: ' S Kolathaya, A Joglekar, S Shetty, D Dholakiya, A Sagi, S Bhattacharya, A Singla, S Bhatnagar, A Ghosal, B Amrutur, Trajectory based deep policy search for quadrupedal walking, 28th IEEE International Conference on Robot and Human Interactive Communication (RO-MAN)'
---
In this paper, we explore a specific form of deep reinforcement learning (D-RL) technique for quadrupedal
walking—trajectory based policy search via deep policy networks. Existing approaches determine optimal policies for each time step, whereas we propose to determine an optimal policy for each walking step. We justify our approach based on the fact that animals including humans use “low” dimensional trajectories at the joint level to realize walking. We will construct these trajectories by using Bezier polynomials, with
the coefficients being determined by a parameterized policy. In order to maintain smoothness of the trajectories during step transitions, hybrid invariance conditions are also applied. The
action is computed at the beginning of every step, and a linear PD control law is applied to track at the individual joints. After each step, reward is computed, which is then used to update
the new policy parameters for the next step. After learning an optimal policy, i.e., an optimal walking gait for each step, we then successfully play them in a custom built quadruped robot, Stoch 2, thereby validating our approach.

[Download paper here](https://github.com/SuhanNShetty/SuhanNShetty.github.io/files/pdf/2019_Stoch.pdf)

<!-- Recommended citation: 

**Cite as**: 

Ma, J., Shang, P., Lu, C., Meraghni, S., Benaggoune, K., Zuluaga, J., Zerhouni, N., Devalland, C. and Al Masry, Z., 2019. A portable breast cancer detection system based on smartphone with infrared camera. Vibroengineering PROCEDIA, 26, pp.57-63.
{: .notice}


- BibTeX:

<pre>
@article{ma2019portable,
  title={A portable breast cancer detection system based on smartphone with infrared camera},
  author={Ma, Jian and Shang, Pengchao and Lu, Chen and Meraghni, Safa and Benaggoune, Khaled and Zuluaga, Juan and Zerhouni, Noureddine and Devalland, Christine and Al Masry, Zeina},
  journal={Vibroengineering PROCEDIA},
  volume={26},
  pages={57--63},
  year={2019},
  publisher={JVE International Ltd.}
}
</pre> -->