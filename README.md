# Todo Cloud App Menggunakan Minikube

## Identitas
Nama: Zachari  
NIM: 32602400113  
Kelas: B  
Mata Kuliah: Cloud Computing  

## Deskripsi Aplikasi
Aplikasi ini adalah aplikasi Todo List sederhana berbasis web yang berjalan di cloud emulator lokal menggunakan Minikube. Aplikasi ini menggunakan Kubernetes untuk menjalankan dua service utama, yaitu Flask sebagai web application dan PostgreSQL sebagai database.

## Service yang Digunakan
1. Flask Web Service
2. PostgreSQL Database Service

## Teknologi yang Digunakan
- Ubuntu
- Docker
- Minikube
- Kubernetes
- Python Flask
- PostgreSQL
- GitHub

## Struktur Project

```text
todo-cloud-app/
│
├── app/
│   ├── app.py
│   ├── requirements.txt
│   └── templates/
│       └── index.html
│
├── Dockerfile
│
├── k8s/
│   ├── postgres-deployment.yaml
│   ├── postgres-service.yaml
│   ├── flask-deployment.yaml
│   └── flask-service.yaml
│
└── README.md
