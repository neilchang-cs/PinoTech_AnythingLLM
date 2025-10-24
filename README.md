# 🧠 Project Title

This project is designed to run in a **Windows 11 + WSL (Windows Subsystem for Linux)** environment with GPU acceleration support (e.g., RTX 2080).  
Before executing `./run`, please make sure both **Docker** and **Ollama** are properly installed.

---

## 📦 Environment Information

| Component | Description |
|------------|-------------|
| Operating System | Windows 11 (24H2) |
| Development Environment | WSL (Windows Subsystem for Linux) |
| GPU | NVIDIA RTX 2080 |

---

## ⚙️ Prerequisites

Before running the project (`./run`), please ensure the following dependencies are installed.

### 1️⃣ Install Docker (on Windows)

Download and install Docker Desktop from the official website:  
👉 [https://www.docker.com/](https://www.docker.com/)

> **Note:**  
> - Ensure Docker Desktop is **running**.  
> - Enable **WSL integration** for your chosen Linux distribution under Docker settings.  

---

### 2️⃣ Install Ollama (on WSL)

Inside your WSL environment, run the following command:

```bash
curl -fsSL https://ollama.com/install.sh | sh
```

> **Tips:**  
> - The installation script automatically detects your system architecture and environment.  
> - After installation, verify it by running `ollama --version`.  
> - If you are using a GPU (e.g., RTX 2080), make sure the **NVIDIA driver with WSL support** is installed on Windows.  

---

## Loading AI Model

After installing ollama, you can refer to the "command" content to load the available models.


## 🚀 Running the Project

Once Docker and Ollama are installed, you can start the project by running:

```bash
./run
```