---
slug: qwen2.5-coder-7b
name: Qwen 2.5 Coder 7B Instruct
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 7
size_gb: 4.70
quant: Q4_K_M
vram_min_gb: 5
vram_recommended_gb: 6
system_ram_min_gb: 4
system_ram_recommended_gb: 8
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:7b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 4.7 GB. High-quality coding model at mid-size tier.
---

## Summary

7B parameter coding model with strong reasoning and multi-file context. Fits fully on the 5070 Ti with headroom.

## Usage

```bash
ollama run qwen2.5-coder:7b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 5 GB |
| Recommended VRAM | 6 GB |
| Min System RAM | 4 GB |
| Recommended System RAM | 8 GB |
