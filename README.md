![Header](https://capsule-render.vercel.app/api?type=waving&color=0:193F73,100:0B7C86&height=200&section=header&text=Soohyun%20Choi&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Reinforcement%20Learning%20%7C%20Sequential%20Decision%20Making&descAlignY=58&descSize=17)

<div align="center">

### Hi, I'm Soohyun 👋

Integrated M.S./Ph.D. student in Electronic Engineering at Hanyang University  
Information and Intelligence Systems Lab (IISL) · Advisor: Prof. Songnam Hong

[![Website](https://img.shields.io/badge/Website-0B7C86?style=flat-square&logo=googlechrome&logoColor=white)](https://schoish.github.io/)
[![CV](https://img.shields.io/badge/CV-193F73?style=flat-square&logo=readme&logoColor=white)](https://schoish.github.io/assets/Soohyun_Choi_CV.pdf)
[![Email](https://img.shields.io/badge/Email-C43D4D?style=flat-square&logo=gmail&logoColor=white)](mailto:petersun0221@hanyang.ac.kr)

</div>

## Research

I study **reinforcement learning and sequential decision making**, focusing on
iterative policy improvement and generative long-horizon planning.

My current work studies **Multi-step Proximal Policy Improvement (MPI)**, which
refines an offline policy through a short sequence of critic-guided proximal
steps. Each step re-centers the proximity anchor at the preceding policy,
providing path-wise control of movement beyond a fixed data anchor. I analyze
how **τ**, the effective discretization step size, balances conservative local
movement against farther but more critic-error-sensitive refinement. In
parallel, I am extending **PathBridger** toward **PathFlower**, a framework for
generating goal-conditioned state flows.

### Current directions

- 🌀 **Multi-step Policy Improvement**  
  Treating behavior-regularized offline actor updates as proximal steps and
  composing re-centered refinements. I study when τ keeps updates local,
  enables useful finite-step movement, or enters critic-error-sensitive regions.

- 🌉 **PathBridger**  
  Generating state-space bridges for long-horizon offline goal-conditioned
  reinforcement learning.

- 🌸 **PathFlower**  
  Extending explicit subgoal bridges toward final-goal-conditioned generative
  state flows.

## Selected projects

| Project | Focus |
|---|---|
| [**PathBridger**](https://github.com/SChoish/PathBridger) | Subgoal bridges for long-horizon offline goal-conditioned RL |
| [**MPI**](https://github.com/SChoish/MPI) | Re-centered proximal refinements for offline policy improvement |
| [**POGO**](https://github.com/SChoish/POGO) | Geometric policy optimization for offline reinforcement learning |

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
