# Práctica 3: Control ON-OFF de temperatura

Repositorio correspondiente a la práctica de control térmico con ESP32 de la asignatura **Sistemas Embebidos** (Universidad Politécnica del Bicentenario)[cite: 37].

## 👥 Integrantes
- Alejandro Almanza Pérez[cite: 37]
- Vanessa Guadalupe Soria Zavala[cite: 37]
- Adán Rodríguez Ortiz[cite: 37]
- América Aranzazu Rodríguez Pérez[cite: 37]

---

## 📌 Descripción de la práctica
Implementación de un sistema de control de temperatura de tipo ON-OFF con histéresis dentro de una cámara de pruebas (caja de cartón), utilizando un sensor digital **DS18B20** en protocolo 1-Wire, una pantalla **LCD 16x2 I2C**, tres botones de configuración con antirrebote por software (`SEL`, `UP`, `DOWN`), y tres relevadores para controlar un **foco** (calentamiento), una **celda Peltier con disipador** (enfriamiento) y un **ventilador de circulación** permanente[cite: 37].

---

## 📂 Contenido del repositorio
- `src/main.cpp`: Código fuente con control de temperatura, umbrales configurables y temporización sin bloqueos (`millis()`)[cite: 37].
- `diagram.json`: Configuración de simulación en Wokwi[cite: 37].
- `docs/reporte.pdf`: Reporte completo de la práctica en formato PDF[cite: 37].
- `img/`: Carpeta con capturas del montaje físico, esquemáticos y pruebas del sistema térmico[cite: 37].
