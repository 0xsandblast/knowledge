# Introduction
## Table of contents
- [Introduction](#introduction)
  - [IT (security) Knowledge Base](#it-security-knowledge-base)
  - [The big Why](#the-big-why)
- [Academics](#academics)
  - [Networks & Security](#networks--security)
  - [Cryptography](#cryptography)
  - [Intrusion Detection & Prevention](#intrusion-detection--prevention)
  - [Reverse-engineering & Virology](#reverse-engineering--virology)
  - [Privacy & Multimedia content delivery protection](#privacy--multimedia-content-delivery-protection)
  - [Operating Systems](#operating-systems)
  - [System Programmation](#system-programmation)

## IT (security) Knowledge Base
This repository aims to list about everything I learned in general purposes IT, with a focus on security. It contains both academical and personnal projects as I give them the same importance, and I try to be as exhaustive as concise when describing them. Also, I strongly believe that the best way to ensure the comprehension of a subject is to teach it.

## The big Why
I got into computers firstly because my father is an IT engineer himself, and I have somehow been in it progressively since I was at middle school. What I like the most about computers is the boundless realm of possibilities which leaves room for creativity and resolution of intricate problems within this relatively nascent yet highly contemporary virtual world.

# Academics
Please find below a summary of all the subjects I had the opportunity to study in my academic career. I would like to point out that each subject listed has been studied in depth, unless explicitly stated. Courses generally begin with a historical context. 

_Note: For reasons of confidentiality and out of respect for the professors, I do not publish academic projects publicly. Please contact me so that I can share these projects with you. Thank you._

## Networks & Security
- **Cisco CCNA**:
  - Networking Essentials
    - Models, equipment, protocols, addressing
  - Introduction to Networks
    - Same as above plus LAN, WAN, WLAN, VLAN
  - Switching, Routing and Wireless Essentials
    - Same as above plus other concepts, Inter-VLANs, STP, NAT, OSPFv2, BGP, ACL, VPN/IPSec
- **Labs**:
  - Configuration of virtual networks on Cisco Packet Tracer
  - Configuration on physical devices, mostly Cisco firewalls
    - These labs were particularly interesting as we had to configure the equipments from scratch and manually interconnect computers with the firewall, define routes and implement different security measures.
   
## Cryptography
- **Symmetric**:
  - Old techniques (substitution, transposition)
  - Stream cipher (PRNG, LFSR)
  - Block cipher (AES, modes: ECB, CTR, CBC, CFB)
- **Asymmetric**:
  - Mathematical approach: prime factorization
  - RSA, Discrete logarithm and Elgamal, Elliptic Curves, Diffie-Hellman
- **Integrity**:
  - Certificates
  - MAC, Hashing functions (MD4/5, SHA-X)
- **Signature & Authentication**:
  - Passwords attacks, Challenge/response, Zero Knowledge
- **Post-quantum & quantum** (overview):
  - Transfering from today's to tomorrow's techniques
  - Using quantum ressources vs using quantum algorithms
- Physical Attacks : Correlation Power Analysis (CPA) with Pearson coefficient; Differential Fault Analysis (DFA) with Piret-Quisquater and NUEVA. 

## Intrusion Detection & Prevention
- **Tools**:
  - Apache Splunk, ELK (Elastic Search, Kibana, Logstash), SNORT, Suricata
- **Techniques**:
  - Signature-based
  - Behavioral (Machine Learning)
- **Cyber Threat Intelligence**:
  - Understanding and qualifying threats

### Projects
- **Suricata IDS** : establishing signature-based rules and testing in the case of a directory traversal attack
- Data mining and machine learning with **Orange**, determining behavior-based rules from training dataset
- **Elastic Suite - ELK** : [in progress]

## Reverse-engineering & Virology 
- **x86** Architecture and _ad hoc_ Assembly Language
- Stack and heap **memory management**
- **Static and dynamic analysis** (mainly with Ghidra, and Windows' Sysinternals suite for reconnaissance phase)
- **Malware types**
- **Android** Virology : application architecture, composants, syscalls, deployment. Reversing (apktool, ByteCodeViewer, etc.), anti-reversing techniques. 
- Review of major **APTs, TTPs**: primo-infection, persistance, stealth
- **Labs**:
  - Reversing known malwares' techniques (Ghidra)

### Projects
  - Real-life situtation : full analysis of an infected machine, decryption and deletion of the malware (Ghidra, Python). Ask for full report and scripts. 
  - **Andoid** [in progress ...] - reversing a malware

## Privacy & Multimedia content delivery protection
- **Intellectual property**:
  - Digital watermarking (LSB, Scalar Quantification, Spectrum Spreading, ECC)
  - Identifying attacks on watermarks (anti-piracy techniques)
- **Privacy**:
  - Partition-Based Model Approach (k-anonimity, l-diversity)
  - Differencial Privacy (Laplace mechanism) 
- **Law**:
  - GDPR (main principles, authorities, control and sanctions, PIA, IS securization, DPO functions)
  - Intellectual property on AI productions
  - Threats towards e-reputation

### Project
- Study research : finding the most efficient algorithm to watermark and track movie piracy (Python)

## Operating Systems
- Low level **Memory management** and **Process scheduling**
- Interruptions, Synchronization

- **Labs**:
  - Programming parts of an OS: [unixv6](https://github.com/bringhurst/xv6)
  - Working with [RISC-V](https://riscv.org/), an open standard instruction set architecture based on RISC principles

## System Programmation
- **C and C++**
- **Threads, processes**
- Files handling, pipes, sockets
- Synchronization: locks, mutex
- **DevOps**: CI/CD, Terraform

## Memory-based attacks
- **Buffer Overflow**, stack analysis, payload and shellcode conception
- **Format String**

### Project
- Real-life scenario setting : investigating a company that has been breached examining the code source, executables, and network traces of a vulnerable component in an application server and replaying attacks (BOF & FS). Ask for final oral support.

## Distributed Systems
- Blockchain
- Distributed Algorithms
- Distributed Computing, Synchronization

### Lab
- Deploying Bitcoin instances within a Regtest network, using *[Bitcoin-core](https://bitcoin.org/en/bitcoin-core/)*.

## Audit and pentest
- **Active Directory** : Environment (machines, domains, groups), Authentication (LDAP, Kerberos, NTLM), GPO. 
  - Lab : enumeration, compromising AD accounts, servers, networks, privilege escalation. Tools : Mimikatz, Impacket, ldapsearch, Enum4linux, Metasploit, etc. Ask for pentest report.
- **AWS** : Cloud architecture (systems and networks), pentesting theory and practice in [HackTheBox's Hailstorm lab](https://www.hackthebox.com/business/professional-labs/cloud-labs-blacksky). Ask for pentest report.  
### CTFs
*Oragnized by companies specifically for our student group.*
- **Airbus** "*Avionics*" : Simulating a real-world black-box audit on a specialized Real-Time Operating System designed for embedded applications. Involves techniques like jailing, reverse engineering, key recovery using timing attacks.
- **Wavestone** : Jeopardy-style CTF, categories : PWN, Web, Programmation, Forensics

