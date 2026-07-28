---
slug: qwen2.5-3b
name: Qwen2.5 3B Instruct
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 3
size_gb: 1.80
quant: Q4_K_M
vram_min_gb: 2
vram_recommended_gb: 3
system_ram_min_gb: 2
system_ram_recommended_gb: 4
context_window: 32768
modalities: [text, tools]
ollama_tag: qwen2.5:3b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Small general-purpose Qwen2.5 instruct model. Fully GPU-offloaded on 5070 Ti.
---

## Summary
Qwen2.5 3B is a compact instruct-tuned model with solid tool-use behavior for its size. Good for lightweight agent routing and quick UI responses.

## Hardware requirements
- **VRAM:** ~1.8 GB model weights
- **System RAM:** 2–4 GB spare
- **GPU offload:** fully GPU

## Performance notes
- High throughput on RTX 5070 Ti
- Best-fit candidate for tier-1 conversational agents

## Local verification
- Ollama tag: `qwen2.5:3b`
- Size from local manifest: 1.80 GB

## License/usage restrictions
Apache 2.0 — commercial use allowed.

## Sources
- Local Ollama manifest at `G:\ollama\models\library\manifests\registry.ollama.ai\library\qwen2.5\3b`
