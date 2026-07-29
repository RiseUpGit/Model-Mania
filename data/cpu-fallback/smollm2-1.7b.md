---
slug: smollm2-1.7b
name: SmolLM2 1.7B Instruct
provider: HuggingFace SmolLM
license: apache-2.0
branch: cpu-fallback
parameters_b: 1.7
size_gb: 1.80
quant: Q4_K_M
vram_min_gb: 1
vram_recommended_gb: 2
system_ram_min_gb: 2
system_ram_recommended_gb: 4
context_window: 8192
modalities: [text]
ollama_tag: smollm2:1.7b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 1.8 GB. TinyLM-family model ideal for CPU-only fallback.
---

## Summary

1.7B compact instruct model trained on a high-quality dataset. Suitable for CPU-only fallback with minimal RAM.

## Usage

```bash
ollama run smollm2:1.7b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 1 GB |
| Recommended VRAM | 2 GB |
| Min System RAM | 2 GB |
| Recommended System RAM | 4 GB |
