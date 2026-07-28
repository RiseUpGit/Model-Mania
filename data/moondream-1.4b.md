---
slug: moondream-1.4b
name: Moondream 1.8B
provider: vikhyatk / Moondream
license: apache-2.0
branch: vision
parameters_b: 1.8
size_gb: 1.70
quant: Q4_K_M
vram_min_gb: 2
vram_recommended_gb: 3
system_ram_min_gb: 2
system_ram_recommended_gb: 4
context_window: 8192
modalities: [text, vision]
ollama_tag: moondream:1.8b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 1.7 GB. Compact vision-language model.
---

## Summary

Small vision-language model capable of image understanding and related text tasks. Runs well on modest GPU memory.

## Usage

```bash
ollama run moondream:1.8b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 2 GB |
| Recommended VRAM | 3 GB |
| Min System RAM | 2 GB |
| Recommended System RAM | 4 GB |
