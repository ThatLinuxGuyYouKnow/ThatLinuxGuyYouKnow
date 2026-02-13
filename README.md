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
