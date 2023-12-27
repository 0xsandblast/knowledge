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
I got into computers firstly because my father is an IT engineer himself, and I have somehow been in it progressively since I was at middle school. What I like the most about computers is the boundless realm of possibilities which leaves room for creativity and resolution of inctricate problems within this relatively nascent yet highly contemporary virtual world.

# Academics
Please find below a summary of all the subjects I had the opportunity to study in my academic career. I would like to point out that each subject listed has been studied in depth, unless explicitly stated. Courses generally begin with a historical context. 

_Note: For reasons of confidentiality and out of respect for the professors, I do not publish my projects publicly. Please contact me so that I can share these projects with you. Thank you._

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

## Intrusion Detection & Prevention
- **Tools**:
  - Apache Splunk, ELK (Elastic Search, Kibana, Logstash), SNORT, Suricata
- **Techniques**:
  - Signature-based
  - Behavioral (Machine Learning)
- **Cyber Threat Intelligence**:
  - Understanding and qualifying threats

## Reverse-engineering & Virology 
- **x86** Architecture and _ad hoc_ Assembly Language
- Stack and heap **memory management**
- **Static and dynamic analysis** (mainly with Ghidra, and Windows' Sysinternals suite for reconnaissance phase)
- **Malware types**
- Review of major **APTs, TTPs**: primo-infection, persistance, stealth
- **Labs**:
  - Reversing known malwares' techniques 
  - Real-life situtation : full analysis of an infected machine, decryption and deletion of the malware (ask for full report and scripts)  

## Privacy & Multimedia content delivery protection
- **Intellectual property**:
  - Digital watermarking (LSB, Scalar Quantification, Spectrum Spreading, ECC)
  - Identifying attacks on watermarks (anti-piracy techniques)
- **Privacy**:
  - Partition-Based Model Approach (k-anonimity, l-diversity)
  - Differencial Privacy (Laplace mechanism) 

## Operating Systems
- Low level **Memory management** and **Process scheduling**
- Interruptions, Synchronization
- Programming parts of an OS: ![unixv6](https://github.com/bringhurst/xv6)
- Working with ![RISC-V](https://riscv.org/), an open standard instruction set architecture based on RISC principles

## System Programmation
- **C and C++**
- **Threads, processes**
- Files handling, pipes, sockets
- Synchronization: locks, mutex
- **DevOps**: CI/CD, Terraform

