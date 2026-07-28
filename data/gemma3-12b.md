---
slug: gemma3-12b
name: Gemma 3 12B Instruct
provider: Google
license: gemma
branch: vision
parameters_b: 12
size_gb: 8.10
quant: Q4_K_M
vram_min_gb: 9
vram_recommended_gb: 10
system_ram_min_gb: 8
system_ram_recommended_gb: 16
context_window: 128000
modalities: [text, vision]
ollama_tag: gemma3:12b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 8.1 GB. Multimodal 128K context model.
---

## Summary

12B multimodal instruct model with image understanding and a 128K context window. Best compact vision option that still fits on the 5070 Ti.

## Usage

```bash
ollama run gemma3:12b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 9 GB |
| Recommended VRAM | 10 GB |
| Min System RAM | 8 GB |
| Recommended System RAM | 16 GB |
