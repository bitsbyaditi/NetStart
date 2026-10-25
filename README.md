# NetStart — Network Design and Configuration

## Overview
NetStart is a beginner networking project built using Cisco Packet Tracer. It demonstrates two separate local area networks (LANs) connected through a router.

## Network Topology
- 4 PCs
- 2 Cisco 2960 switches
- 1 Cisco 2911 router
- 2 IP networks connected through a router

## IP Addressing

| Device | IP Address | Subnet Mask | Default Gateway |
|---|---|---|---|
| PC0 | 192.168.1.10 | 255.255.255.0 | 192.168.1.1 |
| PC1 | 192.168.1.11 | 255.255.255.0 | 192.168.1.1 |
| PC2 | 192.168.2.10 | 255.255.255.0 | 192.168.2.1 |
| PC3 | 192.168.2.11 | 255.255.255.0 | 192.168.2.1 |
| Router G0/0 | 192.168.1.1 | 255.255.255.0 | Not applicable |
| Router G0/1 | 192.168.2.1 | 255.255.255.0 | Not applicable |

## What I Practiced
- Connecting PCs, switches, and a router
- Configuring IPv4 addresses and subnet masks
- Setting default gateways
- Connecting two different IP networks through a router
- Testing connectivity using the `ping` command
- Checking directly connected routes on the router

## Connectivity Testing
Successful ping tests were completed between:
- PC0 and PC2
- PC1 and PC3
- PC0 and its default gateway
- PC3 and its default gateway

All listed tests completed with 0% packet loss during testing.

## Project File
Open `netstart_.pkt` using Cisco Packet Tracer to view the network topology.

## Tools
- Cisco Packet Tracer
