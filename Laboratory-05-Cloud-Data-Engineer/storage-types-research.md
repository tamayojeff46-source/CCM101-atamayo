# Types of Cloud Storage Research

## Comparison Table

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
| :--- | :--- | :--- | :--- |
| **Block Storage** | Splits raw data into fixed-sized blocks, each with a unique identifier; it does not store file-level metadata. It connects directly to compute instances as a virtual dedicated hard drive. | Operating systems, boot/root volumes for virtual machines, and high-performance transactional databases. | Amazon EBS (Elastic Block Store), Azure Managed Disks, Google Cloud Persistent Disk |
| **File Storage** | Stores data in a centralized, hierarchical tree structure of folders and files, accessible by multiple compute instances simultaneously over a local network using protocols like NFS or SMB. | Shared application directories, local network file repositories, and content management systems (CMS). | Amazon EFS (Elastic File System), Azure Files, Google Cloud Filestore |
| **Object Storage** | Stores data as independent, self-contained units (objects) containing the file data, rich customizable metadata, and a globally unique identifier within a flat address space without folders. | Massive unstructured datasets, including user-uploaded photos, streaming video, automated backups, and log archives. | Amazon S3 (Simple Storage Service), Azure Blob Storage, Google Cloud Storage |

## Client Explanation: Why Object Storage is the Best Choice

Object storage is the ideal solution for your photo-sharing platform because it provides virtually unlimited horizontal scalability to store millions of user-uploaded images without hitting the capacity and indexing limits of traditional file systems. Unlike ephemeral container storage, object storage persists data independently and safely while enabling you to attach custom metadata (such as user IDs and timestamps) directly to each photo. Additionally, it allows fast, cost-effective direct uploads and downloads via standard web HTTP/S APIs, ensuring high availability and seamless access across all devices.
