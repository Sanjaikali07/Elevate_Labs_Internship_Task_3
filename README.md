# Elevate_Labs_Internship_Task_3
Elevate Labs Internship Task 3

# 📄 Advanced Vulnerability Scan Report using Nessus Essentials

## 🔍 Overview

This document provides a detailed summary of an internal vulnerability scan performed using **Tenable Nessus Essentials** on a local network environment. The objective of this assessment was to identify and evaluate known vulnerabilities present in two target hosts within the network.

---

## 🧰 Scan Environment

* **Scanner**: Nessus Essentials (Local Scanner)
* **Policy**: Advanced Scan
* **Severity Base**: CVSS v3.0
* **Date**: June 28, 2025
* **Start Time**: 9:47 PM
* **End Time**: 9:54 PM
* **Elapsed**: 8 minutes

---

## 🖥️ Hosts Scanned

1. **192.168.224.30**
2. **192.168.224.69**

---

## 📊 Vulnerability Summary

| Host IP        | Critical | High | Medium | Low | Info | Total |
| -------------- | -------- | ---- | ------ | --- | ---- | ----- |
| 192.168.224.30 | 0        | 0    | \~4    | 74  | -    | 78    |
| 192.168.224.69 | 1        | 2    | \~3    | 12  | -    | 18    |

> 🔴 **Critical vulnerabilities detected** on host `192.168.224.69`. Immediate remediation recommended.

---

## 🧪 Key Findings

### 1. **Critical Vulnerability** (192.168.224.69)

* **Category**: Likely related to remote code execution or privilege escalation
* **Action**: Review plugin ID and CVE reference from full report; patch or disable vulnerable service immediately

### 2. **Multiple Low-Level Vulnerabilities** (192.168.224.30)

* **Category**: Informational or minor misconfigurations
* **Action**: While low priority, should be documented and remediated where feasible to strengthen security posture

---

## 🖼️ Screenshots

Included is a screenshot of the Nessus Essentials interface summarizing the scan results:

**Files:**
`Nessus Screenshot 1`
`Nessus Screenshot 2`

* Shows: Hosts, vulnerability counts, scan metadata, severity pie chart
* Confirms scan completion and target IPs

---

## 📌 Recommendations

* Address critical and high vulnerabilities on 192.168.224.69 immediately
* Apply system and service updates
* Disable deprecated or unused services (e.g., SMBv1, TLS 1.0)

---

## 📁 Files Included

* `Full internal vulnerability scan by Nessus.html`: Full report (exported from Nessus)
* `Nessus Screenshot 1.png`: Snap of scan in running status
* `Nessus Screenshot 2.png`: Visual summary of scan results

---

## ✍️ Author

**Sanjai K**

Elevate Labs Intern | Aspiring Penetration Tester
