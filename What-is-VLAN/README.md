# What is VLAN?

A beginner-friendly introduction to **Virtual Local Area Networks (VLANs)** and one of the fundamental concepts in modern computer networking.

This repository contains the second article in my **Networking Fundamentals Series**, focusing on the theory and concepts behind VLANs before moving into practical configuration and hands-on labs.

## 📖 About This Article

In a traditional flat network, all devices may share the same broadcast domain. As a network grows, this can lead to increased broadcast traffic, more complicated management, and security concerns.

VLANs solve these problems by allowing a single physical switch to be logically divided into multiple separate networks.

For example:

* **VLAN 10** → Sales
* **VLAN 20** → Finance
* **VLAN 30** → IT

Although these departments may use the same physical switch, each VLAN operates as a separate logical network.

## 🧠 What You'll Learn

This article covers:

* What a VLAN is
* Why VLANs are needed
* Problems with traditional flat networks
* How VLAN segmentation works
* VLAN IDs
* Access Ports
* Trunk Ports
* IEEE 802.1Q
* Broadcast domains
* Communication between VLANs
* Advantages of VLANs
* Real-world VLAN use cases

## 🔌 Access Ports vs Trunk Ports

### Access Port

An access port belongs to a single VLAN and is typically used to connect end devices such as:

* Computers
* Printers
* IP Phones

### Trunk Port

A trunk port can carry traffic from multiple VLANs over a single physical connection.

Trunking is commonly used between switches and relies on the **IEEE 802.1Q** standard for VLAN tagging.

## 🔐 Why VLANs Matter

VLANs provide several important benefits:

* **Improved security** through logical network isolation
* **Reduced broadcast traffic**
* **Simpler network management**
* **Better scalability**
* **More efficient use of physical infrastructure**

VLANs are widely used in environments such as:

* Enterprise networks
* Universities
* Hospitals
* Hotels
* Data centers

## 📄 Article

The complete article is available as a PDF:

**[What is VLAN?](What-is-VLAN.pdf)**

## 🧪 What's Next?

This article focuses on the **conceptual side of VLANs**.

In the next part of the series, I will move from theory to practice by building a VLAN lab in **Cisco Packet Tracer** and configuring VLANs step by step.

## 📚 Networking Fundamentals Series

**Article 02 — What is VLAN?**

This project is part of my personal networking learning journey, where I study networking concepts, build practical labs, document what I learn, and continuously improve my technical skills.

More networking articles and hands-on labs will be added over time.

**Author:** Omid Noory
**Category:** Networking Fundamentals
**Level:** Beginner
**Last Updated:** July 2026
