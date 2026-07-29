---
slug: tinyllama
name: TinyLlama 1.1B Instruct
provider: TinyLlama
license: apache-2.0
branch: cpu-fallback
parameters_b: 1.1
size_gb: 0.637
quant: Q4_K_M
vram_min_gb: 1
vram_recommended_gb: 2
system_ram_min_gb: 1
system_ram_recommended_gb: 2
context_window: 2048
modalities: [text]
ollama_tag: tinyllama
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 637 MB. Ultra-light CPU/edge fallback model.
---

## Summary

1.1B ultra-compact instruct model. Minimal resource use for CPU-only fallback or embedded use.

## Usage

```bash
ollama run tinyllama
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 1 GB |
| Recommended VRAM | 2 GB |
| Min System RAM | 1 GB |
| Recommended System RAM | 2 GB |
