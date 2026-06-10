# Day 36 - Standard ACL

## Objective

Block traffic from employee network using a Standard ACL.

## Topology

PC1 --- R1 --- R2 --- Server

## ACL

access-list 10 deny 192.168.10.0 0.0.0.255
access-list 10 permit any

## Verification

show access-lists
show ip interface g0/1

## Result

Successfully blocked source network using Standard ACL.
