# 6-DoF Object Pose Estimation

-  6 Degree of Freedom: Object Pose Estimation (Part Based)
-  Paper: https://arxiv.org/abs/2203.01929

**Overview:**
  - Position (x, y, z)
  - Orientation (a, b, c)
  - Technically you get a highly detailed mesh of the object by scanning it with cam equipment
  - The goal is to make it easier to estimate the pose of an unseen objects without training
  - Only relies on a single pre-trained model / neural network

## CenterSnap: 
   - Single-Shot Multi-Object 3D Shape Reconstruction and Categorical 6D Pose and Size Estimation
   - A framework for real-time 6D pose and size estimation and 3D shape reconstruction of novel object instances.
   - CenterSnap is an anchor-free, single-shot approach to jointly optimize for 3D shape reconstruction and 6D pose and size.
   - CenterSnap performs effective sim2real transfer using limited real-world examples. Our technique runs at 40 FPS on Nvidia Quadro RTX 5000 GPU
