# Deep RL Survey — English Version (v0.9)

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
- [ ] Lecture 10 onward — Exploration, offline RL, and remaining topics / unified comparison

## After each study module
Explain intuition, architecture, data, training targets, losses, gradient flow, limitations, and links to prior methods. Add short numerical examples and review questions. Mark incomplete parts clearly.

**Updated:** 2026-10-20, v0.9. Added Lecture 9: stochastic optimization, PG/FOG numerical and analytic comparisons, BPTT, SHAC with TD(lambda), PWM and the smoothness/fidelity tradeoff. The new chapter follows Chapter 5 in `main.tex`; existing outline chapters remain in place.
