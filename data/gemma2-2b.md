---
slug: gemma2-2b
name: Gemma 2 2B Instruct
provider: Google
license: gemma
branch: gpu-only
parameters_b: 2
size_gb: 1.60
quant: Q4_K_M
vram_min_gb: 2
vram_recommended_gb: 3
system_ram_min_gb: 2
system_ram_recommended_gb: 4
context_window: 8192
modalities: [text]
ollama_tag: gemma2:2b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 1.6 GB. Compact text-only instruct model.
---

## Summary

Text-only 2B instruct model. Excellent lightweight baseline when you want low latency and minimal VRAM.

## Usage

```bash
ollama run gemma2:2b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 2 GB |
| Recommended VRAM | 3 GB |
| Min System RAM | 2 GB |
| Recommended System RAM | 4 GB |
