# Cloud Infrastructure Components

## Compute Resources

**Purpose:** Compute resources provide the processing power needed by a computer system to execute applications, commands, and background tasks. The processor handles instructions and allows the system to perform different operations.

**Importance in cloud computing:** Compute resources are necessary for running websites, applications, virtual machines, and other cloud workloads. The amount of compute available affects how efficiently a system can handle its users and tasks.

**Relation to KillerCoda environment:** In the KillerCoda environment, the virtual machine uses a CPU as its main processing resource. This CPU allows the Ubuntu server to execute terminal commands, run system services, and perform the tasks required during the laboratory activity.

## Storage Resources

**Purpose:** Storage resources are used to keep operating system files, applications, configurations, and user data. They provide the space needed for information to be stored and accessed by the system.

**Importance in cloud computing:** Storage is important because cloud applications need dependable space for saving and retrieving information. Different storage options allow organizations to select an appropriate solution based on capacity, speed, reliability, and cost.

**Relation to KillerCoda environment:** The KillerCoda server contains virtual storage that holds its Linux operating system and other system files. Commands such as `df -h` can be used to check available storage, while `findmnt` can display the mounted storage locations.

## Networking Resources

**Purpose:** Networking resources enable computers and cloud services to exchange information with one another. Network interfaces and IP addresses allow a server to establish connections and communicate with other devices.

**Importance in cloud computing:** Networking is essential because cloud resources usually need to communicate with users, applications, databases, and other services. It provides the connection required for accessing cloud applications and transferring data between systems.

**Relation to KillerCoda environment:** The KillerCoda server has network interfaces configured for communication within its environment. The `ip a` command can be used to view the network interfaces, IP addresses, and other network configuration details of the Linux server.

## Operating System

**Purpose:** An operating system manages the computer's hardware and software resources while providing an environment for applications and users. It controls processes, memory, storage, networking, and other important system functions.

**Importance in cloud computing:** The operating system provides the basic platform where cloud applications and services operate. It also gives administrators the tools needed to configure, monitor, secure, and maintain cloud servers.

**Relation to KillerCoda environment:** The KillerCoda virtual server uses Ubuntu Linux as its operating system. The command `cat /etc/os-release` can be used to identify the Ubuntu version, while `uname -r` displays the Linux kernel version. These features provide the foundation for managing and operating the cloud-based server.
