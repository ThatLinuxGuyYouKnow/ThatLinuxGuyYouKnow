# Alabi Ayobami 

### Applied AI Engineer & Mobile Systems Specialist

I specialize in **Knowledge Distillation**, **On-Device Inference**, and **Computer Vision**. My focus is building systems that run heavy compute workloads efficiently on the Edge (iOS/Android/Linux).

---

## ⚡ Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **AI & ML** | PyTorch, TensorFlow, ONNX Runtime, llama.cpp, LoRA/QLoRA, Hugging Face |
| **Mobile & Systems** | C++, Dart (Flutter), Swift, Bash, Linux Kernel, Docker |
| **Data & Backend** | Python, FastAPI, PostgreSQL, Vector Databases (Chroma/Pinecone) |
| **Infrastructure** | AWS (SageMaker), GCP, GitHub Actions (CI/CD) |

---

## Featured Engineering Projects

### [EchoLLM](https://github.com/ThatLinuxGuyYouKnow/EchoLLM) | *On-Device Inference Engine* <Building>
 
**A privacy-first mobile LLM runtime capable of running 1B+ parameter models offline.**
*   **Distillation:** Built a pipeline to distill reasoning capabilities from **DeepSeek-R1** into a **1.7B parameter Qwen model**.
*   **Optimization:** Manually quantized models to **4-bit GGUF**, reducing memory footprint to <1.2GB while maintaining 95% of reasoning benchmarks.
*   **Systems:** Implemented a **C++ FFI bridge** to link the underlying inference engine directly to the Flutter UI, achieving **20 tokens/s** on consumer mobile hardware.

### 🎵 [Vibe-Tuner]([LINK_HER](https://github.com/ThatLinuxGuyYouKnow/EchoLLM)E) | *NLP-Driven Recommendation System* <Building>
 
**An NLP engine that maps abstract human sentiment to Spotify Audio Features.**
*   **Architecture:** Replaced standard keyword search with a semantic vector mapping system (User Prompt -> Valence/Energy/Danceability Vectors).
*   **Integration:** deeply integrated with the **Spotify Web API** to generate algorithmic playlists based on "Vibe" rather than Genre.
*   **Stack:** Flutter, Python (NLP Middleware), Spotify OAuth 2.0.

### 👁️ [Rubik-YOLO](https://github.com/ThatLinuxGuyYouKnow/rubik-yolo) | *Real-Time Mobile Computer Vision*
**High-performance object detection system for 3D spatial objects.**
*   **CV Pipeline:** Trained a custom **YOLOv8** model using Oriented Bounding Boxes (OBB) to track Rubik's cubes in dynamic lighting.
*   **Deployment:** Converted PyTorch weights to **ONNX** for optimized cross-platform execution on mobile NPU/CPUs.
*   **Data Ops:** Built an active learning loop using Label Studio to correct model drift.

---

## 🛠️ Open Source & Tools

*   **[Bible_Extractor (ETL)](https://github.com/ThatLinuxGuyYouKnow/bible_extractor_v1):** A T5-based NLP pipeline for normalizing and structuring unstructured archaic text data.
*   **[Jemma](https://github.com/ThatLinuxGuyYouKnow/jemma):** CLI-based developer tooling for automating data validation workflows.

## 🔭 Current Research
*   **Symbolic Distillation:** Experimenting with distilling "Chain of Thought" reasoning from 70B models into <3B mobile-class models.
*   **Edge Quantization:** Benchmarking perplexity degradation in GGUF vs. AWQ formats for mobile NPUs.

## 📫 Connect
*   **GitHub:** [ThatLinuxGuyYouKnow](https://github.com/ThatLinuxGuyYouKnow)
*   **LinkedIn:** [LinkedIn](https://github.com/ThatLinuxGuyYouKnow/jemma)
