---
slug: llava-34b
name: LLaVA 1.6 34B
provider: haotian-liu / Microsoft
license: apache-2.0
branch: hybrid
parameters_b: 34
size_gb: 20.0
quant: Q4_K_M
vram_min_gb: 16
vram_recommended_gb: 20
system_ram_min_gb: 16
system_ram_recommended_gb: 24
context_window: 4096
modalities: [text, vision]
ollama_tag: llava:34b
local_verified: false
verified_date: null
verified_by: null
notes: Exceeds 5070 Ti VRAM; hybrid CPU+GPU mode required. Size is typical/official estimate.
---

## Summary
LLaVA 34B is the largest LLaVA model with strong multimodal reasoning. Use for high-quality image analysis when latency is secondary.

## Hardware requirements
- **VRAM:** 20 GB class
- **System RAM:** 16–24 GB spare for hybrid
- **GPU offload:** partial GPU + CPU layers

## Performance notes
- Best local vision quality in the LLaVA line
- Slower; not for real-time UI

## Local verification
- Size source: public/official estimate
- Size: ~20 GB

## License/usage restrictions
Apache 2.0

## Sources
- https://ollama.com/library/llava
