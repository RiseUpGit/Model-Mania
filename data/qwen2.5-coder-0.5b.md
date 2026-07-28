---
slug: qwen2.5-coder-0.5b
name: Qwen2.5 Coder 0.5B
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 0.5
size_gb: 0.40
quant: Q4_K_M
vram_min_gb: 0.5
vram_recommended_gb: 1
system_ram_min_gb: 1
system_ram_recommended_gb: 2
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:0.5b
local_verified: false
verified_date: null
verified_by: null
notes: Tiny code model. Verified size from ollama.com/library page.
---

## Summary
Qwen2.5 Coder 0.5B is the smallest code-specific Qwen model. Useful for ultra-lightweight code completion and preprocessing where latency matters more than depth.

## Hardware requirements
- **VRAM:** ~398 MB
- **System RAM:** 1–2 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Extremely fast
- Limited reasoning depth
- Best for simple autocomplete or triage

## Local verification
- Size source: ollama.com/library/qwen2.5-coder
- Size: 398 MB

## License/usage restrictions
Apache 2.0

## Sources
- https://ollama.com/library/qwen2.5-coder
