---
slug: qwen3.5-27b
name: Qwen 3.5 27B Instruct
provider: Alibaba
license: apache-2.0
branch: hybrid
parameters_b: 27
size_gb: 17.0
quant: Q4_K_M
vram_min_gb: 16
vram_recommended_gb: 20
system_ram_min_gb: 16
system_ram_recommended_gb: 32
context_window: 32768
modalities: [text]
ollama_tag: qwen3.5:27b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 17 GB. Hybrid GPU+CPU offload required.
---

## Summary

27B parameter Qwen 3.5 model. Highest quality in the Qwen 3.5 local lineup, requires partial system RAM offload.

## Usage

```bash
ollama run qwen3.5:27b
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 16 GB |
| Recommended VRAM | 20 GB |
| Min System RAM | 16 GB |
| Recommended System RAM | 32 GB |
