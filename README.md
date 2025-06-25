# SOC Automation with Wazuh, TheHive, and Shuffle (DigitalOcean Deployment)

## 📌 Project Overview
This project demonstrates how to automate Security Operations Center (SOC) workflows by integrating:
- **Wazuh** for log collection, SIEM functionality, and threat detection
- **TheHive** for security incident management and response
- **Shuffle** as the SOAR engine to orchestrate alert handling and automate playbooks

All components are deployed on **DigitalOcean** cloud infrastructure using separate droplets to simulate a cloud-based SOC setup.

---

## 🧰 Tools Used

| Tool        | Role                                               |
|-------------|----------------------------------------------------|
| **Wazuh**   | SIEM & Host-based Intrusion Detection              |
| **TheHive** | Security Incident Response Platform (SIRP)         |
| **Shuffle** | SOAR to automate workflows between Wazuh & TheHive |
| **DigitalOcean** | Cloud platform hosting all services          |
| **Sysmon**  | Windows endpoint telemetry ingested by Wazuh       |


