![Header](https://capsule-render.vercel.app/api?type=waving&color=0:193F73,100:0B7C86&height=200&section=header&text=Soohyun%20Choi&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Reinforcement%20Learning%20%7C%20Generative%20Models%20%7C%20Stochastic%20Processes&descAlignY=58&descSize=14)

<div align="center">

### Hi, I'm Soohyun 👋

Integrated M.S./Ph.D. student in Electronic Engineering at Hanyang University  
Information and Intelligence Systems Lab (IISL) · Advisor: Prof. Songnam Hong

[![Website](https://img.shields.io/badge/Website-0B7C86?style=flat-square&logo=googlechrome&logoColor=white)](https://schoish.github.io/)
[![CV](https://img.shields.io/badge/CV-193F73?style=flat-square&logo=readme&logoColor=white)](https://schoish.github.io/assets/Soohyun_Choi_CV.pdf?v=20260904)
[![Email](https://img.shields.io/badge/Email-C43D4D?style=flat-square&logo=gmail&logoColor=white)](mailto:petersun0221@hanyang.ac.kr)

</div>

## Research

My research interests lie in **reinforcement learning**, particularly in the
mathematical and geometric analysis of learning algorithms. I am also interested
in developing new algorithms and modeling frameworks using **generative models**
and **stochastic processes**, especially for goal-conditioned and long-horizon
control.

My work on [**Multi-step Proximal Policy Improvement (MPI)**](https://github.com/SChoish/MPI)
interprets behavior-anchored actor updates as proximal steps and composes
sequential re-centered refinements. I study how policy geometry, step size, and
critic error shape finite-step improvement. The manuscript is available as a preprint.

My current research extends this direction through **MART**, which studies how
refinement depth changes critic-facing bootstrap exposure and deployment reach
under a fixed policy-improvement horizon, and **AMO**, which learns the total
proximal-flow horizon through a bilevel outer objective. In parallel, I am
extending **PathBridger** toward **PathFlower**, a framework for generating
goal-conditioned state flows.

### Current directions

- 🧭 **MART: Multi-Step Actor Refinement Trajectories**  
  Dividing a fixed policy-improvement horizon across persistent local actors to
  study the stability frontier, critic-facing exposure, and deployment reach.

- ⚙️ **AMO: Adaptive Multiscale Policy Optimization in Offline Reinforcement Learning**  
  Learning the total policy-improvement horizon `T` from an offline bilevel
  objective with a two-scale structure: the critic uses the local `T/N` policy,
  while the actor represents the full-horizon `T` policy.

- 🌸 **PathFlower**  
  Extending explicit subgoal bridges toward final-goal-conditioned generative
  state flows.

## Selected projects

| Project | Focus |
|---|---|
| [**PathBridger**](https://github.com/SChoish/PathBridger) | Subgoal bridges for long-horizon offline goal-conditioned RL · [arXiv](https://arxiv.org/abs/2608.29061) |
| [**MPI**](https://github.com/SChoish/MPI) | Re-centered proximal refinements for offline policy improvement |
| [**POGO**](https://github.com/SChoish/POGO) | Precursor to MPI: transport-based, JKO-style policy optimization |


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
