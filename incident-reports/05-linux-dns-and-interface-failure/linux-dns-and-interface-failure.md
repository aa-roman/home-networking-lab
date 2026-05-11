# Linux DNS and Interface Failure

## Incident
Ubuntu VM experienced connectivity and DNS resolution failures.

## Symptoms
- Network connectivity loss
- DNS name resolution failure

## Troubleshooting Process
1. Verified interface state using ip addr
2. Identified disabled interface
3. Restored interface state
4. Inspected DNS configuration
5. Corrected invalid nameserver configuration

## Root Cause
Disabled network interface and incorrect DNS server configuration.

## Resolution
Re-enabled interface and restored valid DNS configuration.

## Skills Practiced
- Linux networking
- DNS troubleshooting
- Interface troubleshooting
- Connectivity diagnostics
