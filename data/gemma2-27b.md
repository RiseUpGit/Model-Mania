---
slug: gemma2-27b
name: Gemma 2 27B Instruct
provider: Google
license: gemma
branch: hybrid
parameters_b: 27
size_gb: 15.0
quant: Q4_K_M
vram_min_gb: 16
vram_recommended_gb: 20
system_ram_min_gb: 16
system_ram_recommended_gb: 32
context_window: 8192
modalities: [text]
ollama_tag: gemma2:27b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 15 GB. Hybrid GPU+RAM required.
---

## Summary

Largest Gemma 2 text instruct variant. Strong reasoning, but needs partial CPU offload on this hardware.

## Usage

```bash
ollama run gemma2:27b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 16 GB |
| Recommended VRAM | 20 GB |
| Min System RAM | 16 GB |
| Recommended System RAM | 32 GB |
