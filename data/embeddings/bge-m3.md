---
slug: bge-m3
name: BGE M3
provider: BAAI
license: mit
branch: embeddings
parameters_b: null
size_gb: 1.20
quant: null
vram_min_gb: 2
vram_recommended_gb: 3
system_ram_min_gb: 2
system_ram_recommended_gb: 4
context_window: 8192
modalities: [text]
ollama_tag: bge-m3:latest
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 1.2 GB. Multilingual embedding model with longer context.
---

## Summary

Multilingual embedding model with broader context and dense/sparse output support. Good baseline for multilingual search.

## Usage

```bash
ollama run bge-m3:latest
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 2 GB |
| Recommended VRAM | 3 GB |
| Min System RAM | 2 GB |
| Recommended System RAM | 4 GB |
