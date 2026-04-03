---
title: "Aggressiveness-conservativeness trade-off in cooperative driving: An adaptive CBF approach under perception constraints"
collection: publications
permalink: /publication/2025-paper-trc1
excerpt: 'An adaptive CBF-based cooperative driving framework that balances safety and efficiency under perception constraints.'
date: 2026-02-01
venue: 'Transportation Research Part C: Emerging Technologies'
paperurl: 'https://doi.org/10.1016/j.trc.2025.105435'
citation: 'Q. Liu and J. Wang. (2026). &quot;Aggressiveness-conservativeness trade-off in cooperative driving: An adaptive CBF approach under perception constraints.&quot; <i>Transportation Research Part C: Emerging Technologies</i>, 183, 105435.'
---
This paper proposes a cooperative driving framework for perception-constrained environments by integrating an adaptive Control Barrier Function (ACBF) into a Model Predictive Control (MPC) formulation. The method dynamically adjusts safety margins according to the observable spatial structure, enabling a real-time trade-off between aggressiveness and conservativeness.

To improve computational tractability, the paper develops a convexification strategy for nonlinear ACBF constraints and further implements an ADMM-based parallel optimization algorithm. The study also provides a formal asymptotic stability analysis for the closed-loop system under the proposed MPC-ACBF scheme.

Numerical experiments show that the proposed method achieves a 0% collision rate across representative scenarios, reduces task completion time by more than 15% relative to conservative baselines, and improves minimum inter-vehicle distance by more than 1.5 m compared with aggressive strategies. These results indicate that the method can preserve control efficiency while substantially improving safety and robustness under constrained perception.
