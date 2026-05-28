### 💻 HARDWARE COMPATIBILITY & DEPLOYMENT MATRIX (ACE OS v8.0)

Before compiling the state registry, ensure your runtime processor matches the required token density. Hallucinations and syntax degradation are deterministic hardware errors.
WARNING: The proposed examples of real LLM models are not responsible for the result of work on these models themselves, they show the necessary technical level for operation.

| Hardware Tier | System Verdict | Target Models (Examples) | Failure Mode if Violated |
| :--- | :--- | :--- | :--- |
| **Cloud APIs** | 👑 ULTIMATE TARGET | Google Gemini 3.1 Pro, Claude Opus 4.7, GPT-5.5 | None. Flawless Prose Lock and maximum context caching efficiency. |
| **Enterprise (≥70B)** | 🟢 ABSOLUTE STABLE | Mistral Large 3 (675B), Qwen3-235B-A22B, Llama 4 Maverick | Pristine logic parsing. Requires high-VRAM local compute hosting nodes. |
| **Enthusiast (32B-70B)**| 🟢 FULLY COMPATIBLE| Gemma 4 31B, Qwen3-32B, Llama 4 Scout (109B MoE) | Stable operation. Requires dynamic hot-swapping every 25-30 steps. |
| **Transition (16B-32B)**| 🟡 PARTIAL ONLY | Gemma 4 26B MoE, Qwen3-14B | Syntactic drift occurs by step 10. Only suitable for basic unit testing. |
| **Lightweight (8B-16B)**| 🔴 NOT RECOMMENDED| Qwen3-8B, Llama 3.1 8B | Complete execution failure. Instant logic decay and JSON breakdown. |
