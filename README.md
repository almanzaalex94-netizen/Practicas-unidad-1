# ⚙️ Portafolio de Prácticas - Sistemas Embebidos

Repositorio global que contiene la documentación, códigos fuente y diseños de simulación de las prácticas correspondientes a la asignatura de **Sistemas Embebidos** de la **Universidad Politécnica del Bicentenario**[cite: 5, 10, 37].

---

## 👨‍🎓 Datos Generales
* **Asignatura:** Sistemas Embebidos[cite: 5, 10, 37]
* **Profesor:** Hugo Antonio Méndez Guzmán[cite: 5, 10, 37]
* **Grupo:** IME 702[cite: 10]

### Integrantes del Equipo:
* Alejandro Almanza Pérez[cite: 5, 10, 37]
* Vanessa Guadalupe Soria Zavala[cite: 5, 10, 37]
* Adán Rodríguez Ortiz[cite: 5, 10, 37]
* América Aranzazu Rodríguez Pérez[cite: 5, 10, 37]

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

### 📁 Práctica 3: Control ON-OFF de temperatura
* **Descripción:** Implementación de un sistema de control de temperatura de tipo ON-OFF con histéresis dentro de una cámara de pruebas (caja de cartón)[cite: 37]. Utiliza un sensor digital DS18B20 en protocolo 1-Wire, una pantalla LCD 16x2 I2C, tres botones de configuración con antirrebote por software (`SEL`, `UP`, `DOWN`), y tres relevadores para accionar un foco (calentamiento), una celda Peltier con disipador (enfriamiento) y un ventilador de circulación permanente[cite: 37].

---

## 🛠️ Stack Tecnológico
* **Microcontrolador:** ESP32 DevKit C V4[cite: 5]
* **Entorno de Desarrollo:** Arduino IDE[cite: 5]
* **Simulación:** Wokwi[cite: 5]
* **Librerías principales:** `LiquidCrystal_I2C`, `DallasTemperature`, `OneWire`[cite: 20, 37]
