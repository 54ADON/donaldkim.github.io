---
title: "Implementing Azure Functions"
excerpt: "Building and deploying serverless apps using triggers, Azure CLI, and .NET."
layout: single
date: 2025-05-21
read_time: true
header:
  overlay_image: /assets/images/labs/azure-functions.png
  caption: "Building Serverless Logic with Azure"
tags: [Azure, Serverless, Functions, Cloud]
categories: [Cloud Security]
---

## 🧩 Problem Statement

Use Azure Functions to build serverless apps triggered by events such as HTTP requests, timers, and storage access.

---

## 🔍 Approach

1. Created Azure resources (Function App, Storage Account).
2. Configured a local .NET function project using Azure Core Tools.
3. Built three functions: one HTTP-triggered, one timer-triggered, and one integrating with Azure Blob Storage.
4. Deployed and tested the functions using `func` and Azure Portal.

---

## 🛠️ Tools Used

- Azure Portal
- Azure CLI
- Azure Functions Core Tools
- Visual Studio Code
- curl (for local function testing)

---

## 📸 Screenshots

### HTTP Trigger Test
![HTTP Echo Response](/assets/images/labs/azure-func-http.png)

### Timer Trigger Console Log
![Timer Logs](/assets/images/labs/azure-func-timer.png)

### Azure Deployment Success
![Azure Function Deployment](/assets/images/labs/azure-func-deploy.png)

---

## 📘 Key Lessons Learned

- Learned to develop and debug serverless logic locally and in the cloud.
- Gained confidence using CLI tools for deployment and config.
- Functions offer incredible flexibility when combined with cloud services.

