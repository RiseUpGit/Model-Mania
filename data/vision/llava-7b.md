---
slug: llava-7b
name: LLaVA 1.6 7B
provider: haotian-liu / Microsoft
license: apache-2.0
branch: vision
parameters_b: 7
size_gb: 4.70
quant: Q4_K_M
vram_min_gb: 5
vram_recommended_gb: 6
system_ram_min_gb: 4
system_ram_recommended_gb: 6
context_window: 4096
modalities: [text, vision]
ollama_tag: llava:7b
local_verified: false
verified_date: null
verified_by: null
notes: Size is typical/official estimate; not verified from local manifest.
---

## Summary
LLaVA 1.6 7B is an end-to-end vision-language model for general-purpose visual question answering and image understanding.

## Hardware requirements
- **VRAM:** ~4.7 GB
- **System RAM:** 4–6 GB spare
- **GPU offload:** fully GPU viable

## Performance notes
- Strong general vision/Q&A
- Good baseline multimodal model

## Local verification
- Size source: public/official estimate
- Size: ~4.7 GB

## License/usage restrictions
Apache 2.0

## Sources
- https://ollama.com/library/llava
