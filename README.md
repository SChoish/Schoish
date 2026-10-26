![Header](https://capsule-render.vercel.app/api?type=waving&color=0:193F73,100:0B7C86&height=200&section=header&text=Soohyun%20Choi&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Reinforcement%20Learning%20%7C%20Generative%20Models%20%7C%20Stochastic%20Processes&descAlignY=58&descSize=14)

<div align="center">

### Hi, I'm Soohyun 👋

Integrated M.S./Ph.D. student in Electronic Engineering at Hanyang University  
Information and Intelligence Systems Lab (IISL) · Advisor: Prof. Songnam Hong

[![Website](https://img.shields.io/badge/Website-0B7C86?style=flat-square&logo=googlechrome&logoColor=white)](https://schoish.github.io/)
[![CV](https://img.shields.io/badge/CV-193F73?style=flat-square&logo=readme&logoColor=white)](https://schoish.github.io/assets/Soohyun_Choi_CV.pdf?v=20261001b)
[![Email](https://img.shields.io/badge/Email-C43D4D?style=flat-square&logo=gmail&logoColor=white)](mailto:petersun0221@hanyang.ac.kr)

</div>

## Research

My research interests lie in **reinforcement learning**, particularly in the
mathematical and geometric analysis of learning algorithms. I am also interested
in developing new algorithms and modeling frameworks using **generative models**
and **stochastic processes**, especially for goal-conditioned and long-horizon
control.

My work on [**Multi-step Proximal Policy Improvement (MPI)**](https://github.com/SChoish/MPI)
studies how re-centered proximal updates compose policy improvement. The revised
paper, [**Is One Step Enough for Offline Policy Improvement?**](https://arxiv.org/abs/2609.03842v2),
distinguishes subdividing a fixed nominal total horizon `T` into `K` stages with
local horizon `T/K` from adding refinement stages at a common local horizon.
It examines re-centering, policy geometry, discretization, and critic error.

[**Role-Adaptive Policy Optimization (RAPO)**](https://arxiv.org/abs/2609.40149)
learns policy-update coefficients through role-specific meta-gradients. For
TD3+BC, it separates execution and bootstrap actors and adapts their coefficients
using local policy improvement and target stability, respectively. For IQL, it
retains the original value updates and adapts the inverse temperature of
advantage-weighted policy extraction.

### Current directions

- 🌸 **PathFlower**  
  Extending PathBridger's explicit subgoal bridges toward final-goal-conditioned
  generative state flows for long-horizon offline goal-conditioned RL.

## Selected projects

| Project | Focus |
|---|---|
| [**PathBridger**](https://github.com/SChoish/PathBridger) | Subgoal bridges for long-horizon offline goal-conditioned RL · [arXiv](https://arxiv.org/abs/2608.29061) |
| [**MPI**](https://github.com/SChoish/MPI) | Is One Step Enough for Offline Policy Improvement? · [arXiv v2](https://arxiv.org/abs/2609.03842v2) |
| **RAPO** | Role-Adaptive Policy Optimization for Offline Reinforcement Learning · [arXiv](https://arxiv.org/abs/2609.40149) |


## Background

- 🎓 Integrated M.S./Ph.D. student, Hanyang University
- 🧠 Information and Intelligence Systems Lab
- 🏭 Research participant in an SK hynix–Hanyang University project
- 🏅 Graduation Honors, Hanyang University

## Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

<div align="center">
  <sub>Exploring better paths for long-horizon decision making 🌱</sub>
</div>
