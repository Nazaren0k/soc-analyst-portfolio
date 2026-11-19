# Firewall Traffic Simulator

Python simulation that generates connection attempts, checks them against IP/port rules, logs allow/block decisions, and summarizes traffic. Work in progress.

## Features
- Random private source IPs and common destination ports
- Blocks only when source IP is in `firewall_rules` **and** port is in `blocked_port_list`; everything else is allowed
- Logs decisions to `FireWall.log` (sample: [sample_firewall.log](./sample_firewall.log))
- Allowed/blocked counts, top talkers, blocked IP/port pairs
- Alert when a blocked IP hits an activity threshold

## Run
```bash
python firewall_checker.py
```
Source: [firewall_checker.py](./firewall_checker.py)

## Planned
Configurable rules, structured logging, input validation, tests.

Educational only: does not inspect live traffic or change any real firewall.

[← Back to all projects](../)
