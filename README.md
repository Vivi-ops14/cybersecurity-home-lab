\# Cybersecurity Home Lab



A hands-on cybersecurity home lab built in an Ubuntu virtual machine to practice network scanning, service enumeration, firewall configuration, and authorized security testing in a controlled environment.



\## Project Overview



This project demonstrates the setup and testing of a basic Linux security environment using Oracle VirtualBox and Ubuntu. I configured network services, analyzed exposed ports with Nmap, implemented firewall rules with UFW, and verified how firewall changes affected network accessibility.



\## Tools Used



\- Ubuntu 24.04 LTS

\- Oracle VirtualBox

\- Nmap

\- UFW Firewall

\- OpenSSH

\- Python HTTP Server



\## Lab Activities



\- Created and configured an Ubuntu virtual machine in VirtualBox.

\- Identified the VM's network interface and IP address.

\- Used Nmap to scan for open ports and enumerate running services.

\- Installed and enabled OpenSSH to create an SSH service on TCP port 22.

\- Configured UFW with a default-deny incoming policy.

\- Created firewall rules to permit selected network services.

\- Started a Python HTTP server on TCP port 8080 as an authorized test service.

\- Used Nmap before and after firewall changes to verify port accessibility.

\- Accessed the HTTP server through Firefox to confirm the service was reachable.

\- Saved scan results and firewall configuration as project evidence.



\## Key Findings



Nmap identified SSH on port 22 and the Python HTTP server on port 8080 when the services were available. Firewall rules were then modified with UFW to demonstrate how access to a network service can be permitted or restricted. Repeated scans were used to verify the configuration changes.



\## Screenshots



The Screenshots folder contains evidence from the lab, including:



1\. Initial service scan before firewall hardening

2\. UFW firewall configuration

3\. Network interface and Nmap testing

4\. HTTP directory listing demonstrating the test server

5\. Authorized testing page accessed through Firefox

6\. Nmap service and version detection



\## Files



\- `nmap-scan.txt` - Saved Nmap service/version scan results

\- `firewall-status.txt` - Saved UFW firewall configuration

\- `index.html` - Test webpage hosted by the Python HTTP server

\- `Screenshots/` - Screenshots documenting the lab



\## Security Notice



All scanning and testing in this project was performed within my own controlled virtual lab environment for educational purposes.

## Lab Evidence

### Nmap Service Detection
![Nmap service detection](Screenshots/6-%20nmap%20service%20detection.png)

### Firewall Configuration
![Firewall enabled](Screenshots/2-%20firewall%20enabled.png)

### Network Interface Scan
![Network interface scan](Screenshots/3-%20network%20interface%20scan.png)

### Authorized Testing Environment
![Authorized testing environment](Screenshots/5-%20firefox%20authorized%20testing%20environment.png)

### Firewall Hardening Comparison
![Before firewall hardening](Screenshots/1-%20before%20firewall%20hardening.png)

### HTTP Directory Listing
![HTTP directory listing](Screenshots/4-%20insecure%20directory%20listing.png)
