---
title: "Azure Authentication & Authorization Lab"
excerpt: "Implementing identity management using Microsoft Entra ID and ASP.NET Core."
layout: single
date: 2025-05-28
read_time: true
image: /assets/images/labs/azureauthcover.jpg
header:
  overlay_image: /assets/images/labs/azure-auth-flow.png
  caption: "Secure Sign-In with Entra ID and ASP.NET"
tags: [Azure, Authentication, Entra ID, ASP.NET]
categories: [Cloud Security]
---

## Problem Statement

Implement a secure login system using Microsoft Entra ID in a cloud environment. The goal was to integrate Azure identity services into a .NET web app for single-tenant sign-in.

---

## Approach

1. Set up Microsoft Entra ID with an application and user.
2. Configured authentication with proper redirect URIs and token handling.
3. Created and deployed a .NET MVC app using OpenID Connect and MSAL.
4. Tested login flow and validated user permissions.

---

## Tools Used

- Microsoft Azure Portal
- Entra ID (formerly Azure AD)
- Visual Studio Code
- .NET CLI
- OpenID Connect + MSAL

---

## Screenshots

### Entra ID App Registration
![Azure Entra ID App Setup](/assets/images/labs/azure-app-registration.png)

### Successful ASP.NET Login
![Authenticated User Dashboard](/assets/images/labs/azure-auth-success.png)

---

## Key Lessons Learned

- How to register and manage cloud applications in Azure Entra ID.
- Setting up token-based auth flows in ASP.NET securely.
- Debugging redirect URIs and token scopes is crucial in cloud auth.

