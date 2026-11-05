# Deep RL Survey — English Version (v1.2)

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
- [x] Lecture 12 study module — Inverse RL: reward ambiguity, feature matching, max-margin, MaxEnt likelihood and gradient, Guided Cost Learning, GAIL, AIRL (`chapters/12_inverse_rl.tex`; supplied PDF cover calls this Lec 16)
- [ ] Later lectures — Remaining topics / unified comparison

## After each study module
Explain intuition, architecture, data, training targets, losses, gradient flow, limitations, and links to prior methods. Add short numerical examples and review questions. Mark incomplete parts clearly.

**Updated:** 2026-11-05, v1.2. Added the inverse RL chapter with reward non-identifiability, potential-based shaping, feature matching versus maximum margin, MaxEnt likelihood and feature-expectation gradient, sampling/importance weighting, Guided Cost Learning, GAIL occupancy matching and AIRL transfer assumptions. Registered the chapter in `main.tex`; existing chapters remain intact.
