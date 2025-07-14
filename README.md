# Task 2: Play with a Relay Module

This is part of the Mongol Tori Electronics Recruitment Tasks.  
The objective of this task is to power a 5V relay module and hear the **"click"** sound when the relay is triggered — without using any microcontroller or code.

---

## ✅ Objective

- Power the relay safely.
- Trigger the relay manually using a jumper wire.
- Hear the mechanical "click" sound confirming it is working.

---

## 🧰 Components Used

| Item                  | Details                     |
|-----------------------|------------------------     |
| 5V Relay Module       | SRD-05VDC-SL-C              |
| 9V Battery            | Standard rectangular        |
| Battery Clip          | To connect 9V battery       |
| Breadboard            | For connections             |
| Jumper Wires          | Male-to-male, Male to female
                          Used to short IN to GND     |

---

## ⚠️ Caution

- **Do not leave the relay connected to 9V for too long**, as it is rated for 5V.
- This setup is only for short testing.

---

## 🔌 Wiring Instructions

### Control Pins of Relay:
VCC → 5V (connected to 9V battery + for a short time)
GND → GND (connected to 9V battery –)
IN → Connected to GND using jumper to trigger the relay


### Steps:
1. Place relay module into the breadboard.
2. Connect:
   - VCC to the 9V battery’s **+ terminal**
   - GND to the battery’s **– terminal**
3. Use a jumper wire to briefly connect **IN** pin to **GND** pin.
4. You should hear a **"click"** and see the relay's **red LED light up**.

---

## 📷 Demonstration

I have added some photos and a video
---

## 📖 What I Learned

- How to safely power and test a 5V relay module
- How relays work as electromagnetic switches
- Basics of low-level trigger relays

