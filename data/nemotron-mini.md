---
slug: nemotron-mini
name: Nemotron Mini
provider: NVIDIA
license: apache-2.0
branch: gpu-only
parameters_b: null
size_gb: 2.51
quant: Q4_K_M
vram_min_gb: 3
vram_recommended_gb: 4
system_ram_min_gb: 2
system_ram_recommended_gb: 4
context_window: 8192
modalities: [text]
ollama_tag: nemotron-mini:latest
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Lightweight instruct/chat model. Easily fits fully on 5070 Ti.
---

## Summary
Nemotron Mini is a small open-weight chat/instruct model best suited for fast local chat, lightweight tool routing, and fallback generation.

## Hardware requirements
- **VRAM:** ~2.5 GB model weights
- **System RAM:** 2–4 GB spare
- **GPU offload:** fully GPU

## Performance notes
- High tok/s on RTX 5070 Ti
- Best for low-latency UI agents and router fallback

## Local verification
- Ollama tag: `nemotron-mini:latest`
- Size from local manifest: 2.51 GB

## License/usage restrictions
Apache 2.0 — commercial use allowed with attribution.

## Sources
- Local Ollama manifest at `G:\ollama\models\library\manifests\registry.ollama.ai\library\nemotron-mini\latest`
