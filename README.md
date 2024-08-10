# Taskfive
Nmap scanning of ports of metasploitable

# OVERVIEW 

In this repository , a port scan on the Metasploitable virtual machine with the IP address 10.0.2.5 using Kali Linux has been done. This scan helps identify open ports and active services, providing insights into potential vulnerabilities.

# NMAP SCAN DETAILS

The Nmap scan was conducted using this command

sudo nmap -n -p- -sV 10.0.2.5 -oN nmap.txt

sudo: Runs the command with superuser privileges, necessary for certain types of scans.

nmap: The network scanning tool.

-n: Disables DNS resolution to speed up the scan by skipping the hostname resolution step.

-p-: Scans all 65,535 TCP ports on the target machine.

-sV: Enables service version detection, allowing Nmap to determine the versions of the services running on the open ports.

10.0.2.5: The IP address of the target machine (your Metasploitable VM).

-oN nmap.txt: Saves the scan results in a file named nmap.txt in a human-readable format.

# FILES

nmap.txt : Contains the result of the scan.

# INSTRUCTIONS

1.Clone this repository to your local machine.

git clone https://github.com/Athulya2002/Taskfive.git

2.Navigate to the repository

cd Taskfive

3.Open nmap.txt to view the scan reults

cat nmap.txt
