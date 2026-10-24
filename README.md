# BioMach ♻️🤖
**Reciclaje inteligente con Inteligencia Artificial e Internet de las Cosas**

![C++](https://img.shields.io/badge/Language-C%2B%2B-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Arduino%2520UNO%2520R4-green.svg)
![AI](https://img.shields.io/badge/AI-Teachable%2520Machine-orange.svg)
![Status](https://img.shields.io/badge/Status-Prototipo%2520Funcional-brightgreen.svg)

Sistema automatizado de recolección de plástico enfocado en fomentar la cultura ambiental y la economía circular en el ámbito escolar, desarrollado por el **Centro de Interés Tecnobot Lisama - Liceo Samario**.

---

## 🧭 Diagrama de Flujo del Sistema (Ciclo de Usuario)

```mermaid
graph TD
    A[1. Regístrate] -->|App Lovable| B[2. Escanea la botella]
    B -->|Cámara del celular| C[3. IA la reconoce]
    C -->|Modelo Teachable Machine| D[4. Se abre la compuerta]
    D -->|Arduino UNO R4 + IoT| E[5. Gana puntos]
    E -->|1 punto por botella| F[Redimible en Cafetería Escolar]
```

---

## 🔄 Circuito de Economía Circular

```mermaid
graph LR
    Estudiante -->|Deposita botella| BioMach[BIOMACH + IA]
    BioMach -->|Control IoT| Arduino[Arduino & IoT]
    Arduino -->|Procesa material| Cooperativa[Cooperativa de Reciclaje]
    Cooperativa -->|Transforma en mobiliario| Cafeteria[Cafetería Escolar]
    Cafeteria -->|Incentivos / Puntos| Estudiante
```

---

## 🎯 Objetivos de Desarrollo Sostenible (ODS)
Este proyecto impacta directamente en los siguientes ODS de la Agenda 2030:
- **ODS 4:** Educación de calidad
- **ODS 9:** Industria, innovación e infraestructura
- **ODS 11:** Ciudades y comunidades sostenibles
- **ODS 12:** Producción y consumo responsables
- **ODS 13:** Acción por el clima
- **ODS 17:** Alianzas para lograr los objetivos

---

## 🛠️ Especificaciones de Hardware y Software
- **Microcontrolador:** Arduino UNO R4 (con capacidades IoT).
- **Inteligencia Artificial:** Modelo de reconocimiento de imágenes entrenado en Teachable Machine.
- **Desarrollo Frontend / App:** Plataforma Lovable.
- **Mecanismo:** Compuerta automatizada conectada a actuadores controlados por el microcontrolador.

---

## 📋 Asignación de Pines y Conexiones

| Componente | Función | Pin Arduino UNO R4 | Tipo |
| :--- | :--- | :--- | :--- |
| **Módulo IoT / ESP** | Comunicación Serial / Wi-Fi | Pines TX / RX o I2C | Digital / Bus |
| **Servo / Motor Compuerta** | Apertura de depósito | Pin 9 | PWM |
| **Sensor Presencia / Tapa** | Detección de recipiente lleno | Pin A0 | Digital In |
| **Alimentación Lógica** | VCC / GND | 5V / GND Común | Alimentación |

---

## 👥 Equipo Creador
* **Estudiantes:** Frank Jair Gutierrez Camargo, Shauny Carolina Bailon Perea, Camilo Andres Solano Arce, Maria Sofia Mendoza Ebratt, Juan Jose Diago Quiñones, Flor Marieth De Leon Espino.
* **Docente Líder:** Maria Del Pilar Hernandez Calderon.