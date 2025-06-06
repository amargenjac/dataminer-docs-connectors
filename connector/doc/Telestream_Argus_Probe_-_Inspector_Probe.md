---
uid: Connector_help_Telestream_Argus_Probe_-_Inspector_Probe
---

# Telestream Argus Probe - Inspector Probe

The Inspector probe will keep track of a large number of program streams for real-time linear and/or ABR preparation and delivery. Because these streams must be encoded or transcoded, and checked for regulatory compliance before being sent downstream to viewers, it is of high importance to monitor the status of these programs and streams.

This connector is automatically generated by the connector **Telestream Argus Probe**.

## Configuration

This connector is used by DVEs that are **automatically created** by the parent element. No user input is required.

## Usage - Range 1.0.0.x

### Probe

Generic probe information is available such as **IP** and **MAC Address**, **Type**, **Location**, **Status**, and **Device Status**.

### Monitoring Points

The **Monitoring Points Table** lists all monitoring points filtered per probe. It gives an overview of the number of **Active**, **Good**, **Outage**, **Warning**, and **History Flows** and **Programs**.

### Flows

All flows linked to the probe are listed in the **Flows Table**. It shows the status of each flow. The **display key** is a combination of the Probe Name, Monitoring Point Alias, and Flow Name.

### Programs

All programs linked to the probe are listed in the **Programs Table**. It shows the status of each program and the number of **Current Alarms** and **History Alarms**. The **display key** is a combination of the Probe Name, Monitoring Point Alias, Flow Name, and Program Name.
