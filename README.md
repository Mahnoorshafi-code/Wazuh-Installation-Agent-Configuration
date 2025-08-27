# Wazuh Installation and Agent Configuration  

This repository contains documentation and screenshots of my first internship task, where I successfully installed and configured *Wazuh (SIEM)* and connected its agent for monitoring.  

---

## 📌 Task Overview  
The objective of this task was to:  
1. Install the Wazuh server on Ubuntu.  
2. Configure Wazuh Manager and Dashboard.  
3. Install the Wazuh Agent on Windows/Ubuntu.  
4. Connect the agent to the Wazuh server for log collection and monitoring.  

---

## 🛠 Tools & Technologies Used  
- *Operating Systems:* Ubuntu (for Wazuh server), Windows (for agent)  
- *Wazuh Version:* (mention the version you installed, e.g., 4.x)  
- *Elasticsearch / OpenSearch* (for data storage)  
- *Kibana / Wazuh Dashboard* (for visualization)  

---

## ⚙ Steps Performed  

### 1. Install Wazuh Server  
```bash
curl -sO https://packages.wazuh.com/4.7/wazuh-install.sh
bash wazuh-install.sh -a
