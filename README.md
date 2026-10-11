# ⚙️ Portafolio de Prácticas - Sistemas Embebidos

Repositorio global que contiene la documentación, códigos fuente y diseños de simulación de las prácticas correspondientes a la asignatura de **Sistemas Embebidos** de la **Universidad Politécnica del Bicentenario**[cite: 5, 10].

---

## 👨‍🎓 Datos Generales
* **Asignatura:** Sistemas Embebidos[cite: 5, 10]
* **Profesor:** Hugo Antonio Méndez Guzmán[cite: 5, 10]
* **Grupo:** IME 702[cite: 10]

### Integrantes del Equipo:
* Alejandro Almanza Pérez[cite: 5, 10]
* Vanessa Guadalupe Soria Zavala[cite: 5, 10]
* Adán Rodríguez Ortiz[cite: 5, 10]
* América Aranzazu Rodríguez Pérez[cite: 5, 10]

---

## 📂 Estructura del Repositorio

El repositorio se encuentra organizado de forma modular por cada práctica desarrollada a lo largo de la unidad[cite: 1]:

### 📁 Práctica 1: Control de dispositivos básicos
* **Descripción:** Implementación de sistemas de control digital básicos mediante una tarjeta de desarrollo ESP32, evaluando el comportamiento de las entradas digitales con botones y diferentes tipos de cargas de salida[cite: 5].
* **Variaciones incluidas:**
  1. *Control de LED* (Salida digital directa con resistencia limitadora)[cite: 5].
  2. *Control de Motor DC* (Conmutación de potencia mediante transistor NPN y diodo flyback)[cite: 5].
  3. *Control de Socket y Foco AC* (Aislamiento eléctrico y control de alto voltaje mediante módulo relevador)[cite: 5].

### 📁 Práctica 2: Control ON-OFF de nivel
* **Descripción:** Diseño e implementación de un sistema automático de control de nivel de líquidos en un tanque[cite: 16]. Emplea un sensor ultrasónico HC-SR04 para la medición de distancia, una pantalla LCD 16x2 con interfaz I2C para la visualización de parámetros en tiempo real, botones de configuración de umbrales ($LL$ y $HL$), y un sistema de relevadores para accionar de forma cíclica las bombas de llenado y drenado[cite: 16].

---

## 🛠️ Stack Tecnológico
* **Microcontrolador:** ESP32 DevKit C V4[cite: 5]
* **Entorno de Desarrollo:** Arduino IDE[cite: 5]
* **Simulación:** Wokwi[cite: 5]
* **Lector de Periféricos:** Librerías `LiquidCrystal_I2C`[cite: 20]
