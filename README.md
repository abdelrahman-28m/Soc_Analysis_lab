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

## 🚨 Step 3: Real-time Alerting
Configured a **Real-time Alert** titled "SSH Brute force detected" to notify security analysts immediately.
![Splunk Alert](Screenshot%202026-04-29%20093911.png)
