Project Deaf:

A smart glove that translates sign language into speech.

What It Does?

Project Deaf is a wearable system that helps deaf and hard-of-hearing individuals communicate more easily.

The glove:

Detects finger bends using flex sensors
Tracks hand movement using a gyroscope & accelerometer
Recognizes predefined sign language gestures
Plays the corresponding word through a speaker

I also built:

A small device that converts speech to text (Raspberry Pi + microphone + OLED display)
A vibration band that converts sound frequencies into haptic feedback so users can feel sound

How It Works?

Arduino collects finger and motion data
Gesture data is validated to avoid false triggers
Recognized signs trigger audio files stored on an SD card
Wireless communication connects both gloves
FFT is used in the vibration module to split sound into frequency bands

Tech Used:

Arduino Nano and Pro Mini
Raspberry Pi Zero
MPU6050
NRF24L01
FFT signal processing
C++ (embedded)
Python (speech recognition)

Why I Built It?

Hearing devices are expensive and not accessible to everyone.
This project was designed to be:

Affordable
Portable
Practical
Built with off-the-shelf components

Total hardware cost: ~$30–$50.

Built as a hardware + embedded systems project focused on accessibility and real-world impact.
