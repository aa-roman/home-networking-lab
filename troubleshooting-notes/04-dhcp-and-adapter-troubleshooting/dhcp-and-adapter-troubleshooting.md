# DHCP and Adapter Troubleshooting

## DHCP
DHCP automatically assigns:
- IP addresses
- subnet masks
- gateways
- DNS servers

## APIPA
169.254.x.x addresses usually indicate DHCP failure.

## Commands

### Release DHCP Lease
ipconfig /release

### Renew DHCP Lease
ipconfig /renew

## Troubleshooting Workflow
1. Verify adapter enabled
2. Verify IP assignment
3. Check for APIPA addresses
4. Test gateway reachability
5. Test external connectivity
6. Verify DNS resolution
