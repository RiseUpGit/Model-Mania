# Hardware Baseline
## Host
- **GPU:** Zotac RTX 5070 Ti 16GB GDDR7
- **VRAM usable:** ~15.9 GiB
- **System RAM:** 31.4 GiB
- **Runtime:** Ollama at localhost:11434
- **Env:** `OLLAMA_NUM_GPU=999`, `CUDA_VISIBLE_DEVICES=0`

## Size thresholds
- **GPU-only safe zone:** model weights ≤ 14 GiB
- **Hybrid practical ceiling:** 14–20 GiB with partial CPU offload
- **Hybrid absolute max:** ~35–45B parameter models run well, up to ~70B usable with aggressive CPU offload
- **100B+:** mostly CPU offload, not real-time

## Quantization rule of thumb
- Q4_K_M ~ 0.7× original model size
- Q5_K_M ~ 0.85× original model size
- Q8_0 ~ 1.0× original model size
- FP16 ~ 1.1× original model size

## Retired hardware
- 1080 Ti retired to shelf, not in active rig
- 5060 Ti is Alex’s gaming card, not used for local AI
