## Mission Overview
Stepping into the role of a Site Reliability Engineer (SRE) at CloudNova Technologies to establish host system performance baselines, deploy containerized web applications, simulate user web traffic, and monitor application logs and real-time metrics.

## Objectives
* Utilize native Linux command-line tools to monitor host CPU, Memory, and Disk capacity.
* Deploy a web container and track its real-time performance using Docker metrics.
* Generate web traffic and extract application access logs for analysis.
* Translate raw performance data into a readable technical report using Markdown.
* Continue expanding a professional GitHub Cloud Computing Portfolio.

## Monitoring Commands Executed
* `free -h` - Checks the server's current memory (RAM) usage.
* `df -h` - Checks the server's available disk storage capacity[.
* `top` - Displays active processes and CPU load[cite: 2].
* `docker run -d -p 8080:80 --name client-website nginx` - Deploys an Nginx web server container in the background.
* `curl http://localhost:8080` - Simulates user traffic visiting the website.
* `curl http://localhost:8080/hidden-admin-page` - Simulates a user visiting a non-existent page to trigger a 404 error.
* `docker logs client-website` - Retrieves application access logs from the container.
* `docker stats` - Displays a live dashboard of container resource consumption.

## Skills Learned
* Establishing host system hardware performance baselines in a Linux environment.
* Simulating web traffic and intentionally triggering HTTP status errors (200 OK vs 404 Not Found).
* Extracting and analyzing containerized application logs to find specific error codes.
* Utilizing real-time metric streams to verify container resource efficiency.
* Documenting observability metrics and system health accurately using Markdown.
