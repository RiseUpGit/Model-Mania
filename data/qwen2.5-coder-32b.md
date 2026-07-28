---
slug: qwen2.5-coder-32b
name: Qwen 2.5 Coder 32B Instruct
provider: Alibaba
license: apache-2.0
branch: hybrid
parameters_b: 32
size_gb: 19.0
quant: Q4_K_M
vram_min_gb: 16
vram_recommended_gb: 20
system_ram_min_gb: 16
system_ram_recommended_gb: 32
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:32b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 19 GB. Hybrid GPU+CPU offload required on this hardware.
---

## Summary

Largest Qwen 2.5 Coder variant. Requires partial system RAM offload alongside the 5070 Ti. Use when quality outweighs latency.

## Usage

```bash
ollama run qwen2.5-coder:32b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 16 GB |
| Recommended VRAM | 20 GB |
| Min System RAM | 16 GB |
| Recommended System RAM | 32 GB |
