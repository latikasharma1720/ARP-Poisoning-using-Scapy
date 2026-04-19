ARP Poisoning Simulation using Scapy

This project demonstrates an ARP (Address Resolution Protocol) poisoning attack using Python and the Scapy library. It showcases how an attacker can manipulate ARP tables within a local network to intercept communication between a victim machine and the gateway.

The goal of this project is to understand how Man-in-the-Middle (MITM) attacks work at the network layer and highlight the importance of securing local network communications.

Understand the working of ARP in local networks
Simulate ARP spoofing/poisoning attacks
Demonstrate how traffic can be intercepted
Analyze the impact of MITM attacks on network security

How It Works

The attacker sends spoofed ARP responses to the victim and gateway
The victim’s ARP table gets updated with the attacker’s MAC address
Network traffic is redirected through the attacker system
This allows interception or manipulation of data

The project demonstrates how communication between a local system and gateway can be manipulated within a network environment .

Tech Stack

Python
Scapy (Packet Manipulation Library)
Networking Concepts (ARP, TCP/IP)

Key Concepts Learnt:

ARP Protocol & ARP Table
ARP Spoofing / Poisoning
Man-in-the-Middle (MITM) Attack
Packet Manipulation & Network Interception

It is intended to demonstrate network security concepts and should only be used in controlled environments.
