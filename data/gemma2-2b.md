---
slug: gemma2-2b
name: Gemma 2 2B Instruct
provider: Google
license: gemma
branch: gpu-only
parameters_b: 2
size_gb: 1.60
quant: Q4_K_M
vram_min_gb: 2
vram_recommended_gb: 3
system_ram_min_gb: 2
system_ram_recommended_gb: 3
context_window: 8192
modalities: [text]
ollama_tag: gemma2:2b
local_verified: false
verified_date: null
verified_by: null
notes: Size from ollama.com/library.
---

## Summary
Gemma 2 2B is a compact Google instruct model. Good for small-footprint chat and fallback agents.

## Hardware requirements
- **VRAM:** ~1.6 GB
- **System RAM:** 2–3 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Efficient and fast
- Weak on very complex reasoning compared to larger models

## Local verification
- Size source: ollama.com/library
- Size: ~1.6 GB

## License/usage restrictions
Gemma License

## Sources
- https://ollama.com/library/gemma2
