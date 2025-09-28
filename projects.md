---
layout: default
title: Projects
---

# Projects

## Large-Scale RL for Continuous Control (Isaac Gym / MuJoCo)
- **Scale:** 4,096 parallel actors; **~90k env steps/s** on GPU via batched physics, pinned memory, async transfers.  
- **Engineering:** deterministic seeding; Docker + Hydra; CI with **throughput KPIs** to catch perf regressions.  
- **Impact:** **~100× speedup** vs CPU baselines; enabled extensive ablations and faster iteration. :contentReference[oaicite:9]{index=9}

## Dynamics-Aware PPO for Quadruped Locomotion
- **Method:** critic enriched with dynamics features; GRF prediction → torque mapping for low-level control.  
- **Result:** **30% faster convergence**; **+10% episode return** across seeds; stable gait transitions. :contentReference[oaicite:10]{index=10}

## Bipedal (2D Strider) RL Pipeline
- **Optimization:** batched rollouts; memory pinning; async GPU I/O; curriculum + reward shaping for stand-to-walk.  
- **Result:** reduced fall rates; target speed/energy metrics achieved; strong reproducibility. :contentReference[oaicite:11]{index=11}

## FCOS Object Detector (from scratch)
- **Stack:** CNN backbone + FPN + centerness; NMS inference; clean training/eval loops.  
- **Outcome:** robust multi-scale detection; code emphasizes readability and testing. :contentReference[oaicite:12]{index=12}

## Maze Navigation Robot (Webots)
- **Perception/Control:** particle filter for sensor denoising; global **A\*** planning + local feedback control.  
- **Result:** reliable collision-free traversal; targets met within 5-minute constraints. :contentReference[oaicite:13]{index=13}
