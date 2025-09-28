---
layout: default
title: Yiru Wu
---

# Yiru Wu · Machine Learning Engineer / Software Engineer

I design and build large-scale **GPU-accelerated RL systems** and high-quality software.  
Recent work: vectorized simulators (Isaac Gym, MuJoCo) with **4,096+ parallel actors** achieving **~90k env steps/s**, and PPO controllers with **30% faster convergence** and **+10% episode return** via dynamics-aware critics. :contentReference[oaicite:1]{index=1}

<div style="display:flex; gap:12px; flex-wrap:wrap;">
  <a class="btn btn-primary" href="/resume">Resume (PDF)</a>
  <a class="btn" href="/projects">Projects</a>
  <a class="btn" href="/experience">Experience</a>
  <a class="btn" href="mailto:wu754@wisc.edu">Email</a>
  <a class="btn" href="https://github.com/<your-github-username>">GitHub</a>
  <a class="btn" href="https://www.linkedin.com/in/<your-linkedin-slug>/">LinkedIn</a>
</div>

---

## Highlights
- **Large-scale RL infrastructure**: 4,096-actor Isaac Gym pipelines, batched physics, pinned memory, async GPU I/O; **~100× speedup** vs CPU. :contentReference[oaicite:2]{index=2}  
- **Algorithmic impact**: dynamics-aware critic for PPO → **30% faster convergence**, **+10% return** across seeds. :contentReference[oaicite:3]{index=3}  
- **MLOps & reproducibility**: Docker, Hydra, deterministic seeding, W&B/TensorBoard, CI with throughput KPIs. :contentReference[oaicite:4]{index=4}  
- **Systems mindset**: profiling wall-clock/throughput, regression detection, metric instrumentation. :contentReference[oaicite:5]{index=5}

## Core Skills
**Languages/Tools:** Python, PyTorch, NumPy, Pandas, Docker, GitHub Actions  
**ML/RL:** PPO, Actor-Critic, Reward Design, Ablations, CNNs, Gaussian Processes  
**Sim/Robotics:** Isaac Gym (vectorized), MuJoCo, GRF-to-torque mapping  
**Ops:** Reproducible training, CI/CD, experiment tracking

---

## Recent Projects
### High-Throughput RL Simulator (Isaac Gym, 4,096 actors)
End-to-end GPU pipeline; batched physics & memory layout tuning; **~90k env steps/s**.  
Result: dramatic wall-clock reduction, enabling broader ablations. :contentReference[oaicite:6]{index=6}

### Dynamics-Aware PPO for Quadruped Locomotion
Critic augmented with dynamics features → **30% faster convergence**, **+10% return**; stable GRF-to-torque control. :contentReference[oaicite:7]{index=7}

### FCOS Detector in PyTorch
From-scratch anchor-free detector (CNN + FPN + centerness + NMS); clean, reproducible training pipeline. :contentReference[oaicite:8]{index=8}

> See more on the [Projects](/projects) page.
