# Practical Work: MQTT Broker Deployment

## Objective
Deploy and configure an MQTT broker and demonstrate Publish/Subscribe functionality.

## Technologies Used
- Eclipse Mosquitto
- Docker
- MQTT protocol
- Postman (MQTT client)

## How to Run

cd broker
docker compose up -d

Check container:
docker ps

## MQTT Concepts

Topic – logical channel (example: test/topic)

Publish – sending a message to a topic

Subscribe – receiving messages from a topic

QoS Levels:
0 – At most once
1 – At least once
2 – Exactly once

## Project Structure

```
pz-MQTT
├── broker/
│   ├── docker-compose.yml
│   └── mosquitto.conf
├── pz-MQTT/
│   └── broker/
│       └── mosquitto.conf/
└── screenshots/
```
