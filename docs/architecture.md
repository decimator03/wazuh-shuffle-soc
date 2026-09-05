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

## 🔄 Data Flow

The integration can be understood as a sequence of stages:

1. **Security Event Collection**  
   Security events are collected and monitored by Wazuh.

2. **Alert Generation**  
   Wazuh identifies relevant activity and generates a security alert.

3. **Alert Processing**  
   Relevant alerts are passed to Shuffle SOAR for workflow processing.

4. **Alert Enrichment**  
   The SOAR workflow can add additional context to the alert.

5. **Investigation & Response**  
   The enriched information supports further investigation and response actions.

**Role:** Supporting analyst decision-making

The enriched alert information can then be used to support further investigation and appropriate response actions.

## 🔗 SIEM-to-SOAR Integration

The integration connects the detection capabilities of Wazuh with the automation capabilities of Shuffle SOAR.

```text
┌───────────────┐
│ Security Data │
└───────┬───────┘
        ↓
┌───────────────┐
│     Wazuh     │
│      SIEM     │
└───────┬───────┘
        ↓
   Security Alert
        ↓
┌───────────────┐
│    Shuffle    │
│      SOAR     │
└───────┬───────┘
        ↓
 Alert Enrichment
        ↓
Investigation / Response
