# Enterprise ITSM Governance Framework & ServiceNow Operational Standard

## Executive Summary
This repository contains an enterprise-grade **IT Service Management (ITSM)** governance framework aligned with **ISO 20000:2018** and **ITIL Foundation** standards. It is designed to scale IT operations across multi-country enterprise environments (APAC Region).

This framework standardizes core workflows for *Incident, Problem, Change, Asset, and Event Management*, establishes SLA/OLA matrices, and integrates field operations with automated service support.

---

## 📂 Repository Structure & Process Charters

Detailed process specifications are structured within the [`Process-Charters/`](./Process-Charters/) directory:

* 📄 **[Charter 01: IT Change Management](./Process-Charters/Charter-01-IT-Change-Management.md)** — Risk control, CAB protocols, and change execution workflows.
* 📄 **[Charter 02: IT Incident Management](./Process-Charters/Charter-02-Incident-Management.md)** — Severity levels (P1–P4), SLA targets, and escalation paths.
* 📄 **[Charter 03: IT Problem Management](./Process-Charters/Charter-03-Problem-Management.md)** — Root Cause Analysis (RCA) and Known Error Database (KEDB).
* 📄 **[Charter 04: Service Asset & Configuration Management (SACM)](./Process-Charters/Charter-04-Service-Asset-and-Configuration-Management.md)** — CMDB management and CI relationships.
* 📄 **[Charter 05: Hardware Asset Management (HAM)](./Process-Charters/Charter-05-Hardware-Asset-Management.md)** — Asset lifecycle, tagging, and eco-friendly E-Waste disposal.
* 📄 **[Charter 06: Software Asset Management (SAM)](./Process-Charters/Charter-06-Software-Asset-Management.md)** — License compliance, audit readiness, and cost reclamation.
* 📄 **[Charter 07: Release & Deployment Management](./Process-Charters/Charter-07-Release-and-Deployment-Management.md)** — DEV/Staging/PROD deployment governance.
* 📄 **[Charter 08: Knowledge & Event Management](./Process-Charters/Charter-08-Knowledge-and-Event-Management.md)** — Knowledge base acceleration and automated event monitoring.

---

## 🏗️ Core ITSM Governance & SLA Matrix

### 1. Incident Severity & SLA Targets
Ensures rapid incident recovery based on business impact criteria.

| Impact Level | Urgency | SLA Target (Response) | SLA Target (Resolution) | Escalation Path |
| :--- | :--- | :--- | :--- | :--- |
| **P1 - Critical** | High | < 15 Mins | < 2 Hours | Country IT Manager -> Regional Director |
| **P2 - High** | Medium | < 30 Mins | < 4 Hours | Lead Engineer -> Infrastructure Manager |
| **P3 - Medium** | Low | < 2 Hours | < 8 Hours | Tier 2 Support Team |
| **P4 - Low** | Low | < 4 Hours | < 24 Hours | Tier 1 Service Desk |

### 2. Change Management Protocol (CAB)
Ensures infrastructure and application changes execute with zero unplanned downtime.

```text
[ Change Request (CR) Created ] ──> [ Technical Review ] ──> [ CAB Approval ] ──> [ Off-Peak Execution ] ──> [ PIR Review ]
