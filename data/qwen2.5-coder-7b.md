---
slug: qwen2.5-coder-7b
name: Qwen2.5 Coder 7B
provider: Alibaba
license: apache-2.0
branch: gpu-only
parameters_b: 7
size_gb: 4.70
quant: Q4_K_M
vram_min_gb: 5
vram_recommended_gb: 6
system_ram_min_gb: 4
system_ram_recommended_gb: 6
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:7b
local_verified: false
verified_date: null
verified_by: null
notes: Verified size from ollama.com/library page.
---

## Summary
Qwen2.5 Coder 7B is the first size where Qwen Coder shows strong reasoning on code tasks. Suitable for real-time agent coding with good accuracy.

## Hardware requirements
- **VRAM:** ~4.7 GB
- **System RAM:** 4–6 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Strong code reasoning for mid-size model
- Good for agentic coding workflows

## Local verification
- Size source: ollama.com/library/qwen2.5-coder
- Size: 4.7 GB

## License/usage restrictions
Apache 2.0

## Sources
- https://ollama.com/library/qwen2.5-coder
