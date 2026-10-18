# Hi, I'm Wang Yihan. (Frankl)

**AI Infra / LLM Inference intern** — CUDA, distributed inference, vLLM/nano-vllm.

I build and profile GPU kernels, study LLM inference systems end-to-end, and
write about what I learn. I'm working toward an internship in AI infrastructure,
with a focus on CUDA operator optimization and LLM serving.

## 🛠 Tech Stack

- **Languages:** C++17 · Python · C
- **Parallel:** CUDA · Triton · MPI · OpenMP · NCCL
- **Inference:** vLLM · PyTorch · PagedAttention · Continuous Batching · KV Cache · FlashAttention · AWQ/GPTQ
- **Distributed:** Tensor Parallel · DDP · AllReduce · RDMA/NVLink (fundamentals)
- **Tools:** Linux · CMake · Git · Nsight Compute · nsys · nvidia-smi · nccl-tests

## 🔭 Current Work

- CUDA operator optimization: tiled SGEMM, Softmax, profiling with Nsight Compute
- nano-vllm source study: PagedAttention, Continuous Batching, KV-cache management
- vLLM / nano-vllm open-source contribution (PRs below)
- Technical blog: [wyh1309.github.io](https://wyh1309.github.io)

## 📌 Pinned Repositories

1. **[cuda-sgemm-opt](https://github.com/wyh1309/cuda-sgemm-opt)** — tiled SGEMM optimization,
   naive → bank-conflict-free, with Nsight Compute profiling and GFLOPS analysis.
2. **[nano-vllm-study](https://github.com/wyh1309/nano-vllm-study)** — PagedAttention,
   Continuous Batching, and scheduler source analysis + secondary-development feature.
3. **[llm-quant-benchmark](https://github.com/wyh1309/llm-quant-benchmark)** — AWQ/GPTQ
   quantization benchmark on a 7B model: TTFT / TPOT / throughput / VRAM.
4. **[tensor-parallel-inference](https://github.com/wyh1309/tensor-parallel-inference)** —
   2-GPU tensor parallel inference with NCCL communication overhead analysis.
5. **[gqa-decoder](https://github.com/wyh1309/gqa-decoder)** — hand-written GQA decoder
   layer with KV cache (inference path).
6. **[ai-infra-notes](https://github.com/wyh1309/ai-infra-notes)** — learning notes:
   OS → PagedAttention, GPU/CUDA, distributed inference, interview prep.

## 🤝 Open Source Contributions

| PR | Repo | Status |
|----|------|--------|
| [Doc] link to PR here | vLLM | merged / submitted |
| [Doc] link to PR here | nano-vllm | merged / submitted |
| [Feature] link to PR here | nano-vllm | submitted |

## 📫 Contact

- Email: `2105230337@qq.com`


---

> Note to self: each project repo's own README must contain **performance numbers,
> profiling screenshots, reproduction steps, and an architecture diagram**.
