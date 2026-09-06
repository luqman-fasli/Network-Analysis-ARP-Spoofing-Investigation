# 🔎 Network Analysis & ARP Spoofing Investigation

A hands-on network security investigation using Wireshark to analyse a suspected Man-in-the-Middle (MITM) attack, identify ARP spoofing activity, reconstruct FTP traffic, and investigate sensitive information exposed through plaintext network communication.

---

## 📌 Project Overview

This project demonstrates a practical network investigation based on a scenario where an attacker gains physical access to an internal network by connecting a laptop to an unused switch port.

The attacker attempts to intercept communication between legitimate hosts and obtain sensitive information from the central server.

The investigation focuses on:

- ARP spoofing detection
- Man-in-the-Middle (MITM) analysis
- MAC address and IP address mapping
- Wireshark Expert Information
- FTP traffic analysis
- TCP stream reconstruction
- File transfer investigation
- Sensitive information exposure through plaintext protocols

---

## 🎯 Investigation Objectives

- Identify suspicious ARP activity
- Determine whether an MITM attack is taking place
- Identify the MAC address associated with the suspected attacker
- Identify files transferred from the central server
- Recover and analyse the transferred file
- Investigate employee information contained within the transferred data
- Demonstrate the security risks of plaintext FTP communication

---

## 🧪 Investigation Environment

**Primary Tool:**
- Wireshark

**Network:**
- 192.168.56.0/24

**Protocols Analysed:**
- ARP
- FTP
- TCP

---

## 🕵️ Investigation Workflow

```text
Investigation Scenario
        ↓
Identify Network Endpoints
        ↓
Filter ARP Traffic
        ↓
Review Expert Information
        ↓
Identify Duplicate IP Warning
        ↓
Analyse IP/MAC Relationships
        ↓
Identify Suspected Attacker MAC
        ↓
Analyse FTP Traffic
        ↓
Follow TCP Stream
        ↓
Identify Transferred File
        ↓
Recover & Analyse File
        ↓
Investigate Sensitive Information
