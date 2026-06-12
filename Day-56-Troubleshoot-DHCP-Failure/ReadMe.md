# Day 56 - Troubleshoot DHCP Failure

## Ticket ID

INC-DHCP-056

## User Complaint

Users connected to VLAN 10 cannot obtain IP addresses.

## Symptoms

- PC1 shows 169.254.x.x address
- Users cannot access network resources
- DHCP service should be provided by R2

## Expected Behavior

- PC1 should receive an IP address automatically
- PC1 should receive:
  - IP Address
  - Subnet Mask
  - Default Gateway
- PC1 should be able to ping its default gateway

## Rules

- Do not rebuild the topology
- Do not erase configurations
- Investigate before making changes
- Identify the root cause
- Fix the issue
- Verify the solution

## Success Criteria

- PC1 receives a valid DHCP address
- DHCP binding appears on R2
- PC1 can ping default gateway
- Ticket can be closed
