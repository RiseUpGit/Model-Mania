# Catalog Entry Schema
Every model gets one markdown file under `data/` named `<slug>.md`.

## Frontmatter
```yaml
---
slug: qwen3.6-27b
name: Qwen3.6 27B
provider: Alibaba
license: apache-2.0
branch: hybrid
parameters_b: 27
size_gb: 16.2
quant: Q4_K_M
vram_min_gb: 12
vram_recommended_gb: 16
system_ram_min_gb: 12
system_ram_recommended_gb: 20
context_window: 128000
modalities: [text, tools, thinking]
ollama_tag: qwen3.6:27b
local_verified: true
verified_date: 2026-07-28
verified_by: Newton
notes: Proven running on 5070 Ti with OLLAMA_NUM_GPU=999, spills ~2GB to system RAM.
---
```

## Required sections
1. Summary
2. Hardware requirements
3. Performance notes
4. Local verification
5. License/usage restrictions
6. Sources
