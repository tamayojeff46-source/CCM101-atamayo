# Mission Reflection: Cloud Security

1.A host-based firewall acts as a vital last line of defense for a server. Even if an attacker manages to breach the physical network perimeter or outer network security groups, the host firewall ensures that unauthorized ports and services remain strictly guarded locally on the machine itself.

2.Managing open network ports is critical because every active port represents a potential entry point; closing unused ports directly shrinks the system's attack surface and reduces exposure to automated exploits.

3.In a real enterprise environment, leaving a database port like MySQL (port 3306) open directly to the public internet is extremely dangerous. It exposes the database management system to brute-force attacks, credential stuffing, and unauthenticated remote exploits, which can easily lead to massive data breaches.

4.Completing this mission significantly changed my perspective on how easily a server can be compromised. Before configuring UFW, simply deploying a container exposed it instantly to anything scanning the web. Activating a Default Deny policy showed me how quickly foundational security rules can neutralize ambient internet threats.

5.Looking at my GitHub portfolio now with eight completed missions, I feel proud of how structured and professional it has become. It documents a complete journey from cloud basics and infrastructure blueprints to deployment, operations, and now robust cloud security engineering.
