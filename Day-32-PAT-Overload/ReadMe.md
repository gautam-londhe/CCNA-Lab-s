# Day 32 - PAT Overload

## Objective

Configure PAT (NAT Overload) allowing multiple users to share a single public IP.

## Topology

PC1
PC2
PC3
 |
SW1
 |
R1
 |
ISP

## Public IP

209.165.200.225

## Verification

show ip nat translations
show ip nat statistics
show access-lists

## Result

Successfully configured PAT and verified multiple hosts sharing one public IP.
