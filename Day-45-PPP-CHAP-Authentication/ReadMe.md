# Day 45 - PPP CHAP Authentication

## Objective

Secure a PPP link using CHAP authentication.

## Topology

R1 -------- R2

## Network

10.10.10.0/30

## Authentication

CHAP

Password: Cisco123

## Verification

show interfaces serial 0/0/0
show ip interface brief
ping 10.10.10.2

## Result

Successfully authenticated PPP peers using CHAP.
