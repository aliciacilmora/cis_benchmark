# CIS Benchmark Audit System

## Overview

This project provides an audit system for various operating systems based on the CIS (Center for Internet Security) benchmarks. It checks for compliance with the security configurations recommended by CIS, ensuring a secure and hardened environment for your systems. Currently, the audit system supports:

* Linux
* OpenBSD
* Solaris
* Ubuntu
* Ubuntu Server

<h2 align="center">
  Video explanation: https://youtu.be/vCxzgJkzA6Y
</h2>

The audit covers all critical aspects as specified in the CIS benchmarks, such as user access, file permissions, network configurations, and more.

## How It Works

The system performs checks based on the specific CIS benchmarks for each platform. The checks cover a wide range of security measures, including but not limited to:

* File and directory permissions
* User and group policies
* Network configurations
* Software updates and patches
* Service configurations
* Logging and monitoring settings

Each check corresponds to a specific section in the CIS benchmark document, ensuring complete compliance with the guidelines.

## Setup

### Prerequisites:

- Supported OS: Linux, OpenBSD, Solaris, Ubuntu, Ubuntu Server
- Dependencies:
i. Shell scripting tools (e.g., bash, sh)
ii. Access to system-level configurations (root access may be required for some checks)


### Installation:

- Clone the repository:
```
git clone https://github.com/aliciacilmora/cis_benchmark.git
```

- Make the audit script executable:
```
chmod +x checkcisbenchmark.sh
```

- Run the audit script:
```
./checkcisbenchmark.sh          # non sudo mode
sudo ./checkcisbenchmark.sh     # sudo mode
```
