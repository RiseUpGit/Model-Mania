---
slug: mxbai-embed-large
name: mixedbread AI Large Embeddings
provider: mixedbread.ai
license: apache-2.0
branch: embeddings
parameters_b: null
size_gb: 0.67
quant: null
vram_min_gb: 1
vram_recommended_gb: 2
system_ram_min_gb: 1
system_ram_recommended_gb: 2
context_window: 512
modalities: [text]
ollama_tag: mxbai-embed-large:latest
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Verified on-disk size 669 MB. Lightweight embedding model for retrieval and semantic search.
---

## Summary

Embedding model optimized for retrieval and similarity search. Tiny memory footprint with solid throughput.

## Usage

```bash
ollama run mxbai-embed-large:latest
```

## Hardware

| Metric | Requirement |
|--------|-------------|
| Min VRAM | 1 GB |
| Recommended VRAM | 2 GB |
| Min System RAM | 1 GB |
| Recommended System RAM | 2 GB |
