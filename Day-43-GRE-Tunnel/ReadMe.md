# Day 43 - GRE Tunnel

## Objective

Create a GRE tunnel between Branch and HQ routers.

## Topology

R1 ---- R2 ---- R3

## Tunnel Network

172.16.1.0/30

## Verification

show interfaces tunnel0
show ip route
show ip interface brief

## Result

Successfully created a GRE tunnel and routed traffic through it.
