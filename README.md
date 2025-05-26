# Task 1 - Network Port Scanning (Cyber Security Internship)

## What I Did

I used **Nmap** on **Kali Linux (in VirtualBox)** to scan my local network and find open ports on devices. This helps to understand what services are running and how exposed a network is.

## Tool Used

- **Nmap** (Network scanning tool)

## Command I Used

```bash
sudo nmap --privileged -sS -oN open_ports_report.txt 10.0.2.15/24

This command performs a TCP SYN scan on the local network range 10.0.2.15/24 and saves the result in a file.

What I Found
One host is up: 10.0.2.2

Open ports found on it:

135 (msrpc)

139 (netbios-ssn)

445 (microsoft-ds)

902 (iss)

5357, 8080, and some high ports (49152–49157)

These ports show what services are running on the device.


What I Learned
How to use Nmap for scanning

How to read open ports and understand what services they might be running

Basic idea of network exposure and port-based security
