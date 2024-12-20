
## CyberSwipe Domain WHOIS Analysis

This repository contains detailed reports and scripts for analyzing domain information using WHOIS and other related tools. It serves as a comprehensive guide for understanding the structure, security, and configurations of the domain cyberswipe.in.

Features

-WHOIS data analysis for the domain cyberswipe.in.

-Detailed network and hosting information.

-SSL/TLS configuration and encryption details.

-DNS security recommendations (SPF, DMARC, DNSSEC).

-Summary of server- and client-side technologies used.

-Actionable security and optimization recommendations.
## Deployment




```bash
  whoid example.com

├── reports/
│   ├── WHOIS_Analysis_Report.md
│   ├── Network_Configuration_Report.md
│   ├── SSL_TLS_Report.md
│   └── Recommendations.md
├── scripts/
│   ├── fetch_whois_data.sh        # Script to fetch WHOIS data for a domain
│   ├── dnssec_check.py            # Python script to check DNSSEC implementation
│   ├── ssl_scan_tool.py           # Script to analyze SSL/TLS configurations
│   └── content_security_validator.py # Script to validate Content Security Policy (CSP)
├── README.md                      # Project overview and usage instructions
└── LICENSE                        # License details
```

Installation
```bash
sudo apt update
sudo apt install whois openssl python3 python3-pip -y
pip3 install requests dnspython

```
Usage...

Run WHOIS Data Fetching:
```bash
bash scripts/fetch_whois_data.sh cyberswipe.in

```
Check DNSSEC Configuration:
```bash
python3 scripts/dnssec_check.py cyberswipe.in

```
Analyze SSL/TLS:

```bash
python3 scripts/ssl_scan_tool.py cyberswipe.in
```
Validate CSP Settings:
```bash
python3 scripts/content_security_validator.py cyberswipe.in

```



## Used By

This project is used by the following companies:

- cyber-swipe

## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhay-kumar-aa2100299)

[![facebook](https://img.shields.io/badge/facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/abhay.arya.91?mibextid=ZbWKwL)



## 🛠 Skills
C/C++,python...


## 🚀 About Me
I'm a cyber security explorer.

## Optimizations

What optimizations did you make in code? E.g. refactors, performance improvements, accessibility

## Feedback & Support

If you have any feedback and need to Support, please reach out to us at abhayarya@cyberswipe.in

