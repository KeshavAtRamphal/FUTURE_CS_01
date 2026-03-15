# FUTURE_CS_01
Security testing project and reports.
# 🛡️ Cyber Security & Database Design Portfolio (2026)

Welcome to my security research repository. This project contains a full vulnerability assessment of the **Altoro Mutual** test environment and a deep dive into **Database Security and Design**.

## 📑 Project Overview
- **Author:** Keshav Ramphal
- **Task:** Vulnerability Assessment & Database Infrastructure
- **Tools Used:** Nmap, OWASP ZAP, HCL AppScan
- **Environment:** Kali Linux / Arch Linux

---

## 🏗️ Table of Contents
1. [Executive Summary](#-executive-summary)
2. [Vulnerability Assessment](#-vulnerability-assessment)
3. [Database Design & Integrity](#-database-design--integrity)
4. [Corrective Actions](#-corrective-actions)
5. [Legal Disclaimer](#-legal-disclaimer)

---

## 🚀 Executive Summary
A comprehensive security audit of `http://altoro.testfire.net/login.jsp`. The report identifies critical entry points and suggests architectural changes to the database to prevent data leaks.

## 🔍 Vulnerability Assessment
I identified **10 key alerts** during the reconnaissance phase:
- **High Risk:** SQL Injection (SQLi), Insecure Direct Object Reference (IDOR).
- **Medium Risk:** Cross-Site Scripting (XSS), Security Misconfigurations.



## 🗄️ Database Design & Integrity
Using **Crow’s Foot Notation**, the project outlines a secure schema to prevent physical data breaches and redundancy.

### Key Concepts:
- **ERD Modeling:** Moving from Many-to-Many (M:M) to One-to-Many (1:M) using Bridge Tables.
- **Primary Keys:** Unique identification for data integrity.
- **Data Normalization:** Ensuring no duplicated data exists within the system.



## 🛠️ Corrective Actions
- Implementing parameterized queries to stop SQLi.
- Enforcing Referential Integrity through Foreign Key constraints.

## ⚖️ Legal Disclaimer
- Everything was done legally and no illgal actions where commited
- Please do NOT steal my work or i will report you 😊
