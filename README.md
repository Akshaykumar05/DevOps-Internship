# DevOps-Internship at IoTIoT
This repo will contain internship related projects and content.

# Project-1: Linux Networking Firewall and Routing
* Firewall, Domain Name System (DNS), Load Balancing and QoS.
# Project-2: DevOps - Kubernetes Clustering
* Build and maintain cluster using kubernetes / docker / Linux HA to deploy applications on the cluster and ensure HA.
# Project-3: DevOps - Building a k3s cluster
* Building a cluster using lightweight kubernetes to optimise the server and improve performance.

## Project-1, Topic-1: Linux Networking Firewalls and Routing
### What is Firewall?
* A firewall is a network security system that monitors and controls the incoming and outgoing network traffic based on predetermined security rules. Firewalls act as barriers between a trusted internal network and an untrusted external network such as the internet. They are used to protect a network from unauthorized access, malware, and other network security threats.

### Need of Firewall
1. **Protection from external threats**: Firewalls can help to protect a network from external threats such as malware, hackers, and malicious software.
2. **Control access to a network**: Firewalls can be used to control access to a network by blocking or limiting certain types of traffic.
3. **Enforce security policies**: Firewalls can be used to enforce security policies such as requiring authentication for certain types of access or prohibiting the use of certain types of software.
4. **Improve network performance**: Firewalls can help to improve network performance by blocking traffic that is not needed, such as spam or other types of unwanted traffic.

Overall, firewalls are an important part of a defense-in-depth security strategy and can help to protect a network from external threats and enforce security policies.

### Features of Firewall

### Documentation on

1. What is Firewall? Why do we use firewall & features of firewall
1. How are all the features in firewall implemented

### Firewall
* A Firewall is a network security device that monitors and filters incoming and outgoing network traffic based on an organization's previously established security policies. At its most basic, a firewall is essentially the barrier that sits between a private internal network and the public Internet.

### Why do we use firewall
We use firewall because there are always new cybersecurity threats.which can impact both large companies and individuals. For every improved steps in cybersecurity take ten. And while you can always try to assess to website's safety, a firewall casts a much wider security net.

### Features of firewall
1. **Monitoring traffic**: A firewall works constantly to monitor your traffic based on specifically defined rules. Without a firewall acting as a security guard for your traffic, your network, devices, and personal data are exposed.
2. **Stopping online attacks**: While IT technicians work to secure data in a comapany's network and maintain a firewall's network security, pirates armed with malware and other threats seek to obtain that data and sell it a hefty sum. Without a firewall, it is easire for malware to slip through the cracks in the network.
3. **Preventing hacks and data loss**: IT technicians and antivirus software developers work around the clock to keep hackers from gaining access to private data. Without a firewall, your device, your data are left exposed. If cybercriminals get access, it can lead to leaked confidential data, fraud, or even identity theft.
4. **Improve network performance**: Firewalls can help to improve network performance by blocking traffic that is not needed, such as spam or other types of unwanted traffic.

### Implementation of Firewall in Linux:
* **Netfilter**: Netfilter is a framework provided by the Linux kernel that allows various networking-related operations to be implemented in the form of customized handlers.
* **iptables**: The iptables command is a powerful interface for your local Linux firewall. It provides thousands of network traffic management options through a simple syntax.
* **nftables**: nftables is a subsystem of the Linux kernel providing filtering and classification of network packets/datagrams/frames.
* **Uncomplicated Firewall (UFW)**: Uncomplicated Firewall (UFW) is a program for managing a netfilter firewall designed to be easy to use. It uses a command-line interface consisting of a small number of simple commands, and uses iptables for configuration.
* **Firewalld**: Firewalld can restrict access to services, ports, and networks. You can block specific subnets and IP addresses. As with any firewall, firewalld inspects all traffic traversing the various interfaces on your system.
* **Shorewall**: Shorewall is a gateway/firewall configuration tool for GNU/Linux. It is a higher-level firewall management utility that simplifies the process of configuring iptables rules.

### Iptables.
### Nftables.

## Topic-2: DNS
### Documentation on
1. Why do we use DNS & features of DNS
2. How are all the features in DNS implemented.

* **Domain Name System** (DNS) is a decentralized system that converts human-readable domain names into IP addresses, allowing computers to communicate with each other.
* DNS is essentially a translator between what people want and what a netWhy do we use firewall

We use firewall because there are always new cybersecurity threats.which can impact both large companies and individuals. For every improved steps in cybersecurity take ten. And while you can always try to assess to website's safety, a firewall casts a much wider security net.work needsto make that happen.
* The DNS servers store and manage the mapping of domain names to IP addresses, and respond to DNS queries from clients, such as web browsers.
* In the reverse direction, DNS can also translate an IP address into a fully qualified domain name (FQDN), using what's called a pointer (PTR) request (for a DNS PTR record) or "reverse lookup". This can be important to technical folks, but these requests are not as commonly seen by regular people running their browsers and other applications.

### BIND DNS server
### Dnsmasq DNS server

## Topic-3: LOAD BALANCING

### Documentation on
1. Why do we use Load balancer & features of Load balancer
2. How are all the features in Load balancer implemented in Linu
## Load Balancer
* Load balancing is the process of distributing a set of tasks over a set of resources, with the aim of making their overall processing more efficient. It acts as a reverse proxy and distributes network or application traffic across a number of servers. Load balancers are used to increase capacity (concurrent users) and reliability of applications.

## Why do we use Load Balancer?
* There are three important problem domains that load balancers were made to address: performance, availability, and economy.
* When scaling out or distributing the computational load, a load balancer can help distribute the workload among an array of servers, while also allowing capacity to be added or removed as necessary, which solves the issue of performance.
* Load balancer provides redundancy and automatic recovery mechanism, which solves the issue of availability.
* Load balancing also offers economic solutions. It’s cheaper and easier to add a small node to a pool than to upgrade and replace a large one, which solves the issue of economy.

## Features of Load Balancer
* Manages traffic spikes and prevents spikes on a single server
* Minimizes user request response time
* Ensures performance and reliability of computing resources, both physical and virtual
* Adds redundancy and resilience to computing environments
* Load balancing delivers the flexibility to add and remove servers as demand dictates.
* The ability to offload the encryption and decryption process from the servers i.e. SSL termination.
* The ability to cache frequently requested content.

![image](https://user-images.githubusercontent.com/114390890/229454291-0ec600d2-4bad-4a91-bc64-75b01abc8aa2.png)

## Load balancer implementation in Linux
* **Nginx**: Nginx is a well-liked reverse proxy and web server that may function as a load balancer. It offers excellent performance and scalability and supports a variety of load-balancing techniques, including IP hash and round-robin.

* **HAProxy** - HAProxy is a popular open-source load balancer and proxy server that supports TCP and HTTP-based protocols. HAProxy provides advanced features such as content-based routing, session persistence, health checking, and SSL acceleration.

* **Pound** - Pound is a lightweight and flexible reverse proxy and load balancer that supports HTTP and HTTPS protocols. Pound provides features such as URL rewriting, SSL offloading, and access control.

* **AWS Elastic Load Balancer** (ELB): AWS ELB is a load balancer offered by Amazon Web Services (AWS) that can be used to distribute traffic across multiple Amazon Elastic Compute Cloud (EC2) instances

## Topic:4- Quality of Servise (in Linux)
* Documentation on
1. Why do we use QOS & features of QOS
2. How are all the features in QOS implemented

* Quality of Service (QoS) is a way of managing and prioritizing network traffic to ensure that important data gets sent and received faster and more reliably than less important data.

### Why do we use QoS?
* Quality of Service (QoS) is a technology we used in computer networks to ensure that network resources are used optimally and that the most important network traffic is given priority over less important traffic. QoS is an important aspect of network management and is especially critical for large networks where many devices are competing for limited network resources.
* Using a QoS-enabled network, network administrators can prioritize different types of traffic based on their importance, assign specific amounts of bandwidth to specific types of traffic, and control the flow of traffic to reduce network congestion. This helps to ensure that the network provides a high quality of service to its users, even during periods of high demand.

### The Features of QoS are:
Classification of incoming traffic to traffic classes, based on attributes, including:

1. Device Configuration
2. Ingress interface
3. Packet content
4. Combination of these attributes

* **Traffic Classification**: Classifies each incoming packet as belonging to a specific traffic flow, based on the packet contents and/or the port. The classification is done by ACL (Access Control List), and only traffic that meets the ACL criteria is subject to CoS or QoS classification.

* **Assignment to Software Queues**: Assigns incoming packets to forwarding queues. Packets are sent to a particular queue for handling as a function of the traffic class to which they belong.

Other Traffic Class-Handling Attribute: Applies QoS mechanisms to various classes, including bandwidth management.

## How are all the features in QOS implemented
1. **Traffic prioritization**: Once traffic has been classified, QoS can prioritize certain types of traffic over others based on their importance or criticality. This can be done using methods such as Weighted Fair Queuing (WFQ) or Low Latency Queuing (LLQ)
2. **Traffic classification**: QoS begins with the classification of network traffic into different categories based on its type, source, destination, or other characteristics. This can be done using protocols such as Differentiated Services Code Point (DSCP) or Class of Service (CoS).
3. **Congestion management**: QoS can manage network congestion using methods such as Random Early Detection (RED) or Explicit Congestion Notification (ECN).
4. **Bandwidth management**: QoS can allocate and control bandwidth resources among different types of traffic using methods such as Class-Based Shaping (CBS) or Class-Based Policing (CBP).
5. **Policy-based management**: QoS provides policy-based management, allowing network administrators to define and enforce policies that govern how network resources are allocated and how traffic is managed.
6. **Latency and jitter control**: QoS can help reduce network latency and jitter using methods such as Priority Queuing (PQ) or Class-Based Weighted Fair Queuing (CBWFQ).

## How are all the features in QOS implemented
1. **Traffic prioritization**: Once traffic has been classified, QoS can prioritize certain types of traffic over others based on their importance or criticality. This can be done using methods such as Weighted Fair Queuing (WFQ) or Low Latency Queuing (LLQ)
2. **Traffic classification**: QoS begins with the classification of network traffic into different categories based on its type, source, destination, or other characteristics. This can be done using protocols such as Differentiated Services Code Point (DSCP) or Class of Service (CoS).
3. **Congestion management**: QoS can manage network congestion using methods such as Random Early Detection (RED) or Explicit Congestion Notification (ECN).
4. **Bandwidth management**: QoS can allocate and control bandwidth resources among different types of traffic using methods such as Class-Based Shaping (CBS) or Class-Based Policing (CBP).
5. **Policy-based management**: QoS provides policy-based management, allowing network administrators to define and enforce policies that govern how network resources are allocated and how traffic is managed.
6. **Latency and jitter control**: QoS can help reduce network latency and jitter using methods such as Priority Queuing (PQ) or Class-Based Weighted Fair Queuing (CBWFQ).

### Document your hands-on experience with setting up and configuring different load balancers in the issues
1. HA Proxy
2. Nginx
3. Traefik

# NIC Internship
## REDMINE
* OpenSource Project Management tool.
* It is written in Ruby language.
* It has no cost as its free.
* It is build in wiki and also supports community forums.
* It has option to upload with latest updates. Even you can publish any if you want.
* Multiple projects can be created and we can manage them in one tool.
* It provide the feature for the visual graps and charts which helps to visualise the projects progress.
* Has the provision to add roles and permissions.
* We can log the time that is spent on the bugs/issues.
* Provides the search funtionality when you want to look for some existing information.

## INODE number
* The inode (index node) is a data structure in a Unix-style file system that describes a file-system object such as a file or a directory. Each inode stores the attributes and disk block locations of the object's data.
* When a file is created on a system, a file name and Inode number is assigned to it. Generally, to access a file, a user uses the file name but internally file name is first mapped with respective Inode number stored in a table.
* **Note**: Inode doesn't contain the file name. Reason for this is to maintain hard-links for the files. When all the other information is separated from the file name then only we can have various file names pointing to the same Inode.

## IP Address, Private and Public
## Class of IPs
## ARP/MAC Address
## rwx- file and directories
## UGO -?

## Link: Hard link and Soft link (difference and work?)
## cat, less, more, grep (read difference)
## Linux booting (6 types)
## Prepare a chart of RHEL version (6 Vs 7 and 8 Vs 9)
## SUID and GUID (read permission)
## ls search its 10 commands with "-" with their use.

### 6 factors to follow in Corporate
1. Responsibilty
2. Communication Skills
3. Ability to learn
4. Research skills
5. Quality of work

