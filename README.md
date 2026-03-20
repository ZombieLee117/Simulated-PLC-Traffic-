# Simulated-PLC-Traffic-
Simulated OT/ICS lab generating and analyzing Modbus TCP PLC traffic using Wireshark

# PLC Traffic Monitoring Lab (Modbus TCP)

## Overview
This project simulates industrial control system (ICS) traffic using Modbus TCP. A simulated PLC (Modbus Slave) communicates with a client (QModMaster), and traffic is captured and analyzed using Wireshark.

## Tools Used
- Modbus Slave (PLC simulator)
- QModMaster (Modbus client)
- Wireshark (packet capture & analysis)

## Key Findings
- Observed Modbus TCP request/response cycles
- Identified Function Code 0x03 (Read Holding Registers)
- Analyzed Transaction IDs to correlate communication pairs
- Captured traffic over TCP port 1502

## Example Packet Analysis
- Unit ID: 255
- Function Code: 0x03
- Register Count: 5
- Data: Default values (0)

## Skills Demonstrated
- OT/ICS protocol analysis
- Network packet capture and filtering
- Modbus TCP communication understanding
