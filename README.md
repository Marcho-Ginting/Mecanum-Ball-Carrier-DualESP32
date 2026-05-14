# Mecanum-Ball-Carrier-DualESP32

A high-performance mechatronic system utilizing omnidirectional locomotion and a distributed processing architecture for precision robotics tasks.

## 📊 Technical Specifications
* **Architecture:** Dual-ESP32 System (Distributed processing for control and feedback).
* **Locomotion:** 4-wheel drive using Mecanum wheels for 360-degree holonomic movement.
* **Actuation:** 4x High-torque Direct Drive actuators with integrated encoders.
* **PCB:** Custom-manufactured board for power distribution and encoder signal conditioning.

## ⚡ Engineering Highlights
* **Distributed Processing:** Implemented a Dual-ESP32 architecture to isolate real-time motor control and encoder processing from higher-level telemetry and communication, ensuring system stability.
* **Precision Motion Control:** Developed algorithms for Mecanum wheel kinematics, utilizing closed-loop encoder feedback to achieve high-precision velocity and positional tracking.
* **System Integration:** Engineered a custom PCB to consolidate four motor drivers and encoder inputs, optimizing signal integrity and reducing the mechanical footprint of the electronics.
* **Leadership:** Led a cross-disciplinary team of engineers, managing the full development lifecycle from component selection to final system debugging.

## 📂 Repository Structure
* `/logic`: Main logic digital board
* `/pdb`: Driver motor and power distribution board.

## 📷 3D KiCad Render Images

<table style="width:100%">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/d2523e2f-f1d4-4292-b517-9fade1e2caa5" width="400px"/><br/>
      <b>PDB</b>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/e657f1ac-b52f-46bd-bcaf-cec199f32f83" width="400px"/><br/>
      <b>Logic</b>
    </td>
  </tr>
</table>
