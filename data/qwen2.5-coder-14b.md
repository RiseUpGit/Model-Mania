---
slug: qwen2.5-coder-14b
name: Qwen2.5 Coder 14B
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 14
size_gb: 9.00
quant: Q4_K_M
vram_min_gb: 9
vram_recommended_gb: 10
system_ram_min_gb: 6
system_ram_recommended_gb: 10
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:14b
local_verified: false
verified_date: null
verified_by: null
notes: Verified size from ollama.com/library page.
---

## Summary
Qwen2.5 Coder 14B is a high-capability local coding model within direct VRAM budget. Good for deep code generation and multi-step repair.

## Hardware requirements
- **VRAM:** ~9.0 GB
- **System RAM:** 6–10 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Strong local alternative to larger closed models
- Slower than 7B, but meaningfully better on hard tasks

## Local verification
- Size source: ollama.com/library/qwen2.5-coder
- Size: 9.0 GB

## License/usage restrictions
Apache 2.0

## Sources
- https://ollama.com/library/qwen2.5-coder
