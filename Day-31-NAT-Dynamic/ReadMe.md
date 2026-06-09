
# Day 31 - Dynamic NAT

## Objective

Configure Dynamic NAT using a public IP pool.

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

## NAT Pool

209.165.200.230
209.165.200.231

## Verification

show ip nat translations
show ip nat statistics
show access-lists
show ip route

## Result

Successfully configured Dynamic NAT and verified address translations from the NAT pool.
