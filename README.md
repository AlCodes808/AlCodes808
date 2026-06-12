

<div align="center">
  
#  🖖  Hi, I'm Alonzo

### Software Engineer | Systems & Cloud


</div>

---

## 🚀 About Me

```yaml
role: Full Stack Software Engineer
education: 
  - BS Computer Science
  - MS Cyber Security (In Progress)
specialties:
  - Cloud Infrastructure & AWS
  - Machine Learning & AI
  - Systems Security
  - Systems Programming
```


---

## 🛠️ Technical Arsenal

<div align="center">

### Languages
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Systems & Embedded
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![OpenSSL](https://img.shields.io/badge/OpenSSL-721412?style=for-the-badge&logo=openssl&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Cloud & Infrastructure
![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

</div>


---

## 🏆 Professional Certifications

<div align="center">

### ☁️ Cloud & Machine Learning
[![AWS MLA](https://img.shields.io/badge/AWS-Machine_Learning_Engineer_Associate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/certification/certified-machine-learning-engineer-associate/)
[![AWS SAA](https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/certification/certified-solutions-architect-associate/)
<!--  [![AWS Developer](https://img.shields.io/badge/AWS-Developer_Associate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/certification/certified-developer-associate/)  -->
<!-- [![AZ-900](https://img.shields.io/badge/Azure-Fundamentals_(AZ--900)-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)](https://learn.microsoft.com/en-us/certifications/azure-fundamentals/)  -->

### 🔒 Security & Infrastructure
[![Security+](https://img.shields.io/badge/CompTIA-Security%2B-E51937?style=for-the-badge&logo=comptia&logoColor=white)](https://www.comptia.org/certifications/security)
[![Network+](https://img.shields.io/badge/CompTIA-Network%2B-E51937?style=for-the-badge&logo=comptia&logoColor=white)](https://www.comptia.org/certifications/network)
<!-- [![Splunk](https://img.shields.io/badge/Splunk-Core_Certified_User-000000?style=for-the-badge&logo=splunk&logoColor=white)](https://www.splunk.com/en_us/training.html) -->
[![ITIL 4](https://img.shields.io/badge/ITIL-4_Foundation-6C3483?style=for-the-badge&logo=itil&logoColor=white)](https://www.axelos.com/certifications/itil-certifications)

### 📊 Project Management
[![Project+](https://img.shields.io/badge/CompTIA-Project%2B-E51937?style=for-the-badge&logo=comptia&logoColor=white)](https://www.comptia.org/certifications/project)
<!-- [![CAPM](https://img.shields.io/badge/PMI-CAPM-00558C?style=for-the-badge&logo=pmi&logoColor=white)](https://www.pmi.org/certifications/certified-associate-capm)  -->

</div>

---



---

## 🎯 Featured Projects

### 🔧 [OTA-Fleet-RollGuard](https://github.com/AlCodes808/OTA-Fleet-RollGuard)
> Production-grade over-the-air firmware update engine for distributed embedded fleets
- Built C++17 client daemon with strict 8-state machine managing the full update lifecycle from idle through automatic rollback
- Implemented cryptographic verification pipeline using OpenSSL - SHA-256 hashing and RSA signature validation rejects tampered packages before a single byte is applied
- Delta patch system using bsdiff reduces bandwidth by downloading only what changed between firmware versions
- Rollback engine snapshots firmware pre-update and restores automatically on health check failure with zero manual intervention
- Integrated AWS IoT Core MQTT, S3 artifact storage, DynamoDB fleet state tracking, Lambda rollout controller, and SNS alerting
- Staged canary rollout halts automatically when fleet failure rate exceeds configurable threshold
- Recall tracking system - per-device remediation records with regulatory-grade auditability

### 📡 [HELIX - Fleet Telemetry Platform](https://github.com/AlCodes808/fleet-telemetry)
> End-to-end telemetry platform for monitoring aerospace embedded systems in real time
- C++ agent implements AWS Signature Version 4 from scratch using libcurl and OpenSSL to ship metrics directly to Kinesis
- Dual anomaly detection - threshold and z-score statistical analysis runs on every telemetry record in Lambda
- Node.js API with WebSocket support feeds a live React dashboard with alert management across a 10-device simulated fleet
- DynamoDB with 12-hour TTL auto-expiry keeps storage costs near zero at scale

### 🛡️ [CAN Bus Sentinel IDS](https://github.com/AlCodes808/CAN-Bus-Sentinel-IDS)
> Automotive intrusion detection combining rule-based engines with ML-powered anomaly analysis
- 5 rule-based detection engines plus Isolation Forest ML model achieving 86% detection accuracy
- Deployed ML from Python training to embedded C inference with zero external dependencies and under 1ms processing per frame
- Detected 23 attacks that bypassed traditional signature-based detection through statistical timing pattern analysis

### 🚗 [CAN Bus Communication Simulator](https://github.com/AlCodes808/CAN-Bus-Communication-Sim)
> Automotive CAN 2.0B network simulator with multi-ECU communication and real-time diagnostics
- 4 ECUs with priority-based message arbitration, collision detection, and diagnostic trouble code management
- Embedded systems concepts: circular buffers, state machines, binary protocols, timing-driven execution

### 🔒 [AWS Pentesting CTF](https://github.com/AlCodes808/AWS-Pentesting-pivoting)
> Cloud security lab demonstrating real-world attack chains in misconfigured AWS infrastructure
- SSRF exploitation, IMDSv1 abuse, IAM credential theft, and lateral movement across segmented VPC
- End-to-end intrusion chain across DMZ, Internal, and Restricted tiers


<!--
### [CyberSecurity and CloudSec directory here](https://github.com/AlCodes808/Networking-And-Cybersecurity )
> OSCP study writeups, CTF solutions, and security research

--> 


