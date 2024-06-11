# LoRa-Enabled-NodeMCU-Nodes-for-Efficient-Agricultural-Monitoring-in-IoT
Agricultural monitoring is essential for optimizing
crop production and ensuring food security. However,
conventional methods of monitoring are often costly, laborintensive, and unreliable. In this paper, we propose a novel
agricultural monitoring system that uses a network of low-cost,
low-power, and long-range devices to collect and transmit data on
various soil and environmental parameters. The system consists of
a main central unit based on Raspberry Pi, and several nodes
distributed across the field, each equipped with an ESP32
microcontroller and sensors for measuring soil moisture, water
level, temperature, and humidity. The nodes communicate with
the central unit using LoRa, a wireless technology that offers longrange, low-bandwidth, and low-power communication. We
compare the performance of LoRa with other wireless
technologies such as Wi-Fi and ZigBee and show that LoRa has
several advantages in terms of range, power consumption,
scalability, and robustness. The central unit processes the data and
displays it on a web interface, which allows the user to monitor the
field conditions and control the irrigation system remotely. We
evaluate the feasibility and effectiveness of our system through
simulations and experiments, and demonstrate that it can provide
accurate, timely, and reliable information for
agricultural management.

Component Required:
1. Raspberry Pi 3 Model B
2. ESP32
3. LoRa sx1276
4. Soil moisture sensor
5. DHT11
6. Rainfall sensor
7. Servo Motor

![image](https://github.com/ahzamafaq/LoRa-Enabled-NodeMCU-Nodes-for-Efficient-Agricultural-Monitoring-in-IoT/assets/171343226/d9cf0bf9-caf3-41a7-9e62-db231e713f22)

Result:
Upon the successful implementation of our system, we
observed the transmission of data to the ThingSpeak server,
with a corresponding image displayed in Fig. 1. The outcomes
pertaining to LoRa technology were particularly noteworthy,
as the Received Signal Strength Indication (RSSI) values were
meticulously recorded for each transmission. Notably, the
RSSI values exhibited a quadratic decline with increasing
distance, a phenomenon indicative of signal attenuation over
distance.
The RSSI values provided in decibels (dB) serve as
crucial metrics, reflecting the signal strength of individual data
transfers. This parameter is directly associated with the quality
of data transmission and the spatial proximity of the nodes to
the central server. The observed trends in RSSI values not only
affirm the efficacy of the LoRa technology but also underscore
its potential in enabling robust and efficient communication
across varying distances within the agricultural monitoring
network.

![image](https://github.com/ahzamafaq/LoRa-Enabled-NodeMCU-Nodes-for-Efficient-Agricultural-Monitoring-in-IoT/assets/171343226/e9179256-d9bd-4624-8b64-d6496116df09)


