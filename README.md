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

### [Rubik-YOLO — Real-Time Rubik's Cube Solver Vision System](https://github.com/ThatLinuxGuyYouKnow/rubik-yolo)

A specialized computer vision model that accurately detects and identifies Rubik's Cube face colors and orientations in real-time, designed as the visual foundation for automated cube-solving systems.

**What It Does:**
- Detects and classifies all 6 cube face colors (Blue, Green, Orange, Red, White, Yellow) simultaneously
- Handles non-standard cube orientations using Oriented Bounding Boxes (OBB)
- Operates robustly under varying lighting conditions and camera angles
- Processes frames at 30+ FPS on mid-range Android devices

**Technical Implementation:**
- Fine-tuned YOLOv8-nano on a self-curated, diverse Rubik's Cube dataset
- Custom annotations created in Label Studio with support for rotated bounding boxes
- Achieved ~0.95 mAP over 72 training epochs with early stopping
- Converted PyTorch weights to ONNX format for mobile NPU acceleration
- Built inference pipeline supporting live camera, static images, and video processing

**Use Case:** Serves as the perception layer for Rubik's Cube solving applications, enabling real-time state detection needed for algorithmic solving.

### [EchoLLM — Privacy-First Mobile LLM Runtime](https://github.com/ThatLinuxGuyYouKnow/EchoLLM)

On-device inference engine enabling offline LLM execution on mobile platforms, with optional cloud model access via BYOK (Bring Your Own Key) usage model.

**Technical Highlights:**
- Distilled reasoning capabilities from DeepSeek-R1 (671B) into a 1.7B Qwen model, preserving 95% of benchmark performance
- Engineered 4-bit quantization pipeline reducing model size to <1.2GB while maintaining sub-200ms first-token latency
- Built high-performance C++ FFI bridge between llama.cpp and Flutter, achieving 20 tokens/s on consumer hardware

**Impact:** Enables privacy-preserving AI assistants that operate completely offline—no cloud APIs, no telemetry, no compromises.
