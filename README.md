# Soc_Analysis_lab
# 🛡️ SOC Analysis Lab: SSH Brute Force Detection

## 🎯 Overview
In this project, I simulated a real-world Brute Force attack on an SSH service using **Hydra**. Then, I used **Splunk** to ingest logs, analyze the traffic, and build an automated alerting system.

## 🛠️ Step 1: Attack Simulation (Hydra)
Simulated over 1,000 login attempts to generate realistic security events in Linux `auth.log`.
![Hydra Attack](Screenshot%202026-04-29%20093432.png)

## 🔍 Step 2: Log Analysis & Visualization (Splunk)
Used **SPL (Splunk Processing Language)** to filter failed login attempts and visualized the data to identify attack patterns.
![Splunk Visualization](Screenshot%202026-04-29%20093632.png)

## 🚨 Step 3:---

## 🛡️ SOC Analysis Lab: Nmap Reconnaissance Detection

# Soc_Analysis_lab

## 🛡️ Project 1: SSH Brute Force Detection
### 🎯 Overview
In this project, I simulated a real-world Brute Force attack on an SSH service using **Hydra**. Then, I used **Splunk** to ingest logs, analyze the traffic, and build an automated alerting system.

### 🚀 Key Milestones
* **Step 1: Attack Simulation (Hydra)**: Simulated login attempts to generate security events.
* **Step 2: Log Analysis (Splunk)**: Used SPL to filter failed logins and visualize data.
* **Step 3: Real-time Alerting**: Configured a "SSH Brute force detected" alert.

---

## 🛡️ Project 2: Nmap Reconnaissance Detection
### 🎯 Overview
In this project, I simulated a network reconnaissance attack using **Nmap** from a Kali Linux machine. I configured a **Splunk Universal Forwarder** to monitor system logs and ingest them into **Splunk Enterprise** for real-time threat detection.

### 🚀 Key Milestones
* **Log Forwarding**: Configured the Splunk Universal Forwarder to capture and ship Windows Security Logs.
* **Attack Simulation**: Performed a comprehensive port scan to generate security events.
* **Detection Engineering**: Developed custom SPL queries to identify scanning patterns.
* **Visibility**: Built a dedicated SOC dashboard to monitor active reconnaissance.

### 📸 Evidence
![Nmap Detection Dashboard](./Screenshot%202026-05-04%20131009.png)
