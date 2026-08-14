# Checkpoint 7 – Linux Investigation

## Linux Server Investigation

For this checkpoint, I used the KillerCoda Playground to investigate a Linux server. I used different Linux commands to identify the operating system, CPU, memory, and available disk space. This activity helped me understand how basic Linux commands can be used to gather important information about a server.

### 1. Operating System

I used the command:

`cat /etc/os-release`

This command is used to view information about the operating system installed on the server. Based on the result, the server is running **Ubuntu 24.04.4 LTS (Noble Numbat)**. This shows that the Linux environment is based on Ubuntu, which is a popular Linux distribution.

### 2. CPU Information

I used the command:

`lscpu`

The `lscpu` command provides information about the processor and CPU configuration. Based on the result, the server uses an **x86_64 architecture** with **1 CPU, 1 core, and 1 thread**. The processor is identified as an **Intel Xeon E312xx (Sandy Bridge)**. The result also shows that the Linux environment is running on a **KVM virtual machine**.

This information helped me understand that the Linux server is running in a virtualized environment rather than directly using a physical computer.

### 3. Memory

I used the command:

`free -h`

This command shows the amount of memory being used and the amount that is still available. The server has approximately **1.9 GiB of total memory**. Around **427 MiB is currently being used**, while approximately **1.4 GiB is available**.

The server also has **1 GiB of swap memory**, which is currently not being used. This means that the server still has enough available memory for its current tasks.

### 4. Disk Space

I used the command:

`df -h`

This command displays information about the storage space of the Linux server. The main filesystem has **19 GB of total storage**, with approximately **5.4 GB used** and **13 GB available**. Only about **30% of the main storage is being used**.

This shows that the server still has enough available disk space for additional files, applications, and other server activities.

## Cloud Migration

If this Linux server were migrated to the cloud, it could be hosted using virtual machine services from different cloud providers such as **AWS, Microsoft Azure, or Google Cloud**.

| Cloud Provider  | Service That Could Host the Linux Server | Reason                                                             |
| --------------- | ---------------------------------------- | ------------------------------------------------------------------ |
| AWS             | Amazon EC2                               | It provides virtual machines that can run Linux operating systems. |
| Microsoft Azure | Azure Virtual Machines                   | It supports Linux-based virtual machines and workloads.            |
| Google Cloud    | Compute Engine                           | It provides configurable virtual machines that can run Linux.      |

## My Understanding

Based on my investigation, I learned that a Linux server can be moved to different cloud platforms without necessarily changing the operating system. Services such as Amazon EC2, Azure Virtual Machines, and Google Compute Engine can provide virtual machines where Ubuntu Linux can run.

I also learned that before moving a server to the cloud, it is important to check its CPU, memory, storage, and other system requirements. The information collected using commands such as `lscpu`, `free -h`, and `df -h` can help an organization determine the resources needed for the cloud environment.

For me, the main lesson from this activity is that Linux and cloud computing are closely connected. A Linux server can run on physical hardware, a virtual machine, or a cloud platform. The organization can choose the cloud provider based on its budget, required performance, available resources, and business needs.

Overall, this investigation helped me better understand how Linux commands can be used to examine a server and how the information gathered can be useful when planning a cloud migration.
