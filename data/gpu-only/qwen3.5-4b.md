---
slug: qwen3.5-4b
name: Qwen 3.5 4B Instruct
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 4
size_gb: 3.40
quant: Q4_K_M
vram_min_gb: 4
vram_recommended_gb: 5
system_ram_min_gb: 3
system_ram_recommended_gb: 6
context_window: 32768
modalities: [text]
ollama_tag: qwen3.5:4b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 3.4 GB. Strong quality within a small footprint.
---

## Summary

4B parameter Qwen 3.5 model. Strong instruction following and context handling for local use.

## Usage

```bash
ollama run qwen3.5:4b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 4 GB |
| Recommended VRAM | 5 GB |
| Min System RAM | 3 GB |
| Recommended System RAM | 6 GB |
