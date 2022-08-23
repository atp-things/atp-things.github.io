---
sidebar_position: 2
---

# Databases

## Document database

Preferred database - MongoDB

Document database is preferred option for storing the data. It is used for storing the dataEntity, dataSet, dataRecord, personRegistry, deviceRegistry, propertyRegistry

- dataEntity - It has a pointer to the database where data is stored (timeseries, dataSet, dataRecord)
- personRegistry - access control, device ownership, dataEntity ownership
- deviceRegistry - dataEntity pointers

## Timeseries

Preferred database - MongoDB Timeseries (optional InfluxDB)

The timeseries database stores the data. The data is linked to dataEntity with uuid stored as metadata.

Timeseries values:

- timestamp
- uuid
- value_X (X represents value dimension)

## SQL

Preferred - MySQl (optional MariaDB, PosgreSQL)
The SQL database is used to store timeseries data, due to Time series databases do not have an option for updating historical data.

Columns:

- timestamp
- uuid
- dimension
- value
