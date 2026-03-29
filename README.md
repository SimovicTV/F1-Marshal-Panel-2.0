# F1-Marshal-Panel-2.0
This version is a major upgrade over the original — both visually and functionally.

🚦 **F1 Marshal Panel – Version 2.0** 🏁

After a lot of testing, tweaking, and feedback, I’m happy to share **Version 2.0** of my DIY F1 Marshal Panel project.

This version is a major upgrade over the original — both visually and functionally.

---

### 🔧 Hardware

* 16×16 WS2812 LED matrix
* ESP8266 (Wemos D1 Mini)
* Powered and controlled via ESPHome + Home Assistant

---

### 🚀 What’s new in Version 2.0

* 🏁 **New FINISHED mode**
  Clean 4×4 checkered flag animation with smooth fade transitions, optimized for low-resolution panels.

* 🚨 **Improved Safety Car (SC)**
  Static white “SC” with **4 independent moving “snakes”** around the border (extended length for smoother motion).

* 🟡 **Virtual Safety Car (VSC)**
  Constant yellow border + blinking white “VSC” text.

* 🟢 **CLEAR logic fixed**
  Green signal now turns off correctly after 5 seconds (no more stuck state).

* 🔴 **RED & YELLOW refined**
  Better timing and visual clarity.

* 💡 **Brightness control**
  Adjustable directly from Home Assistant.

* 🎮 **Built-in TEST buttons**
  Trigger every state manually (CLEAR / YELLOW / RED / SC / VSC / FINISHED).

* 🧠 **Smart HA integration**

  * `sensor.f1_track_status`
  * `sensor.f1_session_session_status`
  * Automatic reaction to session finish

---

### ⚙️ Behavior

* Panel automatically reacts to live F1 data from Home Assistant
* FINISHED mode overrides all other states (30 seconds runtime)
* System is stable, responsive, and designed for real-time use

---

### 🎯 Goal

The main idea was to create a **portable, standalone F1 marshal-style panel** that:

* works reliably
* looks clean even on a 16×16 matrix
* can be easily integrated or taken anywhere

---
<img width="320" height="1677" alt="image" src="https://github.com/user-attachments/assets/934f1014-1145-4799-90c7-37a05030abc7" /> <img width="320" height="2226" alt="image" src="https://github.com/user-attachments/assets/6a5c5afc-3e25-4ee9-9302-bd6a5729b7e9" />

<img width="270" height="480" alt="image" src="https://github.com/user-attachments/assets/7cd9e9ed-1e70-4f47-b38e-b5a0a4f97a62" />




If anyone is building something similar or has ideas for further improvements, I’d love to hear feedback!

🏁 Version 2.0 is just the beginning.

