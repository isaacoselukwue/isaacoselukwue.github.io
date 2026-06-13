# Isaac Oselukwue

**Lincoln, United Kingdom**

Email: princeizak@live.com  
LinkedIn: [linkedin.com/in/isaacoselukwue](https://linkedin.com/in/isaacoselukwue)  
GitHub: [github.com/isaacoselukwue](https://github.com/isaacoselukwue)

---

## Professional Summary

Software Engineer specialising in computer vision, robotics autonomy, and deployable ML systems, with experience integrating perception components into ROS2/TensorRT-based robotic platforms and a broader background in reliable, tested, high-availability software. Skilled in Python, C++, PyTorch, computer vision, data pipelines, monitoring, and production software engineering, bringing a safety-critical mindset from robotics and regulated financial environments.

---

## Education

**M.Sc. Computer Science** | University of Lincoln, United Kingdom  
September 2024 – September 2025

**B.Sc. Computer Science** | University of Lagos, Nigeria  
2015 – 2021

---

## Technologies and Languages

**Computer Vision / ML:** PyTorch, Transformers, YOLO, RF-DETR, SAM, OpenCV, BLIP, ViT, ResNet, ConvNeXt, Depth Anything v2, DPT, detection, segmentation, classification, tracking, depth/pose estimation, LoRA

**Robotics / Deployment:** ROS2, C++, TensorRT, real-time/edge inference, NVIDIA Jetson, hardware/software integration, Docker

**MLOps / Data:** dataset preparation, evaluation pipelines, MLflow, telemetry, model monitoring, Git, CI/CD, experiment tracking

**Software Engineering:** Python (structured codebases, type hints, pytest), C#, JavaScript, FastAPI, Kafka, PostgreSQL, Redis, TDD, microservices

---

## Relevant Role Fit

- **Computer vision:** YOLO-style detection, depth/pose estimation, classical CV cues, multimodal image understanding, VQA
- **Robotics integration:** ROS2, C++ nodes, TensorRT deployment, real-time perception for robotic control
- **ML / data pipelines:** dataset preprocessing, transformation, evaluation workflows, monitoring, telemetry
- **Production engineering:** structured Python/C++ codebases, Git, TDD, microservices, CI-ready development
- **Safety-critical mindset:** experience delivering reliable software in regulated financial environments

---

## Work Experience

### Software Engineer | Agaricus Robotics
**October 2025 – Present** | Lincoln, United Kingdom

- Engineered and deployed a ROS2-based robotic perception stack for real-time control, combining YOLO-style detection, depth/pose estimation, region analysis via segmented masks, and classical CV quality cues; integrated Python ML prototypes with C++/TensorRT inference for ultra-low-latency edge deployment, achieving sub-15 ms inference latency and a 3x throughput increase (30 FPS) on NVIDIA Jetson Orin Nano
- Built dataset preparation and evaluation workflows for perception models, including annotation review, train/validation/test splits, augmentation, benchmarking, and failure-case analysis using metrics such as mAP, IoU, latency, and confidence distributions
- Implemented telemetry for ML-driven decisions, tracking inference latency, throughput, confidence distributions, and error categories to support reproducible releases and operational debugging (MLOps)
- Contributed to maintainable robotics software through modular Python/C++ components, Git-based workflows, unit/integration testing (pytest/GTest), and reproducible deployment practices (Docker/CI)

### Full-Stack & Data Engineer (part-time) | University of Lincoln
**May 2025 – September 2025** | Sustainability/AutoTraits Teams | Lincoln, United Kingdom

- Developed interactive dashboards in Python to visualise strawberry field sensor data and image metrics supporting agritech ML experiments
- Implemented automated data pipelines for sensor and image-derived datasets, supporting preprocessing, transformation, quality checks, and repeatable training/evaluation cycles
- Built geospatial features including soil-habitat rasterisation, habitat-connectivity overlays and a navigation view, wiring them to a Tailwind-styled front end so researchers could query carbon storage and water-infiltration hotspots on demand

### Software Engineer | Zedvance Finance
**April 2024 – September 2024** | Business Banking Team | Lagos, Nigeria

- Designed and implemented core features for the Business Plus platform, including Identity Management, POS Transactions, and Branch & Admin Account Creation, improving operational efficiency by 30% and setup time for new businesses by 40%
- Co-developed a permission management library enforcing fine-grained access control across microservices, enhancing security and compliance
- Co-designed a Saga orchestration library for POS-related workflows, ensuring transaction consistency across distributed services and reducing failure rates by 25%

### Application Developer | FCMB Group Plc
**December 2023 – April 2024** | Asset Management Group | Lagos, Nigeria

- Architected and developed core Asset Management services as independent, scalable microservices, improving modularity and maintainability and reducing deployment time by 8%
- Enhanced system reliability by implementing event-driven communication via Kafka, reducing message failures by 32% and improving inter-service coordination

### Software Engineer | Sterling Bank Plc
**October 2021 – December 2023** | Integrations & Partnership Support | Lagos, Nigeria

- Redesigned and optimised Sterling's NIP (Nigeria's Interbank Instant Payment) services, increasing throughput to 600+ transactions per second with auto-scaling and reducing infrastructure costs by 78%
- Bridged legacy and modern systems by building a central middleware service, converting SOAP-based debit/credit services into RESTful APIs, improving interoperability and reducing system bottlenecks

### Software Developer | CoralPay Technologies
**August 2020 – September 2021** | Engineering Technology Group | Lagos, Nigeria

- Developed and maintained full-stack integrations for CoralPay's payment services using ASP.NET MVC, ensuring seamless connectivity and reliability for client applications

---

## Projects

**Multimodal Vision-Language Modelling** – Fine-tuned ResNet, ViT, BLIP, and Phi-4-based models for feature extraction and visual question answering using LoRA and selective layer freezing; evaluated model behaviour across image-text reasoning tasks

**yolo26-eval** – Production-grade YOLO26 object detection: exports the model to ONNX and serves it with FastAPI and ONNX Runtime (no PyTorch at runtime), cutting the container from ~2.2 GB to ~350 MB and cold-start to under 2 seconds; uses YOLO26's NMS-free detection head for single-call CPU inference (~96 ms, 13 objects), with a lightweight HTML/Tailwind dashboard and Dockerised deployment on Render

**Audio.AI** – Audio transcription and summarisation solutions using Whisper and Deepgram, with dedicated implementations in .NET and Python

**xdu** – Cross-platform clone of the POSIX `du` disk-usage estimator in portable C++17, summing real allocated blocks for byte-for-byte parity with GNU `du`; handles hard-link/cycle de-duplication via (device, inode) tracking, a full option set (human-readable sizes, depth limits, globs, thresholds, sorting, JSON/CSV, colour) and a differential test suite against the system `du`

**ILS** – Open-source Integrated Library System using a TCP-based client/server architecture in C++, demonstrating network programming and system design

---

## Relevant Expertise & Compliance

Experience developing and maintaining systems in regulated financial environments (Zedvance, FCMB, Sterling Bank), ensuring high availability, security, and transaction consistency across distributed services. Keen interest in applying robust, reliable ML development practices to safety-critical applications.

---

## Certifications

- Microsoft Certified: Azure Fundamentals
- Microsoft Certified: Azure AI Fundamentals
- Microsoft Certified: Azure Data Fundamentals
- Microsoft Certified: Power Platform Fundamentals
- Microsoft Certified: Security, Compliance, and Identity Fundamentals
- ITIL Foundation

---

## Interests

Avid tennis fan and player.
