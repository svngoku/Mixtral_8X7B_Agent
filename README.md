# Mixtral 8X7B — Deploying an *Open* AI Agent

The goal of this repo is to show how to deploy an AI agent using the new Open source model `Mistral 8X7B` on an instance (`AWS`, `RunPod`).

## 1. Create an instance

The instance must have the following characteristics:

- 160 GB VRAM
- 8 max
- 250 GB RAM  24 vCPU

## 2. Install the dependencies

```sh
!pip install -qU \
    transformers==4.36.1 \
    accelerate==0.25.0 \
    duckduckgo_search==4.1.0
```
