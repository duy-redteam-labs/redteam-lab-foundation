# Red Team Lab Foundation (Mini-Corp)

## Overview
Personal red team lab to practice networking, VM operations, segmentation, and centralized logging in a safe environment.

## Scope (Lab-only)
This lab is for local VMs only. No real-world targets. No credential harvesting.

## What you will build
- 1 attacker: Kali/Ubuntu
- 1–2 victims: Windows + Ubuntu
- 1 vulnerable service: DVWA / Juice Shop / Metasploitable
- 1 log server: Splunk Free / ELK / Wazuh

## Tech Stack
- Hypervisor: VirtualBox/VMware
- Networking: NAT / Host-only / (optional) bridged
- Logging: Wazuh/ELK/Splunk (choose one)

## How to Run
1. Follow build guide in docs/
2. Bring up VMs
3. Verify connectivity + log ingestion
4. Use snapshots to reset after exercises

## Deliverables
- Network diagram: docs/diagrams/
- Build checklist + scripts: scripts/
- Lab runbook (reset/snapshot/restore): docs/reports/

## Status
- [ ] Diagram
- [ ] Build checklist
- [ ] Runbook
