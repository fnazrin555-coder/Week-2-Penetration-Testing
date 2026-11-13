# Week-2-Penetration-Testing
Website Footprinting and Reconnaissance using Kali Linux | Networkwalks Batch B084.
🔐 Week 2 – Website Footprinting & Reconnaissance

Name: Fathima Nazrin KE
Organization: Networkwalks
Batch: B084
Platform: Kali Linux
Domain Used: "networkwalks.com"

📌 Project Overview

This project focuses on website footprinting and reconnaissance using various tools available in Kali Linux.

The objective of this practical is to gather publicly available information about a website, identify its technologies, resolve DNS records, inspect HTTP responses, and detect Web Application Firewall (WAF) protection.

🎯 Objectives

- Understand website footprinting and reconnaissance.
- Collect domain registration information.
- Identify website technologies and frameworks.
- Perform DNS lookup and enumeration.
- Inspect HTTP responses.
- Detect Web Application Firewall protection.

🛠️ Tools Used

No.| Tool| Purpose
1| WHOIS| Domain registration lookup
2| WhatWeb| Website technology detection
3| NSLookup| DNS resolution
4| cURL| HTTP response inspection
5| WAFW00F| WAF detection
6| DNSRecon| DNS enumeration

💻 Practical Tasks & Commands

1. WHOIS – Domain Information

whois networkwalks.com

Used to identify domain registration details, registrar information, creation date, expiry date, and name servers.

2. WhatWeb – Technology Fingerprinting

whatweb networkwalks.com

Used to identify the web server, CMS, JavaScript libraries, and other technologies.

3. NSLookup – DNS Resolution

nslookup networkwalks.com

Used to resolve the domain name into its IP address.

Observed IP: "192.232.216.135"

4. cURL – HTTP Inspection

curl -I https://<authorized-domain>

Used to inspect HTTP response headers, server information, and redirect behavior.

5. WAFW00F – Firewall Detection

wafw00f networkwalks.com

Observed Result: ModSecurity (SpiderLabs) WAF detected.

6. DNSRecon – DNS Enumeration

dnsrecon -d networkwalks.com

Used to enumerate DNS records, including:

- SOA Records
- NS Records
- A Records
- MX Records
- TXT Records
- SRV Records

Observed Result: 8 DNS records reported.

📊 Key Findings

- Domain registrar identified as GoDaddy.
- Hosting name servers associated with HostGator.
- Apache web server fingerprint detected.
- WordPress technology fingerprint detected.
- Domain successfully resolved to an IPv4 address.
- ModSecurity WAF detected.
- Multiple DNS record types enumerated.

📸 Screenshots & Evidence

This repository includes practical screenshots showing the execution and outputs of the six reconnaissance tasks.

📚 Learning Outcomes

Through this practical, I learned:

- Basic website footprinting techniques.
- Domain and DNS information gathering.
- Website technology identification.
- HTTP response inspection.
- Web Application Firewall detection.
- DNS enumeration using Kali Linux tools.

⚠️ Disclaimer

This project is intended strictly for educational purposes and authorized security testing.

All testing against third-party websites must be conducted with explicit permission from the website owner. The findings documented here are reconnaissance observations and do not establish exploitable vulnerabilities.

---

Created by Fathima Nazrin KE
Networkwalks | Batch B084
Week 2 – Penetration Testing Practical   
