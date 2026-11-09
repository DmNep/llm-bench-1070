### Generation speed, tokens/s (prompt of the given size already in context)

| Model | Params | Quant | Ctx | 1K | 4K | 16K | 25K |
|---|---|---|---:|---:|---:|---:|---:|
| Qwen3.8-Flash-Next unsloth-UD-IQ4_XS (Strata, GTX1070 8GB, NVMe) | 125B | UD-IQ4_XS | 32768 | 14.0 | 14.1 | 14.3 | 13.9 |

### Prompt reading (prefill) speed, tokens/s

| Model | Params | Quant | Ctx | 1K | 4K | 16K | 25K |
|---|---|---|---:|---:|---:|---:|---:|
| Qwen3.8-Flash-Next unsloth-UD-IQ4_XS (Strata, GTX1070 8GB, NVMe) | 125B | UD-IQ4_XS | 32768 | 151.4 | 214.2 | 225.8 | 228.0 |

### Memory reported by the engine after the runs (Ollama; for llama.cpp the value is given by hand from nvidia-smi, if any)

| Model | Reported VRAM, GB | Reported total, GB |
|---|---:|---:|
| Qwen3.8-Flash-Next unsloth-UD-IQ4_XS (Strata, GTX1070 8GB, NVMe) | 8.0 | n/a |

