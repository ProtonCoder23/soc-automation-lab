# SOC Automation with Wazuh, TheHive, and Shuffle (DigitalOcean Deployment)

## 📌 Project Overview
This project demonstrates how to automate Security Operations Center (SOC) workflows by integrating:
- **Wazuh** for log collection, SIEM functionality, and threat detection
- **TheHive** for security incident management and response
- **Shuffle** as the SOAR engine to orchestrate alert handling and automate playbooks

All components are deployed on **DigitalOcean** cloud infrastructure using separate droplets to simulate a cloud-based SOC setup.

---

## 🧱 Architecture Overview

The system processes alerts from monitored endpoints via Wazuh agents, sends them through Shuffle for enrichment and correlation, and then creates structured incidents in TheHive. Analysts are notified with enriched details, streamlining response efforts.

![SOC Architecture](soc architecture diagram.png)

---

## 🧰 Tools Used

| Tool        | Role                                               |
|-------------|----------------------------------------------------|
| **Wazuh**   | SIEM & Host-based Intrusion Detection              |
| **TheHive** | Security Incident Response Platform (SIRP)         |
| **Shuffle** | SOAR to automate workflows between Wazuh & TheHive |
| **DigitalOcean** | Cloud platform hosting all services          |
| **Sysmon**  | Windows endpoint telemetry ingested by Wazuh       |


