# Práctica 1: Control de dispositivos básicos

Repositorio correspondientes a las actividades prácticas de la asignatura de **Sistemas Embebidos** de la Universidad Politécnica del Bicentenario.

## 👥 Integrantes
- Alejandro Almanza Pérez
- Vanessa Guadalupe Soria Zavala
- Adán Rodríguez Ortiz
- América Aranzazu Rodríguez Pérez

---

## 📌 Descripción de la práctica
Implementación de sistemas de control digital utilizando una tarjeta de desarrollo **ESP32** para accionar distintos tipos de cargas (LED, motor DC y foco de corriente alterna), aplicando conceptos de señales digitales, niveles lógicos (`HIGH`/`LOW`), resistencias de pull-up internas (`INPUT_PULLUP`), y elementos de potencia (transistores NPN y módulos relevadores).

---

## 📂 Contenido del repositorio
- `src/led/main.cpp`: Código para el control básico de un LED con botones.
- `src/motor/main.cpp`: Código para el control de un motor DC mediante un transistor 2N2222.
- `src/foco/main.cpp`: Código para el control de un foco AC de 110V mediante un módulo relevador (relay).
- `diagram.json`: Configuración de simulación en Wokwi.
- `docs/reporte.pdf`: Reporte completo de la práctica en formato PDF.
- `img/`: Carpeta con esquemáticos y capturas de pantalla del funcionamiento físico.
