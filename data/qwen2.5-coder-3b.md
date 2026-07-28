---
slug: qwen2.5-coder-3b
name: Qwen2.5 Coder 3B
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 3
size_gb: 1.90
quant: Q4_K_M
vram_min_gb: 2
vram_recommended_gb: 3
system_ram_min_gb: 2
system_ram_recommended_gb: 4
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:3b
local_verified: false
verified_date: null
verified_by: null
notes: Verified size from ollama.com/library page.
---

## Summary
Qwen2.5 Coder 3B is a compact code-focused model with solid instruction following. Good default for lightweight coding agents and inline edits.

## Hardware requirements
- **VRAM:** ~1.9 GB
- **System RAM:** 2–4 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Good speed/quality tradeoff for local coding assist
- Handles single-file generation and repair well

## Local verification
- Size source: ollama.com/library/qwen2.5-coder
- Size: 1.9 GB

## License/usage restrictions
Apache 2.0

## Sources
- https://ollama.com/library/qwen2.5-coder
