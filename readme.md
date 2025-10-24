---
layout: default # Or whatever the theme specifies
---

# Irfan Sipai
## Python AI/ML Developer

<p align="center">
  <a href="mailto:ee.irfansmail@gmail.com">[ Email ]</a> &bull;
  <a href="https://linkedin.com/in/extremesecret0" target="_blank">[ LinkedIn ]</a> &bull;
  <a href="https://github.com/vxedit" target="_blank">[ GitHub ]</a>
</p>

---

### About Me

I'm an Electrical Engineering graduate who transitioned into Python development, specializing in AI/ML and backend systems. With 1.5 years at Autobits Labs, I have hands-on experience building complex projects from scratch, focusing on real-time processing, performance optimization (including GPU acceleration), and creating robust, scalable solutions. I enjoy tackling challenging technical problems and delivering well-architected software.

---

### Skills & Technologies

* **Programming:** Python (Expert), JavaScript (Intermediate)
* **AI/ML:** TensorFlow, PyTorch, InsightFace, Scikit-learn, Pandas, NumPy, MediaPipe, OpenCV, ONNX Runtime
* **Backend:** FastAPI, Flask, Django, REST APIs, WebSockets
* **Databases:** PostgreSQL (SQLAlchemy asyncpg), Redis
* **Asynchronous Processing:** Celery, `asyncio`
* **DevOps & Tools:** Docker, Docker Compose, Git, Linux (Ubuntu), FFmpeg, Nginx
* **Specialized:** GPU Acceleration (CUDA, cuDNN), Real-Time Video Processing, Microservices Architecture, API Design, System Resilience

---

### Featured Projects

#### 1. Real-Time Face Recognition & Surveillance Platform (FastAPI Microservices)

* **Description:** Designed and developed a high-performance, scalable platform for real-time face recognition across multiple IP camera streams. Features a web dashboard for live monitoring, subject management, access control, and analytics. (*Developed professionally at Autobits Labs - Source code is proprietary*).
* **Architecture:** Decoupled microservices using FastAPI (Control Service for API/DB, Processing Service for Video/AI). Communication via HTTP and WebSockets. Containerized with Docker Compose.
* **Key Features & Implementation Details:**
    * GPU-accelerated AI (InsightFace/ONNX Runtime on CUDA/cuDNN) for efficient detection & recognition.
    * Concurrent RTSP stream decoding using FFmpeg with CUDA hardware acceleration.
    * Self-healing `VideoStream` class in the Processing Service to automatically detect and restart failed streams with exponential backoff, ensuring high availability.
    * Asynchronous backend operations (`asyncio`, `SQLAlchemy`, `httpx`) for non-blocking performance.
    * Persistent AI task configuration per camera stored in PostgreSQL.
    * Granular role-based access control (RBAC) via subject-camera permissions.
    * Background notification system (Email/Telegram) using `asyncio.Queue` for non-blocking alerts.
    * RESTful API design for frontend communication and service orchestration.
* **Technologies:** FastAPI, Python, PostgreSQL, SQLAlchemy (asyncpg), Docker, Docker Compose, FFmpeg, CUDA, cuDNN, ONNX Runtime, InsightFace, WebSockets, `asyncio`, `httpx`, Pydantic.

#### 2. Real-Time Indian Sign Language Recognition with Speech Output

* **Description:** An application utilizing a webcam to detect hand gestures (ISL for 0-9, A-Z) in real-time via MediaPipe. Classifies gestures using a TensorFlow/Keras model and provides spoken feedback using asynchronous text-to-speech. Includes prediction debouncing for stable output.
* **Key Features:** MediaPipe landmark detection, Keras model inference, OpenCV for visualization, prediction stability logic (`deque`), non-blocking audio output (`threading`, `queue`, `pyttsx3`).
* **Technologies:** Python, TensorFlow/Keras, MediaPipe, OpenCV, NumPy, `threading`, `queue`, `pyttsx3`.

#### 3. Chili Powder Quality Analysis (ML Model)

* **Description:** Developed machine learning models (PLSR, Transformers) using TensorFlow to predict key quality metrics (pigmentation, capsaicinoid concentration) in chili powder from spectrography data.
* **Results:** Achieved significant accuracy improvements: +20% for pigmentation prediction and +15% for capsaicinoid prediction compared to baseline.
* **Technologies:** Python, TensorFlow, Scikit-learn, Pandas, NumPy, Matplotlib.

---

### Work Experience

* **Python AI/ML Developer** - Autobits Labs, Rajkot (Aug 2024 – Present)
    * Led development of the FastAPI-based Face Recognition system.
    * Developed and optimized ML models for chili powder analysis.
    * Implemented various backend services and automation tools (details in CV).
* **Python Developer** - Nijitek Pvt. Ltd, Ahmedabad (Feb 2024 – Jul 2024)
    * Built a Django system for automated personalized book generation.
    * Created an OpenCV/FFmpeg pipeline for video slideshow automation.
    * Optimized Celery/Redis for high-load order processing.

---

### Contact

Feel free to reach out!

* **Email:** ee.irfansmail@gmail.com
* **LinkedIn:** [linkedin.com/in/extremesecret0](https://linkedin.com/in/extremesecret0)
* **GitHub:** [github.com/vxedit](https://github.com/vxedit)
