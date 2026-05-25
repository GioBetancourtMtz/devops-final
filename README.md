# Multi-Container DevOps Lab

Proyecto de infraestructura multi-contenedor utilizando Docker Compose y Nginx como reverse proxy y balanceador de carga.

---

##  Tecnologías utilizadas

- Docker
- Docker Compose
- Nginx
- Linux Ubuntu
- VirtualBox
- GitHub
- Networking básico

---

## Arquitectura

Cliente → Nginx Reverse Proxy → Backends Dockerizados

- Backend v1
- Backend v2
- Backend v3

---

## Funcionalidades

- Reverse Proxy con Nginx
- Balanceo de carga entre múltiples contenedores
- Comunicación interna entre servicios Docker
- Despliegue multi-contenedor
- Configuración de red en Linux virtualizado

---

## Estructura del proyecto

```bash
backend-v1/
backend-v2/
backend-v3/
proxy/
docker-compose.yml
```

---

##  Cómo ejecutar el proyecto

```bash
docker compose up -d --build
```

---

## Acceso

```bash
http://192.168.100.15:8080
```

---

##  Aprendizajes

Durante este proyecto se trabajó con:

- Docker networking
- Reverse proxy
- Troubleshooting Linux
- Docker Compose
- Configuración Nginx
- Virtualización
- Git y GitHub SSH

---

## Autor

Giovanni Betancourt



##Screenshots
<img width="1366" height="768" alt="Estructura" src="https://github.com/user-attachments/assets/eeacb7c3-c7b7-4303-9e8f-3b5ef2969a4c" />
<img width="1366" height="768" alt="docker" src="https://github.com/user-attachments/assets/ace1f567-a301-4c66-b2a6-3f80f04997b6" />
<img width="1366" height="768" alt="Backends" src="https://github.com/user-attachments/assets/6596d4f8-5c28-491b-8492-8c0ec0d695b7" />
