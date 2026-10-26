# Pipeline SCADA Monitoring Dashboard
# Video Demo
## Project Overview

Simulated pipeline monitoring system developed using **Ignition Perspective**.

The dashboard provides an operator-facing interface for monitoring pipeline pressure, flow rate, pump status, valve status, and system health.

## Key Features

### Real-Time Process Monitoring
- Simulated pipeline pressure readings
- Simulated flow rate monitoring
- Flow gauge visualization
- Pump and valve status indicators
- System health status display

### Alarm Monitoring
- High-pressure alarm configured above 480
- Low-flow alarm configured below 120
- Alarm Status Table for viewing active alarms
- Alarm priority filtering

### Historical Data Trending
- Tag history recording using a SQLite-backed historian
- Historical pressure and flow visualization
- Trend chart for observing simulated process changes over time

### Simulated Process Data
- Pressure values simulated around 400–500
- Flow values simulated around 115–135
- Dynamic tag expressions used to generate changing process readings

## Technologies Used

- Inductive Automation Ignition
- Ignition Perspective
- Ignition Tag System
- Ignition Alarm System
- Tag Historian
- SQLite
- Expression-based process simulation

