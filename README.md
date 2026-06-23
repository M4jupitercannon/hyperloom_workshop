# Hyperloom Workshop

This repository contains a workshop notebook demonstrating Hyperloom's
agentic inference optimization workflow for a Qwen3-30B-A3B vLLM workload on
AMD MI300X.

Open `workshop_hyperloom_qwen3_vllm_forge.ipynb` to review:

- Hyperloom architecture and optimization phases
- Example throughput gain analysis
- Why Forge GEMM tuning improves the measured MoE/GEMM path
- Startup and monitor cells for running Hyperloom on a prepared environment

The `slides/` directory contains the images referenced by the notebook.
