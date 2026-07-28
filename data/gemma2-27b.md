---
slug: gemma2-27b
name: Gemma 2 27B Instruct
provider: Google
license: gemma
branch: hybrid
parameters_b: 27
size_gb: 16.0
quant: Q4_K_M
vram_min_gb: 12
vram_recommended_gb: 16
system_ram_min_gb: 12
system_ram_recommended_gb: 20
context_window: 8192
modalities: [text]
ollama_tag: gemma2:27b
local_verified: false
verified_date: null
verified_by: null
notes: Size from ollama.com/library. Near/at VRAM ceiling on 5070 Ti; likely needs hybrid mode.
---

## Summary
Gemma 2 27B is the largest Gemma 2 model. High-quality general-purpose reasoning, but at the edge of single-GPU fit.

## Hardware requirements
- **VRAM:** near/at 16 GB ceiling
- **System RAM:** 12–20 GB spare for hybrid
- **GPU offload:** partial; hybrid likely needed

## Performance notes
- Strong for general reasoning and chat
- Reserve for non-real-time tasks

## Local verification
- Size source: ollama.com/library
- Size: ~16.0 GB

## License/usage restrictions
Gemma License

## Sources
- https://ollama.com/library/gemma2
