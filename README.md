# Ayobami

**Full-Stack (Mobile & Web) and AI Engineer**

I build production-grade AI/ML systems optimized for mobile devices and resource-constrained environments.

## Current Work

Building [**EchoLLM**](https://snapcraft.io/echollm) — a desktop application that provides seamless access to state-of-the-art models from frontier labs (Claude, GPT, Gemini) with a privacy-first approach. Built with Flutter and available on the Snap Store.

Actively developing:
- Offline model support via llama.cpp integration
- Custom model distillation pipelines for mobile deployment
- Quantization techniques to run advanced models on phones and laptops

## Tech Stack

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-000000?style=flat&logo=llama&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

---

## Featured Projects

### [Rubik-YOLO — Real-Time Mobile Object Detection](https://github.com/ThatLinuxGuyYouKnow/rubik-yolo)

Custom YOLOv8 model engineered for tracking 3D objects under dynamic lighting conditions.

**Technical Highlights:**
- Curated and labeled custom dataset using Label Studio
- Trained YOLOv8 with Oriented Bounding Boxes (OBB) for rotation-invariant detection
- Converted PyTorch weights to ONNX for mobile NPU acceleration
- **Performance:** Achieved 30+ FPS on mid-range Android devices

### [EchoLLM — Privacy-First Mobile LLM Runtime](https://github.com/ThatLinuxGuyYouKnow/EchoLLM)

On-device inference engine enabling offline LLM execution on mobile platforms, with optional cloud model access via BYOK (Bring Your Own Key) usage model.

**Technical Highlights:**
- Distilled reasoning capabilities from DeepSeek-R1 (671B) into a 1.7B Qwen model, preserving 95% of benchmark performance
- Engineered 4-bit quantization pipeline reducing model size to <1.2GB while maintaining sub-200ms first-token latency
- Built high-performance C++ FFI bridge between llama.cpp and Flutter, achieving 20 tokens/s on consumer hardware

**Impact:** Enables privacy-preserving AI assistants that operate completely offline—no cloud APIs, no telemetry, no compromises.
