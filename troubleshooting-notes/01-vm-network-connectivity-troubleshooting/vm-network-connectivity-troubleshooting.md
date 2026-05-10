# VM Network Connectivity Troubleshooting

## Scenario
Ubuntu virtual machine lost internet connectivity after network adapter misconfiguration.

## Symptoms
- ping google.com failed
- No external network access

## Troubleshooting Process
1. Verified VM was powered on
2. Checked Ubuntu network configuration
3. Inspected VirtualBox network adapter settings
4. Identified adapter was set to "Not Attached"

## Root Cause
VirtualBox network adapter had been disconnected.

## Resolution
Changed adapter mode back to NAT and restarted VM.

## Commands Used

- ping google.com
- ip addr
