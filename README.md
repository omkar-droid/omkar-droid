# 👋 Hi, I'm Omkar Shewale

**LLM Inference & ML Systems Engineer**
🎓 M.S. Computer Science — Illinois Institute of Technology, Chicago

I work on making large language models fast and efficient to serve — GPU
inference optimization, serving-runtime internals (vLLM / SGLang /
TensorRT-LLM), CUDA/Triton kernels, quantization, KV-cache & prefix reuse,
and distributed inference across GPUs and TPUs.

---

## 🔧 Open Source

Contributing to **[SGLang](https://github.com/sgl-project/sglang)**, a
high-performance LLM serving framework — improving unit-test coverage for core
runtime components (KV-cache, scheduler admission control, compilation
tracking).

➡️ **[My SGLang pull requests](https://github.com/sgl-project/sglang/pulls?q=is%3Apr+author%3Aomkar-droid)**

---

## 🚀 Featured Projects

### 🔥 [CUDA Softmax Worklog](https://github.com/omkar-droid/cuda-softmax-worklog)
Five progressively optimized row-wise softmax CUDA kernels benchmarked on an NVIDIA
H100 — naive → coalesced → warp-shuffle → vectorized → shared-cached — reaching
**86% of peak HBM (3.4 TB/s), up to 2.3× faster than `torch.softmax`** (26× over the
naive kernel), with double-precision correctness checks and a roofline-style analysis
of each bottleneck. `CUDA · C++ · H100`

### ⚡ [TensorRT Inference Optimization](https://github.com/omkar-droid/tensorrt-inference-optimization)
A full TensorRT inference pipeline for CNNs — ONNX export, engine build, INT8
calibration, benchmarking, and accuracy validation across FP16/INT8 precision.
`Python · TensorRT · CUDA`

### 📚 [AI-Powered Document Summarization (RAG + LLMs)](https://github.com/omkar-droid/AI-Powered-Document-Summarization)
An end-to-end retrieval-augmented summarization service — Kafka ingestion,
vector retrieval, LLM generation, and Redis/Cassandra storage behind a FastAPI.
`Python · RAG · FastAPI`

---

## 🧰 Skills

**Languages:** Python, C++, CUDA, SQL
**LLM Serving & Inference:** vLLM, SGLang, TensorRT-LLM, NVIDIA Triton, ONNX Runtime, Ray Serve
**GPU / Kernels:** CUDA & Triton kernels, CUDA Graphs, kernel fusion, Nsight, FP16/BF16/FP8, quantization
**Inference Optimization:** continuous batching, PagedAttention / KV-cache, prefix caching, speculative decoding, tensor/pipeline parallelism, NCCL
**ML Frameworks:** PyTorch, JAX/XLA, Hugging Face Transformers
**Systems & MLOps:** Docker, Kubernetes, Ray, Linux performance tooling, CI/CD

---

## 🔬 Currently building

- **TPUServe-JAX** — distributed transformer inference on Cloud TPU with
  JAX/XLA: from-scratch decoder, four mesh-sharding strategies, multi-model
  serving, and a Pallas attention kernel. *(publishing soon)*
- Cross-runtime **KV-cache / prefix-reuse benchmarking** on NVIDIA H100.

---

## 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/omkarshewale-/) · shewaleomkar25@gmail.com
