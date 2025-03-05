# 🌟 STM32 Traffic Light and Clock Simulation 🌟

This project includes multiple exercises to simulate and control LEDs and a 7-segment display using an STM32 microcontroller, modeled and tested in Proteus. The exercises build up from simple LED toggling to a complete clock display with multiple LEDs and a countdown timer.

## 📖 Table of Contents
- [💡 Exercise 1: LED Control](#exercise-1-led-control)
- [🚦 Exercise 2: Traffic Light Simulation](#exercise-2-traffic-light-simulation)
- [🔄 Exercise 3: 4-Way Traffic Light](#exercise-3-4-way-traffic-light)
- [7️⃣ Exercise 4: 7-Segment Display](#exercise-4-7-segment-display)
- [⏳ Exercise 5: Traffic Light with Countdown](#exercise-5-traffic-light-with-countdown)
- [🕒 Exercise 6: Analog Clock Simulation](#exercise-6-analog-clock-simulation)
- [🧹 Exercise 7: Clear All LEDs](#exercise-7-clear-all-leds)
- [🎯 Exercise 8: Set LED by Number](#exercise-8-set-led-by-number)
- [🚫 Exercise 9: Clear LED by Number](#exercise-9-clear-led-by-number)
- [⏰ Exercise 10: Complete Clock Display](#exercise-10-complete-clock-display)

## 💡 Exercise 1: LED Control
**Objective:** Connect two LEDs to STM32 and toggle their states every 2 seconds.
- **Components:** 🟥 RED LED (PA5), 🟨 YELLOW LED (PA6)
- **Report:**
  1. 📝 Schematic from Proteus with link to project file
  2. 🧑‍💻 Source code for the LED toggle in an infinite loop

## 🚦 Exercise 2: Traffic Light Simulation
**Objective:** Add a 🟩 GREEN LED (PA7) and simulate a simple traffic light sequence.
- **Cycle:** 🟥 RED (5s), 🟨 YELLOW (2s), 🟩 GREEN (3s)
- **Report:**
  1. 📝 Schematic from Proteus
  2. 🧑‍💻 Source code for the traffic light sequence

## 🔄 Exercise 3: 4-Way Traffic Light
**Objective:** Simulate a 4-way traffic light system using 12 LEDs arranged as shown in the reference design.
- **Report:**
  1. 📝 Schematic of the 4-way traffic light

## 7️⃣ Exercise 4: 7-Segment Display
**Objective:** Connect a 7-segment common anode display to STM32 (PB0 to PB6) and implement the `display7SEG(int num)` function.
- **Behavior:** Display numbers 0–9 by setting appropriate LED segments
- **Report:**
  1. 📝 Schematic including the 7-segment display
  2. 🧑‍💻 Source code for the `display7SEG` function

## ⏳ Exercise 5: Traffic Light with Countdown
**Objective:** Integrate the 7-segment display into the 4-way traffic light to show a countdown timer.
- **Report:**
  - 🧑‍💻 Source code only (re-using the `display7SEG` function)

## 🕒 Exercise 6: Analog Clock Simulation
**Objective:** Arrange 12 LEDs to represent an analog clock face (PA4 to PA15) and create a program to light them up sequentially.
- **Report:**
  1. 📝 Schematic of the clock face
  2. 🧑‍💻 Source code to light LEDs in sequence

## 🧹 Exercise 7: Clear All LEDs
**Objective:** Implement the `clearAllClock()` function to turn off all LEDs representing the clock face.
- **Report:**
  - 🧑‍💻 Source code for `clearAllClock()`

## 🎯 Exercise 8: Set LED by Number
**Objective:** Implement the `setNumberOnClock(int num)` function to turn on a specific LED.
- **Report:**
  - 🧑‍💻 Source code for `setNumberOnClock(int num)`

## 🚫 Exercise 9: Clear LED by Number
**Objective:** Implement the `clearNumberOnClock(int num)` function to turn off a specific LED.
- **Report:**
  - 🧑‍💻 Source code for `clearNumberOnClock(int num)`

## ⏰ Exercise 10: Complete Clock Display
**Objective:** Combine all previous functions to create a working analog clock display with 12 LEDs for hour, minute, and second hands.
- **Behavior:** Only 3 LEDs light up at any given time for hour, minute, and second.
- **Report:**
  - 🧑‍💻 Source code for the complete clock implementation

---

**🛠 Tools:**
- 🖥 STM32 Microcontroller
- 🧪 Proteus for simulation
- 📚 HAL library for STM32 programming

**🚀 How to Use:**
1. 🌀 Clone this repository.
2. 📝 Open the provided Proteus simulation files.
3. 🔥 Flash the provided STM32 code onto your board.
4. 👀 Follow each exercise’s instructions and observe the expected behavior.

**👥 Contributors:**
- 🧑‍💻 Beckversync

**📜 License:**
HCMUT

