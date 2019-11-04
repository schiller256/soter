# Soter (SO+ER)
Real Time Implementation of Gunshot Detection IoT System.

SO+ER demonstrates the power of open-source hardware (OSH) to enable the first non-commercial, community driven, kinetic and gunshot detection network. The detector architecture is free and based on open source hardware.

Creating a better tomorrow with today's technology.

### Reference Architecture
This Do-It-Yourself (DIY) project contains an array of microphones, sensors, and an internet enabled single-board computer. The collector listens for and records sharp sounds with high levels of energy. Recordings are analyzed in the cloud using machine learning to categorize the characteristics. SO+ER is configurable to notify you when a detection is received.

The SO+ER name derives from the Greek personification or daimon of safety, preservation and deliverance from harm.

### Getting Started:
1) Read the License (License.txt)
2) Manufacture the Printed Circuit Board (PCB)
3) Manufacture the enclosure
4) Purchase the sensor breakouts
5) Assemble the PCB
6) Flash the collector
7) Finalize assembly

NOTE: You will need Git Large File Storage (LFS) to download the firmware. More information about [git lfs is available here](https://git-lfs.github.com).

The collector integrates the following OSH commercial components:

Sensor Components | Quantity
----------|--------
BeagleBone Black Wireless | 1
Adafruit MEMS Microphone breakout | 4
Adafruit Temperature breakout | 1
Sparkfun 9DOF breakout | 1
Sparkfun GPS module | 1

Your estimated minimum cost to assemble a single collector is $200 USD.

In the repository there are three (3) directories that contain the engineering artifacts and Bill of Materials (BOMs) required to manufacture and assemble the collector.

We have used the following PCB manufactures and services:
- Seeed Studio Fusion PCB
- OSH Park

We have used the following additive (3D Printing) manufactures and services:
- Shapeways
- 3D Hubs

We recommend using Selective Laser Sintering (SLS) technology when manufacturing the enclosure due to the exacting measures required to mount the electronics and couple the enclosure bodies.

### Operational Notes
* SO+ER transmits, processes, and stores data on cloud servers in the United States of America.
* Use a firewall to deny all collector network traffic on port 22 (SSH).
