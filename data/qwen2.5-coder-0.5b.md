---
slug: qwen2.5-coder-0.5b
name: Qwen 2.5 Coder 0.5B Instruct
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 0.5
size_gb: 0.40
quant: Q4_K_M
vram_min_gb: 1
vram_recommended_gb: 2
system_ram_min_gb: 1
system_ram_recommended_gb: 2
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:0.5b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Small, fast, runs easily on 5070 Ti. Good for quick completions.
---

## Summary

Ultra-small 500M parameter coding model. Best for fast inline suggestions, comment generation, and simple refactors on low-resource workloads.

## Usage

```bash
ollama run qwen2.5-coder:0.5b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 1 GB |
| Recommended VRAM | 2 GB |
| Min System RAM | 1 GB |
| Recommended System RAM | 2 GB |

## Context

This model was pulled and verified locally as part of the BMG offline model library build.
