---
slug: gemma4-e2b
name: Gemma 4 E2B Instruct
provider: Google
license: gemma
branch: vision
parameters_b: 2.3
size_gb: 7.20
quant: Q4_K_M
vram_min_gb: 8
vram_recommended_gb: 9
system_ram_min_gb: 6
system_ram_recommended_gb: 10
context_window: 128000
modalities: [text, vision, audio]
ollama_tag: gemma4:e2b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 7.2 GB. Edge multimodal model with vision+audio.
---

## Summary

Effective 2.3B multimodal model with image and audio understanding. Compact enough for frequent local use despite larger quantized size.

## Usage

```bash
ollama run gemma4:e2b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 8 GB |
| Recommended VRAM | 9 GB |
| Min System RAM | 6 GB |
| Recommended System RAM | 10 GB |
