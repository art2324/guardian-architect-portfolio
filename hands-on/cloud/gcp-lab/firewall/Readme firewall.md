# Firewall Configuration

## Purpose
Allow HTTP traffic to reach the virtual machine.

## Configuration Details
- Direction: Ingress
- Protocol: TCP
- Port: 80
- Source IP range: 0.0.0.0/0
- Target: VM with tag "http-server"

## Result
Firewall rule successfully applied and HTTP access enabled.