# Private GPU Inference Server — Agentic AI Security Lab

## Overview

Designed, built, and operate a locally-hosted GPU inference server in a rack server at home for private AI/ML workloads. The primary purpose is to research and build security controls around agentic AI — using a fully private, data-sovereign environment where models, prompts, and outputs never leave the local network.

## Hardware & Platform

- Rack-mounted server with GPU(s) for inference
- Self-managed local networking and security stack

## Software Stack

- **Inference engine**: vLLM — serving quantized open-weight models
- **Agentic harness**: OpenCode — AI coding/agent framework integrated directly with the inference endpoint
- **Access**: Available via a private, self-managed network stack (VPN/tunneled), not exposed to the public internet
- **Model pipeline**: Quantized models loaded and served locally, enabling fast iteration without cloud API dependencies

## Key Objectives

- **Data sovereignty**: All inference data, model weights, and agent interactions remain on-premises — critical for financial services sensitivity testing
- **Agentic AI security research**: Sandbox environment for understanding and hardening the network security perimeter around AI agents that can execute code, access APIs, and interact with production-like systems
- **Rapid prototyping**: Private inference endpoint for testing AI-driven network automation, security policy generation, and infrastructure-as-code workflows before any production consideration
- **Skill development**: Hands-on experience across the full AI inference stack — from GPU drivers and CUDA through to model serving, quantization, and agent integration

## Relevance

This capability directly informs production GPU fabric design and security architecture decisions — understanding the full stack from bare metal GPU inference through to agentic AI harnesses provides practical insight that feeds back into enterprise-scale deployments.
