RAIN-SENSING-MOTARISED-UMBERLLA-BAG
🌧️ Rain Sensing Motorized Umbrella Bag

📌 Project Overview

The *Rain Sensing Motorized Umbrella Bag* is an innovative automation project developed using Arduino to offer a hands-free solution for protecting individuals from rain. It integrates a rain sensor to detect precipitation and triggers a motorized mechanism to open or close an umbrella placed inside a custom-designed bag. This project serves as an excellent demonstration of how embedded systems and sensors can enhance comfort and reduce manual effort in daily life.

This device is especially useful for commuters, cyclists, and pedestrians who need quick protection from sudden rain without the hassle of manually opening an umbrella. Once the system detects rainfall, it activates a gear motor using an L298N driver to open the umbrella. When the rain stops, it retracts it automatically, providing a seamless and user-friendly experience.



⚙️ Working Principle

The operation of this system is simple yet effective. A rain sensor module monitors for the presence of water. Upon detecting rain, it sends an analog signal to the Arduino UNO microcontroller. The Arduino interprets the signal and triggers the motor driver (L298N), which in turn powers the DC gear motor responsible for unfolding the umbrella.

As soon as the sensor detects that the rain has stopped, the system reverses the motor direction, causing the umbrella to close. The use of conditional logic ensures that the motor does not run unnecessarily, saving power and increasing efficiency.

This smart approach eliminates the need for manual control while offering flexibility for future upgrades such as Bluetooth control, solar-powered operation, or mobile app integration.



🧾 Components Used

| Component             | Description                              |
|----------------------|------------------------------------------|
| Arduino UNO          | The main microcontroller for logic       |
| Rain Sensor Module   | Detects presence of rain (analog sensor) |
| L298N Motor Driver   | Controls direction and speed of motor    |
| DC Gear Motor (12V)  | Responsible for umbrella actuation       |
| Battery (4.5V)       | Provides power to the system             |
| Connecting Wires     | Used for all internal connections        |
| Custom Umbrella Bag  | Housing for the entire mechanism         |



🧠 Key Features

- **Automatic Detection:** Operates automatically during rain without human input.
- **Motorized Operation:** Effortless umbrella opening/closing using a gear motor.
- **Low Voltage System:** Entire system runs on a safe 4.5V power supply.
- **Modular Build:** Easy to repair and customize based on user needs.
- **Future-Ready:** Designed with space and logic for Bluetooth upgrades.



📐 Block & Circuit Diagram

- **Block Diagram:** Explains the signal flow from rain detection to motor control.
- **Circuit Diagram:** Includes full wiring connections between Arduino, motor driver, and sensor.

> You can find the circuit diagram in the `CIRCUIT DIAGRAM PNG` file of the repository.



💻 Code Functionality (Summary)

The Arduino sketch handles the sensor input and controls the motor driver output. It uses basic `if-else` statements to:
- Check if rain is detected using analog input.
- Trigger the appropriate motor direction using digital pins.
- Stop the motor when no rain is detected.

You can find the full code inside the `CODE` file in this repository.


