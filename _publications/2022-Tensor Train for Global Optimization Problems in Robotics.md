---
title: "Tensor Train for Global Optimization Problems in Robotics"
collection: publications
permalink: /publication/2022-Tensor Train for Global Optimization Problems in Robotics

excerpt: 'The convergence of many numerical optimization techniques is highly sensitive to the initial guess provided to the solver. We propose an approach based on low-rank tensor approximation techniques to initialize the existing optimization solvers close to the optima. The approach uses only the definition of the cost function (no gradient information is required) and does not need access to any database of good solutions. This renders the method less susceptible to getting stuck in poor local optima as compared to gradient-based methods.'
date: 2022
# venue: 'Vibroengineering PROCEDIA, Vol. 26'
website: 'https://sites.google.com/view/ttgo/home'
paperurl: 'https://arxiv.org/pdf/2206.05077.pdf'
citation: 'S Shetty, T Lembono, T Loew, S Calinon, Tensor Train for Global Optimization Problems in Robotics, arXiv:2206.05077'
---

The convergence of many numerical optimization techniques is highly sensitive to the initial guess provided to the solver. We propose an approach based on low-rank tensor approximation techniques to initialize the existing optimization solvers close to the optima. The approach uses only the definition of the cost function (no gradient information is required) and does not need access to any database of good solutions. This renders the method less susceptible to getting stuck in poor local optima as compared to gradient-based methods. Unlike existing approaches in robotics that solve each optimization problem corresponding to a given task from scratch, we parameterize the optimization problem with respect to the tasks. We first transform the cost function, which is a function of task parameters and optimization variables, into an unnormalized probability density function. Then for a given task, we generate samples from the conditional distribution with respect to the given task parameter and use them as initialization for the optimization solver. As conditioning and sampling from an arbitrary density function is challenging, we use Tensor Train decomposition to obtain a surrogate probability model from which we can efficiently obtain the conditional model and the samples. The proposed method can produce multiple solutions coming from different modes (when they exist) for a given task. We first evaluate the approach by applying it to various challenging benchmark functions for numerical optimization that are difficult to solve using gradient-based optimization solvers with a naive initialization, showing that the proposed method can produce samples close to the global optima and coming from multiple modes. We then demonstrate the generality of the framework and its relevance to robotics by applying the proposed method to inverse kinematics and motion planning problems with a 7-DoF manipulator, as commonly encountered in robot manipulation.

[Download paper here](https://github.com/SuhanNShetty/SuhanNShetty.github.io/files/pdf/2022_TTGO.pdf)

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