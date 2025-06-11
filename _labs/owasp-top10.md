---
title: "TryHackMe - OWASP Top 10 (2021)"
excerpt: "Hands-on challenge to understand and exploit the OWASP Top 10 vulnerabilities."
layout: single
date: 2025-05-05
read_time: true
image: /assets/images/labs/owasp10cover.png
header:
  overlay_image: /assets/images/labs/owasp-top10-banner.png
  caption: "Practical OWASP Top 10 Labs on TryHackMe"
tags: [TryHackMe, OWASP, Web Security, CTF]
categories: [Web Security]
---

## Problem Statement

I explored the top 10 most critical web application security risks, as identified by OWASP, through interactive hands-on labs in TryHackMe.

---

## Approach

Each vulnerability was explored using a vulnerable web application lab. I gained access to tasks sequentially, solved each challenge using hints, payloads, and Burp Suite where applicable, then documented the flag retrieval process.

---

## Tools Used

- TryHackMe
- Burp Suite Community
- Firefox Developer Tools
- Linux Terminal

---

## Screenshots

### Broken Access Control – IDOR
![IDOR Flag Retrieved](/assets/images/labs/owasp-idor.png)

### Injection – Command Injection
![Command Execution Output](/assets/images/labs/owasp-injection.png)

### SSRF Attack
![SSRF API Key Leak](/assets/images/labs/owasp-ssrf.png)

---

##  Key Lessons Learned

- Always validate and sanitize user inputs.
- Use rate-limiting and proper authentication.
- Outdated components and poor logging expose serious risks.
- Real-world vulnerability exploitation is often much simpler than theory implies.

