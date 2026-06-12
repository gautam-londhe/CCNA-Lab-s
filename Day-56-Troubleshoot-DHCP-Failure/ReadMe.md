# Day 56 - Troubleshoot DHCP Failure

## Ticket

Users in VLAN 10 are unable to obtain IP addresses.

## Symptoms

- PC1 shows APIPA address (169.254.x.x)
- Users cannot access network resources
- DHCP service should be provided by R2

## Objective

Find the root cause and restore DHCP functionality.

## Rules

- Do not rebuild the topology.
- Do not delete configurations unless required.
- Use verification commands to identify the issue.
- Document the root cause and fix.

## Success Criteria

- PC1 receives a valid IP address.
- PC1 can ping its default gateway.
- DHCP bindings appear correctly.
