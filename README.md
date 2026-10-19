# wireless-mobile-security-risk-assessment
Wireless and mobile security assessment focusing on BYOD security, WLAN security, risk analysis, and NIST-aligned remediation planning.


Overview:
This project presents a security assessment of a simulated 35-user organization's wireless and mobile environment. The assessment focuses on identifying risks associated with Wireless Local Area Network (WLAN) infrastructure, mobile device usage, Bring Your Own Device (BYOD) practices, physical security exposure, and organizational security governance. Recommendations were developed using NIST guidance and industry security best practices.

Project Scope:
The assessment evaluated:
Enterprise Wi-Fi infrastructure
Wireless Access Point (WAP) placement
Mobile device security controls
Bring Your Own Device (BYOD) policies
Physical access security
Access control mechanisms
Defense-in-depth strategies
Governance and compliance considerations

Objectives:
Identify wireless network security weaknesses
Assess mobile device and BYOD risks
Analyze physical security vulnerabilities
Evaluate governance and security controls
Develop risk-based remediation recommendations
Align security improvements with NIST guidance
Environment Assessed
Organization Profile
35 users
Three-story headquarters
Eight Wireless Access Points (WAPs)
Gigabit managed switch
Mobile workforce with company-issued devices
Active BYOD program

Security Challenges:
Wireless signal leakage
Unoccupied building space with network access
Unmanaged mobile devices
Minimal BYOD restrictions
Lack of access control enforcement

Key Findings:
1. Wireless Signal Leakage
One wireless access point was configured to provide coverage for outdoor employee use. Wireless spectrum analysis revealed that the signal extended beyond the organization's physical perimeter, enabling wireless access from adjacent areas.
2. Unsecured Third Floor
An unoccupied floor retained active wireless coverage and functional Ethernet ports. Unauthorized individuals could potentially gain physical access and connect directly to the corporate network.
3. Unmanaged Mobile Devices
Eight traveling sales employees relied on company-issued mobile devices. The organization lacked Mobile Device Management (MDM), encryption requirements, remote wipe capabilities, and passcode enforcement.
4. Insecure BYOD Program
The organization's BYOD policy lacked security controls and configuration requirements, increasing the risk of malware infection, credential theft, and unauthorized access.

Risk Assessment:
Finding	Likelihood	Impact	SeverityWAP Signal Leakage	High	High	High
Unsecured Third Floor	High	Critical	Critical
Unmanaged Mobile Devices	High	Critical	Critical
Insecure BYOD Program	High	High	High
Source: Risk analysis conducted during the assessment.

Threat Model:
Threat Actors
External attackers
Rogue insiders
Disgruntled employees
Device thieves

Potential Attack Techniques:
Rogue Access Points
Evil Twin Attacks
Packet Sniffing
Credential Theft
Physical Intrusion

Security Recommendations:
Wireless Security
Conduct wireless site surveys
Reduce signal leakage through AP tuning
Monitor wireless coverage boundaries
Mobile Security
Deploy Mobile Device Management (MDM)
Require encryption
Enforce remote lock and wipe
Implement patch management
Identity & Access Management
Implement Multi-Factor Authentication (MFA)
Restrict network access to approved devices
Create formal access control policies
Physical Security
Implement badge-controlled access
Deploy surveillance monitoring
Secure unused office areas
BYOD Security
Establish security requirements for personal devices
Require device compliance checks
Consider corporate-owned alternatives where appropriate

Skills Demonstrated:
Wireless Security Assessment
Mobile Device Security
BYOD Risk Management
Risk Assessment
Security Architecture
Defense-in-Depth
Threat Modeling
Security Governance
Compliance Analysis
NIST Framework Application

Frameworks and Standards:
NIST SP 800-153
NIST SP 1800-22
Defense-in-Depth Principles
Risk-Based Security Analysis

Disclaimer
This assessment was conducted in a controlled educational environment for cybersecurity training and portfolio development purposes. No production systems were targeted or accessed.
