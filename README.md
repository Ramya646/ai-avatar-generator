# 🎭 AI Avatar Generation System

## 📌 Overview

This project generates a talking avatar video from text input.

It follows a pipeline:
**Text → Speech → Lip-Synced Video**

The system uses deep learning models to convert text into speech and synchronize lip movements with a given face video.

---

## ⚙️ Tech Stack

* Frontend: React (Vite)
* Backend: Flask
* Database: PostgreSQL
* Text-to-Speech: OpenVoice
* Lip Sync: Wave2Lip

---

## 🧠 Architecture

![Architecture Diagram](assets/architecture.png)

---

## 🚀 Features

* 🔐 User Authentication (Login/Register)
* 🎤 Text-to-Speech Generation
* 🎥 Lip-Synced Avatar Video Generation
* 📂 Avatar History Storage
* 🗑️ Delete Generated Avatars

---

## 🔄 Workflow

1. User enters text from frontend
2. Backend generates speech using OpenVoice
3. Generated audio is passed to Wave2Lip
4. Lip-synced video is created
5. Output video is sent back to frontend
6. History is stored in MongoDB

---

## ▶️ How to Run

### Backend

```bash
cd backend
pip install -r requirements.txt
python run.py
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## ⚠️ Important Note

Model files are not included due to size limitations.

Download them from:

* Wave2Lip: https://github.com/Rudrabha/Wav2Lip
* OpenVoice: https://github.com/myshell-ai/OpenVoice

Place them in:

```
backend/app/files/checkpoints/
```

---

## 📌 Future Improvements

* Improve lip-sync quality (SadTalker integration)
* Add real-time avatar generation
* Deploy using cloud services

---

## 👩‍💻 Author

K RAMYA
