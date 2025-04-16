# Edge Device Management Platform

A cloud-based platform to manage, monitor, and control edge devices.

## Modules
- FastAPI backend
- MongoDB for storage
- MQTT (Mosquitto) for communication
- Device Simulator
- Simple HTML frontend

## How to Run

```bash
docker-compose up --build


# Verify MQTT Broker is Listening
#docker exec -it mosquitto mosquitto_sub -h 127.0.0.1 -p 1884 -t sensor/data
#docker exec -it mosquitto mosquitto_pub -h 127.0.0.1 -p 1884 -t sensor/data -m "Hello MQTT"
