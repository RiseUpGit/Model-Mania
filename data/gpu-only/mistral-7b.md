---
slug: mistral-7b
name: Mistral 7B Instruct v0.3
provider: Mistral AI
license: apache-2.0
branch: gpu-only
parameters_b: 7
size_gb: 4.50
quant: Q4_K_M
vram_min_gb: 5
vram_recommended_gb: 6
system_ram_min_gb: 3
system_ram_recommended_gb: 5
context_window: 32768
modalities: [text]
ollama_tag: mistral:7b
local_verified: false
verified_date: null
verified_by: null
notes: Size from ollama.com/library.
---

## Summary
Mistral 7B Instruct v0.3 is a proven general-purpose instruct model. Compact, fast, and commercially friendly.

## Hardware requirements
- **VRAM:** ~4.5 GB
- **System RAM:** 3–5 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Good general chat/code balance
- Mature tool-use behavior in Ollama

## Local verification
- Size source: ollama.com/library
- Size: ~4.5 GB

## License/usage restrictions
Apache 2.0

## Sources
- https://ollama.com/library/mistral
