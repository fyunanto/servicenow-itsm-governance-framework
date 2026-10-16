# Enterprise ITSM Governance Framework & ServiceNow Operational Standard

## Executive Summary
Dokumen ini berisi kerangka kerja tata kelola **IT Service Management (ITSM)** dan **ISO 20000:2018 / ITIL Foundation Standard** yang dirancang untuk menskalakan operasional IT enterprise di wilayah multi-negara (APAC Region). 

Framework ini mencakup pembakuan alur kerja *Incident, Problem, Change, dan Release Management*, penetapan matriks SLA/OLA, serta model integrasi *Field Services* dan *Chatbot Automation*.

---

## 🏗️ Core ITSM Workflows & Governance Standard

### 1. Incident Management & SLA Matrix
Menjamin resolusi insiden operasional secara cepat berdasarkan kriteria dampak bisnis (*Business Impact*).

| Impact Level | Urgency | SLA Target (Response) | SLA Target (Resolution) | Escalation Path |
| :--- | :--- | :--- | :--- | :--- |
| **P1 - Critical** | High | < 15 Mins | < 2 Hours | IT Manager -> Regional Director -> Executive Steering |
| **P2 - High** | Medium | < 30 Mins | < 4 Hours | Lead Engineer -> Country IT Manager |
| **P3 - Medium** | Low | < 2 Hours | < 8 Hours | Tier 2 Helpdesk Support |
| **P4 - Low** | Low | < 4 Hours | < 24 Hours | Tier 1 Service Desk |

### 2. Change Management Process (CAB Protocol)
Memastikan seluruh perubahan infrastruktur jaringan, server, dan aplikasi berjalan tanpa mengganggu ketersediaan sistem bisnis (*Zero Unplanned Downtime*).

```text
[ Change Request (CR) Created ] 
               │
               ▼
   [ Initial Technical Review ] ──> (Rejected/Revised)
               │
               ▼
[ Change Advisory Board (CAB) Approval ]
               │
               ▼
   [ Pre-Deployment Staging Test ]
               │
               ▼
   [ Production Execution (Off-Peak) ]
               │
               ▼
  [ Post-Implementation Review (PIR) ]
