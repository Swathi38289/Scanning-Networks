# Nmap Network Reconnaissance Task

## Objective
Performed network reconnaissance using Nmap and analyzed traffic using Wireshark.

## Tools Used
- Kali Linux
- Nmap
- Wireshark
- VirtualBox

## Commands Used

### TCP SYN Scan
nmap -sS 10.0.2.0/24 -oA scan_results

### Basic Scan
nmap 10.0.2.15

## Files Included
- scan_results.txt → Nmap normal output
- scan_results.xml → XML format output
- scan_results.html → HTML converted report
- scan1.txt → Additional scan output
- Wireshark screenshots → Packet capture analysis

## Observations
- Identified open ports
- Observed SYN packets in Wireshark
- Understood TCP 3-way handshake
- Learned difference between root and user permissions

## Learning Outcome
This task helped in understanding:
- TCP SYN scanning
- Network reconnaissance
- Packet-level traffic analysis
- Linux file permissions
