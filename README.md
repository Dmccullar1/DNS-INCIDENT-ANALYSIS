# DNS-INCIDENT-ANALYSIS
Analysis of a DNS connectivity incident using tcpdump network traffic

## Overview
This project documents the investigation of a network connectivity incident involving a failed DNS request.

## Scenario
Users were unable to access a website, prompting an investigation into the network traffic to determine the cause.

## Tools Used
- tcpdump

## Skills Demonstrated
- Network traffic analysis
- DNS
- UDP
- ICMP
- Port 53
- Packet analysis
- Incident documentation

## Findings
Analysis of the captured network traffic showed that a DNS request was sent using UDP port 53. An ICMP response indicated that UDP port 53 was unreachable, preventing the DNS request from being completed successfully.

## Conclusion
The investigation indicated that the DNS service was unavailable or unable to accept traffic on UDP port 53. This prevented the domain name from being properly resolved.

## Project File
The full cybersecurity incident report is included in this repository.
