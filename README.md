# 🚨 Proactive Threat Detection and Response with Wazuh and ELK Stack

A centralized Security Information and Event Management (SIEM) system designed using **Wazuh**, **Elasticsearch**, **Logstash**, **Kibana**, and **Filebeat** to provide real-time threat detection, log analysis, file integrity monitoring, vulnerability detection, and security compliance auditing.

---

## 🔍 Project Overview

With the rising complexity of cyber threats, organizations require a proactive system to continuously monitor, detect, and respond to suspicious activities. This project integrates the **Wazuh security platform** with the **ELK Stack** to build a robust SIEM solution that collects logs from multiple endpoints and provides insightful threat intelligence through visual dashboards.

---

## 📈 Key Features

- 🔐 **Real-time Log Analysis** from Windows, Linux, and Cloud sources.
- 🛡️ **File Integrity Monitoring (FIM)** to detect unauthorized changes.
- 🔍 **Vulnerability Detection** using Wazuh’s in-built scanning engine.
- 📊 **Kibana Dashboards** for interactive threat visualization.
- ⚙️ **Customizable Rules** for advanced threat detection.
- 🧠 **MITRE ATT&CK Mapping** for security event classification.

---

## 🛠️ Tools & Technologies Used

- **Wazuh Manager & Agent**
- **Elasticsearch** (Data Indexing)
- **Logstash** (Log Pipeline)
- **Kibana** (Visualization)
- **Filebeat** (Log Shipping)

---

## 🚀 How to Run the Project

1. **Start Ubuntu Environment** (or Virtual Machine).
2. **Install and Configure**:
   - Elasticsearch
   - Wazuh Manager & Agent
   - Logstash & Filebeat
   - Kibana with Wazuh Plugin
3. **Generate Certificates** for secure communication.
4. **Start Services** (`systemctl start` for each tool).
5. **Access Kibana** on `http://<server-ip>:5601` and monitor events.

---

## 🔍 Sample Insights

- ✅ Endpoint log collection and threat alerts
- 🔍 File integrity changes (FIM)
- ⚠️ MITRE ATT&CK-based classifications
- 📌 Real-time event correlation and alert forwarding

---
