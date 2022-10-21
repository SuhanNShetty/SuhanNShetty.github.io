---
title: "Trajectory Prediction with Compressed 3D Environment Representation using Tensor Train Decomposition"
collection: publications
permalink: /publication/2021-Trajectory Prediction with Compressed 3D Environment Representation using Tensor Train Decomposition

excerpt: 'Trajectory optimization for motion planning is a fundamental problem in robotics. Algorithms typically require good initialization in order to find optimal trajectories. To provide such initialization, many approaches rely on the concept of memory of motion, where a function approximator is trained on a database of robot trajectories to predict good initial trajectories for novel situations, and hence speeding up the subsequent trajectory optimization process. To be able to generalize well to new environment, an expressive environment descriptor is necessary. We propose to encode the environment by discretized signed distance functions (SDF) which are then compressed using a tensor train (TT) decomposition approach.'
# date: 2022-06-01
# venue: 'Vibroengineering PROCEDIA, Vol. 26'
# website: 'https://sites.google.com/view/ttgo/home'
paperurl: 'https://ieeexplore.ieee.org/document/9659407'
citation: 'Brudermüller, L., Lembono, T.S., Shetty, S. and Calinon, S. (2021). Trajectory Prediction with Compressed 3D Environment Representation using Tensor Train Decomposition. In Proc. IEEE Intl Conf. on Advanced Robotics (ICAR), pp. 633-639'
---
Trajectory optimization for motion planning is a fundamental problem in robotics. Algorithms typically require good initialization in order to find optimal trajectories. To provide such initialization, many approaches rely on the concept of memory of motion, where a function approximator is trained on a database of robot trajectories to predict good initial trajectories for novel situations, and hence speeding up the subsequent trajectory optimization process. To be able to generalize well to new environment, an expressive environment descriptor is necessary. We propose to encode the environment by discretized signed distance functions (SDF) which are then compressed using a tensor train (TT) decomposition approach. In order to show the expressiveness of this low-rank TT-SDF representation, three function approximators are compared: a nearest neighbor predictor, an artificial neural network and a mixture density network. We demonstrate the proposed method with motion planning examples on two different systems (point-mass and quadcopter). Our experiments demonstrate that the TT-SDF encoding can provide meaningful environment descriptors in order to predict good motion trajectories for warm-starting an optimal control solver.

[Download paper here](https://github.com/SuhanNShetty/SuhanNShetty.github.io/files/pdf/2021_Lara.pdf)

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