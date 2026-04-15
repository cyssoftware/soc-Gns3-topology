## SOC GNS3 Topology Project

This project demonstrates how to use **Splunk (SIEM solution)** to collect, parse, and analyze logs in order to detect **brute-force attacks**.

You can import the provided file `soc project.gns3` into your GNS3 environment for testing and simulation.

---

## 🔧 Project Topology

The following topology was used in this project:

![Topology](https://github.com/user-attachments/assets/9ac3bf97-7856-4f7a-adb1-109b0ec1d2ab)

---

## 📊 Splunk Results & Analysis

### 📥 Log Ingestion (Fetching Logs)

![Fetching Logs](https://github.com/user-attachments/assets/473aeffa-376b-47dd-90cd-bbe5db11fd4b)

---

### 📈 Authentication Attempts Overview

Pie chart showing **blocked vs failed authentication attempts**:

![Pie Chart](https://github.com/user-attachments/assets/bb5aeed5-b405-4f8f-97c6-d51d47ef0d6b)

---

### 🚨 Brute Force Detection Alert

An alert was configured to detect brute-force attacks with the following condition:

> More than **10 failed attempts within 1 minute**

![Alert Condition](https://github.com/user-attachments/assets/dcef0d60-491a-45ac-9861-b1f9e9449146)

---

### ⚠️ Triggered Alerts

![Triggered Alerts](https://github.com/user-attachments/assets/ae70758e-043f-4c7d-8abf-74549b9f91fd)

---

### 📌 Alert Results

![Alert Results](https://github.com/user-attachments/assets/e0dee252-b4df-4d87-a34e-a1873f36eedd)

---

## ✅ Summary

- Built a simulated SOC environment using GNS3  
- Integrated Splunk for log analysis  
- Created SPL queries to detect brute-force attacks  
- Configured real-time alerts based on attack patterns  

---

## 📁 Usage

1. Import `soc project.gns3` into GNS3  
2. Start the topology  
3. Ingest logs into Splunk  
4. Run SPL queries and monitor alerts  

---

## 📌 Notes

This project is intended for **educational and cybersecurity training purposes**.
