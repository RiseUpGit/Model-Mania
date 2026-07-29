---
slug: llava-13b
name: LLaVA 1.6 13B
provider: haotian-liu / Microsoft
license: apache-2.0
branch: vision
parameters_b: 13
size_gb: 8.00
quant: Q4_K_M
vram_min_gb: 9
vram_recommended_gb: 10
system_ram_min_gb: 6
system_ram_recommended_gb: 10
context_window: 4096
modalities: [text, vision]
ollama_tag: llava:13b
local_verified: false
verified_date: null
verified_by: null
notes: Size is typical/official estimate; not verified from local manifest.
---

## Summary
LLaVA 13B offers a meaningful quality jump over 7B on complex visual reasoning while still fitting on a 16GB GPU.

## Hardware requirements
- **VRAM:** ~8 GB
- **System RAM:** 6–10 GB spare
- **GPU offload:** fully GPU viable

## Performance notes
- Stronger than 7B on images charts/diagrams
- Still responsive enough for local use

## Local verification
- Size source: public/official estimate
- Size: ~8 GB

## License/usage restrictions
Apache 2.0

## Sources
- https://ollama.com/library/llava
