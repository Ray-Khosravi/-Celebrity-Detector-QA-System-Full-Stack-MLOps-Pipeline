# Celebrity-Detector-QA-System-Full-Stack-MLOps-Pipeline
🌟 Overview This project is an end-to-end production-grade pipeline that detects celebrities in images and provides a Question-Answering (QA) interface. Beyond the AI model, the core focus here is Infrastructure as Code and Automated Deployment, ensuring the system is scalable, monitored, and production-ready.

🏗️ System Architecture & Workflow
The entire lifecycle of the application—from local development to cloud deployment—is automated. Below is the high-level architecture:

<img width="1277" height="739" alt="Celebrity+Detector+QA+Workflow" src="https://github.com/user-attachments/assets/69887a96-df24-48d6-ba43-e27563f90374" />






🔍 Pipeline Breakdown:

1. Development Setup (The Engine)

Image Handler: Robust preprocessing for incoming visual data.

Celebrity Detector: ML core for facial recognition and celebrity identification.

QA Engine: A logic layer to handle user queries based on detection results.

FastAPI/Routes: Clean API implementation for seamless frontend/backend communication.

2. Containerization (The Package)
   
Docker: The application is fully containerized to ensure environment parity.

Kubernetes Manifests: Defined deployment and service files for orchestration.

3. Version Control & CI/CD (The Automation)
   
GitHub: Source of truth for code versioning.

CircleCI: Automated pipeline that triggers on every push.

GAR (Google Artifact Registry): Automated builds and image storage.

GKE (Google Kubernetes Engine): Zero-downtime deployment to a managed Kubernetes cluster.

🛠️ Tech Stack

Language: Python 3.x

ML/AI: OpenCV 

DevOps: Docker, Kubernetes (K8s)

Cloud: Google Cloud Platform (GCP), GKE, GAR

CI/CD: CircleCI

🚀 Key Engineering Features

End-to-End Automation: No manual intervention from code commit to cloud deployment.

Cloud-Native Design: Built specifically for Google Cloud’s ecosystem.

Scalability: Horizontal scaling enabled via Kubernetes pods.

QA-Ready: Integrated testing and QA engine code within the dev cycle.


👋 Contact & Connect

Ray Khosravi - AI / Machine Learning Engineer

[LinkedIn](https://www.linkedin.com/in/raoufkhosravi/)

raykhosravi1993@gmail.com
