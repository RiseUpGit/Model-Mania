---
slug: llama3.2-1b
name: Llama 3.2 1B Instruct
provider: Meta
license: llama3.2
branch: gpu-only
parameters_b: 1
size_gb: 0.70
quant: Q4_K_M
vram_min_gb: 1
vram_recommended_gb: 2
system_ram_min_gb: 1
system_ram_recommended_gb: 2
context_window: 131072
modalities: [text]
ollama_tag: llama3.2:1b
local_verified: false
verified_date: null
verified_by: null
notes: Compact Meta instruct model with very large context. Size from ollama.com/library.
---

## Summary
Llama 3.2 1B is Meta’s small-footprint instruct model with a very large context window. Useful for fast lightweight chat and preprocessing.

## Hardware requirements
- **VRAM:** ~0.7 GB
- **System RAM:** 1–2 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Fast and efficient
- Weak on complex reasoning vs larger models

## Local verification
- Size source: ollama.com/library
- Size: ~0.7 GB

## License/usage restrictions
Llama 3.2 Community License

## Sources
- https://ollama.com/library/llama3.2
