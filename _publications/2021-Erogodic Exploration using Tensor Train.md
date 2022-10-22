---
title: "Ergodic Exploration using Tensor Train: Applications in Insertion Tasks"
collection: publications
permalink: /publication/2021-Erogodic Exploration using Tensor Train

excerpt: '
By generating control policies that create natural search behaviors, ergodic control provides a principled solution to address tasks that require exploration. Since a large class of ergodic control algorithms relies on spectral analysis, they suffer from the curse-of-dimensionality, both in storage and computation. This drawback has prohibited the application of ergodic control in robot manipulation since it often requires exploration in state space with more than 2 dimensions. Indeed, the original ergodic control formulation will typically not allow exploratory behaviors to be generated for a complete 6D end-effector pose. In this research work, we propose a solution for ergodic exploration in multidimensional spaces using low-rank tensor approximation techniques. We rely on tensor train decomposition, a recent approach from multilinear algebra for low-rank approximation and efficient computation of multidimensional arrays. The proposed solution is efficient both computationally and storage-wise, hence making it suitable for its online implementation in robotic systems.

 We leverage our algorithm for high-dimensional ergodic exploration to solve the peg-in-hole insertion problem. We model peg-in-hole insertion task as a target detection problem and use our ergodic controller for the exploration in the 6D state space of the robot end-effector. The approach is applied to a peg-in-hole insertion task using a 7-axis Franka Emika Panda robot, where ergodic exploration allows the task to be achieved without requiring the use of force/torque sensors but only using human demonstrations. The approach can handle uncertainties in the location of the hole and/or graspings of the peg that typically exists in insertion tasks.'
date: 2021
# venue: 'Vibroengineering PROCEDIA, Vol. 26'
website: 'https://sites.google.com/view/ergodic-exploration/'
paperurl: 'https://ieeexplore.ieee.org/document/9473030'
citation: 'S Shetty, J Silvério, S Calinon, Ergodic Exploration using Tensor Train: Applications in Insertion Tasks, IEEE Transactions on Robotics (T-RO)'
---

By generating control policies that create natural search behaviors, ergodic control provides a principled solution to address tasks that require exploration. Since a large class of ergodic control algorithms relies on spectral analysis, they suffer from the curse-of-dimensionality, both in storage and computation. This drawback has prohibited the application of ergodic control in robot manipulation since it often requires exploration in state space with more than 2 dimensions. Indeed, the original ergodic control formulation will typically not allow exploratory behaviors to be generated for a complete 6D end-effector pose. In this research work, we propose a solution for ergodic exploration in multidimensional spaces using low-rank tensor approximation techniques. We rely on tensor train decomposition, a recent approach from multilinear algebra for low-rank approximation and efficient computation of multidimensional arrays. The proposed solution is efficient both computationally and storage-wise, hence making it suitable for its online implementation in robotic systems.

 We leverage our algorithm for high-dimensional ergodic exploration to solve the peg-in-hole insertion problem. We model peg-in-hole insertion task as a target detection problem and use our ergodic controller for the exploration in the 6D state space of the robot end-effector. The approach is applied to a peg-in-hole insertion task using a 7-axis Franka Emika Panda robot, where ergodic exploration allows the task to be achieved without requiring the use of force/torque sensors but only using human demonstrations. The approach can handle uncertainties in the location of the hole and/or graspings of the peg that typically exists in insertion tasks.

[Download paper here](https://github.com/SuhanNShetty/SuhanNShetty.github.io/files/pdf/2021_E2T2.pdf)

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