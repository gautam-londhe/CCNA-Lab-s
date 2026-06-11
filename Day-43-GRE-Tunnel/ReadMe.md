# Day 43 - PPP Configuration

## Objective

Configure PPP between two routers.

## Topology

R1 -------- R2

## Network

10.10.10.0/30

## Verification

show interfaces serial 0/0/0
show ip interface brief
ping 10.10.10.2

## Result

Successfully established a PPP WAN link.
