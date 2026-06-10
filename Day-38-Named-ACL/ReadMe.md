# Day 38 - Named ACL

## Objective

Configure a Named Extended ACL to block ICMP traffic from PC2.

## Topology

PC1
PC2
 |
SW1
 |
R1
 |
R2

## ACL Name

BLOCK_PC2_PING

## Verification

show access-lists
show ip interface g0/0

## Result

Successfully configured and verified a Named ACL.
