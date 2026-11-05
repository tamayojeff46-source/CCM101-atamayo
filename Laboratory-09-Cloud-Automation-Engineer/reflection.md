# Mission 9 Reflection

1. **Why is automation critical when managing hundreds of cloud servers?**
   Automation is critical because manual administration does not scale. When managing hundreds or thousands of servers, logging into each instance manually to perform routine tasks like backups, updates, or configuration changes is extremely slow, inefficient, and highly prone to human error. Automation ensures consistency, speed, and reliability across large-scale infrastructure.

2. **What are the potential dangers of automation? (What happens if there is a destructive typo inside a script that is scheduled to run on 1,000 servers?)**
   The primary danger of automation is its scale of impact. If a script contains a destructive typo (such as an incorrect `rm -rf` path or a misconfigured variable) and is executed automatically across 1,000 servers, it can instantly corrupt, delete, or break production environments enterprise-wide before an administrator has time to react. 

3. **How did writing a Bash script differ from creating a Docker Compose YAML file (Mission 6)?**
   Writing a Bash script is an imperative, procedural process where you explicitly list command-line instructions step-by-step for the shell to execute sequentially. In contrast, creating a Docker Compose YAML file is declarative; you define the desired target state of your multi-container application architecture, and Docker handles how to build and spin up those containers accordingly.

4. **Review your entire GitHub repository from Laboratory 1 to Laboratory 9. How has your understanding of Cloud Computing transformed over the course of this semester?**
   Over the course of this semester, my understanding has evolved from basic theoretical cloud concepts and infrastructure blueprints into hands-on practical deployment, containerization, orchestration, security hardening, and finally, operational automation. I have shifted from acting as a manual system operator to thinking like a full-fledged cloud and DevOps engineer.

5. **Which role did you enjoy the most (Infrastructure Engineer, Cloud-Native Engineer, Security Engineer, etc.) and why?**
   I enjoyed the **Cloud Automation / DevOps Engineer** role the most because it ties everything together. Building scripts and automated pipelines that remove tedious manual labor and make systems self-sustaining highlights the true power and efficiency of modern cloud engineering.
