# TCP SYN Flood Lab

## Description

Network security laboratory focused on the implementation and analysis of a TCP SYN Flood attack using Kali Linux in a controlled environment.

The project simulates a Denial of Service (DoS) attack against an Apache server and analyzes the network traffic using security tools.

## Objective

Understand how TCP SYN Flood attacks work, how they affect servers and how to detect and mitigate them through network analysis.

## Attack Implemented

TCP SYN Flood

This attack exploits the TCP three-way handshake by sending a large number of SYN packets without completing the connection, causing the server to consume resources and become unavailable.

## Tools Used

* Kali Linux
* hping3
* Wireshark
* Apache Server
* Linux Networking Tools

## Laboratory Environment

* Attacker: Kali Linux
* Victim: Apache Server
* Controlled virtual network
* Traffic monitoring with Wireshark

## Process

1. Configure Apache server as victim
2. Verify network connectivity
3. Launch SYN Flood attack using hping3
4. Capture traffic with Wireshark
5. Analyze TCP packets and SYN requests
6. Observe server behavior under attack
7. Study mitigation techniques

## Attack Command Example

```bash
sudo hping3 -S --flood -p 80 <target-ip>
```

## Traffic Analysis

Wireshark is used to monitor:

* SYN packets
* TCP connections
* Network traffic behavior
* Server response

## Impact

* Server resource exhaustion
* Connection saturation
* Possible denial of service
* Network congestion

## Mitigation

* Firewall rules
* SYN cookies
* Rate limiting
* Intrusion detection systems
* Traffic filtering

## Educational Purpose

This project was developed for educational and cybersecurity learning purposes in a controlled environment.

## Author

Persfone
Technical Informatics Graduate - UNR
