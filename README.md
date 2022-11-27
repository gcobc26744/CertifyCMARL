# CertifyCMARL: Certified Policy Smoothing for Cooperative Multi-Agent Reinforcement Learning (AAAI 2023)

##
Cooperative multi-agent reinforcement learning (c-MARL) is widely applied in safety-critical scenarios. In this domain, the analysis of robustness is extremely important, however, the robustness certification for c-MARLs has never been explored. We propose a novel certification method, which is the first work that leverages a scalable approach for c-MARLs to determine actions with guaranteed certified bounds. c-MARL certification poses two key challenges compared with single-agent systems: (i) the accumulated uncertainty as the number of agents increases; (ii) the potential lack of impact when changing the action of a single agent into a global team reward. These challenges prevent us from directly using existing algorithms. Hence, we employ the false discovery rate (FDR) controlling procedure considering the importance of each agent to certify per-state robustness and propose a tree search-based algorithm to find a lower bound of the global reward under the minimal certified perturbation. As our method is general, it can also be applied in single-agent environments. We empirically show that our certification bounds are much tighter than those of the state-of-the-art RL certification solutions. We also run experiments on two popular c-MARL algorithms: QMIX and VDN, in two different environments,
with two and four agents. The experimental results show that our method produces a meaningful guaranteed robustness for all models and environments.

##

### Note: This work is just accepted by the Thirty-Seventh AAAI Conference on Artificial Intelligence (AAAI 2023). Now we are preparing for the final version of this work. Our tool will be released soon via this repository.

-- Wenjie Ruan
