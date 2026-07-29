---
slug: gemma4-e4b
name: Gemma 4 E4B Instruct
provider: Google
license: gemma
branch: vision
parameters_b: 4.5
size_gb: 9.60
quant: Q4_K_M
vram_min_gb: 10
vram_recommended_gb: 11
system_ram_min_gb: 8
system_ram_recommended_gb: 16
context_window: 128000
modalities: [text, vision, audio]
ollama_tag: gemma4:e4b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 9.6 GB. Strong multimodal edge model.
---

## Summary

Effective 4.5B multimodal model with vision and audio. Fits on the 5070 Ti with comfortable headroom.

## Usage

```bash
ollama run gemma4:e4b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 10 GB |
| Recommended VRAM | 11 GB |
| Min System RAM | 8 GB |
| Recommended System RAM | 16 GB |
