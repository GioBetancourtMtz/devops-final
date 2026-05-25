# Multi-Container DevOps Lab

Proyecto de infraestructura multi-contenedor utilizando Docker Compose y Nginx como reverse proxy y balanceador de carga.

---

## 🚀 Tecnologías utilizadas

- Docker
- Docker Compose
- Nginx
- Linux Ubuntu
- VirtualBox
- GitHub
- Networking básico

---

## 🧠 Arquitectura

Cliente → Nginx Reverse Proxy → Backends Dockerizados

- Backend v1
- Backend v2
- Backend v3

---

## ⚙️ Funcionalidades

- Reverse Proxy con Nginx
- Balanceo de carga entre múltiples contenedores
- Comunicación interna entre servicios Docker
- Despliegue multi-contenedor
- Configuración de red en Linux virtualizado

---

## 📦 Estructura del proyecto

```bash
backend-v1/
backend-v2/
backend-v3/
proxy/
docker-compose.yml
```

---

## ▶️ Cómo ejecutar el proyecto

```bash
docker compose up -d --build
```

---

## 🌐 Acceso

```bash
http://localhost:8080
```

---

## 📚 Aprendizajes

Durante este proyecto se trabajó con:

- Docker networking
- Reverse proxy
- Troubleshooting Linux
- Docker Compose
- Configuración Nginx
- Virtualización
- Git y GitHub SSH

---

## 👨‍💻 Autor

Giovanni Betancourt
