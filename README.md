# 🛡️ Wazuh + Shuffle SOAR Integration

## 📌 Overview

This project focused on integrating **Wazuh SIEM** with **Shuffle SOAR** to explore automated security alert enrichment and response workflows within a Security Operations Center (SOC) environment.

The implementation explored how security events detected by a SIEM can be processed through a SOAR platform to support alert enrichment, investigation, and automated response workflows.

## 🎯 Objectives

- Integrate Wazuh SIEM with Shuffle SOAR
- Monitor and analyse security events
- Forward relevant security alerts to Shuffle
- Enrich alerts through automated workflows
- Explore automated response actions
- Understand SIEM-to-SOAR integration within SOC operations

## 🏗️ Architecture

```text
Security Event
      │
      ▼
  Wazuh SIEM
      │
      ▼
Alert Detection
      │
      ▼
 Shuffle SOAR
      │
      ▼
Alert Enrichment
      │
      ▼
Response Workflow
