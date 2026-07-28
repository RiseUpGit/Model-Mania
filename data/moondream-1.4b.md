---
slug: moondream-1.4b
name: Moondream 1.4B
provider: vikhyatk / Moondream
license: apache-2.0
branch: vision
parameters_b: 1.4
size_gb: 1.00
quant: Q4_K_M
vram_min_gb: 1
vram_recommended_gb: 2
system_ram_min_gb: 1
system_ram_recommended_gb: 2
context_window: 4096
modalities: [text, vision]
ollama_tag: moondream:1.4b
local_verified: false
verified_date: null
verified_by: null
notes: Small efficient vision model. Size is typical/official estimate.
---

## Summary
Moondream 1.4B is a tiny vision-language model optimized for efficiency. Good for fast image captioning and simple VQA on edge/local hardware.

## Hardware requirements
- **VRAM:** ~1 GB
- **System RAM:** 1–2 GB spare
- **GPU offload:** fully GPU

## Performance notes
- Very fast
- Limited reasoning depth vs larger vision models

## Local verification
- Size source: public/official estimate
- Size: ~1 GB

## License/usage restrictions
Apache 2.0

## Sources
- https://ollama.com/library/moondream
