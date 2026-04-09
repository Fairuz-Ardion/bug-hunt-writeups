# SQL Injection Vulnerability - PTSP Jakarta

## Information

| Aspek | Detail |
|-------|--------|
| **Vulnerability** | SQL Injection |
| **Target** | ptsp.jakarta.go.id |
| **Severity** | 🔴 **Critical** (Dump Databases) |
| **Discovery Date** | April 2026 |
| **Reported To** | Diskominfotik Provinsi DKI Jakarta |
| **Status** | ✅ Fixed & Disclosed with permission |

---

## 👤 Researcher

**Fairuz Raihan Ardion**
- Cybersecurity Enthusiast | Bug Hunter
- 📍 Jakarta, Indonesia
- Platform: CSIRT Jakarta

---

## 🎯 Finding Overview

Discovered a SQL Injection vulnerability in the PTSP Jakarta government portal that could allow unauthorized access to backend database information.

### Technical Details

| Severity Level | Impact |
|----------------|--------|
| **CVSS Score** | 7.5 (High) |
| **CVSS Vector** | CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N |
| **CWE** | CWE-89: Improper Neutralization of SQL Injection |

---

## 🔍 Vulnerability Description

### Affected Component
- **Endpoint**: *I Can't give this information because of some reason.*
- **Parameter**: *?id=*
- **HTTP Method**: GET/POST
