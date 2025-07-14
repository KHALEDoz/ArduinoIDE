# LED Connection with Arduino Uno and Resistor on Breadboard
# LED_Blink.ino

void setup() {

  pinMode(13, OUTPUT);
  
  }

void loop() {

  digitalWrite(13, HIGH);
  
  delay(1000);
  
  digitalWrite(13, LOW);  
  
  delay(1000);      
  
}

#  LED Blink using Arduino

This is a simple project that demonstrates how to blink an LED using Arduino Uno, a resistor, and a breadboard.

## Circuit Diagram
<img width="1536" height="1024" alt="LED Circle with Arduino" src="https://github.com/user-attachments/assets/81d12f04-4117-4e91-87dc-d1a9e1391ffe" />

## Components Used
- Arduino Uno
- Breadboard
- LED (Red)
- 220Ω Resistor
- Jumper Wires

##  Circuit Instructions
1. Connect the **anode (long leg)** of the LED to **digital pin 13** through a **220Ω resistor**.
2. Connect the **cathode (short leg)** of the LED to **GND**.
3. Upload the code using Arduino IDE.

## Code Behavior
- LED turns ON for 1 second.
- Then OFF for 1 second.
- Repeats this loop forever.
