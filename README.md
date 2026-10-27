# 9v-button-led-circuit
A breadboard hardware project featuring a push-button switch that turns an LED on and off, powered by a 9V battery and simulated in Tinkercad Circuits.

## Components Used

* Power Source: 9V Battery
* LED: Standard Red LED (Requires 2V - 3V)
* Resistor: 800 Ohm Current-Limiting Resistor
* Switch: Push-button Switch
* Prototyping: Breadboard and Jumper Wires

---

## Circuit Calculations and Logic

* Voltage Protection: A 9V battery provides too much voltage for an LED, which only requires around 2V to 3V. Connecting the LED directly to the 9V battery will burn it out.
* Resistor Choice: An 800 Ohm resistor is added in series to absorb the excess voltage and safely limit the electrical current flowing to the LED.

---

## Wiring and Connections

1. Power Input: Connect the 9V battery positive wire (red) to one side of the push-button switch.
2. Switch to Resistor: Connect the other side of the push-button switch to the 800 Ohm resistor.
3. Resistor to LED: Connect the open end of the resistor to the LED Anode (the positive, longer leg).
4. Ground Loop: Connect the LED Cathode (the negative, shorter leg) back to the 9V battery negative wire (black) to complete the circuit.
5. Breadboard Rows: Ensure components connecting together share the same row of terminal pins on the breadboard.

---

## Simulation Link

* Live Tinkercad Simulation: https://www.tinkercad.com/things/8ik0d6wQDvm

---

## Repository Structure

├── README.md         # Project documentation and engineering notes
└── schematic/        # Circuit diagrams and screenshots
