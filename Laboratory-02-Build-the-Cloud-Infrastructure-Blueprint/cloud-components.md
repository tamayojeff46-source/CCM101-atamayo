# Cloud Infrastructure Components

## 1. Compute Resources
* **Purpose:** Nagpoproseso ng computational tasks, nagpapatakbo ng applications, at nag-eexecute ng system instructions.
* **Cloud Importance:** Ito ang virtualization layer (Virtual Machines o Containers) na pumapalit sa pisikal na on-premise hardware servers.
* **Linux Environment Relation:** Kinakatawan ng Virtual CPU (vCPU) at RAM sa KillerCoda terminal na nagpapatakbo ng Linux process scheduler.

## 2. Storage Resources
* **Purpose:** Nag-iimbak ng data, configuration files, operating system images, at application logs nang temporary (ephemeral) o permanent (persistent).
* **Cloud Importance:** Sinisiguro nito ang data persistence, durability, at accessibility kahit mag-restart o ma-terminate ang virtual machine.
* **Linux Environment Relation:** Ang root file system (`/`) at block devices na makikita gamit ang `df -h` at `lsblk`.

## 3. Networking Resources
* **Purpose:** Nagbibigay-daan sa komunikasyon sa pagitan ng mga server, database, internet, at mga end-users.
* **Cloud Importance:** Nagbibigay ng security isolation (VPC/VNet), routing, IP address management, at firewall rules.
* **Linux Environment Relation:** Ang network interface (`eth0`/`ens3`) at IP allocation na nakita gamit ang `ip -brief address`.

## 4. Operating System
* **Purpose:** Nagsisilbing interface sa pagitan ng hardware resources at user applications.
* **Cloud Importance:** Nagbibigay ng standardized platform (karamihan ay Linux) para sa software deployments, container runtimes, at automation scripts.
* **Linux Environment Relation:** Ang Linux kernel at distributions (tulad ng Ubuntu) na ginagamit sa KillerCoda instance.
