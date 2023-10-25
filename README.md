# Reinforcement Learning Project

This repository contains the code and results for two reinforcement learning questions:

## 1: Multi-armed Bandit

In this part of the project, I implemented a 10-armed testbed following the description in Section 2.3 of the textbook. I compared three methods of action value estimation:

### (a) Epsilon-Greedy Action Selection

- Varying the parameter epsilon to control the level of exploration vs. exploitation.
- Analyzing how changing epsilon affects the percentage of times the optimal action is selected and the average reward.

### (b) Optimistic Initial Value

- Adjusting the initial value estimates for action selection.
- Observing how optimistic initial values impact the choice of actions and average rewards.

### (c) Upper-Confidence-Bound Action Selection

- Tuning the confidence bound parameter to balance exploration and exploitation.
- Investigating the impact of different confidence bounds on action selection and average rewards.

I have provided visualizations similar to Figure 2.3 and Figure 2.4 to report our findings and conclusions.

## 2: Markov Reward Process

In this part of the project, I implemented the TD(0) algorithm for a Markov reward process. I empirically compared the prediction capabilities of the TD(0) algorithm for different values of the learning rate parameter (alpha).

### Key Analyses:

- Plotting how the root-mean-squared errors change with the number of episodes for different values of alpha.
- Examining whether the root-mean-squared errors converge to zero.
- Investigating the effect on root-mean-squared errors when alpha is set to 1/n (sample average update rule).