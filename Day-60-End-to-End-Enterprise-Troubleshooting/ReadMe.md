# Day 60 - End-to-End Enterprise Troubleshooting

## Objective

Troubleshoot and verify an enterprise network consisting of:

- VLANs
- Trunking
- OSPF
- DHCP
- NAT
- ACLs

## Topology

PC1 --- SW1 --- R1 --- R2

## Tasks

1. Verify VLAN configuration
2. Verify trunk operation
3. Verify DHCP assignment
4. Verify OSPF adjacency
5. Verify NAT translations
6. Verify ACL functionality
7. Restore end-to-end connectivity

## Verification Commands

show vlan brief
show interfaces trunk
show ip ospf neighbor
show ip dhcp binding
show ip nat translations
show access-lists

## Result

Successfully restored enterprise connectivity.
