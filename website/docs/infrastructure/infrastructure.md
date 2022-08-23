---
sidebar_position: 1
---

# Infrastructure

## Identities

- dataEntity - The elementary data object (metadata and reference to dataSet, dataRecord, dataTimeseries).
- dataSet - Set of multiple dataEntities
- dataRecord - dataSet ()
- dataTimeseries -
- personRegistry - The registry of persons (users with permissions and ownership)
- deviceRegistry
- deviceRegistryConnected
- property (house, apartment)

### Services

- REST API (GET, POST)
- MQTT server (broker)
- Databases (MongoDB (noSQL and timeseries),InfluxDB, MariaDB, MySQL, PostgreSQL) local and in cloud. And Python and JavaScript clients.
- Redis inmemory database and message queue.
- Dashboard (manage entities, visualize data, )
- ModbusTCP client/server
- ModbusRTU client/server
- Bluetooth beacon receiver
- Picoscope acquisition
- Device monitor (computer, phone)

### Programming Languages

- Python ([package](https://github.com/atp-things/pkg-python-util))
- JavaScript (npm package)
- C/C++ (later)

### Connectivity

- Ethernet
- Wi-Fi
- Bluetooth
- Zigbee
- LoRa

### Communication protocols

- REST API
- Web Socket
- MQTT
- ModbusTCP
- ModbusRTU
- Bluetooth
- Ethernet/IP
- OPC UA
- Zigbee
- LoRa
