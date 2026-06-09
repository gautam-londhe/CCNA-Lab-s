
# Day 30 - Static NAT

## Objective

Configure Static NAT to publish an internal server using a public IP address.

## Topology

PC1 -> SW1 -> R1 -> ISP

Server connected to R1 LAN.

## NAT Mapping

192.168.10.100 -> 209.165.200.227

## Verification

show ip nat translations
show ip nat statistics
show ip route
show ip interface brief

## Result

Successfully configured Static NAT and verified translation table.
