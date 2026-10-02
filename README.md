# Laundry Assistant Voice Control

Build a smart home prototype that uses light sensor, door sensor, RGB LED to accept local voice commands. Include setup instructions, a circuit diagram, tested firmware, and sample output.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 73 |
| Category | Smart Home |
| Platform | Arduino Nano 33 IoT |
| Difficulty | Intermediate |
| Estimated build time | 24 hours |
| Connectivity | BLE |
| Core components | light sensor, door sensor, RGB LED |
| Control mode | closed loop control |

## Repository layout

- `firmware/laundry-assistant-voice-control/laundry-assistant-voice-control.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/laundry-assistant-voice-control/laundry-assistant-voice-control.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **Arduino Nano 33 IoT**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Voice Control demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
