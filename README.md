# pi-smx-batoi-26-27
Este es el repositorio de ejemplo del proyecto de PI de SMX del curso 2026/2027
# Proyecto ERA
Es un proyecto personal para monitorear, gestionar y optimizar el consumo energetico de mis servidores locales
# Descripción
Esta solución nace de la necesidad de controlar la eficiencia energética de mi infraestructura doméstica
# Objetivos
Reducir el consumo eléctrico de mis equipos locales mediante la optimización de tareas.
Recopilar y visualizar métricas de uso de CPU, RAM y temperatura en tiempo real.
Automatizar el envío de alertas cuando se alcancen umbrales críticos de consumo.
# Tecnologías utilizadas
Lenguaje: Python 3
Entorno de ejecución: Linux (Ubuntu Server / Debian)
Scripting: Bash
Control de versiones: Git y GitHub
# Equipos y dispositivos
| Dispositivo | Función | Sistema Operativo | Consumo Promedio |
| :--- | :--- | :--- | :---: | :---: |
| **Raspberry Pi 4** | Servidor central | Raspberry Pi OS | ~5W | 
| **Servidor HomeLab** | Procesamiento y datos | Ubuntu Server 22.04 | ~45W | 
| **ESP32 NodeMCU** | Sensor de temperatura | Firmware C++ Custom | ~0.5W | 
# Recursos e imágenes
<img width="416" height="737" alt="image" src="https://github.com/user-attachments/assets/3610f555-9492-4c5d-b5c7-d1efd6beea88" />
# Instalación
Para preparar el sistema e instalar las herramientas necesarias, ejecuta el comando de actualización sudo apt update && sudo apt install 

#!/bin/bash
Clonar el repositorio
Acceder al directorio e instalar dependencias
cd era
pip3 install -r requirements.txt

Inicializar la aplicación
python3 main.py --start
# Tareas
Diseñar la arquitectura básica del proyecto y captura de datos de sensores.
Crear scripts de recopilación en Bash para métricas del sistema.
Desarrollar un panel de control web interactivo para visualización.
Configurar notificaciones de alerta mediante bot de Telegram.
# Autor
Proyecto desarrollado y mantenido por Nico Reig
