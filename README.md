# Cybersecurity-Fundamentals-7-Day-Roadmap-DAY-2-.
Day 2 focuses on networking in cybersecurity: detailed study of IP addressing (IPv4/IPv6, public/private, NAT, subnetting), MAC addresses and spoofing, DNS with threats like poisoning, tunneling and hijacking, TCP/IP layers, and ports/protocols. Includes scanning, flooding, exploits, and defenses like firewalls, IDS, TLS.

Cybersecurity Fundamentals – 7 Day Roadmap

This repository contains my structured 7-day journey into cybersecurity fundamentals. Each day focuses on specific areas required to build a strong theoretical foundation. Notes are extensive (270+ pages) and include both theoretical and security-oriented perspectives.

NOTES LINK :- [ https://acrobat.adobe.com/id/urn:aaid:sc:AP:d61a3552-a89f-4b76-b5da-105ab9e8f98e ]
NOTES LINK :- [ https://acrobat.adobe.com/id/urn:aaid:sc:AP:d61a3552-a89f-4b76-b5da-105ab9e8f98e ] 

📘 Day 2 – Networking Fundamentals in Cybersecurity

   { 1. Networking in Security Context }

Networking is the backbone of all cyber operations. Every attack—malware, phishing, ransomware, DDoS, APTs—travels over a network.

Attack Surface View: Each exposed service/port is a potential entry point.

  {Case Studies:}

Mirai Botnet exploited IoT networking weaknesses.

Stuxnet spread internally via networked systems.

Defensive View: Network segmentation, firewalls, IDS/IPS depend entirely on deep networking knowledge.

  {2. IP Addressing }

IPv4 vs IPv6 differences, structure, addressing space.

Public vs Private IPs, NAT and its role in security.

Static vs Dynamic IPs (DHCP) and security risks.

Subnetting basics: logical segmentation for defense in depth.

   { 3. MAC Address }

Role as hardware identifier.

MAC spoofing techniques by attackers.

Use in authentication and access control.

  { 4. DNS (Domain Name System) }

Function: domain to IP translation.

Attacks: DNS poisoning, DNS hijacking, DNS tunneling.

Defense: DNSSEC, secure resolvers.

   { 5. TCP/IP Model in Depth }

Application Layer: Protocols (HTTP, HTTPS, FTP, DNS, SMTP).

Security issues: TLS/SSL, spoofing, DNS poisoning, app-layer exploits.

Transport Layer: TCP vs UDP.

Attacks: SYN Flood, UDP flood.

Security: Firewalls, stateful packet inspection.

Internet Layer: IP, ICMP, ARP.

Attacks: IP spoofing, ICMP flooding, ARP poisoning.

Defense: IPSec, routing security.

Network Access Layer: Ethernet, Wi-Fi, framing.

Attacks: MAC spoofing, rogue AP, VLAN hopping.

Defense: WPA3, 802.1X, VLAN design.

Cross-layer attacks: chaining weaknesses across layers.

   { 6. Ports and Protocols (Deep Dive) }

Well-known ports (0–1023): 20/21 FTP, 22 SSH, 23 Telnet, 25 SMTP, 53 DNS, 80 HTTP, 443 HTTPS, 3389 RDP.

Registered ports (1024–49151): App services like MySQL (3306).

Ephemeral ports (49152–65535): Temporary connections.

Security Issues:

Open ports expose attack surface.

Insecure plaintext protocols (Telnet, FTP).

Misconfigurations leading to privilege escalation.

Attacks:

Port scanning (Nmap, Masscan).

Banner grabbing, service fingerprinting.

Exploiting vulnerable services (e.g., SMB EternalBlue on port 445).

Defense:

Minimize exposed ports.

Regular vulnerability scans.

Use encrypted protocols (SSH, HTTPS).

    [  🔒 Summary After 2 Days ]

Day 1: Set the foundation with security principles and governance.

Day 2: Built deep networking knowledge, mapped directly to cyber threats and defenses.
This created the groundwork to analyze real attacks, understand traffic, and apply defensive controls.



## Author
Prepared by [ SHREYANK ]
For learning, documentation, and knowledge sharing. 
