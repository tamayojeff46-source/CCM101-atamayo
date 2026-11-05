# Security Audit Report: Chapter 8 Core Concepts

## 1. The Principle of Least Privilege (PoLP)
The Principle of Least Privilege means giving users, apps, or programs only the exact permissions they need to do their jobs and nothing more. This is really important for cloud user accounts because if a hacker manages to break into one account, they won't get access to the whole system. It helps stop them from moving around and doing more damage.

## 2. Attack Surface
When we talk about a virtual machine, the attack surface is basically all the exposed entry points, open network ports, and running services that someone on the outside can try to exploit. The more open ports and apps you have running, the bigger your attack surface becomes. This gives attackers more chances to find a weak spot and break into your server.

## 3. Default Deny Policy
A default deny policy is a safety rule where the firewall blocks all incoming traffic automatically unless you specifically allow it. It's much safer than trying to block individual hackers one by one because you can't possibly predict every single bad IP address out there. By blocking everything first, any new or forgotten port stays completely protected by default.
