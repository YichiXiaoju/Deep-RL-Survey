# Deep RL Survey — English Version (v1.1)

Plain English with mathematical LaTeX. Based on CS 8803 Fall 2026 course materials and our guided study.

## Overleaf
Upload the complete project ZIP as a new project and preserve the `chapters/` folder. Root file: `main.tex`. Set compiler to **pdfLaTeX** (XeLaTeX also works). GitHub commits do not automatically sync into free Overleaf projects.

## Progress
- [x] Chapter 0 — Overview (initial draft)
- [x] Chapter 1 — Fundamentals (first pass completed; expanded with numerical examples)
- [x] Chapter 2 — Policy Gradients, REINFORCE, reward-to-go, baselines, actor-critic, GAE, PPO clipping (first pass)
- [x] Chapter 3 — Q-Learning, DQN, replay, target networks, Double DQN, data/gradient flow and limitations (first pass)
- [x] Chapter 4 — DDPG, TD3, SAC, actor/critic gradient flow, entropy and temperature tuning (first pass)
- [x] Chapter 5 — Model-Based RL: dynamics, MPC/CEM, model error, uncertainty, PETS, Dyna, MBPO, MVE, value-guided planning, policy backprop (first pass and review)
- [x] Lecture 9 — Beyond Policy Gradients: stochastic optimization, score-function versus pathwise gradients, BPTT, SHAC, PWM (first pass; file `chapters/09_beyond_policy_gradients.tex`)
- [x] Lecture 10 — Exploration: UCB, Thompson sampling, information gain/IDS, pseudo-counts, hashes, EX2, RND, Bootstrapped DQN, VIME, and comparative review (`chapters/10_exploration.tex`)
- [x] Lecture 11 — Offline RL: distribution shift, OPE (IS/DR/marginalized IS), LSTD/LSTDQ/LSPI, BEAR, AWR, IQL, CQL and COMBO (`chapters/11_offline_rl.tex`)
- [ ] Lecture 12 onward — Remaining topics / unified comparison

## After each study module
Explain intuition, architecture, data, training targets, losses, gradient flow, limitations, and links to prior methods. Add short numerical examples and review questions. Mark incomplete parts clearly.

**Updated:** 2026-10-31, v1.1. Added Lecture 11 offline RL notes with Bellman/TD/LSTD derivations, a two-transition numerical example, policy-support reasoning, OPE estimators, expectile regression and all three IQL losses, CQL regularization, and a BEAR/AWR/IQL/CQL comparison. The new chapter is included in `main.tex`; existing sections are preserved.
