This repository contains a simulation comparing the Cost-Aware UCB algorithm presented by Gan et al. in 
"Cost-Aware Cascading Bandit" to our CC-BAI algorithm. CC-BAI is a best-arm identification algorithm based off
of Zhong et al. in "Best Arm Identification for Cascading Bandits in the Fixed Confidence Setting". We offer an
best-arm identification algorithm that is cost-aware, using insights from Gan et al. We find preliminary results
that our algorithm, CC-BAI achieves better regret given long exploration periods which find ideal arm lists
with high probability. In addition to empirical results, our algorithm also directly models the variability
of the reward-to-cost ratio used by Gan et al. Beyond estimating the reward-to-cost ratio, we also model the 
probability that the reward-to-cost ratio is ideal. Thus, we find ideal arms at a pre-defined probability.

Currently, theoretical bounds have not been developed due to the limited scope of this project.