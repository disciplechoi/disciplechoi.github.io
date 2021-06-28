---
layout: post
title:  "Basic Network for Cloud computer System 클라우드 네트워크 기초(2) - LAN"
date:   2021-06-22 10:45:09 +0900
categories: network
---


I've just started taking a network course in Udemy since I realized that I am sooo bad at networking -_______-
This post is referenced to IT Networking Fundamentals For Complete Biginners, Udemy
If you guys want to look at it, here is the link!
[Full link](https://www.udemy.com/course/it-networking-fundamentals/learn/lecture/7307090#notes)


## 1. What Is A Local Area Network?
### 1.1 Network Configuration
* Peer-to-Peer
* Server based

<br/><br/><br/><br/>

### 1.2 Peer-to-Peer Network
* Nodes provide and request services
* User in each node administers resources
* No extra investment
* Easy to setup
* Very weak security
* Additional load on nodes

<br/><br/><br/><br/>

### 1.3 Server Based Network
* Designated computer to administer
* Resources centralized
* Supports larger networks
* Strong security
* Expensive

<br/><br/><br/><br/>

### 1.4 Benefits
Advantages of peer-to-peero networks
* Low cost
* Simple to configure
* User has full accessibility of the computer

Disadvantages of peer-to-peer networks:
* May have duplication in rescurces
* Difficult to uphold security policy
* Difficult to handle uneven loading

Where peer-to-peer network is appropriate:
* 10 or less users
* No specialized service required
* Security is not an issue
* Only limited growth in the foreseeable future

<br/><br/><br/><br/>

### 1.5 Local Area Network(LAN)
A Local Area Network(LAN) is group of computers confined to a small geographic area, such as a single building

A LAN is a group fo computers or devices that share a common communication medium, such as cables or wireless connections

<br/><br/><br/><br/>

### 1.6 Structure of LAN
* LAN is a network which is designed to operate over a small physical area such as an office, factory or a group of buildings
* LAN's are easy to design and troubleshoot
* Exchange of information and sharing of resources becomes easy because of LAN
* In LAN all machines are connected to a single cable
* It is usually a privately owned network

<br/><br/><br/><br/>

### 1.7 Additional Classification
* LAN 
* WAN
* MAN
* CAN

<br/><br/><br/><br/>

## 2. Network Topologies
### 2.1 What Is A Network Topology?
* A network topology is the pattern in which nodes(i.e., computers, printers, routers or other devices) are connected to a local area network(LAN) or other network via links
* There are four prinipal topologies used in LANs : bus, ring, star and mesh

<br/><br/><br/><br/>

### 2.2. Types Of Topologies
* Bus
Takes less cable(cheaper) / Break in the bus, network is down
* Mesh
Break in the cable, network still works(fault tolerant) / Expensive and complex(hard to reconfigure)
* Ring
Easy to install / Expensive parts
* Star
Easy to install, most common, break in worstatio cable network / More expensive than bus

<br/><br/><br/><br/>

### 2.3. Bus Topology
A linear bus topology consists of a main run of cable with a terminator at each end All nodes (file server, workstations, and peripherals) are connected to the linear cable

<br/><br/><br/><br/>

### 2.4. Adavantages And Disadvantages of Bus Topology
Advantages of a Linear Bus Topology
* Easy to connect a computer or peripheral to a linear bus
* Requires less cable length than a star topology

Disadvantages of a Linear Bus Topology
* Entire network shuts down if there is a break in the main cable
* Terminators are requried at both ends of the backbone cable
* Difficult to identify the proble if the entire network shuts down
* Not meant be used as a stand-alone solution in a large building

<br/><br/><br/><br/>

### 2.5. Adavantages And Disadvantages of Star Topology
Advantages of a Star Topology
* Easy to install and wire
* No disruptions to the network when connecting or removing devieces
* Easy to detect faults and to remove parts

Didsadvantages of a Star Topology
* Requires more cable length than a linear topology
* If the hub, switch, or concentrator fails, nodes attached are disabled
* More expensive than linear bus topologies because fo the cost of the hubs etc

<br/><br/><br/><br/>

### 2.6. Some Considerations
* Money : A linear bus network may be the least expensive way to install a network; you do not have to purchase concentrators
* Length of cable needed : The linear bus network uses shorter lengths of cable
* Future growth : With a star topology, expanding a network is easily done by adding another concetrator
* Cable type : The most common cable in schools is unshielded twisted pair, which is most often used with start topologies

<br/><br/><br/><br/>

### 2.7. Ethernet
* A system for connecting a number of computer systems to form a local area network, with protocols to control the passing of information and to avoid simultaneous transmission by two or more systems
* Ethernet is the most widely used local area network(LAN) technology, that defines wiring and signaling standards for the physical layer of TCP/IP





