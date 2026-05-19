# IoT-CloudSec Dataset

## Overview
The IoT-CloudSec Dataset is a synthetic cybersecurity dataset designed for research in IoT security, cloud security, intrusion detection, anomaly detection, and machine learning-based cyber threat analysis.

This dataset simulates IoT device telemetry, cloud-native infrastructure activities, Kubernetes-based environments, and multiple cyberattack scenarios including DDoS attacks and unauthorized access attempts.

The dataset is intended to support:
- Intrusion Detection Systems (IDS)
- Anomaly Detection
- Cyber Threat Intelligence
- AI/ML-based Security Analytics
- Cloud-native Security Research
- IoT Network Security

---

## Features
The dataset includes:
- IoT device telemetry
- Network traffic statistics
- Cloud infrastructure metrics
- Kubernetes metadata
- Security event logs
- Attack classifications
- Anomaly scores
- Timestamped monitoring data

---

## Supported Research Areas
- IoT Security
- Cloud Security
- Cybersecurity
- Intrusion Detection
- DDoS Detection
- Threat Detection
- Network Traffic Analysis
- Artificial Intelligence for Cybersecurity
- Edge and Cloud Computing Security

---

## Attack Categories
The dataset contains both normal and malicious activities such as:
- Normal Traffic
- DDoS Attacks
- Unauthorized Access
- Suspicious Activity Patterns
- Network Anomalies

---

## Dataset Structure

| Column Name | Description |
|---|---|
| timestamp | Event timestamp |
| device_id | Unique IoT device identifier |
| network_traffic | Network traffic statistics |
| cpu_usage | CPU utilization metrics |
| memory_usage | Memory consumption metrics |
| anomaly_score | Calculated anomaly score |
| attack_type | Type of attack detected |
| label | Classification label |

---

## File Format
- CSV format
- UTF-8 encoding

Example:
```csv
timestamp,device_id,network_traffic,cpu_usage,anomaly_score,attack_type,label
2025-01-01 10:00:00,device_01,1200,65,0.92,ddos,malicious
