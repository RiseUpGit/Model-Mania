---
slug: qwen3.5-0.8b
name: Qwen 3.5 0.8B Instruct
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 0.8
size_gb: 1.00
quant: Q4_K_M
vram_min_gb: 1
vram_recommended_gb: 2
system_ram_min_gb: 1
system_ram_recommended_gb: 2
context_window: 32768
modalities: [text]
ollama_tag: qwen3.5:0.8b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 1.0 GB. Fast lightweight model.
---

## Summary

0.8B general-purpose instruct model. Best for quick responses and low-resource workloads.

## Usage

```bash
ollama run qwen3.5:0.8b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 1 GB |
| Recommended VRAM | 2 GB |
| Min System RAM | 1 GB |
| Recommended System RAM | 2 GB |
