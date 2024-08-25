# Stepper_Simulink

This project provides Arduino based speed and direction control for Industrial Grade Stepper Drivers (such as R60, Dm5566, etc.) using Simulink.

## Getting Started

These instructions will guide you on how to run the project.

### Prerequisites

- Arduino board
- Industrial Grade Stepper Drivers (R60, Dm5566, etc.)

### Setup

1. Connect the direction pin to pin 2 and the pulse pin to digital pin 3 of your Arduino board. 
   (You can change these from the S function declaration to your desired pins)

### Running the Project

1. Open the project in Simulink.
2. Select your Arduino board type.
3. Open the "S-Function stepper" block. Make sure "Generate wrapper TLC" is selected under build. If it is, hit "Build".
4. Close the S function and return to the Simulink page.
5. Click on 'Build, Deploy & Start' in Simulink.

Enjoy controlling your stepper drivers!
