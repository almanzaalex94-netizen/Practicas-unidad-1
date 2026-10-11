# Práctica 2: Control ON-OFF de nivel

Repositorio correspondiente al desarrollo del sistema automático de control de nivel de líquidos con ESP32 de la asignatura **Sistemas Embebidos** (Universidad Politécnica del Bicentenario).

## 👥 Integrantes
- Alejandro Almanza Pérez
- Vanessa Guadalupe Soria Zavala
- Adán Rodríguez Ortiz
- América Aranzazu Rodríguez Pérez

---

## 📌 Descripción de la práctica
Implementación de un sistema de monitoreo y control automático del nivel de líquido en un tanque utilizando una tarjeta **ESP32**, un sensor ultrasónico **HC-SR04** para medir la distancia, una pantalla **LCD 16x2 con interfaz I2C**, tres botones de configuración (`SELECT`, `UP`, `DOWN`), y dos módulos relevadores para accionar una bomba de llenado y otra de drenado de forma cíclica en función de los umbrales de nivel bajo (`LL`) y nivel alto (`HL`).

---

## 📂 Contenido del repositorio
- `src/main.cpp`: Código fuente final implementando temporización con `millis()`, máquina de estados, filtrado por mediana para el sensor y rutina de recuperación del bus I2C.
- `docs/reporte.pdf`: Reporte completo de la práctica en formato PDF.
- `img/`: Carpeta con esquemáticos y capturas de pantalla del funcionamiento del circuito físico con las bombas y el tanque.
