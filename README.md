# 🖥️ Primer Parcial - Servicios Telemáticos (G51)


---
## 🧑‍🤝‍🧑 Autores
- **Sebastián Medina García**  
- **Juan David Trujillo**

---

Este repositorio contiene los **scripts** y configuraciones realizadas para el **Primer Parcial** de la asignatura **Servicios Telemáticos**, correspondiente al semestre 2025-03, en la **Universidad Autónoma de Occidente**.

## 📌 Descripción General

El parcial consistió en tres partes principales, cada una abordada en un script o conjunto de archivos independientes:

### **1️⃣ Configuración de Autenticación PAM en Apache**
- Configuración de un **servidor Apache** en Ubuntu 22.04.
- Implementación de autenticación mediante **PAM (Pluggable Authentication Modules)**.
- Creación de un directorio privado `/archivos_privados` protegido.
- Definición de una **lista de usuarios denegados**.
- Personalización del mensaje de error para intentos de acceso cancelados.
- Validación del correcto funcionamiento de la autenticación.

📂 **Carpeta/Archivo:** `01-apache-pam/`

---

### **2️⃣ Configuración de Servidores DNS Maestro/Esclavo**
- Instalación y configuración de **Bind9**.
- Implementación de un servidor **DNS maestro** con zona directa e inversa.
- Configuración de un **DNS esclavo** con **transferencia de zona (AXFR)**.
- Pruebas de resolución directa e inversa desde clientes.
- Verificación de funcionamiento del esclavo sin conexión al maestro.

📂 **Carpeta/Archivo:** `02-dns-maestro-esclavo/`

---

### **3️⃣ Exposición del Servidor Web con Ngrok**
- Configuración de un **túnel seguro** para exponer un servidor web local.
- Implementación de **Ngrok** para acceso remoto.
- Creación de una **página personalizada** de prueba.
- Validación del funcionamiento desde dispositivos externos.

📂 **Carpeta/Archivo:** `03-ngrok/`

---

## 🚀 Tecnologías Utilizadas
- **Ubuntu 22.04 (VMs con Vagrant)**
- **Apache2**
- **PAM (Pluggable Authentication Modules)**
- **Bind9 (DNS)**
- **Ngrok**
- **Bash & Scripts de Configuración**

---


## 📄 Licencia
Este proyecto fue desarrollado únicamente con fines académicos.  
**Universidad Autónoma de Occidente** - Facultad de Ingeniería.  
