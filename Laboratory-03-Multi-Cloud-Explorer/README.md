# Laboratory 03 – Multi-Cloud Explorer

## Overview

This laboratory activity explores three major cloud computing platforms: Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

The activity focuses on researching cloud platforms, comparing their services and capabilities, and identifying suitable cloud solutions based on different client requirements.

## Research

- [AWS Research](./aws-research.md)
- [Azure Research](./azure-research.md)
- [GCP Research](./gcp-research.md)

## Cloud Platform Comparison

- [Cloud Platform Comparison](./cloud-platform-comparison.md)

## Client Recommendations

- [Client Recommendations](./client-recommendations.md)

## Reflection

- [Reflection](./reflection.md)

## Evidence

Screenshots and other evidence collected during the laboratory activity are included as part of the laboratory documentation.

## Cloud Platforms Covered

| Cloud Platform | Provider |
|---|---|
| Amazon Web Services (AWS) | Amazon |
| Microsoft Azure | Microsoft |
| Google Cloud Platform (GCP) | Google |

## Conclusion

This laboratory activity provided an overview of major cloud computing platforms and their services. It also helped identify the differences between cloud providers and determine appropriate cloud solutions for different organizational requirements.

#  Linux Investigation

## KillerCoda Linux Investigation

For this checkpoint, I used a KillerCoda Linux Playground to identify the operating system, CPU information, memory, and disk space of a Linux server. I used Linux commands to collect the required system information.

### 1. Operating System

The Linux server is running:

* **Operating System:** Ubuntu 24.04.4 LTS
* **Version Codename:** Noble Numbat

The operating system information was identified using:

```bash
cat /etc/os-release
```

### 2. CPU Information

The Linux server has:

* **Architecture:** x86_64
* **CPU:** 1 vCPU
* **CPU Model:** Intel Xeon E312xx (Sandy Bridge, IBRS update)
* **CPU Frequency:** approximately 2.0 GHz
* **Cores per socket:** 1
* **Threads per core:** 1

The CPU information was identified using:

```bash
lscpu
```

### 3. Memory

The server has:

* **Total Memory:** 1.9 GiB
* **Used Memory:** 418 MiB
* **Free Memory:** 865 MiB
* **Available Memory:** 1.4 GiB
* **Swap:** 1.0 GiB

The memory information was identified using:

```bash
free -h
```

### 4. Disk Space

The main filesystem of the server has:

* **Total Disk Space:** 19 GB
* **Used Space:** 5.4 GB
* **Available Space:** 13 GB
* **Disk Usage:** 30%

The disk information was identified using:

```bash
df -h
```

## Cloud Hosting Options

If this Linux server were migrated to the cloud, equivalent virtual machine services could be used from AWS, Microsoft Azure, and Google Cloud Platform.

| Cloud Provider            | Cloud Service          | Purpose                                                                         |
| ------------------------- | ---------------------- | ------------------------------------------------------------------------------- |
| **AWS**                   | Amazon EC2             | Provides virtual servers that can run Linux operating systems and applications. |
| **Microsoft Azure**       | Azure Virtual Machines | Provides configurable virtual machines capable of running Linux workloads.      |
| **Google Cloud Platform** | Compute Engine         | Provides virtual machines for running Linux applications and workloads.         |

### AWS – Amazon EC2

Amazon EC2 could host the Linux server as a virtual machine. The organization could select an appropriate instance configuration based on the server's CPU, memory, storage, and workload requirements.

### Microsoft Azure – Azure Virtual Machines

Azure Virtual Machines could host the Linux server using a Linux-compatible virtual machine configuration. CPU, memory, and storage resources can be selected according to the requirements of the workload.

### Google Cloud Platform – Compute Engine

Google Compute Engine could also host the Linux server as a virtual machine. The organization could configure the virtual machine with appropriate CPU, memory, disk, and Linux operating system resources.

## KillerCoda Evidence

The screenshots showing the Linux terminal commands and their results are included in the `Screenshots` folder of this repository.

The evidence includes the system information collected using:

```bash
cat /etc/os-release
lscpu
free -h
df -h
```
