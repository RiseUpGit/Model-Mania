---
slug: qwen2.5-coder-1.5b
name: Qwen2.5 Coder 1.5B
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 1.5
size_gb: 0.99
quant: Q4_K_M
vram_min_gb: 1
vram_recommended_gb: 2
system_ram_min_gb: 1
system_ram_recommended_gb: 2
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:1.5b
local_verified: false
verified_date: null
verified_by: null
notes: Small code model. Verified size from ollama.com/library page.
---

## Summary
Qwen2.5 Coder 1.5B offers a meaningful step up from 0.5B while staying tiny. Good for simple code generation tasks and quick edits.

## Hardware requirements
- **VRAM:** ~986 MB
- **System RAM:** 1–2 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Fast with noticeably better code quality than 0.5B
- Still limited on complex multi-file reasoning

## Local verification
- Size source: ollama.com/library/qwen2.5-coder
- Size: 986 MB

## License/usage restrictions
Apache 2.0

## Sources
- https://ollama.com/library/qwen2.5-coder
