# Nmap-Project
![Nmap-1](https://github.com/sajerestan1/Nmap/assets/53940361/364e9bfe-9416-41e6-b41f-7a1724b9e6f4)

Project Title: LAN Connection Establishment and Device Enumeration
Objective

In this project, I successfully established a connection to a local area network (LAN) via Wi-Fi and utilized the NMAP tool to determine the number of devices currently connected to the LAN.
Skills Applied

    Proficiency in establishing Wi-Fi connections.
    Familiarity with network scanning tools like NMAP.
    Ability to interpret and analyze network scan results.

Tools Used

    NMAP for network scanning.

Steps
![Nmap-2](https://github.com/sajerestan1/Nmap/assets/53940361/7aff1b78-9be9-4783-8adf-05761f68a7a3)
Step 1: Establish LAN Connection via Wi-Fi

I connected to the local area network (LAN) using Wi-Fi. This step involved accessing the network settings on my device and selecting the appropriate Wi-Fi network.
Step 2: Determine Number of Connected Devices Using NMAP

I utilized the NMAP tool to scan the LAN and determine the number of devices currently connected to it. Below is the specific command I used for this task:

bash

nmap -sn <LAN_IP_range>

![Nmap-3](https://github.com/sajerestan1/Nmap/assets/53940361/92fda1fb-b345-4d5b-b59b-3d040f2b5479)


This command performs a ping scan (-sn) on the specified LAN IP range to discover live hosts/devices.

Step 3: Results

Here is a screenshot of my terminal showing the results of the NMAP scan:
![Nmap-4](https://github.com/sajerestan1/Nmap/assets/53940361/a1efb2a2-2b3e-4a0c-82ef-a746711f898f)



Conclusion

By establishing a connection to the LAN via Wi-Fi and utilizing the NMAP tool for network scanning, I successfully determined the number of devices currently connected to the LAN. This project enhanced my understanding of network scanning techniques and their application in monitoring network activity.
