# Ayobami

I build stuff that runs ML models on phones without melting them.

Currently working on EchoLLM, a mobile LLM runtime that lets you run 1B+ parameter models completely offline. The goal is privacy-first AI that doesn't need cloud APIs or eat your battery alive. I've been distilling reasoning capabilities from DeepSeek-R1 into smaller models, quantizing them down to 4-bit, and wiring up C++ inference engines to Flutter UIs.

Other things I've built:
- **Vibe-Tuner**: NLP-driven Spotify recommendations that map your mood to actual audio features instead of just keyword matching
- **Rubik-YOLO**: Real-time object detection on mobile using custom YOLOv8 models, because apparently I enjoy pain
- **Bible_Extractor**: A T5-based pipeline for normalizing archaic text data (long story)

I spend most of my time trying to fit language models into devices with less RAM than my browser tabs, benchmarking quantization formats, and figuring out why things run fast on Linux but not on Android.

**Stack:** PyTorch, C++, Flutter, ONNX, llama.cpp, the usual suspects

**Currently exploring:** Distilling chain-of-thought reasoning into <3B models, edge quantization, making NPUs actually useful

[GitHub](https://github.com/ThatLinuxGuyYouKnow) • [LinkedIn](link)
