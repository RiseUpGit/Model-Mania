---
slug: qwen3.5-2b
name: Qwen 3.5 2B Instruct
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 2
size_gb: 2.70
quant: Q4_K_M
vram_min_gb: 3
vram_recommended_gb: 4
system_ram_min_gb: 2
system_ram_recommended_gb: 4
context_window: 32768
modalities: [text]
ollama_tag: qwen3.5:2b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 2.7 GB. Balanced local model for daily coding and chat.
---

## Summary

2B parameter Qwen 3.5 model. Good balance of speed and quality for local assistive coding.

## Usage

```bash
ollama run qwen3.5:2b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 3 GB |
| Recommended VRAM | 4 GB |
| Min System RAM | 2 GB |
| Recommended System RAM | 4 GB |
