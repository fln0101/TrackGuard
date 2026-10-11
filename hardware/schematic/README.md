# Electrical Schematic

This folder contains the electrical schematic documentation for the TrackGuard project.

## Design Tool

- Software: EasyEDA

## Purpose

The schematic documents the electrical connections between the microcontroller, environmental sensor, and motion sensor.

## Main Hardware

- Seeed XIAO ESP32-C6
- BME280 environmental sensor
- Motion sensor module (identification and communication under investigation)

## Verification Status

The BME280 has responded at I2C address `0x76` during testing.

The motion sensor communication has not yet been verified with the current test setup.

The schematic must be checked against the actual hardware wiring before the design is considered finalized.
