# Hardware-project
An Arduino-based assistive technology project that helps visually impaired users read text through a refreshable Braille display and smart vibration glove.
## Project Overview
This project is an Arduino-based assistive technology designed to help visually impaired users read text through tactile Braille output. The system converts voice input into Braille patterns using a refreshable Braille display and a smart vibration glove.

## Problem Statement
Traditional printed Braille books are bulky and expensive. Existing electronic Braille devices are also costly and not affordable for many students. There is a need for a low-cost, portable, and user-friendly Braille learning solution.

## Solution
This project provides a dual-mode assistive system:
- A refreshable Braille display using servo motors
- A smart glove using vibration motors  
Voice input is converted into text and then into Braille patterns in real time using Arduino and Bluetooth communication.

## Hardware Components Used
- Arduino UNO  
- Bluetooth Module (HC-05 / HC-06)  
- Servo Motors (6x)  
- Vibration Motors (6x)  
- Push Buttons  
- Battery (Li-ion)  
- Braille Cell / Smart Glove setup  

## Working Principle
1. User gives voice input through a mobile app or Google Assistant  
2. Voice is converted into text  
3. Text is sent to Arduino via Bluetooth  
4. Arduino converts text into Braille dot patterns  
5. Output is given through servo motors or vibration motors  
6. User reads the Braille pattern through touch  

## Features
- Low cost and portable  
- Wireless communication  
- Real-time voice to Braille conversion  
- Dual output modes (Braille display & smart glove)  
- Adjustable tactile feedback  

## Applications
- Braille education for visually impaired students  
- Daily communication assistance  
- Public information systems  
- Assistive learning tools  

## Future Enhancements
- Multi-cell Braille display  
- Support for Grade-2 Braille  
- OCR-based text input  
- IoT integration for notifications  

