# Swapnil Gaikwad

**Founder & Architect | High-Performance Computing for AI | Systems Engineering**

A performance-oriented Data Science graduate specializing in architecting and optimizing AI/ML systems from the silicon up. My expertise lies in GPU acceleration (CUDA, Metal, Core ML) and delivering significant performance gains (2-5x) in complex computational models through first-principles engineering.

[LinkedIn](https://www.linkedin.com/in/swapyg/) | [Email](mailto:swapnilg768@gmail.com)

---

## Core Technical Proficiencies

*   **GPU Programming & Acceleration:** C++, CUDA, Metal, NVIDIA TensorRT, Core ML, Kernel Fusion & Optimization, Performance Profiling, Memory Management, FP16 Precision.
*   **Machine Learning & Modeling:** Deep Learning (Diffusion Models, CNNs, SNNs), Model Optimization (Quantization-Aware Training), End-to-End Data Pipelines.
*   **Programming & Infrastructure:** Python (Advanced), C++ (Intermediate), PyTorch, TensorFlow, SQL, Docker, Git, Linux, AWS.

---

## Featured Architectural Work

### GPU-Optimized Diffusion Model for Apple Silicon
This project demonstrates a full-stack approach to performance engineering by porting and natively optimizing a CUDA-based AI Diffusion Model for Apple Silicon.

*   **Multi-Tiered Architecture:** Engineered and benchmarked three separate inference backends: a baseline PyTorch MPS implementation, a custom C++/Metal kernel for low-level operation fusion, and a Core ML-accelerated pipeline targeting the Apple Neural Engine.
*   **Performance Gains:** Achieved a **~2x inference speedup** with the Core ML implementation over the standard PyTorch baseline, proving the significant advantages of leveraging dedicated hardware accelerators.
*   **Advanced Debugging:** Systematically diagnosed and resolved critical low-level memory corruption errors (`segmentation fault`, `malloc`) and PyTorch C++ API limitations (`getDeviceFromPtr`) by implementing robust memory management and a CPU data bridge to ensure architectural stability.

[**View Source on GitHub ->**](https://github.com/SwapyG/GPU_Optimized_Diffusion_Model_For_Apple_Silicon)

### High-Performance Image Generation & Optimization (CUDA)
Architected and deployed a diffusion model pipeline with custom CUDA C++ kernels, delivering a significant performance and efficiency overhaul compared to standard PyTorch implementations.

*   **Performance & Efficiency:** Achieved a **2-3x performance speedup** in image generation and **cut VRAM usage by 40%** through a novel, memory-efficient attention mechanism.
*   **Inference Acceleration:** Accelerated model inference by **5x** through the strategic integration of NVIDIA TensorRT, with minimal accuracy degradation confirmed via rigorous benchmarking.

[**View Source on GitHub ->**](https://github.com/SwapyG/GPU-Optimized-Diffusion-Model) <!-- Add the correct link here -->

---
