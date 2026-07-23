# Firewall

This project secures web-01 by installing and configuring UFW (Uncomplicated Firewall) to block all incoming traffic by default, only allowing specific ports required for the server to function: SSH, HTTP, and HTTPS.

## Tasks

- **0-block_all_incoming_traffic_but** — UFW commands that install the firewall, set the default policy to deny all incoming traffic, allow outgoing traffic, and explicitly permit TCP ports 22 (SSH), 80 (HTTP), and 443 (HTTPS).

## Key Concepts

- **Firewall** — A hardware or software security system that filters incoming and outgoing network traffic based on a defined set of rules.
- **Network vs Host-based Firewall** — A network firewall protects an entire network at its perimeter, while a host-based firewall runs on and protects an individual device.

## Requirements

- All scripts start with `#!/usr/bin/env bash`
- Each script includes a comment describing its purpose
- Scripts are executable
