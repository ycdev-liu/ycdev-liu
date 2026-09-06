# 👋 Hi, I'm Yanchao Liu

Computer Vision / 3D Perception / Robotics Developer  
Focused on visual perception, 6D pose estimation, model fine-tuning, and robotic vision systems.

📍 Chongqing, China  
📫 Email: 1939709345@qq.com  
🔗 GitHub: https://github.com/ycdev-liu

---

## 🚀 About Me

- 🎓 M.S. candidate in Computer Technology at Chongqing Normal University
- 👁️ Focused on computer vision, RGB-D perception, point cloud processing, and 6D pose estimation
- 🤖 Experience with robotic perception systems based on ROS2, RealSense, and vision-guided manipulation
- 🧠 Experience with SAM3 fine-tuning, YOLO, FoundationPose, and vision model deployment
- ⚙️ Interested in model compression, ONNX/TensorRT deployment, and edge AI
- 💻 Strong Python / PyTorch background with C++ engineering experience

---

## 🛠 Technical Skills

### Programming & Deep Learning
- **Python** / PyTorch
- C++  
- CNN / Transformer / Diffusion Models
- NumPy / Pandas

### Computer Vision & 3D Perception
- YOLO / SAM2 / SAM3
- OpenCV / Open3D / PCL
- RGB-D perception
- Point cloud processing
- PCA / RANSAC / ICP
- 6D Pose Estimation
- FoundationPose

### Robotics
- ROS2 / TF
- Camera Calibration / Hand-Eye Calibration
- Robot Kinematics
- RealSense
- LeRobot
- MuJoCo / NVIDIA Isaac Sim

### Model Optimization & Deployment
- LoRA Fine-tuning
- INT8 Quantization
- ONNX / TensorRT
- Linux / Docker / Conda / CMake

### LLM & Backend
- LangGraph / RAG
- FastAPI
- MySQL / PostgreSQL
- Qdrant / ChromaDB
- Redis

---

## 📌 Featured Projects

### 🔹 General-Purpose Dual-Arm Grasping Robot
**Jun 2026 – Sep 2026**

A general-purpose robotic grasping system for warehouse and retail object sorting, integrating vision-language segmentation with grasp pose generation.

**Key Contributions**
- Built the perception pipeline connecting **SAM3 and GraspGenX** through ZMQ and ROS2
- Implemented the workflow from **text prompt → instance segmentation → grasp pose generation → robot execution**
- Designed a human-in-the-loop SAM3 data engine:
  - model pre-annotation
  - manual correction
  - dataset conversion
  - fine-tuning dataset generation
- Fine-tuned SAM3 with **LoRA** for 3 warehouse object categories covering around 60 object appearances
- Improved real-world recognition success rate from **82.6% to 98.2%**
- Achieved **Mask mAP@50 of 44.5%**

**Tech Stack**  
SAM3 · GraspGenX · PyTorch · LoRA · ROS2 · ZMQ · RealSense

---

### 🔹 Industrial Motor 6D Pose Estimation System
**Apr 2026 – Jun 2026**

An RGB-D vision system for industrial motor pick-and-place tasks, supporting multi-object 6D pose estimation and empty-slot localization.

**Key Contributions**
- Designed two 6D pose estimation pipelines for different tray constraints
- Built a classical 3D perception pipeline using:
  - YOLO
  - depth back-projection
  - RANSAC
  - PCA
  - ICP
- Combined a 4×10 tray prior with point cloud processing for motor localization and pose estimation
- Developed a deep perception pipeline based on **LocateAnything + SAM2 + FoundationPose**
- Integrated CAD models for instance segmentation and 6D pose estimation
- Developed empty-slot detection using:
  - Z-axis layering
  - DBSCAN
  - geometric filtering
  - PCA-based orientation estimation
- Integrated the full perception pipeline into ROS2 for robot pick-and-place execution

**Performance**
- Classical 6D Pose Success Rate: **~95%**
- FoundationPose single-object Pose Success Rate: **~98.4%**
- Empty-slot recognition success rate: **~95%**
- Position error: **Z ±1 mm / XY ±2 mm**
- Orientation error: **roll/pitch ±2° / yaw ±3°**
- Stage-wise end-to-end pick-and-place success rate: **~99%**

**Tech Stack**  
Python · C++ · ROS2 · YOLO · OpenCV · Open3D · SAM2 · FoundationPose · TensorRT

---

### 🔹 VLA-based Robotic Manipulation Research
**Mar 2026 – May 2026**

Exploration of Vision-Language-Action models for desktop tool recognition, grasping, and classification tasks.

**Key Contributions**
- Studied **ACT, SmolVLA, GR00T N1, and π-series models**
- Analyzed imitation learning, vision-language fusion, action representation, and end-to-end robot control
- Built training and inference workflows using **LeRobot**
- Participated in robot demonstration data collection, model deployment, parameter tuning, and experiment analysis
- Evaluated VLA models on screwdriver, socket, and plier manipulation tasks

**Tech Stack**  
LeRobot · SmolVLA · PyTorch · RealSense · Robot Teleoperation

---

### 🔹 Intelligent Academic Research Platform
**Nov 2025 – Jan 2026**

A multi-agent academic research platform supporting paper retrieval, automatic downloading, vector database construction, and RAG-based question answering.

**Key Contributions**
- Designed a multi-agent workflow using **LangGraph**
- Implemented Search Agent, Download Agent, RAG Agent, and Supervisor
- Built backend APIs using **FastAPI**
- Designed vector knowledge bases with **Qdrant / ChromaDB**
- Integrated PostgreSQL and MongoDB for structured and unstructured data management

**Tech Stack**  
LangGraph · FastAPI · Qdrant · ChromaDB · PostgreSQL · MongoDB

---

## 🔬 Current Interests

- Computer Vision
- RGB-D / 3D Perception
- 6D Pose Estimation
- Vision Model Fine-tuning
- Model Quantization & Pruning
- ONNX / TensorRT Deployment
- Edge AI
- Robotic Vision Systems

---

## 🏆 Honors & Certifications

- 🥇 Huawei ICT Competition – Provincial First Prize
- 📜 Software Designer – Intermediate Certification
- 🎓 Graduate First-Class Scholarship
- 🏅 Provincial Inspirational Scholarship
- 🏆 Outstanding Student / Outstanding Student Leader
- 🌍 CET-4

---

## 📫 Contact

- Email: **1939709345@qq.com**
- GitHub: **ycdev-liu**
