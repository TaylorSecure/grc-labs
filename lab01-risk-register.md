# Lab 01 – Cybersecurity Risk Register
**Created by:** Shantall Taylor  
**GitHub:** TaylorSecure  
**Date:** 2/18/26

---

## 📌 Purpose
This lab demonstrates a basic cybersecurity risk assessment by identifying assets, threats, vulnerabilities, and risk scores.  
It is designed as the first entry in a hands-on GRC portfolio.

---

## 🏢 Scenario
You are the GRC Analyst for **Sunrise Health Clinic**, a small medical office with 20 employees.  
The organization stores electronic patient records, uses laptops, a cloud storage provider, and email for daily operations.

Your job: **Identify risks and propose mitigation plans.**

---

## 📊 Risk Register

| ID | Asset | Threat | Vulnerability | Likelihood (1–5) | Impact (1–5) | Risk Score (L × I) | Mitigation Plan |
|----|--------|---------|----------------|------------------|----------------|----------------------|-------------------|
| R1 | Patient Records | Phishing Attack | Employees lack security training | 4 | 5 | 20 | Launch monthly phishing awareness training and simulate phishing tests. |
| R2 | Office Wi-Fi | Unauthorized Access | Weak Wi-Fi password & outdated encryption | 3 | 4 | 12 | Upgrade to WPA3, use strong passwords, rotate every 90 days. |
| R3 | Laptops | Malware Infection | No EDR installed | 3 | 5 | 15 | Deploy endpoint detection and response (EDR) on all laptops. |
| R4 | Cloud Storage | Data Leak | Misconfigured access permissions | 2 | 5 | 10 | Perform quarterly access reviews; require MFA for all accounts. |
| R5 | Email System | Ransomware | No attachment scanning | 2 | 4 | 8 | Enable attachment sandboxing; block unknown or risky file types. |

---

## 🧠 Notes & Definitions

### **Asset**
Something valuable (data, people, systems).

### **Threat**
Something that could cause harm (cybercriminals, accidents, human errors).

### **Vulnerability**
A weakness that can be exploited (no MFA, untrained users, misconfigured settings).

### **Likelihood (1–5)**
How likely the event is to occur.  
1 = Rare  
5 = Very likely

### **Impact (1–5)**
How bad it would be if it happened.  
1 = Minimal  
5 = Severe or disastrous

### **Risk Score**
**Likelihood × Impact**  
This helps prioritize what should be fixed first.

---

## ✅ Summary
The highest risk is **phishing attacks** targeting patient data (Risk Score = 20).  
Mitigation should begin with employee training and improved email security controls.

---

## 📁 Status
**Completed**  
This file is part of my ongoing GRC portfolio.
