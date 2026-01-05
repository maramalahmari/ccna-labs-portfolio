# Boson CCNA Challenge Lab 1  
## IPv4 Subnetting & IPv6 SLAAC (EUI-64)

## Overview
In this lab, I configured a new network from scratch and verified full IPv4 and IPv6 connectivity.
The lab focuses on IP planning, subnetting, device configuration, and verification.

This lab is based on Boson NetSim Challenge Lab 1 and was implemented in Cisco Packet Tracer
for portfolio demonstration purposes.

## Objectives
- Configure hostnames on routers and switches
- Design and apply IPv4 subnetting using /30, /28, and /32 networks
- Assign IPv4 addresses to routers, switches, and hosts
- Configure IPv6 addressing using SLAAC and EUI-64
- Verify IPv4 and IPv6 connectivity
- Save configurations on all devices

## Topology Summary
- Two routers connected via a point-to-point WAN link
- Multiple switches and hosts connected on a single LAN segment
- IPv4 used for management and host connectivity
- IPv6 used with SLAAC for automatic address assignment

## Verification
- Successful IPv4 pings from Host1 to all LAN devices
- IPv6 global unicast and link-local addresses verified
- Interfaces confirmed as up/up on all devices

## Files in This Lab
- `ip-plan.md` → IPv4 and IPv6 addressing plan
- `configs/` → Device running-config outputs
- `verification/` → Ping results and verification commands
- `screenshots/` → Topology and command output screenshots
