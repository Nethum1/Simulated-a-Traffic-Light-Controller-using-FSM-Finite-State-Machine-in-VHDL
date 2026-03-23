# Simulated-a-Traffic-Light-Controller-using-FSM-Finite-State-Machine-in-VHDL
An FPGA-based traffic light controller using VHDL manages a highway–farm road intersection. A sensor detects vehicles on the farm road. Normally, the highway stays GREEN and the farm road RED. When a vehicle is detected, the highway turns YELLOW for 3 seconds, then RED for 10 seconds, allowing safe crossing.

A VHDL-based traffic light controller is designed for an FPGA to manage an intersection between a highway and a farm road. The system incorporates a sensor on the farm road to detect the presence of vehicles. Under normal conditions, the highway signal remains GREEN while the farm road stays RED. When a vehicle is detected on the farm road, the controller initiates a sequence where the highway signal changes to YELLOW for 3 seconds, followed by RED for 10 seconds, allowing safe crossing. After this interval, the system returns to its default state, ensuring efficient traffic flow and safety.

🧠 Implemented a state-based control system with states: RED, GREEN, and YELLOW

⏱️ Used a counter to manage signal duration (10 clock cycles for Red/Green, 5 for Yellow)

🛠️ Written entirely in VHDL and tested using Vivado simulation

📶 Outputs are simulated as LEDs for red, green, and yellow lights

This project demonstrates fundamental concepts of digital design, FSM implementation, and HDL simulation—a great foundation for more complex FPGA-based traffic systems or IoT integrations.

