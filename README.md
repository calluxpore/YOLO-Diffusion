## 👁️ YOLO Eye Detection & Diffusion Pipeline
An end-to-end system combining YOLOv8 for eye detection with ComfyUI diffusion models for creative AI-based editing on images, videos, and webcam feeds.

---

### 🔍 Overview
This pipeline detects eyes using a custom-trained YOLOv9 model, then applies diffusion-based modifications (like masking, inpainting, or stylization) via ComfyUI.

---

### 🧠 Features
- Real-time detection (images, video, webcam)
- AI-driven editing using diffusion models
- Simple YOLO annotation with LabelImg
- Lightweight dataset and model
- Works via CLI and ComfyUI

---

### 📁 Project Structure
| Directory/File | Description                                   |
|-----------------|-----------------------------------------------|
| `Dataset/`      | Labeled eye images (~50-60 curated)          |
| `Model/` | YOLOv8 trained model weights                  |
| `Samples/`      | Sample inputs & outputs (images/videos)      |
| `Results/`      | Detection and diffusion result outputs        |
| `README.md`     | Project documentation                       |

---

### 🧪 Dataset & Training
- ~50 labeled face/eye images
- YOLOv8 (Ultralytics, PyTorch)
- Single-class (eye) detection

---

### 🖼️ Outputs
- YOLO: Bounding boxes + confidence
- Diffusion: Eye masking + inpainting via ComfyUI

---