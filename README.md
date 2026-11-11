# 🚨 SAMEI - Sistema de Alerta Multisensorial para Entornos Inclusivos

Este proyecto consiste en el diseño e implementación en hardware reconfigurable (FPGA) de un sistema de alerta para hogares, diseñado específicamente para superar las barreras de los sistemas tradicionales en personas con discapacidad auditiva o visual. 

Desarrollado en **VHDL**, el sistema procesa señales de sensores físicos reales sin latencia para detectar peligros invisibles (como fugas de gas o agua) y emite respuestas adaptadas a diferentes necesidades.

## ⚙️ Características y Soluciones Inclusivas
El sistema aborda problemas comunes de accesibilidad mediante las siguientes soluciones:

* **Respuesta Visual Clara (Discapacidad Auditiva):** Sustituye las alarmas 100% acústicas mediante una salida a pantalla VGA con avisos descriptivos y un LED RGB con un código estricto de colores.
* **Respuesta Sonora Asimétrica (Discapacidad Visual / Daltonismo):** Evita los tonos genéricos utilizando un zumbador con frecuencias y ritmos distintos, permitiendo identificar el peligro exacto sin necesidad de mirar.
* **Detección Física Real (Riesgos Universales):** Integración de sensores de hardware (gas y agua) procesados directamente en la FPGA.

## 🧠 Arquitectura Lógica
El núcleo del sistema está gobernado por una **Máquina de Estados** finita que gestiona las transiciones entre distintos eventos críticos:
* Sistema Correcto
* Alerta Gas
* Alerta Inundación
* Alerta Incendio
* Timbre Manual

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** VHDL
* **Hardware:** FPGA, Pantalla VGA, Sensores de Gas/Agua, Zumbador, LEDs RGB.
* **Conceptos:** Diseño de hardware reconfigurable, Máquinas de estados, Lógica combinacional y secuencial.

## 📂 Contenido del Repositorio
* `/src`: Código fuente en VHDL.
* `Memoria_SAMEI.pdf`: Documentación detallada con esquemas físicos, lógicos y el diseño de la máquina de estados.
* 🎥 **[Ver Vídeo Demostrativo del Sistema SAMEI](https://youtu.be/vvB6sryHlNw?si=INlfsYc-3ewgLeg7)**

---
*Proyecto desarrollado en la Universidad Politécnica de Madrid (UPM) por Mario Reyes Morales,
