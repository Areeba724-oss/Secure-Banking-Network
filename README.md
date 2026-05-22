# Secure-Banking-Network

## Overview

This project is a **Secure Digital Banking Infrastructure Simulation** developed using Cisco Packet Tracer.
The system demonstrates secure communication between different banking departments through VLANs, subnetting, routing, and server connectivity.

The project simulates how a real banking network securely handles communication between:

* Accounts Section
* Reception Section
* Banking Servers
* Customer/Branch PCs

## Objectives

* Design a hierarchical banking network
* Implement VLAN-based departmental isolation
* Configure secure routing between subnets
* Simulate banking server communication
* Test network connectivity using ping
* Apply basic network security measures

## Technologies Used

* Cisco Packet Tracer
* VLAN Configuration
* Subnetting
* Router Configuration
* Access Control Lists (ACLs)
* Network Security Concepts

## Network Architecture

### Management Zone

* Account Section (VLAN 20)
* Reception Section (VLAN 10)

### Server Zone

* Banking Server
* Database/Web Servers

### Public/Customer Zone

* Branch PCs for customer access

## Features

* VLAN Segmentation
* Inter-VLAN Routing
* Secure Router Authentication
* Ping Connectivity Testing
* IP Address Configuration
* ACL-based Security
* Firewall Simulation

## IP Addressing Example

| Department        | IP Range        |
| ----------------- | --------------- |
| Accounts Section  | 192.1.1.0/24    |
| Reception Section | 192.168.10.0/24 |
| Branch Network    | 192.168.10.0/24 |

## Connectivity Testing

The following tests were successfully performed:

* Branch PC → Accounts PC
* Accounts PC → Branch PC
* Reception PC → Branch PC
* PCs → Banking Server

## Security Measures

* VLAN Tagging
* Access Control Lists (ACLs)
* Secure Router Login Authentication
* Enable Secret Password
* Firewall Rule Simulation

## Router Security Configuration

The router was secured using:

* Local username authentication
* Privileged EXEC password
* Saved startup configuration

## Working Mechanism

1. Router manages communication between VLANs
2. Client PCs send requests to Banking Server
3. Server verifies access permissions
4. Secure response is returned to users

## Conclusion

This project demonstrates how networking and security concepts can be integrated to build a secure banking infrastructure. Proper VLAN segmentation, routing, and access policies help protect sensitive banking data from unauthorized access.


## How to Run

1. Open the `.pkt` file in Cisco Packet Tracer
2. Start the network simulation
3. Verify IP configurations
4. Test connectivity using ping commands
