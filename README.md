# Firewall Exploration - Network Security Scenarios

## Overview

This repository contains a set of exercises focused on firewall configuration and network security, conducted as part of the **Advanced Network and Internet Security** course at the New York Institute of Technology (NYIT), Vancouver, Canada. The exercises aim to explore the impact of different firewall settings on network traffic, security, and the ability to block various types of attacks.

## Scenarios

The exercises cover three main scenarios:

1. **No Firewall**: Observing how traffic flows and identifying vulnerabilities in a network without firewall protection.
2. **Perimeter Firewall**: Introducing a perimeter firewall to secure the network and analyzing its effectiveness.
3. **Workstation Database Scenario**: Configuring firewall rules to protect a database from active attacks while allowing legitimate traffic.

Each scenario is documented with a description, the firewall rules used, and the results observed.

## How to Use

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/firewall-exploration.git
    ```
2. **Navigate through the scenarios** to understand how different firewall rules impact network security (for this use the lab manual attached here).

## Scenario Descriptions

- **No Firewall:** 
    - This scenario demonstrates the vulnerability of a network without any firewall protection, where traffic freely flows and can easily be compromised by malicious attacks.
  
- **Perimeter Firewall:**
    - A perimeter firewall is introduced to observe its effect on blocking unauthorized access and preventing various attacks. The scenario focuses on configuring firewall rules to secure the network.

- **Workstation Database Scenario:**
    - In this scenario, firewall rules are created to prevent attacks on a database server while allowing necessary traffic. The scenario demonstrates how specific rules can block malicious traffic while permitting legitimate communication.

## Results

- **No Firewall:** Vulnerabilities are exposed, and the network is compromised by OS exploits.
- **Perimeter Firewall:** The firewall blocks malicious traffic, securing the network, but requires additional rules to allow legitimate communication.
- **Workstation Database Scenario:** Firewall rules effectively block specific attacks while permitting necessary traffic between workstations and the database server.

## Conclusion

These exercises highlight the importance of proper firewall configuration in network security. By exploring different scenarios, users can gain a better understanding of how to create and apply effective firewall rules to protect networks from various threats.

## Tools

The `FirewallWorkstationDataFile.dat` file used in the exercises can be found in this repository along with the tool 'Firewall Virtualization Tool' exe installation file.