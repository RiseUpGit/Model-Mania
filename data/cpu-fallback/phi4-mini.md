---
slug: phi4-mini
name: Phi 4 Mini Instruct
provider: Microsoft
license: mit
branch: cpu-fallback
parameters_b: 3.8
size_gb: 2.50
quant: Q4_K_M
vram_min_gb: 2
vram_recommended_gb: 4
system_ram_min_gb: 4
system_ram_recommended_gb: 6
context_window: 128000
modalities: [text]
ollama_tag: phi4-mini
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 2.5 GB. Microsoft compact model with strong reasoning/math/code for CPU-only fallback.
---

## Summary

3.8B compact instruct model with strong reasoning, coding, and function-calling support. Intended for CPU or low-VRAM fallback.

## Usage

```bash
ollama run phi4-mini
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 2 GB |
| Recommended VRAM | 4 GB |
| Min System RAM | 4 GB |
| Recommended System RAM | 6 GB |
