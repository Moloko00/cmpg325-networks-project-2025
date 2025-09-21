# Basic connectivity test

## Purpose
Verify Packet Tracer installation and that a switch connects two PCs correctly.

## Topology
2 PCs connected to a Cisco 2960 switch.

## Device IPs
- PC0: 192.168.1.10/24
- PC1: 192.168.1.11/24

## How to verify
1. Open `basic_test.pkt` in Packet Tracer.
2. On PC0: Desktop → Command Prompt → `ping 192.168.1.11` → expect replies.
3. On PC1: Desktop → Command Prompt → `ping 192.168.1.10` → expect replies.

## Files
- `basic_test.pkt`
- Screenshot: `../../screenshots/basic_test.png`
