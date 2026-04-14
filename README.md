This project demonstrates the implementation of a Security Information and Event Management (SIEM) system using Wazuh integrated with Suricata for real-time threat detection and monitoring.

**Technologies Used**
Wazuh SIEM
Suricata IDS
Ubuntu & Windows Agents
Docker (optional)
ELK Stack (Wazuh Dashboard)

**Architecture**
Wazuh Server for log collection and analysis
Windows & Ubuntu endpoints as agents
Suricata for network intrusion detection
Centralized dashboard for monitoring alerts

 **Features**
Centralized log monitoring
Real-time threat detection
Custom alert rules
Integration of host-based and network-based security
Incident analysis and response workflow

**Detection Capabilities**
SSH Brute Force Attacks
SQL Injection Attempts
Command Injection
Suspicious IP Traffic
Data Exfiltration Patterns

**Project Setup**
Install Wazuh Server
Configure agents (Windows & Ubuntu)
Install and configure Suricata
Integrate Suricata logs into Wazuh
Create custom detection rules
