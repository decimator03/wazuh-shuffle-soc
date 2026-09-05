# 🧰 Technologies

## Overview

This project explored a combination of SIEM, SOAR, data storage, visualization, and operating-system technologies to build a security monitoring and automation workflow.

---

## 🛡️ Wazuh

**Category:** SIEM & Security Monitoring

Wazuh was used as the primary security monitoring and SIEM component.

### Role

- Security event monitoring
- Security alert detection
- Log and event analysis
- Alert generation

---

## ⚙️ Shuffle SOAR

**Category:** Security Orchestration & Automation

Shuffle was used as the SOAR component of the project.

### Role

- Security workflow automation
- Alert processing
- Alert enrichment
- Response workflow support

---

## 🔎 Elasticsearch

**Category:** Data Storage & Search

Elasticsearch was used as part of the security monitoring environment for storing and searching security event data.

---

## 📊 Kibana

**Category:** Visualization & Monitoring

Kibana was used for security event visualization and dashboard-based monitoring.

### Role

- Event visualization
- Security monitoring
- Alert analysis
- Dashboard-based visibility

---

## 🐧 Linux

**Category:** Operating System

Linux was used as part of the project environment for deploying and working with the security tools involved in the lab.

---

## 🔗 Technology Relationship

The technologies worked together around the following security operations workflow:

```text
                    Security Events
                           │
                           ▼
                    ┌─────────────┐
                    │    Wazuh    │
                    │     SIEM    │
                    └──────┬──────┘
                           │
                           ├──────────────► Elasticsearch
                           │                       │
                           │                       ▼
                           │                    Kibana
                           │
                           ▼
                    ┌─────────────┐
                    │   Shuffle   │
                    │     SOAR    │
                    └──────┬──────┘
                           │
                           ▼
                  Enrichment / Automation
                           │
                           ▼
                    Investigation
                    & Response
```

## 🎯 Why These Technologies?

The combination of these technologies provided exposure to different layers of a SOC environment.

| Technology | Primary Purpose |
|---|---|
| **Wazuh** | Security monitoring and alert detection |
| **Shuffle SOAR** | Security orchestration and automation |
| **Elasticsearch** | Event data storage and search |
| **Kibana** | Security event visualization and monitoring |
| **Linux** | Security tool environment |

## 🧠 Key Takeaway

The project demonstrated how different security technologies can be combined to support a broader SOC workflow.

The overall workflow connects:

**Security Monitoring → Detection → Automation → Enrichment → Visualization → Investigation**


