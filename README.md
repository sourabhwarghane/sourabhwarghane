# Hi, I'm Sourabh Warghane 👋

### AI | Machine Learning | Robotics | Edge AI

I'm an **Electronics & Communication Engineer** with a professional background in **Digital Advertising / Programmatic Advertising**, now transitioning into **Artificial Intelligence and Robotics**.

Over the last couple of years, I have been building practical experience in **Machine Learning, Deep Learning, Computer Vision, ROS 2, Edge AI, Generative AI, and Embedded Systems**.

My main interest is building intelligent systems that can **perceive, understand, decide, and interact with the physical world**.

---

## 🤖 Featured Project — Vector Autonomous Mobile Robot

### ROS 2 | Jetson Orin Nano | YOLOv8 | TensorRT | LiDAR | ESP32

[![Repository](https://img.shields.io/badge/GitHub-View%20Project-181717?logo=github)](https://github.com/sourabhwarghane/my_robot)

**Vector** is a custom Autonomous Mobile Robot that I designed and built from the ground up to explore the integration of **AI, robotics, embedded systems, perception, and human-robot interaction**.

The robot uses an **NVIDIA Jetson Orin Nano** as its primary AI computer and an **ESP32-C3** for low-level motor control and battery monitoring.

### Key Capabilities

* 👁️ Real-time object detection using YOLOv8
* 🎯 Person detection, tracking, and following
* 📡 LiDAR-based obstacle detection
* 🧭 Autonomous obstacle avoidance behaviour
* 🤖 ROS 2 based modular architecture
* ⚡ TensorRT optimized edge inference
* 🎤 Voice commands and wake-word interaction
* 🧠 LLM-assisted conversational interaction
* 🔊 Speech-to-Text and Text-to-Speech
* 🔋 Battery monitoring
* 🛡️ Watchdog and safety monitoring
* 🔌 Jetson ↔ ESP32 serial communication

### High-Level Architecture

```text
                    ┌──────────────┐
                    │ CSI Camera   │
                    └──────┬───────┘
                           │
                           ▼
                    ┌──────────────┐
                    │   YOLOv8     │
                    │  TensorRT    │
                    └──────┬───────┘
                           │
                           ▼
                    ┌──────────────┐
                    │   Tracker    │
                    └──────┬───────┘
                           │
                           ▼
┌────────────┐      ┌──────────────┐      ┌──────────────┐
│  RPLIDAR   │─────▶│   Decision   │─────▶│ Motor Control│
└─────┬──────┘      │     Node     │      └──────┬───────┘
      │             └──────▲───────┘             │
      ▼                    │                     ▼
┌──────────────┐           │               ┌───────────┐
│   Obstacle   │           │               │ ESP32-C3  │
│  Detection   │───────────┘               └─────┬─────┘
└──────────────┘                                 │
                                                 ▼
                                           ┌───────────┐
                                           │  Motors   │
                                           └───────────┘


Microphone
    │
    ▼
Speech-to-Text
    │
    ├──────────────▶ Voice Commands ─────▶ Decision Node
    │
    ▼
   LLM
    │
    ▼
Text-to-Speech
```

This project gave me hands-on experience with the complete robotics workflow:

**Sensors → Perception → AI Inference → Decision Making → Control → Hardware**

---

# 🚀 Projects

## 🤖 Vector — Autonomous Mobile Robot

**ROS 2 • NVIDIA Jetson • YOLOv8 • TensorRT • LiDAR • ESP32 • Computer Vision**

A full edge-AI robotic system combining perception, tracking, obstacle detection, person following, voice interaction, embedded motor control, and safety monitoring.

🔗 [View Repository](https://github.com/sourabhwarghane/my_robot)

---

## 🏠 Ames House Price Prediction

**Python • Pandas • Scikit-learn • Regression • Machine Learning**

An end-to-end machine learning project for predicting residential property prices.

### Project Workflow

* Exploratory Data Analysis
* Missing-value handling
* Data preprocessing
* Feature engineering
* Model training
* Model comparison
* Hyperparameter tuning
* Model evaluation
* Prediction pipeline

The project helped me understand how to take a traditional machine-learning problem from **raw data to a complete predictive workflow**.

---

## 📚 Local RAG / Robotics Knowledge Assistant

**Python • LLM • RAG • Embeddings • Vector Search**

🚧 **In Development**

A local Retrieval-Augmented Generation system designed to answer questions using robotics and technical documents.

### Areas Being Explored

* Document ingestion
* Text chunking
* Embedding generation
* Vector databases
* Semantic search
* Context retrieval
* Prompt construction
* Local LLM inference

The goal is to create a practical assistant capable of retrieving relevant technical knowledge instead of relying only on the LLM's internal knowledge.

---

## 🧠 Edge AI Human Activity Recognition

**Computer Vision • Deep Learning • Edge AI • Model Optimization**

🚧 **In Development**

A computer-vision project focused on recognizing human activities and taking a model through the complete Edge AI workflow:

```text
Dataset
   ↓
Preprocessing
   ↓
Model Training
   ↓
Evaluation
   ↓
Optimization
   ↓
Edge Deployment
```

The project is focused on understanding the challenges involved in moving an AI model from a development environment to **resource-constrained edge hardware**.

---

# 🧪 AI & Robotics Learning Journey

Alongside my main projects, I maintain practical notebooks and experiments covering the fundamentals that support my AI and Robotics work.

### Machine Learning

* Regression
* Classification
* Data preprocessing
* Feature engineering
* Model evaluation
* Cross-validation
* Hyperparameter tuning
* Dimensionality reduction

### Deep Learning

* Neural-network fundamentals
* Training and validation
* Computer Vision
* CNN architectures
* Transfer learning
* Model optimization

### NLP & Generative AI

* Text preprocessing
* TF-IDF
* Embeddings
* Large Language Models
* Retrieval-Augmented Generation
* Speech-to-Text
* Text-to-Speech

### Robotics

* ROS 2
* Nodes, topics, and messages
* Sensor integration
* Computer Vision
* LiDAR
* Robot perception
* Motion control
* Autonomous behaviour
* Human-Robot Interaction

---

# 🛠️ Tech Stack

### Programming & Data

![Python](https://img.shields.io/badge/Python-3776AB?logo=python\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter\&logoColor=white)

### Machine Learning & AI

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikitlearn\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch\&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv\&logoColor=white)

`YOLOv8n` • `Computer Vision` • `Deep Learning` • `NLP` • `RAG` • `LLMs`

### Robotics

![ROS2](https://img.shields.io/badge/ROS_2-22314E?logo=ros\&logoColor=white)

`LiDAR` • `Robot Perception` • `Sensor Integration` • `Motion Control` • `Human-Robot Interaction`

### Edge AI & Embedded Systems

![NVIDIA](https://img.shields.io/badge/NVIDIA_Jetson-76B900?logo=nvidia\&logoColor=white)
![Arduino](https://img.shields.io/badge/ESP32-00979D?logo=arduino\&logoColor=white)

`Jetson Orin Nano` • `CUDA` • `TensorRT` • `ESP32` • `Serial Communication`

### Development Tools

![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux\&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github\&logoColor=white)

---

# 🎯 Currently Focused On

I'm currently strengthening my foundations while continuing to build practical projects in:

* 🧠 Machine Learning
* 🔥 Deep Learning
* 👁️ Computer Vision
* 🤖 ROS 2 & Robotics
* ⚡ Edge AI
* 🧭 Robot Perception & Navigation
* 📚 RAG & Generative AI
* 🚀 AI model optimization and deployment
* 📐 Mathematics for Machine Learning

---

# 💡 Areas of Interest

I'm particularly interested in AI systems that move beyond notebooks and interact with the real world.

```text
Artificial Intelligence
        │
        ├── Machine Learning
        │
        ├── Deep Learning
        │
        ├── Computer Vision
        │
        └── Generative AI
        │
        ▼
     Edge AI
        │
        ▼
     Robotics
        │
        ├── Perception
        ├── Navigation
        ├── Decision Making
        └── Human-Robot Interaction
```

My long-term focus is at the intersection of:

## **AI × Robotics × Edge Computing**

---

# 🤝 Connect With Me

<a href="https://www.linkedin.com/in/sourabh-warghane/">
  <img src="https://img.shields.io/badge/LinkedIn-Sourabh%20Warghane-0A66C2?logo=linkedin&logoColor=white"/>
</a>

</p>

---

### From AI fundamentals to intelligent machines. 🤖

I enjoy learning by **building real systems, understanding how they work, and then improving them one layer at a time**.
