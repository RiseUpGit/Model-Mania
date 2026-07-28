---
slug: qwen2.5-coder-3b
name: Qwen 2.5 Coder 3B Instruct
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 3
size_gb: 1.90
quant: Q4_K_M
vram_min_gb: 2
vram_recommended_gb: 3
system_ram_min_gb: 2
system_ram_recommended_gb: 4
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:3b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 1.9 GB. Strong general-purpose coding model for local use.
---

## Summary

3B parameter coding model with strong instruction following and context handling. Solid default for daily local coding assistance.

## Usage

```bash
ollama run qwen2.5-coder:3b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 2 GB |
| Recommended VRAM | 3 GB |
| Min System RAM | 2 GB |
| Recommended System RAM | 4 GB |
