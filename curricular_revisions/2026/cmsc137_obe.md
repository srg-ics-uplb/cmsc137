# Curricular Proposal for the BS Computer Science

| CC endorsement date | UC endorsement date | ANNEX __ PAGE __ |
|---------------------|---------------------|------------------|
|                     |                     |                  |

**Version:** ____

---

## PROPOSAL FOR THE REVISION OF

# CMSC 137: DATA COMMUNICATIONS AND NETWORKING

---

## A. Course Catalogue Description

| Field | Details |
|-------|---------|
| **Course Number** | CMSC 137 |
| **Course Title** | Data Communications and Networking |
| **Course Description** | Basic principles of data communications; design issues and protocols in the layers of data network; networks for various applications. |
| **Prerequisite** | CMSC 125 |
| **Semester Offered** | 2nd |
| **Course Credit** | 3 units |
| **Number of Hours** | 5 hours/week (2 class, 3 lab) |
| **Course Goal/s** | To introduce students to data communications and networking concepts; enabling them to design, implement, and analyze network-enabled applications and administer basic network environments. |

---

## B. Rationale

Data Communications and Networking is a foundational course in the BS Computer Science curriculum that equips students with the knowledge and skills needed to understand how data is transmitted across networks. As computing becomes increasingly networked and distributed, a thorough understanding of communication protocols, network architectures, and security principles is indispensable. This course bridges theory and practice through hands-on laboratory work with real networking tools and protocols.

---

## C. Course Outline

### 1. Course Outcomes (CO)

Upon completing the course, students must be able to:

- **CO 1.** Explain how data is transmitted over communication channels;
- **CO 2.** Identify and describe the different layers of the OSI reference model and TCP/IP protocol suite, including the protocols available for each layer;
- **CO 3.** Describe how different architectures of Local Area Networks and Internetworks operate, together with the services they provide;
- **CO 4.** Protect and secure data in networked environments;
- **CO 5.** Develop network-enabled applications using a high-level programming language; and
- **CO 6.** Perform basic network administration.

---

### 1.1 Course Outcomes and Relationship to Program Learning Outcomes

| Course Outcomes | A | B | C | D | E | F | G |
|-----------------|---|---|---|---|---|---|---|
| CO 1. Explain how data is transmitted over communication channels. | D | D | R | R | R | D | R |
| CO 2. Identify and describe the different layers of the OSI reference model and TCP/IP protocol suite. | D | D | R | R | R | D | R |
| CO 3. Describe how different architectures of Local Area Networks and Internetworks operate. | D | D | R | R | R | D | R |
| CO 4. Protect and secure data in networked environments. | D | D | R | R | R | D | R |
| CO 5. Develop network-enabled applications using a high-level programming language. | D | D | R | R | R | D | D |
| CO 6. Perform basic network administration. | D | D | R | R | R | D | R |

> **Legend:** I – Introduced; D – Demonstrated; R – Reinforced

#### *Program Learning Outcomes*

A. Analyze complex computing problems by applying principles of computing and other relevant disciplines to identify solutions;  
B. Apply computer science theory concepts and software development fundamentals to produce computing-based solutions;  
C. Communicate effectively in a variety of professional contexts;  
D. Formulate informed judgments in computing practice based on legal, ethical principles, and professional responsibilities;  
E. Function effectively as a member or leader of a team engaged in activities appropriate to the program's discipline;  
F. Design, implement, and evaluate computing-based solutions to meet a given set of computing requirements in the context of the program's discipline;  
G. Lead with honor and excellence in public service and in fields of practice.

---

### 2. Course Content

#### Lecture Topics

| Lecture Topics | Number of hours for in-class work |
|----------------|:---------------------------------:|
| NC-Fundamentals: Data Communications and Computer Networks Overview | 2 |
| NC-Fundamentals: Physical Layer – Signals and Performance | 2 |
| NC-Fundamentals: Physical Layer – Digital and Analog Transmission | 2 |
| NC-Fundamentals: Physical Layer – Bandwidth Utilization, Transmission Media, Switching | 2 |
| NC-Single Hop Communication: Data Link Layer, Data Link Control, HDLC and PPP | 2 |
| NC-Single Hop Communication: Media Access Control, Wired LAN (Ethernet) | 2 |
| NC-Single Hop Communication: Wireless LAN (IEEE 802.11, Bluetooth) | 2 |
| **(MIDTERM EXAM)** | 2 |
| NC-Routing and Forwarding: Network Layer – Addressing, IP | 2 |
| NC-Routing and Forwarding: Network Layer – IP Support Protocols, Routing and Forwarding | 2 |
| NC-Reliable Support: Transport Layer Protocols (TCP, UDP) | 2 |
| NC-Networked Applications: Application Layer – DNS, Email (SMTP/POP/IMAP) | 2 |
| NC-Network Security / NC-Mobility: Software Defined Networks, Other Wireless Networks | 2 |
| NC-Emerging Topics: Peer-to-Peer Networks | 2 |
| **(FINAL EXAM)** | 2 |
| **Total Number of Lecture Hours** | **30** |

#### Laboratory Topics

| Laboratory Topics | Number of hours for in-class work |
|-------------------|:---------------------------------:|
| Configuring a Linux Box for TCP/IP | 3 |
| Network Design: Wiring and Patch Cables | 3 |
| Packet Analysis (Wireshark) | 3 |
| Subnet Calculations | 3 |
| IP Routing | 3 |
| Socket Programming 1 | 3 |
| Socket Programming 2 | 3 |
| DNS and BIND9 | 3 |
| SSH and GPG | 3 |
| Network Emulation and Software Defined Networks | 3 |
| Project | 15 |
| **Total Number of Laboratory Hours** | **45** |

---

### 3. Course Coverage

#### Lecture

| Week | Learning outcome/s | Course Topic | Essential or Key Questions | Suggested Teaching and Learning Activities | Suggested Assessment Tools/Activities | Core Readings/Learning Resources |
|------|--------------------|--------------|----------------------------|--------------------------------------------|---------------------------------------|----------------------------------|
| 1 | Understand course structure, expectations, and grading. | Course Overview and Administrative Matters | What are the goals and expectations for this course? | Lecture | — | Course Syllabus |
| 2 | Describe the components of a data communication system. Compare the OSI and TCP/IP models. | Data Communications and Computer Networks Overview; TCP/IP Protocol Suite; OSI Reference Model | How is data communicated across networks? How do OSI and TCP/IP models relate to each other? | Lecture; Demonstrating samples | Quiz; Recitation | FOR Ch. 1–2; Lecture Slides |
| 3 | Explain signal types, performance metrics, and the limits of data transmission. | Physical Layer: Signals and Performance | What is the difference between analog and digital signals? What determines the maximum data rate of a channel? | Lecture; Demonstrating samples | Quiz; Recitation | FOR Ch. 3–4; Lecture Slides |
| 4 | Describe digital-to-digital, analog-to-digital, and analog-to-analog conversion techniques. | Physical Layer: Digital and Analog Transmission | How is data encoded for transmission? When is modulation used instead of digital encoding? | Lecture; Demonstrating samples | Quiz; Recitation; Problem Set | FOR Ch. 5–6; Lecture Slides |
| 5 | Explain multiplexing techniques, categories of transmission media, and switching concepts. | Physical Layer: Bandwidth Utilization, Transmission Media, Switching | How can a single channel carry multiple signals? What are the trade-offs between different transmission media? | Lecture; Demonstrating samples | Quiz; Recitation | FOR Ch. 7–8; Lecture Slides |
| 6 | Explain framing, error control, and flow control at the data link layer. Describe HDLC and PPP. | Data Link Layer: Data Link Control, HDLC, PPP | How does the data link layer ensure reliable delivery over a single hop? What roles do HDLC and PPP play in WAN links? | Lecture; Demonstrating samples | Quiz; Recitation; Handout | FOR Ch. 10–11; Lecture Slides |
| 7 | Describe MAC sublayer protocols and the operation of Ethernet. | Data Link Layer: Media Access Control, Wired LAN (Ethernet) | How do multiple devices share a single medium without collisions? How does Ethernet detect and handle collisions? | Lecture; Demonstrating samples | Quiz; Recitation; Handout | FOR Ch. 12–13; Lecture Slides |
| 8 (Midterm) | Explain the IEEE 802.11 WLAN standard and Bluetooth technology. | Wireless LAN: IEEE 802.11, Bluetooth | How does wireless MAC differ from wired MAC? How does Bluetooth coexist with Wi-Fi in the ISM band? | Lecture; Demonstrating samples | Quiz; Midterm Exam | FOR Ch. 15–16; Lecture Slides |
| 9 | Perform IP addressing and subnetting. Describe the Internet Protocol. | Network Layer: Addressing, IP | How are IP addresses structured and assigned? How does a packet travel from source to destination across the internet? | Lecture; Demonstrating samples | Quiz; Recitation; Problem Set | FOR Ch. 19–20; Lecture Slides |
| 10 | Explain ARP, ICMP, DHCP, and common routing protocols. | Network Layer: IP Support Protocols, Routing and Forwarding | How do hosts discover each other on a network? How do routers build and maintain their forwarding tables? | Lecture; Demonstrating samples | Quiz; Recitation | FOR Ch. 21–22; Lecture Slides |
| 11 | Distinguish TCP from UDP. Describe connection management and congestion control in TCP. | Transport Layer: TCP and UDP | When should TCP be used instead of UDP? How does TCP guarantee reliable, ordered delivery? | Lecture; Demonstrating samples | Quiz; Recitation; Problem Set | FOR Ch. 23–24; Lecture Slides |
| 12 | Describe the DNS resolution process and the flow of email using SMTP, POP, and IMAP. | Application Layer: DNS, Email | How does a domain name get resolved to an IP address? How does email travel from sender to recipient? | Lecture; Demonstrating samples | Quiz; Recitation; Handout | FOR Ch. 25–26; Lecture Slides |
| 13 | Explain SDN concepts and the characteristics of additional wireless network types. | Software Defined Networks; Other Wireless Networks | How does SDN separate the control and data planes? What are the use cases for LPWAN and 5G? | Lecture; Demonstrating samples | Quiz; Recitation | SDN Readings; Lecture Slides |
| 14 | Describe P2P network architectures and overlay network structures. | Peer-to-Peer Networks | How does a P2P network differ from a client-server model? How is content located without a central server? | Lecture; Demonstrating samples | Quiz; Recitation | Supplementary Readings; Lecture Slides |

#### Laboratory

| Week | Learning outcome/s | Course Topic | Essential or Key Questions | Suggested Teaching and Learning Activities | Suggested Assessment Tools/Activities | Core Readings/Learning Resources |
|------|--------------------|--------------|----------------------------|--------------------------------------------|---------------------------------------|----------------------------------|
| 2 | Configure network interfaces, IP addresses, and basic TCP/IP settings on a Linux system. | Configuring a Linux Box for TCP/IP | How are IP address, subnet mask, default gateway, and DNS configured in Linux? | Discussion; Working through samples; Demonstrating samples | Quiz; Lab Report | Linux Networking Documentation; Exercise #1 Handout |
| 3 | Crimp and test straight-through and crossover Ethernet patch cables. | Network Design: Wiring and Patch Cables | What is the TIA/EIA 568 cabling standard? How is cable continuity verified using a cable tester? | Discussion; Hands-on Lab | Lab Practical | TIA/EIA 568 Standard; Exercise #2 Handout |
| 4 | Capture and analyze network packets using Wireshark; identify protocol headers at each layer. | Packet Analysis (Wireshark) | What information can be extracted from a captured packet? How are protocol layers visible in a packet capture? | Discussion; Working through samples; Demonstrating samples | Quiz; Lab Report | Wireshark Documentation; Exercise #3 Handout |
| 6 | Calculate subnet addresses, broadcast addresses, and valid host ranges given a prefix length. | Subnet Calculations | How is an address space divided into subnets? How do CIDR notation and subnetting relate? | Discussion; Working through samples | Quiz; Problem Set | FOR Ch. 19; Exercise #4 Handout |
| 7 | Configure static routes and observe routing table behavior in a multi-router topology. | IP Routing | How does a router decide which interface to use when forwarding a packet? | Discussion; Working through samples; Demonstrating samples | Quiz; Lab Report | Linux ip-route Documentation; Exercise #5 Handout |
| 9 | Write TCP client and server programs using the socket API in a high-level programming language. | Socket Programming 1 | How are TCP client-server applications structured using the socket API? | Discussion; Working through samples; Demonstrating samples | Quiz; Coding Exercise | Beej's Guide to Network Programming; Exercise #6 Handout |
| 10 | Handle multiple clients concurrently; implement UDP datagram communication using sockets. | Socket Programming 2 | How do concurrent servers manage multiple client connections? How does UDP socket programming differ from TCP? | Discussion; Working through samples; Demonstrating samples | Quiz; Coding Exercise | Beej's Guide to Network Programming; Exercise #7 Handout |
| 11 | Configure BIND9 as an authoritative DNS server; create zone files and verify name resolution. | DNS and BIND9 | How is BIND9 configured to resolve domain names authoritatively? What records are required in a zone file? | Discussion; Working through samples; Demonstrating samples | Quiz; Lab Report | BIND9 ARM; Exercise #8 Handout |
| 12 | Use SSH for secure remote access and GPG for key management and file encryption/signing. | SSH and GPG | How does public-key cryptography secure remote login? How are GPG key pairs generated and used for encryption and signing? | Discussion; Working through samples; Demonstrating samples | Quiz; Lab Report | OpenSSH / GPG Documentation; Exercise #9 Handout |
| 13 | Set up a Mininet virtual network topology and deploy a basic SDN controller. | Network Emulation and Software Defined Networks | How does Mininet emulate a network? How does an OpenFlow controller interact with virtual switches? | Discussion; Working through samples; Demonstrating samples | Quiz; Lab Report | Mininet / OpenFlow Documentation; Exercise #10 Handout |
| 14–16 | Build a complete network-enabled application integrating concepts from the course; present and defend the implementation. | Project | How can multiple protocol layers be combined into a working networked application? | Discussion; Milestone presentations | Milestone presentations; Project Demo; Project Report | Course References; Project Specifications |

---

### 4. Course Requirements

- *Quizzes / Assignments (10%)*
- *Laboratory Exercises (40%)*
- *Midterm Examination (20%)*
- *Final Examination (20%)*
- *Project (10%)*

---

## D. References

### Textbook

- Forouzan, B. A. (2013). *Data Communications and Networking*, 5th Ed. McGraw-Hill, New York.

### Supplementary Textbooks

- Tanenbaum, A. (2003). *Computer Networks*, 4th Ed. Prentice Hall, Singapore.
- Kurose, J. F. and Ross, K. W. (2004). *Computer Networking: A Top-Down Approach Featuring the Internet*. Addison-Wesley.
- Dordal, P. L. *An Introduction to Computer Networks*. http://intronetworks.cs.luc.edu/
- *Computer Networking: Principles, Protocols, and Practice*, 3rd Ed. https://www.computer-networking.info/
- *Computer Networks: A Systems Approach*. https://www.systemsapproach.org/books.html

### Software

- Wireshark: https://www.wireshark.org/
- ICS-NetSim: https://github.com/srg-ics-uplb/ics-netsim
- Cisco Packet Tracer: https://www.netacad.com/courses/packet-tracer
- GNS3: https://www.gns3.com/
- Scapy: http://www.secdev.org/projects/scapy/
- Mininet: http://mininet.org/
- SEED Internet Emulator: https://github.com/seed-labs/seed-emulator
- xv6-net: https://github.com/srg-ics-uplb/xv6-net

---

## E. List of Faculty

| Name | Discipline |
|------|------------|
| *Joseph Anthony C. Hermocilla, MS* | *Computer Science* |
| *Fermin Roberto G. Lapitan, MIT* | *Information Technology* |
| *John Michael Raqueño, BS* | *Computer Science* |
| *Leonard Paul A. Garchitorena, BS* | *Computer Science* |
| *Aaron Carl Maaño, BS* | *Computer Science* |
| *Moh. Al-Fadhel Cali, BS* | *Computer Science* |
