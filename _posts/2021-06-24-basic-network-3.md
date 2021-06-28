---
layout: post
title:  "Basic Network for Cloud computer System 클라우드 네트워크 기초(3) - IP"
date:   2021-06-24 11:04:09 +0900
categories: network
---

I've just started taking a network course in Udemy since I realized that I am sooo bad at networking -_______-
This post is referenced to IT Networking Fundamentals For Complete Biginners, Udemy
If you guys want to look at it, here is the link!
[Full link](https://www.udemy.com/course/it-networking-fundamentals/learn/lecture/7307090#notes)


## 1. IP Address
### 1.1 What is An IP Address?
* Internet Protocol Address (or IP Address) is an unique address that computing devices such as personal computers, tablets, and smartphones use to identify itself and communicate with other devices in the IP network
* Any device connected to the IP network must have an unique IP address within the network

<br/><br/><br/><br/>

### 1.2 Private Or Public IP Address
* An IP address can be private - for use on a local area network(LAN), or public - for use on the Internet or other wide area network(WAN)
* IP addresses can be determinded statically(assigned to a computer by a system administrator) or dynamically (assigned by another device on the network on demand)

<br/><br/><br/><br/>

### 1.3 Example
* An IP address is formatted as a series of four values separated by periods:
* 192.168.0.1
* Each value ranges from 0 through 255
* The IP adderess assigned to your PC on a network is a local address
* Local IP addresses start with 192.168 and 10.0.

<br/><br/><br/><br/>

### 1.4 TCP/IP
* IP is often prefixed by the acronym TCP, as in TCP/IP. The TCP part stands for Transfer Control Protocol : It's simply a set of rules for transmitting information on a network
* Technically, TCP/IP refers to the methods and engineering as oppsed to a specific address or value

<br/><br/><br/><br/>

### 1.5 IP Classes
* The internet community originally defined five address classes to acommodate networks of varying sizes.
* Microsoft TCP/IP supports class A, B, and C address assigned to hosts
* The class of address defines which bits are used for the network ID and which bits are used for the host ID
* It also defines the possible number of networks and the number of hosts per network

<br/><br/><br/><br/>

### 1.6 Class A
* Class A addresses are assigned to networks with a very large number of hosts.
* The high-order bit in a class A address is alwyas set to zero
* The next seven bits(completing the first octet) complete the network ID. The remaining 24 bits(the last three octets) represent the host ID
* This allows for 126 networks and 16,777,214 hosts per network

<br/><br/><br/><br/>

### 1.7 Class B
* Class B addresses are assigned to medium-sized to large-sized networks. The two high-order bits in a class B address are always set to binary 10
* The next 14 bits(completing the first two octets) complete the network ID. The remaining 16 bits(last two octets) represne the host ID
* This allows for 16,384 networks and 65,534 hosts per network

<br/><br/><br/><br/>

### 1.8 Class C
* Class C address are used for small networks. The three high-order bits in a class C address are always set to bianry 1 1 0
* The next 21 bits(completing the first three octets) complete the network ID
* The remaining 8 bits(last octet) represent the host ID. This allows for 2,097,152 networks and 254 hosts per network


![network class](https://t1.daumcdn.net/cfile/tistory/99068D495BE8101D34)

