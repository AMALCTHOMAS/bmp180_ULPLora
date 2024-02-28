# ULPLoRa with BMP180 Integration

This repository contains code libraries and documentation for integrating the ULPLoRa board with the BMP180 sensor. The ULPLoRa board, a combination of an Arduino Pro Mini with an RFM95W LoRa module, provides a versatile platform for wireless communication, while the BMP180 sensor offers precise atmospheric pressure measurements.

## Features

- **ULPLoRa Board:** Utilizes the MCCI LoRaWAN LMIC library for LoRaWAN communication.
- **BMP180 Sensor:** Interfaced with the Adafruit BMP085 library for sensor data acquisition.
- **ChirpStack Integration:** Enables seamless connectivity with the ChirpStack server for LoRaWAN network management.
- **InfluxDB and Grafana Integration:** Facilitates data storage in InfluxDB and visualization in Grafana for effective monitoring and analysis.

## Repository Structure

- **/libraries:** Contains code libraries for the ULPLoRa board and BMP180 sensor.
- **/documentation:** Includes detailed documentation on hardware setup, software configuration, and integration with ChirpStack, InfluxDB, and Grafana.
- ***/program:** Contains the Arduino program for Integrating ULPLoRa Board with BMP180 Sensor for Pressure Monitoring and Visualization


## Getting Started

To get started with the ULPLoRa with BMP180 integration, follow these steps:

1. Clone this repository to your local machine.
2. Refer to the documentation in the `/documentation` folder for detailed setup instructions.
3. Install the necessary code libraries for the ULPLoRa board and BMP180 sensor.
4. Follow the provided examples to start collecting data and transmitting it wirelessly.
5. Integrate with ChirpStack, InfluxDB, and Grafana for advanced monitoring and visualization capabilities.
