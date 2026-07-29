---
slug: gemma4-12b
name: Gemma 4 12B Instruct
provider: Google
license: gemma
branch: vision
parameters_b: 12
size_gb: 7.60
quant: Q4_K_M
vram_min_gb: 8
vram_recommended_gb: 10
system_ram_min_gb: 8
system_ram_recommended_gb: 16
context_window: 128000
modalities: [text, vision]
ollama_tag: gemma4:12b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 7.6 GB. Workstation-grade multimodal model.
---

## Summary

12B workstation multimodal model with image understanding. High-quality vision tasks on a single GPU.

## Usage

```bash
ollama run gemma4:12b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 8 GB |
| Recommended VRAM | 10 GB |
| Min System RAM | 8 GB |
| Recommended System RAM | 16 GB |
