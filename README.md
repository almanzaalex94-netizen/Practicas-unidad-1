# Práctica 1: Control de dispositivos básicos

## 📋 Introducción
Los sistemas embebidos forman parte esencial de la automatización moderna, permitiendo procesar información del entorno y responder de manera automática. En esta práctica se implementaron sistemas de control digital básicos utilizando una tarjeta de desarrollo **ESP32** y el entorno de programación Arduino IDE junto con simulaciones en Wokwi.

## 🎯 Objetivo General
Implementar sistemas de control digital utilizando una tarjeta ESP32 para accionar distintos tipos de cargas (LED, motor DC y foco de corriente alterna), comprendiendo el uso de señales digitales, niveles lógicos (HIGH/LOW) y elementos de potencia o aislamiento.

---

## 🛠️ Estructura de las Subprácticas

1. **Práctica 1.1: Control de LED**
   - **Descripción:** Control de encendido y apagado mediante dos botones pulsadores (`INPUT_PULLUP`) y un LED indicador con resistencia limitadora de 1 kΩ conectados al GPIO 2.
2. **Práctica 1.2: Control de Motor DC**
   - **Descripción:** Control de un motor de corriente directa mediante un transistor NPN (2N2222) como interruptor electrónico y una fuente externa de 5 V con diodo de protección flyback.
3. **Práctica 1.3: Control de Socket y Foco (AC)**
   - **Descripción:** Control de un foco de corriente alterna (110-127 V AC) utilizando un módulo relevador (relay) para asegurar el aislamiento eléctrico entre el circuito de control de bajo voltaje y el de potencia.

---

## 📂 Contenido del Repositorio
- `src/main.cpp`: Código fuente desarrollado en Arduino IDE.
- `diagram.json`: Diagrama esquemático de simulación en Wokwi.
- `docs/reporte.pdf`: Reporte completo de la práctica en formato PDF.
- `img/`: Carpeta con capturas de pantalla de las simulaciones y el montaje físico en protoboard.
