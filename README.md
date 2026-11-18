
# Network and Web Reconnaissance

## 1. Project Overview
This project demonstrates the initial reconnaissance phase of an authorized cybersecurity assessment. The objective was to gather information about a testing environment, identify technologies, enumerate web directories, and perform subdomain discovery.

## 2. Objectives
- Understand basic network configuration.
- Identify web technologies.
- Perform directory enumeration.
- Discover subdomains.
- Resolve discovered domains using DNS tools.
- Analyze reconnaissance results.

## 3. Tools Used
- Kali Linux
- Linux networking commands
- Wappalyzer
- Netcraft
- GoBuster
- Subfinder
- DNSX

## 4. Methodology

### Phase 1: Network Reconnaissance
Used Linux commands to identify network configuration, IP address, gateway, routing information and DNS configuration.

Commands:
- `hostname -I`
- `ip addr`
- `ip route`
- `ping`
- `cat /etc/resolv.conf`
- `nslookup`

### Phase 2: Technology Discovery
Used Wappalyzer and Netcraft to examine technologies and publicly visible information about the target website.

### Phase 3: Web Enumeration
Used GoBuster with a directory wordlist to identify possible directories and files in the authorized testing environment.

### Phase 4: Subdomain Enumeration
Used Subfinder to discover subdomains and DNSX to check DNS resolution.

Commands:
- `subfinder -d example.com -o subdomains.txt`
- `sort -u subdomains.txt -o subdomains_unique.txt`
- `dnsx -l subdomains_unique.txt -o resolved.txt`
- `wc -l subdomains_unique.txt`

## 5. Observations
The recorded assessment included:
- Network configuration details of the Kali Linux machine.
- Technology information collected using Wappalyzer and Netcraft.
- Web directory enumeration using GoBuster.
- 22,248 unique subdomain entries in the recorded Subfinder output.
- One DNS-resolvable result in the recorded DNSX output.

The subdomain results should be interpreted in the context of the specified test domain and the actual lab output.

## 6. Learning Outcomes
- Understood the importance of reconnaissance in penetration testing.
- Practised Linux networking commands.
- Learned basic web technology identification.
- Understood directory and subdomain enumeration.
- Learned how DNS resolution helps validate discovered subdomains.

## 7. Conclusion
This project provided practical exposure to the information-gathering stage of cybersecurity assessment. The tools helped explore network configuration, web technologies, directories and subdomains.

## 8. Project Documentation
The detailed assessment report and practical screenshots are included in this repository.

