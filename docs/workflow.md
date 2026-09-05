## 1. Security Event

The workflow begins with a security-related event occurring within the monitored environment.

These events are collected and monitored by the SIEM platform.

## 2. Event Monitoring & Detection

**Wazuh** acts as the primary security monitoring and detection component.

It analyses security events and identifies activity that meets relevant detection conditions.

When relevant activity is detected, Wazuh generates a security alert.

## 3. Alert Processing

Once an alert is generated, relevant alerts can be passed into **Shuffle SOAR** for further processing.

The SOAR platform provides a way to organize subsequent actions into an automated workflow.

## 4. Alert Enrichment

The enrichment stage is used to provide additional context around a security alert.

Additional information can help analysts better understand the event and determine whether further investigation or response is required.

The purpose of enrichment is to make an alert more informative and useful during the investigation process.

## 5. Investigation

After enrichment, the available information can be reviewed as part of the investigation process.

An analyst can use the additional context to better understand:

- What activity was detected
- Why the alert was generated
- What additional information is available
- Whether the activity requires further investigation

## 6. Response

Based on the investigation and available information, appropriate response actions can be considered.

The SOAR workflow provides the foundation for exploring automated response actions as part of the overall security operations process.

## 🎯 Workflow Objective

The workflow demonstrates how SIEM detection can be connected with SOAR-based automation to support the security alert lifecycle.

The overall process can be summarized as:

**Detection → Processing → Enrichment → Investigation → Response**

The objective is to understand how automation can assist SOC analysts by reducing repetitive processing and providing additional context during alert investigation.

## 🧠 Key Concepts

- **SIEM Detection** — Identifying relevant security events and generating alerts.
- **SOAR Automation** — Processing alerts through defined security workflows.
- **Alert Enrichment** — Adding useful context to security alerts.
- **Investigation** — Analysing available alert information to understand the detected activity.
- **Response** — Supporting appropriate actions based on the investigation.
- **SOC Operations** — Connecting detection, investigation, and response into a structured workflow.

---

## ⚠️ Documentation Note

This document describes the workflow and concepts explored during the project.

The original lab environment is no longer actively hosted, so specific workflow configurations, endpoints, credentials, and deployment details are not included.
