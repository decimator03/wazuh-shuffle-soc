# 🏗️ Architecture

## Overview

The project explored the integration of **Wazuh SIEM** with **Shuffle SOAR** to support automated security alert enrichment and response workflows within a SOC environment.

## Architecture Flow

```text
Security Event
      ↓
  Wazuh SIEM
      ↓
 Alert Detection
      ↓
 Shuffle SOAR
      ↓
Alert Enrichment
      ↓
Investigation / Response
```

## 🧩 Components

### 1. Wazuh SIEM

**Role:** Security monitoring and alert detection

Wazuh acts as the SIEM component of the architecture. It monitors security events, analyses activity, and generates alerts for relevant security events.

---

### 2. Shuffle SOAR

**Role:** Security orchestration and automation

Shuffle acts as the SOAR component. It receives relevant alerts and processes them through automated workflows for alert enrichment and response.

---

### 3. Alert Enrichment

**Role:** Adding investigation context

The enrichment stage adds additional information to security alerts, providing analysts with more context during investigation.

---

### 4. Investigation & Response

**Role:** Supporting analyst decision-making

The enriched alert information can then be used to support further investigation and appropriate response actions.
