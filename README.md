# Wazuh Home Lab
Building a cybersecurity home lab using Wazuh, Ubuntu Server, Windows Server 2025 and VirtualBox.
# Wazuh Home Lab

## Overview

This repository documents my first cybersecurity home lab project built using Wazuh, Ubuntu Server, Windows Server 2025 and VirtualBox.

## Current Status

✅ Ubuntu Server deployed

✅ Wazuh Manager installed

✅ Wazuh Dashboard operational

✅ Wazuh Indexer operational

✅ Windows Server 2025 deployed

🔄 Windows Agent enrollment in progress

⏳ Alert generation and investigation pending

## Environment

| Component | Technology |
|------------|------------|
| Hypervisor | VirtualBox |
| SIEM | Wazuh |
| Linux Server | Ubuntu Server |
| Endpoint | Windows Server 2025 |

## Current Architecture

```text
Windows Server 2025
        |
        |
        v
Ubuntu Server
(Wazuh Manager + Dashboard + Indexer)
```

## Progress

### Infrastructure

- [x] Installed VirtualBox
- [x] Created Ubuntu Server VM
- [x] Created Windows Server 2025 VM
- [x] Configured networking

### Wazuh

- [x] Installed Wazuh Manager
- [x] Installed Wazuh Dashboard
- [x] Installed Wazuh Indexer
- [x] Accessed Wazuh Dashboard

### Monitoring

- [ ] Deploy Windows Agent
- [ ] Register endpoint
- [ ] Generate alerts
- [ ] Investigate events

## Screenshots

### Ubuntu Server

Ubuntu Server running Wazuh Manager, Dashboard and Indexer.

### Windows Server 2025

Windows Server virtual machine prepared for Wazuh agent deployment.

### VirtualBox Environment

Virtualized lab environment used for testing and learning.

## Learning Goals

- Learn SIEM fundamentals
- Learn Linux basics
- Learn Windows Server administration
- Learn security monitoring
- Build practical cybersecurity experience
