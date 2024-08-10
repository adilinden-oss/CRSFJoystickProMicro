# CRSFJoystickProMicro

Fork of [robhaswell/CRSFJoystickProMicro](https://github.com/robhaswell/CRSFJoystickProMicro), which is based on[mikeneiderhauser/CRSFJoystick](https://github.com/mikeneiderhauser/CRSFJoystick). The main difference is the use of the ArduinoJoystick library which supports the AVR platform.

This builds a ExpressLRS to USB Joystick bridge.

## Note

If you build this project you MUST flash your receiver with `RCVR_UART_BAUD=250000`.

## Tested Hardware

- Radiomaster Boxer with internal ExpressLRS
- SpeedyBee Nano ELRS 2.4GHz Receiver
- Sparkfun Pro Micro 5V/16MHz
- Liftoff flight simulator
