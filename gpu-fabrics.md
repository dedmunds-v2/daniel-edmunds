# GPU Fabrics for Large-Scale AI/ML Inference & Training

## Overview

Designed and deployed Ethernet-based GPU fabrics supporting large-scale AI/ML workloads — both inference and training — for financial services use cases.

## Technical Details

- **Fabric type**: Ethernet-based, RoCEv2 (RDMA over Converged Ethernet)
- **Switch platform**: Arista
- **GPU platform**: NVIDIA B300
- **Scale**: Up to 1,024 GPUs per fabric
- **Topology**: Non-blocking, rail-optimized leaf-spine design for maximum east-west bandwidth between GPU nodes
- **Key challenges addressed**:
  - Lossless Ethernet configuration (PFC, ECN) for RDMA traffic
  - Congestion management at scale — balancing flows across ECMP paths, managing incast patterns during all-reduce operations
  - DCQCN tuning for RoCEv2 congestion control
  - Integration with existing low-latency financial network infrastructure
  - Multi-tenancy isolation for GPU resources across different business units

## Outcomes

- Enablement of large-scale model training and inference within the existing colocation and private cloud footprint
- Seamless integration of GPU fabrics alongside traditional low-latency trading network infrastructure
