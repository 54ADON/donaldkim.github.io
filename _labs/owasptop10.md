---
title: "bWAPP - Cross-Site Scripting (XSS)"
layout: single
date: 2025-06-11
author_profile: false
read_time: true
excerpt: "Solving XSS vulnerabilities in the bWAPP lab using Burp Suite and manual testing."
header:
  overlay_image: /assets/images/labs/xss-banner.png
  overlay_filter: 0.4
  caption: "Exploring XSS in bWAPP"
categories: [Web Security, XSS]
tags: [bWAPP, XSS, Burp Suite, Web Pentesting]
---
## 🧪 Problem Statement
Explore different XSS types in bWAPP and exploit them.

## 🔍 Tools Used
- Burp Suite
- Firefox Developer Tools
- bWAPP

## 🛠️ Approach
1. Selected reflected XSS from bWAPP menu.
2. Injected payload `"><script>alert('XSS')</script>`.
3. Observed behavior and tested variations.

## 📸 Screenshots
![XSS Alert](../../assets/images/labs/xss-alert.png)

## 📘 Key Lessons
- Importance of input validation
- How reflected XSS works
