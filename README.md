Task Overview

The objective of this task is to understand firewall concepts and gain hands-on experience in configuring, testing, and documenting firewall rules. The task focuses on controlling inbound and outbound network traffic using Windows Defender Firewall.

🛠 Tools Used

Windows Defender Firewall with Advanced Security

Operating System: Windows 10 / Windows 11

Command Prompt (for basic testing)

🔍 What is a Firewall?

A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predefined security rules. It acts as a barrier between a trusted internal network and untrusted external networks such as the internet.

🔄 Stateful vs Stateless Firewall
Feature	Stateful Firewall	Stateless Firewall
Tracks connection state	Yes	No
Security level	High	Low
Performance	Moderate	Fast
Example	Windows Firewall	Basic packet filters

Windows Defender Firewall is a stateful firewall, meaning it tracks ongoing connections and allows return traffic automatically.

📥 Inbound vs Outbound Rules

Inbound Rule: Controls traffic coming into the system.

Outbound Rule: Controls traffic going out of the system.

⚙️ Firewall Rules Configured
✅ Allowed Rule
Rule Name	Port	Protocol	Action
Allow HTTP	80	TCP	Allow
❌ Blocked Rule
Rule Name	Port	Protocol	Action
Block Telnet	23	TCP	Block
🚫 Malicious IP Blocking

A suspicious IP address was blocked using a custom inbound firewall rule.

Rule Name	IP Address	Action
Block Suspicious IP	203.0.113.45	Block

This prevents any traffic from the specified IP from accessing the system.

🧪 Testing & Verification

Allowed ports were tested and confirmed to accept connections.

Blocked ports failed to establish connections as expected.

Firewall rules were verified using the Monitoring section in Windows Defender Firewall.

Rule behavior confirmed successful enforcement.

📊 Observing Firewall Logs

Firewall activity was observed using:

Windows Defender Firewall → Monitoring

Active rules were verified to ensure correct implementation.

❓ Can a Firewall Stop All Attacks?

No. A firewall cannot stop all attacks.
It helps prevent:

Unauthorized access

Open port exploitation

Suspicious IP traffic

However, it cannot prevent:

Phishing attacks

Malware from trusted sources

Social engineering attacks

Firewalls should be used along with antivirus software, IDS/IPS, and user awareness.

📁 Deliverables

Firewall rules documentation

Explanation of allowed and blocked ports

IP blocking demonstration

GitHub repository with README

🎯 Final Outcome

Learned firewall concepts

Configured inbound firewall rules

Allowed and blocked network ports

Blocked a malicious IP address

Tested and documented firewall behavior

✅ Conclusion

This task helped me understand how firewalls protect systems by controlling network traffic. I gained practical experience in configuring firewall rules, testing connectivity, and documenting security configurations.
