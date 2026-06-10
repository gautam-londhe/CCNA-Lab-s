# Day 34 - Syslog Configuration

## Objective

Configure centralized Syslog logging between a router and Syslog server.

## Topology

Syslog Server
     |
    SW1
     |
     R1

## Syslog Server

192.168.10.100

## Verification

show logging
show run | include logging
show clock

## Result

Successfully configured centralized Syslog logging and verified log generation.
