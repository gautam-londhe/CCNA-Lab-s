# Day 37 - Extended ACL

## Objective

Block ICMP traffic from PC2 while allowing PC1.

## Topology

PC1
PC2
 |
SW1
 |
R1
 |
R2

## ACL

deny icmp host 192.168.10.20 host 172.16.1.1

permit ip any any

## Verification

show access-lists
show ip interface g0/0

## Result

Successfully filtered ICMP traffic using an Extended ACL.
