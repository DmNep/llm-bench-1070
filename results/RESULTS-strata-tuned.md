### Generation speed, tokens/s (prompt of the given size already in context)

| Model | Params | Quant | Ctx | 1K | 4K | 16K | 25K |
|---|---|---|---:|---:|---:|---:|---:|
| Qwen3.8-Flash-Next unsloth-UD-IQ4_XS (Strata, GTX1070 8GB, NVMe, host-core sibling + expert-cache-per-layer) | 125B | UD-IQ4_XS | 32768 | 15.3 | 15.3 | 15.2 | 15.1 |

### Prompt reading (prefill) speed, tokens/s

| Model | Params | Quant | Ctx | 1K | 4K | 16K | 25K |
|---|---|---|---:|---:|---:|---:|---:|
| Qwen3.8-Flash-Next unsloth-UD-IQ4_XS (Strata, GTX1070 8GB, NVMe, host-core sibling + expert-cache-per-layer) | 125B | UD-IQ4_XS | 32768 | 237.6 | 224.9 | 236.5 | 237.6 |

### Memory reported by the engine after the runs (Ollama; for llama.cpp the value is given by hand from nvidia-smi, if any)

| Model | Reported VRAM, GB | Reported total, GB |
|---|---:|---:|
| Qwen3.8-Flash-Next unsloth-UD-IQ4_XS (Strata, GTX1070 8GB, NVMe, host-core sibling + expert-cache-per-layer) | 8.0 | n/a |

