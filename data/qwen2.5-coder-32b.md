---
slug: qwen2.5-coder-32b
name: Qwen2.5 Coder 32B
provider: Alibaba
license: apache-2.0
branch: hybrid
parameters_b: 32
size_gb: 20.0
quant: Q4_K_M
vram_min_gb: 16
vram_recommended_gb: 20
system_ram_min_gb: 16
system_ram_recommended_gb: 24
context_window: 32768
modalities: [text]
ollama_tag: qwen2.5-coder:32b
local_verified: false
verified_date: null
verified_by: null
notes: Verified size from ollama.com/library page. Exceeds 5070 Ti VRAM; hybrid CPU+GPU mode required.
---

## Summary
Qwen2.5 Coder 32B is the code-specialist flagship in this family. It competes with much larger closed models on coding benchmarks, but requires CPU+GPU hybrid execution on this hardware.

## Hardware requirements
- **VRAM:** 20 GB — exceeds 5070 Ti
- **System RAM:** 16–24 GB spare for hybrid offload
- **GPU offload:** partial GPU layer offload

## Performance notes
- Best local code quality in the Qwen2.5 Coder line
- Use for non-real-time heavy coding tasks only
- Will be slower than 14B tier

## Local verification
- Size source: ollama.com/library/qwen2.5-coder
- Size: 20 GB

## License/usage restrictions
Apache 2.0

## Sources
- https://ollama.com/library/qwen2.5-coder
