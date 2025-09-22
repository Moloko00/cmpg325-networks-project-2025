# Bus Topology

## Purpose
Demonstrate a simple bus topology in Packet Tracer using a hub.

## Devices
- 3 x PCs (PC0, PC1, PC2)
- 1 x Hub (Hub-PT)

## Device IPs
- PC0: 192.168.1.1 / 255.255.255.0
- PC1: 192.168.1.2 / 255.255.255.0
- PC2: 192.168.1.3 / 255.255.255.0

## How to verify
1. Open `bus_topology.pkt` in Packet Tracer.
2. On PC0: Desktop → Command Prompt → `ping 192.168.1.2` and `ping 192.168.1.3`. Expect replies.
3. Repeat pings from PC1 and PC2 to confirm full connectivity.

## Files
- `bus_topology.pkt`
- Screenshot: `../../screenshots/bus_topology.png`
