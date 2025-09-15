# ATRIZ – Plataforma de Acceso Remoto para Robótica en Enjambre

ATRIZ es un **laboratorio remoto y abierto** diseñado para la experimentación en robótica de enjambre.  
Su objetivo principal es brindar a estudiantes, investigadores y docentes una infraestructura accesible para el **control, programación y monitoreo de robots Sphero RVR** de manera remota, integrando **frontend, backend y ROS** en una misma arquitectura.

---

## 📑 Documentación

Este repositorio centraliza y organiza los componentes del ecosistema ATRIZ.  
La documentación se encuentra en la carpeta [`docs/`](docs/) e incluye:

- **Documento de Desarrollo de Software**  
  Explica la arquitectura del sistema, diseño modular y lineamientos de implementación.  

- **Documento de Pruebas e Implementación**  
  Contiene la estrategia de validación de la plataforma, incluyendo:  
  - Pruebas del **Frontend** (control de experimentos, transmisión de video).  
  - Pruebas del **Backend** (API RESTful con FastAPI, integración con ROS).  
  - Pruebas de **Seguridad y Autenticación**.  

---

## 🏗️ Estructura del Repositorio

Este repositorio utiliza **submódulos de Git** para integrar los diferentes componentes:

