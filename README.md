# WebSocket Client-Server Project

## Description / Descripción

**English**:  

This project demonstrates a simple WebSocket client-server interaction. The server listens for incoming connections and processes messages from clients, responding in real-time. The application is Dockerized, allowing for easy deployment and testing.  

**Español**:  

Este proyecto demuestra una interacción cliente-servidor simple usando WebSockets. El servidor escucha conexiones entrantes, procesa los mensajes de los clientes y responde en tiempo real. La aplicación está dockerizada, lo que facilita su implementación y pruebas.

---

## Requirements / Requisitos

**Languages and Tools Used / Lenguajes y herramientas utilizadas**:  
- **Python**: Version 3.10 or later / Versión 3.10 o posterior  
- **Docker**: Version 20.10 or later / Versión 20.10 o posterior  
- **Libraries**:
  - `websockets`: To handle WebSocket connections.

---

## Setup Instructions / Instrucciones de Configuración

### Clone the Project / Clonar el Proyecto

```bash
git clone <repository_url>
cd <repository_directory>
```

**Run Without Docker / Ejecutar sin Docker**

**Install Dependencies / Instalar Dependencias:**

```bash
pip install websockets
```
Run the Server / Ejecutar el Servidor:

```bash
python server.py
```
**Run the Client / Ejecutar el Cliente:**

```bash
python client.py
```
**Docker Instructions / Instrucciones para Docker**
Build and Run the Docker Container / Crear y ejecutar el contenedor Docker
Build the Docker Image / Crear la imagen Docker:

```bash
docker build -t websocket-app .
```
**Run the Docker Container / Ejecutar el contenedor Docker:**

```bash
docker run --name websocket-app-container -p 8765:8765 websocket-app
```
Docker Hub
Docker Hub Repository:
Link to Docker Hub Repository

**Repositorio de Docker Hub:**
Enlace al repositorio de Docker Hub

### **Tips for Customization**:
- Replace `<repository_url>` with the actual Git repository URL.
- Replace `#` in the Docker Hub section with the link to your Docker Hub image when available.
