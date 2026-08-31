# Hey there, I'm Yusuf Imam 

**AI Engineer | ML Researcher | Systems Developer** based in Patna, India

I build production-grade AI systems with a focus on **performance**, **scalability**, and **efficiency**. When I'm not training models, you'll find me optimizing Rust code or exploring novel architectures.

---

## What I Do

I specialize in **training and deploying LLMs at scale**, optimizing computer vision pipelines, and building robust MLOps infrastructure. I'm particularly passionate about making AI accessible through efficient model compression, distributed training, and edge deployment.

### Quick Highlights
- Currently training a **1.2B parameter LLM from scratch** (100B tokens on 8x A100s)
- 🦀 Building **high-performance systems in Rust** for ML inference and data processing
- Deployed **real-time computer vision systems** handling <10ms latency in production
-  Active in **open-source**: implementing cutting-edge papers and sharing knowledge
- **Open to roles** in LLM engineering, MLOps, and systems programming

---

## 🛠️ Technical Stack

### **Large Language Models & Generative AI**
I work across the full LLM lifecycle—from pretraining and fine-tuning to deployment:

```
Architecture Design    → PyTorch | JAX | Transformers
Fine-tuning & RLHF    → LoRA, QLoRA, Prefix Tuning, PEFT
Inference Serving     → vLLM, TensorRT-LLM, FastAPI
Knowledge Integration → LangChain, LlamaIndex, RAG pipelines
```

**Recent implementations**: Flash Attention v2, Multi-Query Attention, Rotary Embeddings, SwiGLU activation functions

### **Computer Vision**
End-to-end pipeline experience from data pipeline to edge deployment:

- **Detection & Segmentation**: YOLOv8, Detectron2, Faster R-CNN
- **Modern Architectures**: Vision Transformers (ViT), DINO, SAM
- **Optimization**: TensorRT, ONNX quantization, model distillation
- **Deployment**: Triton Inference Server, Kubernetes orchestration

### **Systems & Performance** 
Rust is my go-to for building performant, memory-safe infrastructure:

![Rust](https://img.shields.io/badge/Rust-CE422B?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

| Category | Skills |
|----------|--------|
| **Core ML/DL** | PyTorch, JAX, TensorFlow, Transformers, Keras |
| **High-Performance** | Rust, CUDA, TensorRT, Flash Attention |
| **LLM Tools** | vLLM, Ollama, HuggingFace, Weights & Biases |
| **MLOps** | Docker, Kubernetes, FastAPI, MLflow, Ray |
| **Data** | Pandas, Polars, DuckDB, Dask, RAPIDS |

---

## 📊 Current Projects

### **1. Efficient-LLM-From-Scratch** 
*Training a production-ready 1.2B parameter LLM from ground zero*

- **Status**: In Development  
- **Scale**: 100B tokens on 8x A100 80GB GPUs
- **Framework**: PyTorch + FSDP (Fully Sharded Data Parallel)
- **Innovations**:
  - Custom BPE tokenizer optimized for efficiency
  - Multi-Query Attention (reduces KV-cache by 8x)
  - Flash Attention v2 integration
  - 4-bit quantization ready for inference
- **Expected**: Beating open-source models in efficiency metrics

### **2. Real-time Object Detection Pipeline** 
*Sub-10ms latency detection system in production*

- **Architecture**: YOLOv8 → TensorRT optimization → Triton Server
- **Performance**: 
  - 10ms p95 latency at 30 FPS
  - Automatic GPU batch adaptation
  - Multi-model serving
- **Infrastructure**: Kubernetes cluster with auto-scaling
- **Deployment**: Handles 50k+ inferences/day reliably

### **3. LLM Fine-tuning Studio** 
*Flexible framework for adapting LLMs to any domain*

- **Techniques**: LoRA, QLoRA, Prefix Tuning, P-Tuning v2
- **Memory Efficient**: 4-bit quantization + gradient checkpointing
- **Use Cases**:
  - Domain-specific knowledge adaptation
  - Instruction following enhancement
  - RLHF pipeline for reward modeling
- **Speedup**: 40% faster than standard fine-tuning

### **4. Rust-based ML Inference Engine** (Coming Soon)
*Ultra-fast tensor operations without Python overhead*

- Building native Rust bindings for ONNX runtime
- Zero-copy inference for video streams
- Benchmark: 3x faster than Python for batch inference

---

##  Research & Learning

### What's on My Radar
- **Efficient Attention**: Reducing KV-cache memory footprint without accuracy loss
- **Neural Architecture Search**: Automating optimal ViT architecture discovery
- **Extreme Quantization**: Pushing LLMs to 2-bit with minimal performance degradation
- **Multimodal Systems**: Bridging vision and language efficiently

### Papers I'm Currently Deep-Diving Into
```
✓ FlashAttention: Fast and Memory-Efficient Exact Attention
✓ LLaMA: Open and Efficient Foundation Language Models  
✓ QLoRA: Efficient Finetuning of Quantized LLMs
✓ Vision Transformers: An Image is Worth 16x16 Words
✓ Scaling Vision Transformers (DeiT)
- Ring Attention: Attention with Explicit Relative Position Bias
- MoE-based LLMs (current deep dive)
```

---

##  Why Work With Me?

✅ **Proven Shipping**: Built and deployed production ML systems handling real-world scale  
✅ **Research-Driven**: Implement cutting-edge papers; not just tutorials  
✅ **Performance Obsessed**: Every millisecond matters—I optimize relentlessly  
✅ **Full Stack**: From research → implementation → deployment  
✅ **Open Source Believer**: Active contributor, believe in community-driven innovation  
✅ **Systems Thinker**: Rust + Python + CUDA perspective on ML problems  

---

##  What I'm Looking For

I'm actively exploring opportunities in:

- **LLM Engineering**: Pretraining, fine-tuning, inference optimization
- **AI Infrastructure**: Building platforms that make ML scalable and efficient
- **Rust + ML**: Performance-critical ML systems with safety guarantees
- **Open Source**: Contributing to high-impact projects (transformers, vLLM, PyTorch)
- **Research Engineering**: Taking papers to production at cutting edge

**📍 Open to**: Full-time roles, research collaborations, and consulting engagements

---

## 🤝 Let's Connect

<div align="center">

I'm always up for:
- **Discussing** ML architecture decisions over coffee (remote ☕)
- **Collaborating** on open-source projects
- **Exploring** novel ideas in AI/ML/Systems

**Want to chat about LLMs, Rust optimization, or scalable ML systems?**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shamskhan404)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shamskhan404)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yusuf@example.com)

</div>

---

## 📊 How I Spend My Time

```
Model Development & PyTorch  ████████████░░░░░░ 65%
Research Paper Implementation ██████████░░░░░░░░░ 55%
Rust Systems Programming      ██████████░░░░░░░░░ 50%
Model Optimization & Tuning   █████████░░░░░░░░░░ 45%
MLOps & Infrastructure        ████████░░░░░░░░░░░ 40%
Writing & Documentation       ██████░░░░░░░░░░░░░ 30%
```

---

## 🎯 2024-2025 Roadmap

**LLM Development**
- [ ] Release 3B model with open weights  
- [ ] Implement and benchmark MoE architecture
- [ ] Achieve SOTA efficiency metrics on standard benchmarks

**Systems & Performance**
- [ ] Complete Rust-based inference engine
- [ ] MLOps platform for distributed training
- [ ] Automated model optimization pipeline

**Community**
- [ ] Publish 4-5 technical deep-dives
- [ ] Mentor 2-3 junior ML engineers
- [ ] Contribute to major open-source projects


<div align="center">

**Last updated**: August 2024 | **Status**: Actively building 🚀

*"The best way to predict the future is to build it."* — Alan Kay

</div>
