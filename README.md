# ITAI3377_L04_GROUP
Lab 04 – IIoT Sensor Network & Protocol Experimentation

Course: ITAI 3377 – AI at The Edge & IIoT Environments
Instructor: Patricia McManus
Student: Brandy Griffin

📌 Project Overview

This project simulates an Industrial Internet of Things (IIoT) sensor network using three communication protocols:

MQTT

CoAP

OPC UA

Each protocol generates simulated temperature and humidity data in real time.
The data is transmitted, received, and visualized using Python.

🛠 Technologies Used

Python 3.10

paho-mqtt

aiocoap

asyncua

pandas

matplotlib

Mosquitto MQTT Broker

📂 Project Structure
iiot_simulation/
│
├── mqtt_sensor_simulation.py
├── coap_sensor_simulation.py
├── opcua_sensor_simulation.py
├── coap_server.py
├── data_visualization.py
├── coap_visualization.py
├── coap_data.csv
├── visualizations/
│   ├── mqtt_visualization.png
│   ├── coap_visualization.png
│   └── opcua_output_running.png

🚀 How to Run the Project
1️⃣ Activate Virtual Environment

Windows:

venv\Scripts\activate

2️⃣ Start MQTT Broker
mosquitto

3️⃣ Run Sensor Simulations

MQTT:

python mqtt_sensor_simulation.py


CoAP:

python coap_server.py
python coap_sensor_simulation.py


OPC UA:

python opcua_sensor_simulation.py

4️⃣ Run Visualization
python data_visualization.py


or

python coap_visualization.py

📊 Results

The project successfully:

Generated real-time temperature and humidity values

Transmitted data using MQTT, CoAP, and OPC UA

Visualized sensor data in real time

Saved visualization proof in PNG format

🧠 Learning Outcomes

Through this lab, I learned:

Differences between MQTT, CoAP, and OPC UA

How to simulate real-time IIoT sensor networks

How to manage ports and troubleshoot server conflicts

How to build live data visualizations using matplotlib
