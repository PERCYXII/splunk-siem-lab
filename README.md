# splunk-siem-lab
A comprehensive Splunk lab featuring AI-generated synthetic logs, MITRE ATT&amp;CK-mapped detections, and interactive security dashboards for incident triage and threat hunting
For a high-quality GitHub repository, you need two types of descriptions:

# Splunk Detection & Triage Lab: AI-Driven Security Monitoring

##  Project Overview
This repository documents a local Splunk environment built to simulate real-world SOC (Security Operations Center) workflows. The lab focuses on the end-to-end lifecycle of an incident: from log ingestion and parsing to detection engineering, MITRE ATT&CK mapping, and interactive visualization.

By leveraging AI-generated synthetic logs, I have simulated various attack vectors (Brute Force, Lateral Movement, Data Exfiltration) to practice high-fidelity alerting and dashboard creation.

##  Objectives
*   **Log Ingestion:** Ingested AI-generated JSON logs simulating Windows Event Logs, Sysmon, and Web Server traffic.
*   **Detection Engineering:** Developed SPL (Search Processing Language) queries to identify malicious patterns.
*   **Framework Mapping:** Aligned all detections with the **MITRE ATT&CK Framework**.
*   **Visualization:** Built interactive, "drill-down" dashboards for real-time monitoring and executive reporting.
*   **Incident Triage:** Documented the investigation process for true-positive alerts.

##  Technical Stack
*   **SIEM:** Splunk Enterprise
*   **Data Generation:** LLM-based synthetic log generation (JSON format)
*   **Languages:** SPL (Splunk Search Processing Language), Markdown
*   **Frameworks:** MITRE ATT&CK, NIST 800-61 (Incident Handling)

## Key Features
### 1. AI-Synthetic Log Ingestion
Instead of using static datasets, I prompted an AI to generate JSON logs representing specific attack scenarios. This allowed me to practice:
*   Parsing nested JSON data in Splunk.
*   Creating custom source types and field extractions.

### 2. Interactive Dashboards
The dashboards included in this repo (see `/Dashboards & Visualization` folder) utilize:
*   **Tokens:** For dynamic filtering by user, IP, or time range.
*   **Drill-downs:** Enabling a "click-to-investigate" workflow from a high-level chart to raw log events.
*   **Single-Value Thresholds:** Using color-coding to highlight critical spikes in failed logins or unauthorized access.

### 3. MITRE ATT&CK Mapping
Each alert and dashboard panel is tagged with specific MITRE techniques (e.g., T1078 - Valid Accounts) to ensure comprehensive security coverage.





