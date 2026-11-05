# Laboratory 8: The Cloud Security Engineer

## Mission Overview
In this mission, we stepped into the role of a Cloud Security Engineer at CloudNova Technologies. The objective was to secure a newly deployed, exposed Ubuntu server by implementing the principle of defense in depth using a host-based firewall (UFW).

## Objectives
* Understand the Attack Surface and the Principle of Least Privilege (PoLP).
* Perform a basic security audit of active network ports on a Linux server.
* Configure the Uncomplicated Firewall (UFW) with a Default Deny policy.
* Implement granular port management to selectively allow SSH and HTTP/8080 traffic.
* Document firewall rules and security best practices using Markdown.
* Update the professional GitHub Cloud Computing Portfolio.

## Commands Executed
* `docker run -d --name secure-web-app -p 8080:80 nginx` - Deployed the vulnerable Nginx web container.
* `sudo ufw allow ssh` - Permanently allowed SSH access on port 22.
* `sudo ufw default deny incoming` - Set foundational policy to block all incoming traffic.
* `sudo ufw default allow outgoing` - Set policy to allow all outgoing traffic.
* `sudo ufw enable` - Activated the UFW firewall.
* `sudo ufw status verbose` - Checked the detailed active firewall status.
* `sudo ufw allow 8080/tcp` - Allowed granular TCP traffic on port 8080.
* `sudo ufw status numbered` - Verified the numbered firewall rule list.

## Skills Learned
* Server hardening and network security configuration.
* Managing host-based firewalls using UFW in Ubuntu.
* Implementing Default Deny postures and precise port management.
* Technical documentation and evidence-based portfolio management.
