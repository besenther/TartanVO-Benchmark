# TartanVO-Benchmark

## Motivation
---
We are interested in image processing, particularly for location tracking, because it might be useful for our senior design project (a rep counter and exertion monitor for weight lifting).

## Design Goals
---
Develop a deep learning tracking algorithm for two mobile systems.

## Deliverables
---
- Implement and understand an end-to-end learning approach for tracking – TartanVO
- Benchmark TartanVO on two datasets to evaluate its performance (data & code provided)
- Analyze performance differences across the datasets and reason about it

## System Blocks
---
Consecutive RGB images
> Matching network 
Optical flow estimation
> Pose network
Camera motion estimation (translation head, rotation head)

## Hardware/Software requirements
---
Python, Laptop with CUDA-enabled GPU

## Lead roles/responsibilities
---
Ben: setup, software, algorithm design
Ratan: writing, research, algorithm design
N/A: networking

## Timeline
---
October: Research TartanVO and implement it
November: Benchmark TartanVO on two datasets
December: Analyze performance differences across the datasets and write a report & presentation

## References
---
Paper: TartanVO: A Generalizable Learning-based VO
	https://arxiv.org/pdf/2011.00359.pdf
Code: https://github.com/castacks/tartanvo
Datasets:
1. EuRoC: https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets
2. KITTI: https://www.cvlibs.net/datasets/kitti/eval_odometry.php
3. HoloSet: https://tinyurl.com/holoset-dataset
