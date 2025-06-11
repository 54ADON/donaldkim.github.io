---
title: "TryHackMe - OWASP Top 10 (2021)"
excerpt: "A hands-on exploration of the OWASP Top 10 vulnerabilities using practical labs."
layout: single
date: 2025-05-05
read_time: true
header:
  overlay_image: /assets/images/labs/owasp-top10-banner.png
  caption: "Practical Security Labs on the OWASP Top 10"
tags: [TryHackMe, OWASP, Web Security, CTF]
categories: [Web Security]
---

## 🔐 Introduction

The OWASP Top 10 is a global standard for identifying critical web application risks. I completed the **"OWASP Top 10 - 2021" room on TryHackMe**, featuring real-world vulnerable applications for each of the ten categories.

---

##  Tasks Completed

### 1. Broken Access Control  
Used Insecure Direct Object Reference (IDOR) to view another user's notes.

### 2. Cryptographic Failures  
Identified unencrypted sensitive data in SQLite database.

### 3. Injection  
Exploited inputs using `${ls}` and `${cat /etc/passwd}` to show command injection.

### 4. Insecure Design  
Guessed password reset answers due to lack of rate-limiting (e.g., "green").

### 5. Security Misconfiguration  
Accessed exposed files via default configurations and poor permissions.

### 6. Vulnerable and Outdated Components  
Observed risks in systems running old and vulnerable software.

### 7. Identification and Authentication Failures  
Bypassed duplicate account registration logic with a slight username variation.

### 8. Software and Data Integrity Failures  
Compared file hashes to detect tampering.

### 9. Security Logging and Monitoring Failures  
Analyzed logs to identify attacker activity (brute force IP).

### 10. Server-Side Request Forgery (SSRF)  
Manipulated URLs to expose internal services and leaked API keys.

---

## 🏁 Completion Badge

*A screenshot of the completion badge can be embedded here.*

---

## 📘 Conclusion

This lab gave me solid hands-on experience across the OWASP Top 10. I enhanced my understanding of secure design principles and practical mitigation strategies, and I’m now more confident identifying and patching common web security flaws.
