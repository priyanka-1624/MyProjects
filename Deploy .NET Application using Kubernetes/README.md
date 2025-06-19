### 🚀 Deploying .NET App using Kubernetes

This project shows how to build a .NET web application using Docker and deploy it on Kubernetes using manifest files.

## 📁 Files Included

- `Dockerfile` – To build the app image  
- `deploy.yaml` – Deployment file for Kubernetes  
- `service.yaml` – To expose the app  
- `pod.yaml` – Optional: for single pod testing  
- `Deploy .NET Application using Kubernetes.pdf` – Steps and explanations
- 'Kubernetes'- key concepts of kubernetes
- `output-screenshot.png` – Final output of the deployed app


## 🛠️ Tools Used

- .NET 6  
- Docker & Docker Hub  
- Kubernetes (Minikube or AKS)  
- kubectl CLI


## 🔧 Steps to Run

1. **Build and Push Docker Image**
docker build -t <your-dockerhub-username>/<image-name>:v1 .
docker push <your-dockerhub-username>/<image-name>:v1

2. **Apply Kubernetes Files**

kubectl apply -f deploy.yaml
kubectl apply -f service.yaml

3. **Access the App**

* For Cloud (AKS):

kubectl get svc dotnet-service


## 📘 About the Project

This was completed as part of my internship at **Software Gurukulam**.
All key Kubernetes concepts like pods, deployments, and services are included and explained in the attached document.


## 🙏 Thanks To

Special thanks to my mentors at **Software Gurukulam** for their support and guidance.

## 📸 Output

![output](https://github.com/user-attachments/assets/813a222b-311b-4901-91b3-274b315eb2ba)


---

```

Let me know if you'd like a version with clickable Docker Hub or LinkedIn links!
```
