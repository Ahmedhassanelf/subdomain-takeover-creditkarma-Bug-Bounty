# subdomain-takeover-creditkarma-Bug-Bounty
Subdomain Takeover vulnerability discovery and analysis on Credit Karma 
# 🔥 Subdomain Takeover Case Study - Credit Karma

## 📌 Overview

This repository documents a **Subdomain Takeover vulnerability** discovered during reconnaissance on Credit Karma assets.

The issue was related to a **misconfigured DNS record (CNAME)** pointing to an unclaimed third-party service.

---

## 🧠 Vulnerability Type

* Subdomain Takeover
* Domain Misconfiguration
* Third-Party Service Mismanagement

---

## 🎯 Affected Subdomains

* [www.creditkarma.com](http://www.creditkarma.com)
* accounts.creditkarma.ca

---

## 🔍 Discovery Process

### 1. Reconnaissance

I started with subdomain enumeration using common recon techniques.

### 2. DNS Analysis

The discovered subdomain was pointing to a third-party service via CNAME.

### 3. Service Identification

The service was identified as **Gemfury**.

### 4. Exploitation

The domain was not claimed on the third-party service, allowing me to:

* Register it on my own account
* Take control of the subdomain

---

## ⚠️ Impact

* Phishing attacks on trusted domains
* Potential session hijacking (cookies)
* Severe reputation damage

---

## 📸 Proof of Concept

![Takeover Proof](images/takeover-proof.png)

---

## 🧾 Result

The report was marked as **Informative**, likely due to business or third-party risk considerations.

However, I later received an **invite to a private bug bounty program**, which was a valuable outcome.

---

## 💡 Key Takeaways

* Always verify third-party integrations
* DNS misconfigurations can lead to critical impact
* Subdomain takeover remains a high-risk issue

---

## 👤 Author

Ahmed Hassan Elfokery| Security Researcher | Bug Bounty Hunter

