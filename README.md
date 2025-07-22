# 🖼️ AI Image Caption Generator

An AI-powered web app that generates natural language captions for uploaded images using BLIP (Bootstrapped Language-Image Pretraining) and a modern full-stack setup (FastAPI + React).

---

## 📸 Demo

![demo](https://github.com/gowthambunny69/ai_image_caption/assets/demo.gif)  
*Upload an image and see how AI describes it!*

---

## 🚀 Features

- 🤖 Uses `Salesforce/blip-image-captioning-base` to generate captions
- ⚙️ FastAPI backend with Torch and HuggingFace Transformers
- ⚛️ React frontend for image upload and caption display
- 🌐 Seamless API integration using Axios
- 🎯 Clean, responsive design (customizable)

---

## 🛠️ Tech Stack

| Layer       | Tools/Tech                                      |
|-------------|-------------------------------------------------|
| Frontend    | React.js, Axios, HTML/CSS                       |
| Backend     | FastAPI, Python, Uvicorn                        |
| AI Model    | `Salesforce/blip-image-captioning-base`         |
| Image Proc  | Pillow (PIL), Torch, Transformers (HuggingFace) |

---

## 🧑‍💻 Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/gowthambunny69/ai_image_caption.git
cd ai_image_caption

## 🧠 Backend Setup (FastAPI)

1. Navigate to the backend folder:
   ```bash
   cd backend

python3 -m venv venv
source venv/bin/activate

install the required packages:
pip install -r requirements.txt

Run the server:
uvicorn main:app --reload