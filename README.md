# 🛡️ Wazuh + Shuffle SOAR Integration

A technical case study documenting the integration of **Wazuh SIEM** with **Shuffle SOAR** for security monitoring, alert enrichment, automation, and SOC response workflows.

---

## 📌 Overview

This project focused on integrating **Wazuh SIEM** with **Shuffle SOAR** to explore how security alerts can move from detection to automated investigation and response.

The project provided practical exposure to:

- Security monitoring
- Alert detection
- SIEM-to-SOAR integration
- Alert enrichment
- Security automation
- Incident response workflows
- Event visualization

---

## 🎯 Objectives

- Integrate **Wazuh SIEM** with **Shuffle SOAR**
- Monitor and analyse security events
- Forward relevant alerts into automated workflows
- Enrich alerts with additional investigation context
- Explore automated response actions
- Understand SIEM and SOAR interaction within SOC operations

---

## 🏗️ Architecture

```text
Security Events
      │
      ▼
┌─────────────┐
│    Wazuh    │
│    SIEM     │
└──────┬──────┘
       │
       ▼
 Alert Detection
       │
       ▼
┌─────────────┐
│   Shuffle   │
│    SOAR     │
└──────┬──────┘
       │
       ▼
Alert Enrichment
       │
       ▼
Investigation / Response
```
For a detailed explanation of the architecture and how the components interact, see [Architecture Documentation](docs/architecture.md).
