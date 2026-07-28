---
slug: qwen3.6-27b
name: Qwen3.6 27B
provider: Alibaba
license: apache-2.0
branch: hybrid
parameters_b: 27
size_gb: 16.22
quant: Q4_K_M
vram_min_gb: 12
vram_recommended_gb: 16
system_ram_min_gb: 12
system_ram_recommended_gb: 20
context_window: 128000
modalities: [text, tools, thinking]
ollama_tag: qwen3.6:27b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Proven running on 5070 Ti with OLLAMA_NUM_GPU=999 and CUDA_VISIBLE_DEVICES=0. Spills ~2GB to system RAM.
---

## Summary
Qwen3.6 27B is the main heavy local reasoning/tool-use model. It exceeds pure VRAM fit, but runs well with GPU offload plus CPU RAM layers on the 5070 Ti + 31.4 GB RAM host.

## Hardware requirements
- **VRAM:** not fully contained at 16.22 GiB
- **System RAM:** 12–20 GB spare for offload
- **GPU offload:** max GPU layers enabled

## Performance notes
- Proven on this hardware
- Best for deep coding, long reasoning, complex agent plans
- Slower than 9B tier; reserve for non-real-time upstream work

## Local verification
- Ollama tag: `qwen3.6:27b`
- Size from local manifest: 16.22 GiB
- Verified env: `OLLAMA_NUM_GPU=999`, `CUDA_VISIBLE_DEVICES=0`
- Verified host: RTX 5070 Ti 16GB, 31.4 GB RAM

## License/usage restrictions
Apache 2.0 — commercial use allowed.

## Sources
- Local Ollama manifest at `G:\ollama\models\library\manifests\registry.ollama.ai\library\qwen3.6\27b`
