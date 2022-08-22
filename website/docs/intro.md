---
sidebar_position: 1
---

# Introduction

ATP Things is the simple IOT platform/tools for managing/connectings things, device, persons, data...

The idea is to have entity (person, device, data) identified by unique identifier (uuid). By knowing that ID you can access all the data related to it. The data can be stored on premiss or in the cloud. The data master data is on the cloud, but everything should also work locally.

## Keywords

- record -> the set of data (measurements ...)
- data point -> single point in time (time series data) or single unit of data.
- time precision -> The precision for unix timestamps.
- time series -> Time series data, also referred to as time-stamped data, is a sequence of data points indexed in time order. Time-stamped is data collected at different points in time. These data points typically consist of successive measurements made from the same source over a time interval and are used to track change over time.

## Time dimension

- Realtime - short delays only applications with RTOS (real time operating system).
- Near RealTime - The application running with delays up to 1 hour.
- Analysis - The application that uses historical data.
