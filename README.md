# network-security-lab-wireshark
A hands‑on network security lab using Wireshark to understand how data flows across networks, analyze TCP handshakes, inspect HTTP vs HTTPS traffic, observe cookies in plaintext, and identify basic security risks such as session hijacking. Designed for beginners building strong networking and cybersecurity foundations.


## Objective
To understand how data moves across networks, how TCP connections are created and closed, and how insecure protocols expose sensitive information.

## Tools
- Wireshark
- Windows PC
- Browser (HTTP & HTTPS)

## Network Basics
PC → Switch → Router → Internet → Server

## TCP Three-Way Handshake
1. SYN – Client requests connection
2. SYN-ACK – Server accepts
3. ACK – Client confirms

## TCP Connection Termination
FIN → FIN-ACK → ACK

## ARP Analysis
Observed broadcast ARP requests used to resolve IP to MAC addresses.

## HTTP Analysis (Insecure)
- Captured HTTP GET requests
- Viewed plaintext headers
- Observed cookies in traffic
- Demonstrated why HTTP is unsafe

## HTTPS Analysis (Secure)
- Traffic encrypted using TLS
- Only "Application Data" visible

## Security Risks Observed
- Credential exposure in HTTP
- Session hijacking via cookies
- ARP spoofing possibility
- SYN flood attack patterns (concept)

## Defensive Takeaways
- Always use HTTPS
- Monitor ARP traffic
- Filter suspicious TCP flags
- Use network segmentation (VLANs)
- Follow NIST Detect & Respond phases

## Framework Mapping
NIST:
- Identify – Network assets
- Protect – HTTPS, VLANs
- Detect – Wireshark analysis
- Respond – Incident investigation
- Recover – Security improvements

## Author
Lucy N.M
