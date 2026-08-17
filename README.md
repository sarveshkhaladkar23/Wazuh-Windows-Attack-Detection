# Wazuh Windows Attack Detection Lab

A hands-on cybersecurity lab demonstrating how attacks originating from Kali Linux can be detected and investigated using Wazuh SIEM on a Windows endpoint.

## 🛡️ Project Overview

This project simulates controlled attacks against a Windows 10 endpoint and demonstrates how Wazuh collects, analyzes and generates security alerts from Windows event logs.

## 🏗️ Lab Architecture

Kali Linux
     |
     | Attack traffic
     ↓
Windows 10
     |
     | Wazuh Agent
     ↓
Wazuh Manager
     |
     ↓
Wazuh Dashboard

## 🔬 Attack Scenarios

### 1. Network Scanning

Tool:
- Nmap

Detection:
- Possible network scan detected
- Rule ID: 100101
- Level: 10
- MITRE ATT&CK: T1046

### 2. SMB Authentication Brute Force

Technique:
- Repeated authentication failures

Detection:
- Multiple Windows logon failures
- Brute-force detection rule
- MITRE ATT&CK mapping

## 📊 Results

The simulated attacks were successfully detected
and visualized in the Wazuh Threat Hunting dashboard.

## 🧰 Tools Used

- Kali Linux
- Windows 10
- Wazuh
- Nmap
- SMB
- PowerShell
- VirtualBox

## 🎯 Learning Outcomes

- SIEM deployment
- Windows event monitoring
- Attack simulation
- Detection engineering
- Custom Wazuh rules
- MITRE ATT&CK mapping
- Threat hunting
