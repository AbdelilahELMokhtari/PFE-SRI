# PFE SRI (Computer Systems and Networks)
The main objective of this project is to provide an integrated solution that significantly enhances the security of a local network by combining the capabilities of an embedded system and the flexibility of custom scripts. Through this work, we aim to provide a robust architecture, advanced detection mechanisms, and a rapid response to security incidents to preserve the integrity, confidentiality, and availability of the data exchanged within the local network.

This project will explore different technologies, protocols, and methodologies related to network security, as well as best practices for securing embedded systems. The goal is to make a significant contribution to the security of local networks by proposing an integrated approach based on an embedded system and custom scripts. With this innovative solution, users of local networks can benefit from increased peace of mind, knowing that their infrastructure is protected against emerging threats and potential attacks.

# I) First Part
Focuses on the design and construction of a custom-built embedded system dedicated to enhancing the security of a local network (for Raspberry Pi 3 Model B).

## Steps
1) Cross-compiler
2) Bootloader
3) Kernel
4) File System
5) Setting up the System on an SD Card

# II) Second Part
DEVELOPMENT OF SCRIPTS

## TOOLS USED
1) Kali
2) Eve-ng
3) Python
## First Chosen Attack
### DHCP Starvation
DHCP starvation (or DHCP exhaustion) is an attack that aims to deplete the pool of available IP addresses on a Dynamic Host Configuration Protocol (DHCP) server. This attack is often carried out in local networks to prevent new devices from receiving a valid IP address, which can disrupt the normal operation of the network.

### Libraries Used for Detecting this Attack
Scapy: Network packet manipulation. It allows users to create, send, capture, and analyze network packets.
Threading: A programming technique that enables the execution of multiple threads (execution threads) in parallel within the same program.
Telnetlib: Allows establishing a Telnet connection with a remote server and interacting with it via the Telnet protocol.
Time: Provides functions for working with time and dates.

## Second Chosen Attack
### MAC Flooding
The goal of MAC flooding is to disrupt the MAC Table. In a typical MAC flooding attack, the attacker sends a large number of Ethernet frames. When sending numerous Ethernet frames to the switch, these frames will have different source addresses. The intention of the attacker is to consume the switch's memory used to store the MAC address table. Legitimate users' MAC addresses will be removed from the MAC Table. Now, the switch can no longer route incoming data to the destination system. Thus, a significant number of incoming frames will be broadcasted to all ports.

### For more details, please refer to the report.
