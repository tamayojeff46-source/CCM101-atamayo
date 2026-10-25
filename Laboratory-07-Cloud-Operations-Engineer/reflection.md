# Mission Reflection

1. **Why is it important to check the host server's resources even if your containers are running perfectly?**
   Even if an individual container appears healthy, the underlying host server shares physical hardware resources (CPU, RAM, disk I/O) across all running workloads. If the host runs out of resources, the operating system can crash or trigger out-of-memory killers, taking down all containers regardless of their internal status.

2. **If a user complains that they cannot log into a web application, how would the `docker logs` command help you solve the problem?**
   The `docker logs` command exposes real-time stdout and stderr streams from the application. By reviewing these logs, I can check if incoming authentication requests are hitting the server, identify specific HTTP error codes like 401 Unauthorized or 500 Internal Server Error, and trace backend database connection failures.

3. **What is the difference between monitoring logs (Checkpoint 4) and monitoring metrics (Checkpoint 5)?**
   Monitoring logs provides discrete event-driven history detailing specific actions, timestamps, and error codes. Monitoring metrics provides continuous quantitative numerical telemetry representing system performance trends like CPU percentage and memory utilization over time. Logs tell you *what* happened; metrics tell you *how hard* the system is working.

4. **How do you think large enterprise companies monitor thousands of containers at the same time?**
   Large enterprises utilize distributed observability and monitoring platforms like Prometheus to automatically scrape time-series metrics across thousands of cluster nodes, combined with visualization dashboards like Grafana to set up automated alerting thresholds, trend analysis, and centralized log aggregation.

5. **How has your ability to troubleshoot Linux environments improved?**
   This laboratory activity enhanced my practical fluency in combining native Linux CLI utilities (`free`, `df`, `top`) with containerized runtime tools (`docker logs`, `docker stats`). I am now more confident in isolating issues by systematically inspecting both host-level infrastructure and application-level behavior.
