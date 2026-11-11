# 🚨 SAMEI - Sistema de Alerta Multisensorial para Entornos Inclusivos

Este proyecto consiste en el diseño e implementación en hardware reconfigurable (FPGA) de un sistema de alerta para hogares, diseñado específicamente para superar las barreras de los sistemas tradicionales en personas con discapacidad auditiva o visual[cite: 4]. 

Desarrollado en **VHDL**, el sistema procesa señales de sensores físicos reales sin latencia para detectar peligros invisibles (como fugas de gas o agua) y emite respuestas adaptadas a diferentes necesidades[cite: 4].

## ⚙️ Características y Soluciones Inclusivas
El sistema aborda problemas comunes de accesibilidad mediante las siguientes soluciones:

* **Respuesta Visual Clara (Discapacidad Auditiva):** Sustituye las alarmas 100% acústicas mediante una salida a pantalla VGA con avisos descriptivos y un LED RGB con un código estricto de colores[cite: 4].
* **Respuesta Sonora Asimétrica (Discapacidad Visual / Daltonismo):** Evita los tonos genéricos utilizando un zumbador con frecuencias y ritmos distintos, permitiendo identificar el peligro exacto sin necesidad de mirar[cite: 4].
* **Detección Física Real (Riesgos Universales):** Integración de sensores de hardware (gas y agua) procesados directamente en la FPGA[cite: 4].

## 🧠 Arquitectura Lógica
El núcleo del sistema está gobernado por una **Máquina de Estados** finita que gestiona las transiciones entre distintos eventos críticos:
* Sistema Correcto[cite: 4]
* Alerta Gas[cite: 4]
* Alerta Inundación[cite: 4]
* Alerta Incendio[cite: 4]
* Timbre Manual[cite: 4]

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** VHDL
* **Hardware:** FPGA, Pantalla VGA, Sensores de Gas/Agua, Zumbador, LEDs RGB.
* **Conceptos:** Diseño de hardware reconfigurable, Máquinas de estados, Lógica combinacional y secuencial.

## 📂 Contenido del Repositorio
* `/src`: Código fuente en VHDL.
* `Memoria_SAMEI.pdf`: Documentación detallada con esquemas físicos, lógicos y el diseño de la máquina de estados.
* **[AQUÍ PUEDES AÑADIR UN ENLACE AL VÍDEO DEMOSTRATIVO SI NO LO SUBES DIRECTAMENTE]**

---
*Proyecto desarrollado en la Universidad Politécnica de Madrid (UPM) por Mario Reyes Morales, Rubén Nuño Peña, David Sánchez Sánchez y Lucas Rojas Tena*[cite: 4].
