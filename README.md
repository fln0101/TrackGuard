# TrackGuard
### Smart Product Journey Monitoring System

**TrackGuard** is an engineering prototype designed to monitor environmental conditions and motion during the transportation of temperature-sensitive products, especially food products.

The project combines environmental sensing, motion monitoring, embedded systems, and a planned local Wi-Fi dashboard.

## Project Objectives

- Monitor ambient temperature and humidity.
- Measure atmospheric pressure.
- Collect three-axis acceleration data.
- Develop impact-event detection and logging.
- Display sensor readings through the Serial Monitor and a local Wi-Fi dashboard.
- Summarize environmental conditions and recorded motion events.

## Hardware

| Component | Purpose | Status |
|---|---|---|
| Seeed XIAO ESP32-C6 | Main microcontroller | Used in testing |
| BME280 | Temperature, humidity, and pressure | Working in tests |
| Motion sensor module | Motion and acceleration monitoring | Identification and communication under investigation |
| Battery | Portable power | Integration pending |
| 3D-printed enclosure | Electronics protection | In development |

## Work Completed

- Connected the BME280 to the XIAO ESP32-C6 using I2C.
- Successfully obtained temperature, humidity, and pressure readings.
- Confirmed the BME280 I2C address as `0x76`.
- Developed and tested initial Arduino sensor-reading code.
- Started motion-sensor integration and I2C diagnostics.
- Began planning the enclosure dimensions and layout.

## Example Environmental Readings

| Measurement | Example |
|---|---:|
| Temperature | 29.39 °C |
| Relative humidity | 40.27% |
| Atmospheric pressure | 940.88 hPa |

These values are examples from development testing, not validated performance specifications.

## Current Challenges

- Confirming reliable motion-sensor communication and measurements.
- Developing a validated impact-detection algorithm.
- Implementing a local Wi-Fi dashboard.
- Completing enclosure and battery integration.

## Planned Features

- Configurable environmental thresholds for different food products.
- Detection and logging of potential impact events.
- A local web dashboard accessible from a phone or computer.
- Journey summaries showing environmental excursions and motion events.
- Testing and validation under controlled conditions.

## Tools

- Arduino IDE
- C++ and Arduino framework
- Seeed XIAO ESP32-C6
- I2C communication
- Onshape
- Git and GitHub

## Limitations

TrackGuard is a prototype for transportation-condition monitoring. An impact event does not necessarily mean that a product was damaged, and environmental readings alone cannot establish food safety.

## Project Status

**In Progress — Sensor Integration and Diagnostics**

Environmental sensing has been demonstrated. Motion-sensor validation, impact detection, Wi-Fi dashboard development, and final enclosure integration remain in progress.
