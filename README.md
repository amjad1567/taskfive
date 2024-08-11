# taskfive
# Task Five: Comprehensive Nmap Scan

## Overview
This repository contains the results of a comprehensive Nmap scan performed on the Metasploitable target machine with the IP address `10.0.2.4`. The scan covers all possible ports to provide a complete overview of the open ports and services running on the target.

## Nmap Scan Details
The Nmap scan was conducted using the following command:

```bash
nmap -p- 10.0.2.4 -oN scan_results.txt
-p- specifies that all 65,535 ports should be scanned.
10.0.2.4 is the IP address of the Metasploitable target machine.
-oN portscan_results.txt saves the scan output in a file named scan_results.txt.
Files
scan_results.txt: Contains the results of the Nmap scan. This file lists all open ports and services found on the target machine.
Instructions
Clone this repository to your local machine:
git clone https://github.com/Amjad1567/taskfive.git
Navigate into the repository directory:
cd taskfive
Open scan_results.txt to view the Nmap scan results:
cat portscan_results.txt
cat portscan_results.txt

