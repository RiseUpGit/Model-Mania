# Model Mania
**Local-first open-weight model catalog for RTX 5070 Ti 16GB + 31.4 GB RAM**

## Purpose
Single source of truth for every free/open-weight model that can run locally on a standalone 5070 Ti. Organized by execution branch for runtime routing in AI Tracker / Hermes workflows.

## Hardware Baseline
- **GPU:** RTX 5070 Ti 16GB VRAM
- **System RAM:** 31.4 GB
- **Ollama runtime:** localhost:11434
- **Verified env:** `OLLAMA_NUM_GPU=999`, `CUDA_VISIBLE_DEVICES=0`

## Branches
- `gpu-only/` — weights fit fully in VRAM
- `hybrid/` — partial GPU offload + CPU RAM layers
- `cpu-fallback/` — no GPU offload
- `embeddings/` — embedding/retrieval
- `vision/` — multimodal image-capable
- `audio/` — speech/audio

## Verification Rule
No entry is accepted without one of:
- local Ollama manifest size + runtime evidence
- official model card size
- documented quant size from a verifiable source

### Sizing provenance tags
- `local_verified: true` — confirmed from local Ollama manifest + runtime
- `local_verified: false` + `verified_date: null` — size from Ollama library page or public estimate only; recheck before first pull

## Workflow
1. Identify candidate
2. Record exact size from manifest/model card
3. Test on host
4. Write catalog entry
5. Commit with evidence path
