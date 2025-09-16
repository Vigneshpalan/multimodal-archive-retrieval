# Multimodal Archive Retrieval System

A **news-style multimodal archive system** that allows storing and retrieving images, videos, audio, and text.  
Users can upload any modality (image, video, audio, or text) and search for similar content in the archive.

---

## 🚀 Project Overview

This project is designed to prototype an **AI-powered archive system** similar to what news channels use.  
It supports:

- **Image search** → Find similar images in the archive
- **Video search** → Retrieve relevant videos via keyframes or embeddings
- **Audio search** → Match audio clips or speech
- **Text search** → Search via captions or descriptions

The system uses **multimodal embeddings** stored in **FAISS** for efficient similarity search.

---

## 🗂 Dataset

For the prototype, we are using the **MSR-VTT dataset**:

- 10,000 short YouTube video clips (~20s each)  
- Human-written captions (20 per video)  
- Video contains **image frames**, **audio track**, and text captions  

> Later, the system can be extended to real-world news archives.

---

## 🛠 Technology Stack

- **Python**  
- **PyTorch / Transformers** (CLIP, Whisper/Wav2Vec2)  
- **FAISS** → Efficient vector similarity search  
- **Streamlit** → Interactive frontend  
- **MoviePy / OpenCV** → Video and frame extraction  

---



