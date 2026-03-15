 # 230V AC to ±12V DC Regulated Power Supply

A simple and reliable **regulated dual power supply circuit** that converts **230V AC mains voltage into ±12V DC output**. This type of power supply is commonly used in **operational amplifier circuits, audio amplifiers, and analog electronics projects**.

---

## 📌 Project Overview

This project demonstrates how to design and build a **dual rail regulated power supply** using a step-down transformer, rectifier diodes, filter capacitors, and voltage regulator ICs.

The circuit converts:

* **230V AC input**
* to **+12V DC and -12V DC regulated outputs**

This provides a **stable dual power supply** required for many electronic circuits.

---

## ⚙️ Components Required

| Component                                | Quantity    |
| ---------------------------------------- | ----------- |
| Step-down Transformer (230V to 12-0-12V) | 1           |
| Bridge Rectifier / Diodes (1N4007)       | 4           |
| Capacitors (2200µF / 25V)                | 2           |
| Capacitors (0.1µF)                       | 2           |
| Voltage Regulator IC 7812                | 1           |
| Voltage Regulator IC 7912                | 1           |
| Heat sinks for regulators                | 2           |
| PCB / Breadboard                         | 1           |
| Connecting wires                         | As required |

---

## 🔌 Circuit Blocks

The power supply consists of the following stages:

### 1️⃣ Step-down Transformer

Reduces **230V AC mains** to **12V-0-12V AC**.

### 2️⃣ Rectifier

The rectifier converts **AC voltage into pulsating DC** using diodes.

### 3️⃣ Filter Capacitors

Large capacitors smooth the rectified voltage and reduce ripple.

### 4️⃣ Voltage Regulators

* **7812** → provides **+12V regulated output**
* **7912** → provides **-12V regulated output**

This ensures stable and constant voltage output.

---

## 📊 Output

| Output        | Voltage |
| ------------- | ------- |
| Positive Rail | +12V DC |
| Ground        | 0V      |
| Negative Rail | -12V DC |

---

## 🔧 Applications

* Operational Amplifier Circuits
* Audio Amplifiers
* Analog Signal Processing
* Laboratory Power Supply
* Sensor Circuits

---

## ⚠️ Safety Notice

This circuit works with **230V AC mains**, which can be dangerous.

Always follow these precautions:

* Use proper insulation
* Do not touch live wires
* Test the circuit carefully
* Use a fuse if possible

---

## 🧠 Learning Outcomes

By completing this project you will understand:

* AC to DC conversion
* Full wave rectification
* Voltage regulation
* Dual power supply design

---

## 📜 License

This project is open-source and free to use for **educational purposes**.
