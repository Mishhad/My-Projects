# Enterprise Network Design Project

## 📌 Overview

This project demonstrates the design and implementation of a small enterprise network using VLANs, inter-VLAN routing, and DHCP configuration in Cisco Packet Tracer.

## 🧠 Objectives

* Segment network using VLANs (HR, Finance, IT)
* Enable communication between VLANs
* Automate IP assignment using DHCP
* Simulate a real-world office network

## 🏗️ Network Design

* 1 Router (Router-on-a-Stick configuration)
* 1 Switch
* 3 PCs (Different departments)

## 🔧 Technologies Used

* VLAN Configuration
* Trunking
* Inter-VLAN Routing
* DHCP
* Ping (Connectivity Testing)

## 🌐 VLAN Details

| VLAN | Department | Network         |
| ---- | ---------- | --------------- |
| 10   | HR         | 192.168.10.0/24 |
| 20   | Finance    | 192.168.20.0/24 |
| 30   | IT         | 192.168.30.0/24 |

## ⚙️ Key Configurations

### Router (Subinterfaces)

* G0/0.10 → 192.168.10.1
* G0/0.20 → 192.168.20.1
* G0/0.30 → 192.168.30.1

### DHCP

* Automatic IP assignment for all VLANs

## 🧪 Testing

* Successfully tested communication between all VLANs using ping

## 🏢 Real-World Relevance

This project simulates how enterprise networks separate departments using VLANs while allowing controlled communication via routing.

## 📁 Files

* enterprise-network-design.pkt

## 👤 Author

Mishhad V V
