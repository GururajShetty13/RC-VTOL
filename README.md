# RC-VTOL Plane

## Project Overview
The **RC-VTOL (Remote-Controlled Vertical Take-Off and Landing)** plane is designed for disaster response applications such as aerial monitoring and small payload delivery. It combines the vertical lift capabilities of quadcopters and the speed of fixed-wing drones. This project showcases the design, fabrication, and testing of a cost-effective, lightweight VTOL aircraft optimized for stability, speed, and payload capacity.

---

## Key Features
- **Vertical Take-Off and Landing (VTOL):** Eliminates the need for a runway.
- **Dual Mode Flight:** Tilting mechanism enables transition between hovering and forward flight.
- **Payload Delivery:** Designed to carry small payloads like medical supplies or cameras.
- **Efficient Monitoring:** Faster coverage of disaster areas compared to traditional quadcopters.
- **Live Video Transmission:** Equipped with a 2MP FPV camera for real-time aerial monitoring.

---

## Objectives
- Design and fabricate a lightweight VTOL aircraft with a thrust-to-weight ratio greater than 1.5.
- Integrate a tilting mechanism for motor axis control during flight.
- Optimize structural dimensions for stable flight and payload capacity.
- Calibrate the KK flight controller for precise control and stability.

---

## Skills Demonstrated
- **Aerodynamics:** Applied concepts for wing design using Clark-Y aerofoil.
- **CAD Modeling:** Designed and analyzed components using 3D modeling software.
- **Structural Analysis:** Evaluated wing strength through static structural simulations.
- **Microcontroller Integration:** Configured KK flight controllers and interfaced with electronic components.
- **Prototyping:** Used 3D printing (ABS material) and foam sheets for lightweight and durable construction.
- **Testing and Optimization:** Performed iterative testing to refine thrust-to-weight ratio and flight performance.

---

## Components and Materials
### Electronics:
- **Motors:** BLDC motor (1600KV)
- **Controller:** KK Board Flight Controller
- **Battery:** 11.1V, 2200mAh, 25C Li-Po
- **FPV Camera:** 2MP with live transmission
- **ESCs:** 30A Electronic Speed Controllers
- **Transmitter/Receiver:** Graupner mz-12, 2.4GHz

### Mechanical:
- **Wing Material:** Depron Foam
- **Structure Support:** Stainless steel rods (10mm)
- **Propellers:** 10x4.5
- **Servo Motors:** 3kg and surface controller servos

### Tools:
- **3D Printing:** ABS motor housing and tilting mechanism
- **Fabrication Materials:** Foam sheets for wings and fuselage

---

## System Architecture
### Design Highlights:
1. **Wing Design:** Clark-Y aerofoil with a 1m wingspan optimized for lift and speed.
2. **Fuselage:** Aerodynamic structure housing critical components.
3. **Tail Stabilizer:** Designed for enhanced maneuverability.
4. **Motor Tilting Mechanism:** Allows axis adjustment for transition between hover and forward flight.

### Block Diagram:
(Add the system diagram from the report here.)

---

## Installation and Usage
### Requirements:
- Assembly of VTOL aircraft components as per the provided design and specifications.
- Installation of KK flight controller and calibration using standard PID values.
- Setup of FPV camera and Graupner transmitter/receiver for live monitoring.

### Steps:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/rc-vtol-plane.git
