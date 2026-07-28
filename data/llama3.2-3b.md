---
slug: llama3.2-3b
name: Llama 3.2 3B Instruct
provider: Meta
license: llama3.2
branch: gpu-only
parameters_b: 3
size_gb: 2.00
quant: Q4_K_M
vram_min_gb: 2
vram_recommended_gb: 3
system_ram_min_gb: 2
system_ram_recommended_gb: 4
context_window: 131072
modalities: [text]
ollama_tag: llama3.2:3b
local_verified: false
verified_date: null
verified_by: null
notes: Size from ollama.com/library.
---

## Summary
Llama 3.2 3B is a better-balanced small Meta model with long context. Good for general-purpose lightweight agents.

## Hardware requirements
- **VRAM:** ~2.0 GB
- **System RAM:** 2–4 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Solid upgrade over 1B on reasoning and instruction adherence
- Still lightweight enough for real-time use

## Local verification
- Size source: ollama.com/library
- Size: ~2.0 GB

## License/usage restrictions
Llama 3.2 Community License

## Sources
- https://ollama.com/library/llama3.2
