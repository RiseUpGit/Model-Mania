---
slug: gemma2-9b
name: Gemma 2 9B Instruct
provider: Google
license: gemma
branch: gpu-only
parameters_b: 9
size_gb: 5.40
quant: Q4_K_M
vram_min_gb: 6
vram_recommended_gb: 7
system_ram_min_gb: 4
system_ram_recommended_gb: 6
context_window: 8192
modalities: [text]
ollama_tag: gemma2:9b
local_verified: false
verified_date: null
verified_by: null
notes: Size from ollama.com/library.
---

## Summary
Gemma 2 9B is a strong mid-size Google instruct model with good instruction following and safety behavior.

## Hardware requirements
- **VRAM:** ~5.4 GB
- **System RAM:** 4–6 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Competitive with other 9B-tier models
- Good general assistant candidate

## Local verification
- Size source: ollama.com/library
- Size: ~5.4 GB

## License/usage restrictions
Gemma License

## Sources
- https://ollama.com/library/gemma2
