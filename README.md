 📄 **Project Description (Short)**

This project is an interactive OLED-based robot face system built using Arduino and the U8g2 graphics library. It uses a capacitive touch sensor to trigger different emotional expressions, animations, and user interactions. The system displays blinking eyes, dynamic facial expressions, animated reactions, and an embedded mini-game to enhance user engagement. Designed for creative robotics and human–machine interaction experiments, this project demonstrates real-time graphics rendering, touch-based control logic, and state-driven animation flow on low-power microcontroller platforms.

---

## 📘 **README**

### 🧠 Interactive Robot Face with Touch Control & Mini Game

This project implements a fully interactive robot face interface on a 128×64 OLED display using Arduino. It combines facial animations, emotion-based responses, and a built-in Flappy-style mini game controlled through a single touch sensor. The system operates using a state-machine flow that manages transitions between idle mode, interaction mode, animation sequences, and gameplay.

The robot face reacts dynamically to user touch input by displaying expressions such as blinking, happy reactions, funny faces, shaking effects, and dialogue-based interactions. A custom double-tap and single-tap detection system is implemented to enable multiple interaction responses using only one input pin. Smooth animation timing is handled using non-blocking delay logic and frame control for consistent performance.

The project also includes a lightweight mini game rendered directly on the OLED display. Players control a moving star character using touch input while avoiding obstacles and tracking scores in real time. Game logic includes gravity simulation, collision detection, scoring, and restart handling.

This system demonstrates effective integration of graphics rendering, input processing, animation control, and embedded game development on limited hardware resources. It is suitable for robotics projects, interactive displays, human–robot interaction prototypes, and embedded UI experimentation.

### ⚙️ Features

* Touch-based interaction system
* Animated robot facial expressions
* Smooth blinking and emotion effects
* Single and double tap detection
* Built-in OLED mini game
* State-based flow control
* Low-power embedded implementation

### 🛠 Hardware Used

* Arduino-compatible board
* 128×64 OLED Display (SSD1306)
* Capacitive Touch Sensor
* I2C Communication

### 📚 Libraries Required

* U8g2 Graphics Library
* Wire (I2C Communication)
