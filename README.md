# Simulation-4-DC-Motors-movement
Arduino-based 4-motor control  simulation using L293D on Tinkercad.


A complete simulation project built on **Tinkercad Circuits** demonstrating 4-wheel DC motor control using the L293D driver

##  Project Features

### Motion Sequence (DC Motors + L293D)
* **Forward Motion:** All 4 DC motors run forward for **30 seconds**.
* **Reverse Motion:** Motors reverse direction for **60 seconds**.
* **Alternating Turns:** Simulates steering by alternating rotation directions (left/right) for **60 seconds**.


---

##  Components Used

* **Arduino Uno**
* **L293D Motor Driver IC**
* **4x DC Motors**
* **External Power Supply** (e.g., 9V Battery)
* **Breadboard & Connecting Wires**

---

##  How It Works (System Execution Flow)

1. **Phase 1: Forward Motion (30 Seconds)**
   * All 4 DC motors rotate forward at full speed for 30 seconds.

2. **Phase 2: Reverse Motion (60 Seconds)**
   * The L293D driver reverses the current polarity, driving all 4 motors backward for 60 seconds.

3. **Phase 3: Alternating Steering (60 Seconds)**
   * The system alternates steering directions (left and right) every 5 seconds for a total duration of 60 seconds.

## Tinkercad Link: https://www.tinkercad.com/things/6CKOZQQf7Ux-fantastic-hillar/editel
