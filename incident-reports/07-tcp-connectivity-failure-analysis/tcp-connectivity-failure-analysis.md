# TCP Connectivity Failure Analysis

## Incident
User experienced inability to access remote web service.

## Symptoms
- Website timeout
- Failed connectivity

## Troubleshooting Process
1. Captured TCP traffic using Wireshark
2. Inspected TCP handshake attempts
3. Identified repeated SYN retransmissions
4. Verified missing SYN/ACK responses

## Root Cause
Remote host unreachable or connection blocked.

## Resolution
Confirmed failed connectivity path and isolated issue to remote communication failure.

## Skills Practiced
- TCP analysis
- Packet troubleshooting
- Retransmission analysis
- Connectivity diagnostics
