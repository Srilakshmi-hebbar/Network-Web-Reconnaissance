
# Findings – Network and Web Reconnaissance

## 1. Network Information Gathering

The network configuration of the Kali Linux system was examined using Linux networking commands.

The following information was identified:

- Local IP address: 10.83.46.71
- Network range: 10.83.46.0/24
- Default gateway: 10.83.46.127

These details helped understand the network configuration and connectivity of the testing environment.

## 2. Technology Discovery

Wappalyzer and Netcraft were used to examine the technologies associated with the target website.

This activity helped identify the web technologies and hosting-related information visible through the tools.

## 3. Directory Enumeration

GoBuster was used for directory enumeration against the authorized lab web application.

The tool was used to identify potentially accessible directories and files.

## 4. Subdomain Enumeration

Subfinder was used to collect subdomains associated with the domain examined during the practical.

The collected results were processed to remove duplicate entries.

- Total unique subdomains recorded: 22,248

## 5. DNS Resolution

DNSX was used to check the DNS resolution status of the collected subdomains.

The recorded results were:

- Resolved entries: 1
- Unresolved entries: 22,247
- Resolved hostname recorded: www.example.com

## 6. Overall Observations

The practical demonstrated how reconnaissance can help collect information about network configurations, website technologies, directories and subdomains.

It also demonstrated the importance of DNS resolution in identifying which discovered subdomains have valid DNS records.

## 7. Conclusion

The reconnaissance exercise provided practical exposure to Linux networking commands and commonly used information-gathering tools.

The exercise improved understanding of the initial information-gathering phase of cybersecurity assessment.

## Disclaimer

This project was performed for educational purposes in an authorized testing environment. Reconnaissance activities must only be conducted with appropriate permission.
