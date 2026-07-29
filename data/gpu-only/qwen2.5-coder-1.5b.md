---
slug: qwen2.5-coder-1.5b
name: Qwen 2.5 Coder 1.5B Instruct
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 1.5
size_gb: 0.99
quant: Q4_K_M
vram_min_gb: 1
vram_recommended_gb: 2
system_ram_min_gb: 1
system_ram_recommended_gb: 3
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:1.5b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 986 MB. Good balance of speed and coding quality.
---

## Summary

1.5B parameter coding-focused instruct model. Handles larger context than the 0.5B variant while remaining lightweight enough for frequent local use.

## Usage

```bash
ollama run qwen2.5-coder:1.5b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 1 GB |
| Recommended VRAM | 2 GB |
| Min System RAM | 1 GB |
| Recommended System RAM | 3 GB |
