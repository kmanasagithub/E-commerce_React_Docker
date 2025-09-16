# 🛒 E-commerce React Docker

A simple **E-commerce front-end application** built with **React (Vite)** and containerized using **Docker**.  
This project demonstrates how to set up a React app for local development and deploy it easily using Docker.

---

## 🚀 Features
- ⚡ Built with **React + Vite** for fast development  
- 🐳 Dockerized for easy deployment anywhere  
- 🎨 Ready for extension into a full E-commerce app (product pages, cart, checkout, etc.)  
- ✅ ESLint configured for clean code  

---

## 🛠️ Tech Stack
- **Frontend**: React (Vite)  
- **Containerization**: Docker  
- **Linting**: ESLint  

---

## 📋 Prerequisites
- Node.js (v18+) and npm  
- Docker installed on your system  

---
 
## 🔧 Running Locally (without Docker)

1. **Clone the repository:**
```bash
git clone https://github.com/kmanasagithub/E-commerce_React_Docker.git
cd E-commerce_React_Docker/frontend
```
2. **Install dependencies:**
 ```bash
   npm install
   ```
3. **Start development server:**
4.  ```bash
   npm run dev
  ```

## 🐳 Running with Docker
You can give your Docker image any name you like. Here we are using `ecommerce-react` as an example.

**Build Docker image:**
```bash
docker build -t ecommerce-react .
```

**Run container:**
```bash
docker run -p 3000:80 ecommerce-react
```

Open in browser 👉 **http://localhost:3000**


## 📥 Pulling from Docker Hub
If you don’t want to clone the code and build the image manually, you can directly pull the image from Docker Hub.  
```bash
docker pull manasakurella/e-commerce:v1
docker run -p 3000:80 manasakurella/e-commerce:v1
```

