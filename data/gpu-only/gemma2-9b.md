---
slug: gemma2-9b
name: Gemma 2 9B Instruct
provider: Google
license: gemma
branch: gpu-only
parameters_b: 9
size_gb: 5.40
quant: Q4_K_M
vram_min_gb: 6
vram_recommended_gb: 7
system_ram_min_gb: 4
system_ram_recommended_gb: 8
context_window: 8192
modalities: [text]
ollama_tag: gemma2:9b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 5.4 GB. Strong text quality at mid-size.
---

## Summary

9B text instruct model. Solid general-purpose quality on a single GPU.

## Usage

```bash
ollama run gemma2:9b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 6 GB |
| Recommended VRAM | 7 GB |
| Min System RAM | 4 GB |
| Recommended System RAM | 8 GB |
