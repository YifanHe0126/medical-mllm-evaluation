# Medical MLLM Evaluation and Model Selection

## Overview
This project evaluates open-source multimodal large language models in medical scenarios and supports model selection through a structured benchmarking workflow.

## Objective
The goal is to compare model quality and deployment-related costs across medical visual QA, radiology report generation, and medical text QA tasks.

## My Contribution
- Designed a unified evaluation workflow for multiple medical tasks
- Built prompt templates and output normalization rules
- Compared model quality together with latency, throughput, and peak VRAM
- Added result logging, caching, and timeout / OOM handling for experimental stability

## Tech Stack
Python, Transformers, Prompt Engineering, Evaluation Pipeline
