##Blue Team Defense Concepts - CYB102 Unit 1: Detailed Summary

Introduction
The document, part of CYB102 Unit 1, focuses on Blue Team Defense Concepts. It aims to equip participants with the knowledge and skills necessary to defend an organization’s information systems against potential cyber threats. The session includes community guidelines, an agenda, and a series of discussions and activities designed to foster understanding and practical application of blue team defense strategies.

Community Guidelines
Participants are encouraged to be fully present, both physically and mentally, during sessions. The emphasis is on building an inclusive community where curiosity and a learning mindset are valued. Participants are also encouraged to ask for help when needed and to keep their cameras on during virtual sessions to enhance engagement and communication.

Agenda
The session is structured as follows:

Introduction (00:00 - 00:10): Brief overview of the session.
What is a Blue Team (00:10 - 00:45): Detailed discussion on the definition and roles of a blue team.
NIST Control (00:45 - 00:55): Examination of NIST control frameworks and their application.
Lab: It Wasn’t Me (00:55 - 1:55): Practical lab exercise to apply blue team concepts.
Wrap Up (01:55 - 2:00): Conclusion and summary of the session.
Discussion Points
The session begins with a discussion on the National Institute of Standards and Technology (NIST) definitions of Red and Blue Teams. According to NIST, a red team is a group authorized to emulate potential adversaries to test an organization’s security posture. In contrast, a blue team is responsible for defending the organization’s information systems, maintaining its security posture against these mock attackers. The discussion explores the roles and benefits of having both red and blue teams within an organization, emphasizing the complementary nature of these teams in enhancing overall security.

Blue Team Responsibilities
NIST defines the blue team as the group responsible for defending an enterprise’s use of information systems by maintaining its security posture against a group of mock attackers. The blue team’s primary role is defensive, focusing on protecting the organization’s critical assets from potential threats.

Blue Team Activities
Key activities undertaken by the blue team include:

Analyzing the Current State of Security: Regular assessment of the organization’s security posture to identify flaws and vulnerabilities.
Digital Footprint Analysis: Evaluating the organization’s digital presence to uncover potential security risks.
DNS Audits: Ensuring the integrity and security of domain name systems.
Installing and Configuring Firewalls: Implementing and managing firewalls to protect against unauthorized access.
Monitoring Network Activity: Continuously observing network traffic to detect suspicious activities.
Installing and Configuring Endpoint Security Software: Ensuring all endpoints are secured against potential threats.
Using Least-Privilege Access: Limiting access rights for users to the minimum necessary to perform their tasks, thereby reducing the risk of insider threats.
Skills for Blue Team Members
Blue team members must possess a range of skills to effectively defend their organization’s information systems:

Risk Assessment: Identifying key assets most at risk of exploitation to prioritize protection resources.
Threat Intelligence: Staying ahead of attackers by understanding existing threats and planning appropriate defenses.
Hardening Techniques: Recognizing and addressing security weaknesses within the organization.
Monitoring and Detection Systems: Using tools like packet sniffers, Security Information and Event Management (SIEM) systems, Intrusion Detection Systems (IDS), and Intrusion Prevention Systems (IPS) to detect and respond to threats.
Security Operations Center (SOC)
The Security Operations Center (SOC) is a centralized unit where highly trained analysts work around the clock to defend and improve an organization’s defenses. Key roles within a SOC include:

SOC Analysts: Monitoring network sensors and security tools to proactively identify potential security threats.
Network Engineers: Ensuring the network infrastructure is secure and resilient.
Malware Analysts: Analyzing and responding to malware threats.
Functional Areas of a SOC
The primary functional areas within a SOC are:

Monitor: Continuously observing network activity to identify potential threats.
Hunt: Actively searching for signs of malicious activity within the network.
Triage: Prioritizing identified threats based on their severity and potential impact.
Respond: Taking action to mitigate identified threats.
Remediate: Implementing controls to prevent future occurrences of similar threats.
Real World SOC Operations
SOC operations typically involve the use of various tools and systems to monitor and respond to security events. Examples include:

WAZUH: A SIEM solution for monitoring, detecting, and alerting on security events and incidents.
The HIVE: A Security Incident Response Platform (SIRP) for tracking security events observed with WAZUH.
CORTEX: A tool for analyzing collected observables from security events to determine appropriate responses.
Cyber Fusion Center
A Cyber Fusion Center is an advanced security operations center designed to enhance and improve enterprise security. It combines standard cybersecurity services, such as threat detection and response, with advanced features like threat intelligence, data analytics, and user and entity behavior analytics. The purpose of a Cyber Fusion Center is to facilitate collaboration and communication between teams engaging in related functions—such as cybersecurity and IT operations—to reduce risk and improve the organization’s overall security posture.

NIST Cybersecurity Framework
The NIST Cybersecurity Framework helps businesses of all sizes understand, manage, and reduce their cybersecurity risk. It provides a voluntary framework outlining best practices to help organizations decide where to focus their time and money for cybersecurity protection.

NIST System Monitoring
NIST recommends monitoring systems by observing audit activities in real-time or through other system aspects such as access patterns and characteristics. System monitoring capabilities are achieved through various tools and techniques, including:

Intrusion Detection and Prevention Systems: Detecting and preventing unauthorized access.
Malicious Code Protection Software: Protecting against malware and other malicious software.
Scanning Tools: Identifying vulnerabilities within the system.
Audit Record Monitoring Software: Keeping track of system activities.
Network Monitoring Software: Observing network traffic to detect anomalies.
Lab Exercise: It Wasn’t Me
Participants engage in a lab exercise where they use Wireshark to inspect .pcap files and extract email content. The goal is to identify legitimate vs. fraudulent emails and correctly identify the source of malicious activities.

Project Preview
The session concludes with a preview of the project, which involves using Wireshark to inspect email content, identifying legitimate vs. fraudulent emails, and pinpointing the malicious entity. Participants are reminded to complete the project before the next session.
