---
slug: qwen3.5-9b
name: Qwen3.5 9B
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 9
size_gb: 6.14
quant: Q4_K_M
vram_min_gb: 6
vram_recommended_gb: 8
system_ram_min_gb: 4
system_ram_recommended_gb: 8
context_window: 128000
modalities: [text, tools, thinking]
ollama_tag: qwen3.5:9b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Fits fully on 5070 Ti with headroom. Strong tool/thinking balance for mid-size workloads.
---

## Summary
Qwen3.5 9B is a mid-size model with good tool-use and thinking behavior. Primary general-purpose agent model when 27B is too expensive for real-time use.

## Hardware requirements
- **VRAM:** ~6.1 GB model weights
- **System RAM:** 4–8 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Solid tok/s on 5070 Ti
- Good default assistant/routing model

## Local verification
- Ollama tag: `qwen3.5:9b`
- Size from local manifest: 6.14 GB

## License/usage restrictions
Apache 2.0 — commercial use allowed.

## Sources
- Local Ollama manifest at `G:\ollama\models\library\manifests\registry.ollama.ai\library\qwen3.5\9b`
