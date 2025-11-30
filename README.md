#Problem Definition

SSH brute-force attacks are a major security risk for any internet-exposed server. Attackers
use automated tools to repeatedly guess login credentials, which can lead to unauthorized
access if weak passwords are in use. Traditional security measures often rely on manual log
monitoring, which is inefficient and slow to respond to rapid, large-scale attacks. Without
real-time detection and automated blocking, systems remain vulnerable to compromise.

This project addresses the challenge of automating SSH attack detection and prevention using
Wazuh (SIEM) and Fail2Ban. The goal is to create a lightweight, open-source solution that
monitors SSH logs for suspicious activity, triggers alerts, and automatically blocks malicious
IPs—reducing the burden on security teams while improving response times. By
implementing this system, organizations can enhance their defenses against one of the most
common attack vectors without expensive commercial tools.

#Project Profile

This project focuses on securing Linux-based servers against SSH brute-force attacks, which 
remain one of the most common methods attackers use to gain unauthorized access. The
solution integrates Wazuh, an open-source SIEM platform, with Fail2Ban, a log-based
intrusion prevention tool, to provide both real-time detection and automated prevention.
Wazuh continuously monitors authentication logs, applies custom rules to detect suspicious
activity, and raises alerts when brute-force patterns are observed. In parallel, Fail2Ban
dynamically blocks malicious IP addresses by modifying firewall rules, thereby preventing
further intrusion attempts. This combined approach offers a robust, automated defense system
with minimal manual intervention.

The outcome of this project is a fully functional, open-source intrusion detection and
prevention system tailored for SSH security. It will provide real-time monitoring, automated
blocking of attackers, and comprehensive reporting, making it a cost-effective security
solution for small to medium enterprises.
