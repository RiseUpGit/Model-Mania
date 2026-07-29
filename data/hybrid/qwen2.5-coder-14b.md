---
slug: qwen2.5-coder-14b
name: Qwen 2.5 Coder 14B Instruct
provider: Alibaba
license: apache-2.0
branch: hybrid
parameters_b: 14
size_gb: 9.00
quant: Q4_K_M
vram_min_gb: 9
vram_recommended_gb: 12
system_ram_min_gb: 8
system_ram_recommended_gb: 16
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:14b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 9.0 GB. Best coding quality in the qwen2.5-coder local lineup.
---

## Summary

14B parameter coding model with top-tier code generation and reasoning. Completes the hybrid branch on this hardware.

## Usage

```bash
ollama run qwen2.5-coder:14b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 9 GB |
| Recommended VRAM | 12 GB |
| Min System RAM | 8 GB |
| Recommended System RAM | 16 GB |
