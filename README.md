# Bluetooth-Controlled Car  

## Overview  
This project demonstrates a **wireless remote-controlled car** using **Bluetooth technology** and a **mobile app**. By integrating an **Arduino Uno** and a **Bluetooth module (HC-05)**, the car can be controlled remotely using simple button commands on a smartphone.  

## Problem Statement  
Remote-controlled devices are widely used in various fields, from **toys** to **industrial automation**. Traditional remote systems rely on bulky controllers or fixed setups, limiting flexibility. This project aims to **simplify remote control** by using a **Bluetooth-enabled mobile app**, making it more accessible and efficient.  

## How It Works  
1. A **mobile app** is used to send movement commands via **Bluetooth**.  
2. The **HC-05 Bluetooth module** receives the commands and sends them to the **Arduino Uno**.  
3. The **Arduino** processes the commands and controls the **motor driver (L293D)**.  
4. The **motor driver** regulates the speed and direction of the **DC motors**, allowing the car to move **forward, backward, left, or right**.  
5. The car is powered by a **battery pack**, ensuring independent movement.  

## Components Used  
- **Arduino UNO** – The brain of the car, processes commands.  
- **Bluetooth Module (HC-05)** – Establishes wireless communication with the mobile app.  
- **Motor Driver (L293D)** – Controls the direction and speed of the DC motors.  
- **DC Motors** – Drives the car forward, backward, left, and right.  
- **Chassis and Wheels** – Forms the structural body of the car.  
- **Power Supply** – Provides the required energy for the car's components.  
- **Mobile App** – Sends control signals via Bluetooth to operate the car.  

## Why It’s Useful  
- Demonstrates the **potential of Bluetooth technology** in wireless control applications.  
- Serves as a **foundation for robotics and automation projects**.  
- Encourages learning about **mobile app integration with hardware**.  
- Can be expanded for **IoT-based smart control systems**.  

## Future Enhancements  
- Add **voice control** using Google Assistant or Alexa.  
- Integrate **Wi-Fi connectivity** for cloud-based control.  
- Implement **obstacle detection** using ultrasonic sensors.  

## How to Use  
1. Assemble the **Bluetooth-controlled car** as per the circuit diagram.  
2. Upload the **provided Arduino code** to your **Arduino Uno**.  
3. Pair the **HC-05 Bluetooth module** with a **mobile phone** via a **Bluetooth terminal app**.  
4. Use the mobile app buttons to **control the car’s movement**.  
