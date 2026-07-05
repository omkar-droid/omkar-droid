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

### ⚡ [TensorRT Inference Optimization](https://github.com/omkar-droid/tensorrt-inference-optimization)
FP16 mixed-precision inference on NVIDIA Tensor Cores with kernel fusion and
quantization — measurable latency reduction while holding accuracy within
tolerance of the FP32 baseline. `Python · TensorRT · CUDA`

### 📈 [Low-Latency Order Matching Engine](https://github.com/omkar-droid/Low-Latency-Order-Matching-Engine)
A low-latency limit-order matching engine in modern C++ using lock-free data
structures, pre-allocation, and cache-friendly layout for real-time financial
workloads. `C++`

### 📡 [High-Performance Market Data Feed Handler](https://github.com/omkar-droid/High-Performance-Market-Data-Feed-Handler)
A high-throughput market-data ingestion/decoding pipeline built for
low-latency, high-volume feeds. `C++ · Systems`

### 🤖 [Multi-Agent AI Planning System](https://github.com/omkar-droid/Multi-Agent-AI-Planning-System-for-Software-Engineering-)
A multi-agent LLM system for software-engineering tasks — task decomposition,
tool use, and coordinated planning across agents. `Python · LLM Agents`

### 📚 [AI-Powered Document Summarization (RAG + LLMs)](https://github.com/omkar-droid/AI-Powered-Document-Summarization)
An end-to-end retrieval-augmented summarization pipeline (Kafka ingestion,
vector retrieval, LLM generation) served behind a low-latency API.
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

## 🔬 Currently exploring

Distributed transformer inference on **Cloud TPU with JAX/XLA** (mesh sharding
strategies + Pallas kernels), and cross-runtime **KV-cache / prefix-reuse
benchmarking** on H100.

---

## 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/omkarshewale-/) · shewaleomkar25@gmail.com
