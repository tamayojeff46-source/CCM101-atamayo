# Multi-Tier Architecture

## What is a Two-Tier Architecture?
A Two-Tier Architecture is a client-server software design where an application is divided into two distinct logical and operational layers: the presentation/application tier and the database tier. This separation allows user interactions and application logic to function independently from the underlying data storage.

---

## The Web/Application Tier
The web/application tier (Nextcloud) serves as the front-facing component that users interact with directly. Its primary roles include:
- Serving the user interface (UI) to client browsers.
- Handling incoming HTTP and HTTPS requests.
- Processing application business logic, user inputs, file uploads, and session handling.

---

## The Database Tier
The database tier (MariaDB) acts as the centralized backend system responsible for managing structured records. Its primary roles include:
- Storing persistent data such as user credentials, access permissions, and application settings.
- Managing file metadata, activity logs, and indexing information for quick retrieval.
- Ensuring data integrity, executing queries, and processing read/write operations securely.

---

## Why Separate Them?
Separating the web server and the database into distinct containers isolates dependencies, prevents resource bottlenecks, and avoids a single point of total system failure. This structure allows each container to be updated, restarted, or scaled independently without taking down the entire application. In addition, it enhances overall security by ensuring that external web traffic cannot directly access the database layer.
