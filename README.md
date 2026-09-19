Project: SCALABLE POWER DRIVER
Arduino Nano 3-LED Blink Controller
Overview:
A simple embedded systems project using an Arduino Nano to control a set of three LEDs that blink in unison. The system also provides real-time status updates over the serial connection, making it easy to monitor the LED state during operation.

How It Works:

The Arduino Nano drives three LEDs (wired in parallel or in series, depending on the circuit) from a single digital output pin (D9).

Every second, all three LEDs toggle between ON and OFF states simultaneously, creating a synchronized blinking pattern.

Each state change is logged to the Serial Monitor at 9600 baud, printing "ALL LEDs ON" or "ALL LEDs OFF" so the user can visually confirm the timing and operation of the circuit.

On startup, the board sends a "Nano 3-LED Controller Ready!" message to indicate the system is initialized and running.

Key Features:

Synchronized control of 3 LEDs from one pin

1-second ON / 1-second OFF blink cycle

Serial feedback for debugging and monitoring

Minimal, beginner-friendly code

Components:

Arduino Nano

3 × LEDs (any color)

3 × current-limiting resistors (~220Ω)

Breadboard and jumper wires

Applications:

Learning basic digital output and timing with delay()

Prototyping indicator lights for a larger project

Foundation for expanding into multi-pattern LED animations (e.g., using separate pins or millis() for non-blocking control)

Components Needed:
• Arduino Nano
• NPN Transistor (2N2222)
• 1kΩ resistor
• 3× 330Ω resistors
• 3× LEDs
• Breadboard & wires
Description:
Foundation for massive LED arrays. This 3-LED prototype demonstrates a system scalable from 3 to 30+ LEDs using the same single Arduino pin.
Core Principle:
"Micro-controller safety meets massive expansion potential."
Key Features:
• Ready to scale to 20+ LEDs instantly
• One pin controls unlimited growth
• Complete microcontroller protection

