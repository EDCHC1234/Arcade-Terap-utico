# Arcade-Terap-utico
# 🎮 Arcade Terapéutico Inteligente

Sistema embebido basado en ESP32 orientado al desarrollo de la motricidad fina y la coordinación ojo-mano en niños con Trastorno del Espectro Autista (TEA) y Trastorno por Déficit de Atención e Hiperactividad (TDAH), mediante minijuegos interactivos y monitoreo remoto utilizando tecnologías IoT.

---

## 📖 Descripción

El Arcade Terapéutico Inteligente es una consola portátil diseñada para complementar las terapias ocupacionales mediante actividades lúdicas que permiten evaluar y estimular habilidades motoras.

El sistema registra automáticamente métricas como:

- Tiempo de reacción
- Precisión
- Cantidad de errores
- Duración de la sesión

Posteriormente los datos son enviados mediante WiFi utilizando MQTT hacia Firebase, donde pueden ser visualizados desde un Dashboard Web por el terapeuta.

---

## 🎯 Objetivos

### Objetivo General

Diseñar e implementar un sistema embebido portátil que contribuya al fortalecimiento de la motricidad fina mediante minijuegos interactivos y tecnologías IoT.

### Objetivos Específicos

- Desarrollar una interfaz gráfica interactiva.
- Implementar minijuegos terapéuticos.
- Capturar métricas del desempeño del usuario.
- Enviar información hacia la nube mediante MQTT.
- Visualizar estadísticas mediante un Dashboard Web.

---

# 🕹️ Juegos

Actualmente el sistema cuenta con los siguientes juegos:

- 🎯 Traza Fácil
- ⭐ Rescate
- 🎨 Color Memory
- 🟢 Simón Dice

---

# ⚙️ Arquitectura del Sistema

El sistema está compuesto por:

- ESP32
- Pantalla OLED SSD1306
- Joystick Analógico
- Botoneras RGB
- LEDs Indicadores
- Buzzer
- WiFi
- MQTT
- Firebase
- Dashboard Web

---

# 🛠️ Hardware

| Componente | Cantidad |
|------------|----------|
| ESP32 NODE MCU | 1 |
| Pantalla OLED SSD1306 | 1 |
| Joystick Analógico | 1 |
| Botones RGB | 4 |
| LEDs | 5 |
| Buzzer | 1 |
| Batería LiPo 3.7V | 1 |
| TP4056 | 1 |

---

# 💻 Software

- Arduino IDE
- PlatformIO
- Wokwi
- Photopea
- Image2CPP
- Firebase
- MQTT
- GitHub



#  Diagrama de conexiones 
![Arcade Terapéutico](images/prototipo.jpg)
