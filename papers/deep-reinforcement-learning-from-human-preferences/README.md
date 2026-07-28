# Deep Reinforcement Learning from Human Preferences

Interactive explainer for [Christiano et al. (2017)](https://arxiv.org/abs/1706.03741).

The explainer includes an Atari-style animated environment, play/pause controls, pairwise policy preference labels, a feedback-budget counter, and a four-stage walkthrough of the paper's method. It visualizes the central loop: an agent produces trajectory segments, a human compares pairs, a reward model learns from those preferences, and the policy improves against the learned reward.
