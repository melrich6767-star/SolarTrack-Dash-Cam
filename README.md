# SolarTrack Dash Cam

A prototype dash camera with solar charging, GPS location logging,
voice recording, and Bluetooth connectivity.

## Features

- Records video using a built-in camera.
- Records audio using a built-in microphone.
- Logs vehicle location using GPS.
- Supports Bluetooth Low Energy connectivity.
- Uses a solar panel to charge a rechargeable battery.
- Saves recordings and location logs to a microSD card.

## Components

- XIAO ESP32S3 Sense with camera, microphone, and Bluetooth
- L76K GPS module
- 5V 5W solar panel
- Solar charger with 5V boost
- 3.7V 4400mAh battery
- 32GB microSD card
- Jumper wires
- USB-A to USB-C cable
- DC power adapter
- Project enclosure
- Mounting bracket and screws

## How It Works

1. The solar panel supplies energy to the charging board.
2. The charging board charges the battery and powers the device.
3. The camera and microphone capture video and audio.
4. The GPS module provides location information.
5. Recordings and location logs are saved to the microSD card.
6. Custom firmware enables Bluetooth communication with a
   compatible phone app.

## Bill of Materials

See BOM.csv for purchase links, vendors, components, quantities,
USD prices, and purposes.

Estimated parts cost: US$129.59.

Shipping, tax, tools, and software development are excluded.
Some prices are estimates, and availability may change.

## Project Status

Planning stage. Assembly, firmware development, and testing
are required.

## Limitations

- Solar runtime depends on sunlight and power consumption.
- GPS provides location logging. Remote live tracking requires
  additional cellular hardware and a data plan.
- Simultaneous video, audio, GPS, and Bluetooth operation
  must be tested.
- This is a demonstration prototype, not an automotive-qualified
  dash camera.
- The selected battery is not qualified for hot parked-car use.
