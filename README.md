# Local Network Port Scan Report

## Overview
This repository contains the results of a local network port scan I performed for learning purposes.  
The objective was to identify open ports on devices within my local network and assess potential security risks.

---

## Files in this repository

| File | Description |
|------|-------------|
| FINDINGS.md | Human-readable report summarizing hosts, open ports, risks, and remediation suggestions. |
| myscan_redacted.nmap | Nmap scan output (human-readable) with IPs redacted. |
| myscan_redacted.gnmap | Grepable Nmap summary output with IPs redacted. |
| myscan_redacted.xml | Machine-readable XML Nmap output with IPs redacted (optional). |

---

## Methodology
1. Scanned my local network (e.g., 192.168.*.*/24) using Nmap.  
2. Used the command:
```bash
sudo nmap -sS -sV -O -oA myscan 192.168.*.*/24
