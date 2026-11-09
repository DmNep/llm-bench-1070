### Generation speed, tokens/s (prompt of the given size already in context)

| Model | Params | Quant | Ctx | 1K | 4K | 16K | 25K |
|---|---|---|---:|---:|---:|---:|---:|
| Qwen3.8-Flash-Next unsloth-UD-IQ4_XS (llama.cpp, n-cpu-moe 47, GTX1070 8GB) | 125B-A6B | UD-IQ4_XS | 32768 | 4.9 | 4.6 | 1.6 | 1.5 |

### Prompt reading (prefill) speed, tokens/s

| Model | Params | Quant | Ctx | 1K | 4K | 16K | 25K |
|---|---|---|---:|---:|---:|---:|---:|
| Qwen3.8-Flash-Next unsloth-UD-IQ4_XS (llama.cpp, n-cpu-moe 47, GTX1070 8GB) | 125B-A6B | UD-IQ4_XS | 32768 | 64.0 | 79.1 | 18.1 | 13.0 |

### Memory reported by the engine after the runs (Ollama; for llama.cpp the value is given by hand from nvidia-smi, if any)

| Model | Reported VRAM, GB | Reported total, GB |
|---|---:|---:|
| Qwen3.8-Flash-Next unsloth-UD-IQ4_XS (llama.cpp, n-cpu-moe 47, GTX1070 8GB) | 7.8 | n/a |

