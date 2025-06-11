---
layout: single
permalink: /labs/
title: Lab Challenges
---

# Lab Challenges

## Challenge 1: OWASP Top 10 - Insecure Direct Object Reference (IDOR)
- **Problem Statement**: Identified an IDOR vulnerability allowing unauthorized access to user data on a web application.  
- **Approach**: Analyzed API endpoints using Burp Suite, crafted requests to access restricted resources, and validated findings with manual testing.  
- **Tools Used**: Burp Suite, Postman, Try Hack Me platform  
- **Key Lessons Learned**: Importance of implementing proper access controls and validating user permissions on server-side logic.  
- **Screenshot**: ![IDOR Screenshot](/assets/images/idor_screenshot.jpg) *(Update with actual screenshot)*  

## Challenge 2: Cross-Site Scripting (XSS) Vulnerability Exploitation
- **Problem Statement**: Exploited a cross-site scripting vulnerability linked to outdated jQuery libraries (CVE-2020-11022, CVE-2015-9251).  
- **Approach**: Injected malicious scripts to test input validation, used browser developer tools to monitor DOM manipulation, and reported findings via HackerOne.  
- **Tools Used**: Browser Developer Tools, Burp Suite, HackerOne  
- **Key Lessons Learned**: Regular library updates and input sanitization are critical to preventing XSS attacks.  
- **Screenshot**: ![XSS Screenshot](/assets/images/xss_screenshot.jpg) *(Update with actual screenshot)*  
