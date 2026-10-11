1. **Why is object storage better suited for storing millions of photos compared to a traditional block storage hard drive?**
Traditional block storage relies on hierarchical folder directories and OS file tables (inodes) that suffer from severe performance bottlenecks when managing millions of media files. In contrast, object storage utilizes a flat address namespace where each file is stored alongside customizable metadata and a unique identifier. This architecture eliminates directory traversal overhead, scales virtually infinitely across storage pools, and provides efficient, cost-effective retrieval ideal for massive collections of photos.

2. **How did using Docker make it easier to deploy the MinIO storage server?**
Deploying MinIO via Docker streamlined the entire process by packaging the application, dependencies, system libraries, and networking boundaries into a self-contained container. Instead of configuring system services, manual binary installations, or dealing with host machine OS dependency issues, a single `docker run` command instantly set up port forwarding (`9000` and `9001`), injected root administrative credentials, and launched a ready-to-use storage server in seconds.

3. **What is a "bucket" in the context of cloud storage?**
A bucket is a fundamental top-level logical container in cloud object storage used to organize and group objects. It acts as an administrative boundary where access control lists (ACLs), read/write permissions, lifecycle retention rules, and data encryption policies are configured and applied to all files stored within it.

4. **How do you think large enterprise companies ensure their object storage data is not lost if the physical server crashes?**
Enterprises ensure high availability and durability by distributing their object storage clusters across multiple availability zones and physical data centers. They use techniques such as erasure coding—which splits data into fragments with parity across multiple drives and nodes—along with asynchronous geo-replication. If a disk or entire physical server crashes, the missing chunks are reconstructed automatically without downtime or data loss.

5. **How is your confidence in navigating the Linux command line growing?**
My confidence with the Linux terminal has grown substantially. Troubleshooting container lifecycles, monitoring runtime states with `docker ps`, inspecting terminal outputs, managing build contexts, and running background daemon tasks has transformed the command-line interface from an intimidating barrier into an intuitive and reliable tool for system automation.
