# Day 36 - Standard ACL

## Objective

Block one host using a Standard ACL.

## Topology

PC1----\
PC2----/---SW1-----R1-----R2



## ACL

Deny:
192.168.10.20

Permit:
All others

## Verification

show access-lists
show ip interface g0/0

## Result

Successfully blocked PC2 while allowing PC1.
