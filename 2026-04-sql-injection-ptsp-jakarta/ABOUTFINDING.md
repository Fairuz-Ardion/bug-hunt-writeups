# SQL Injection Vulnerability - PTSP Jakarta

## 📋 Informasi Umum

| Aspek | Detail |
|-------|--------|
| **Vulnerability** | SQL Injection |
| **Target** | ptsp.jakarta.go.id |
| **Severity** | 🔴 **High** (dapat mengakses data sensitif) |
| **Discovery Date** | April 2026 |
| **Reported To** | Diskominfotik Provinsi DKI Jakarta |
| **Status** | ✅ Fixed & Disclosed with permission |

---

## 👤 Researcher

**Fairuz Raihan Ardion**
- Cybersecurity Enthusiast | Bug Hunter
- 📍 Jakarta, Indonesia
- Platform: HackerOne / Bug Bounty Programs

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
- **Endpoint**: *(Sebutkan endpoint spesifik jika diizinkan)*
- **Parameter**: *(Parameter yang rentan, misal: `?id=` atau form input tertentu)*
- **HTTP Method**: GET/POST

### Proof of Concept (PoC)

```http
GET /[affected-endpoint]?[parameter]=[value]' HTTP/1.1
Host: ptsp.jakarta.go.id
User-Agent: Mozilla/5.0
Accept: text/html
