FICBANK Penetration Testing Assessment

Overview

This repository documents an authorized penetration testing assessment
completed in a controlled University of Maryland Global Campus (UMGC)
laboratory environment. The project evaluated a simulated enterprise
network through reconnaissance, vulnerability discovery, controlled
exploitation, post-exploitation analysis, and remediation planning.

Portfolio Notice: This is an educational cybersecurity project. No
production systems or real user accounts were targeted. Test
credentials and sensitive evidence have been redacted from the public
report.

Objectives

Identify active hosts, exposed services, security weaknesses, and
misconfigurations.

Evaluate existing network and application security controls.

Validate selected vulnerabilities through controlled exploitation.

Demonstrate the security impact of social engineering in an
authorized lab.

Develop prioritized remediation recommendations.

Document post-exploitation cleanup and validation activities.

Methodology

The assessment followed a structured penetration testing workflow
aligned with NIST SP 800-115:

Reconnaissance and Enumeration

DNS and WHOIS reconnaissance

Host discovery

Port and service enumeration

Service fingerprinting

Vulnerability Discovery

Network and web application scanning

Directory enumeration

Security-header review

Cryptographic configuration assessment

Controlled Exploitation

Metasploit Framework module research and testing

Social Engineering Toolkit (SET) phishing simulation

Credential-harvesting demonstration using test credentials

Post-Exploitation and Remediation

Session termination and artifact cleanup

Verification that no persistence mechanisms remained

Risk-based remediation recommendations

Continuous vulnerability-management recommendations

Tools and Technologies

Kali Linux

Nmap

DIG

NSLOOKUP

WHOIS

Nikto

DIRB

WPScan

OpenVAS / Greenbone

Metasploit Framework

Social Engineering Toolkit (SET)

Key Findings

The assessment identified findings involving:

Exposed network services and increased attack surface

Missing HTTP security headers

Publicly accessible web directories and files

Weak SSL/TLS cipher configurations

Weak SSH message authentication algorithms

Outdated or unsupported software

Potential exposure to known service vulnerabilities

Susceptibility to social engineering and credential harvesting

Need for continuous vulnerability management and recurring
penetration testing

Security Recommendations

Recommended improvements included:

Reduce unnecessary externally accessible services.

Strengthen firewall rules and network segmentation.

Enforce strong authentication and multifactor authentication.

Replace unsupported software and maintain timely patching.

Implement recommended HTTP security headers.

Strengthen TLS and SSH cryptographic configurations.

Conduct recurring vulnerability assessments and penetration tests.

Maintain security-awareness and phishing-simulation programs.

Verify remediation through follow-up testing.

Report

The repository includes a sanitized PDF version of the full penetration
testing report. Test credentials and sensitive evidence have been
removed or redacted for public portfolio use.

File: FICBANK_Penetration_Testing_Report_Portfolio.pdf

Skills Demonstrated

Penetration Testing · Vulnerability Assessment ·
Network Reconnaissance · Nmap · OpenVAS · Metasploit ·
Web Security Testing · Social Engineering Testing · Risk Analysis
· Security Remediation · NIST SP 800-115 · Technical Documentation

Disclaimer

This repository is provided strictly for educational and professional
portfolio purposes. All penetration testing activities described in the
report were performed in an authorized laboratory environment. The
techniques and tools documented here should only be used against systems
for which explicit authorization has been granted.
