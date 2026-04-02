# Live at

[# Secure Certificate Vault](https://ritik1290.github.io/Certificate-vault/)

---

# Secure Certificate Vault

A hardened, front-end-only certificate verification system designed to prevent direct asset extraction while allowing controlled visual access.

---

## Overview

This project hosts academic and professional certificates in a protected viewing environment. It is intentionally engineered to prevent direct downloads, scraping, and unauthorized reuse.

---

## Security Architecture

### 1. Data Layer Protection

* Certificates are embedded as Base64 encoded strings
* No raw files are stored or exposed in the repository
* Eliminates direct URL access and bulk scraping

### 2. Rendering Layer

* Certificates are rendered using the HTML5 Canvas API
* No `<img>` tags are used
* Prevents standard "Save Image As" functionality

### 3. Dynamic Watermarking

* Each certificate is rendered with:

  * Owner identification (Ritik Dhage)
  * “VERIFIED COPY” label
  * Real-time timestamp
* Ensures traceability of screenshots and misuse

### 4. Frontend Protection Suite

* Right-click disabled globally
* Developer tool shortcuts blocked
* DevTools detection system:

  * UI blur activation
  * Security overlay display

### 5. Build Security

* Single-file deployment (`index.html`)
* No visible file structure or asset directories
* Reduces attack surface for asset discovery

---

## Purpose

This system is designed strictly for **visual verification**.

Certificates are not intended for:

* Download
* Redistribution
* External usage

---

## Usage

Users may:

* View certificates via UI interaction

Users may NOT:

* Extract, copy, or reuse certificate data
* Attempt to bypass security mechanisms

---

## Legal Notice

All content is the intellectual property of the author.

Unauthorized use, duplication, or distribution is strictly prohibited and may result in legal action.

---

## Deployment

Hosted using GitHub Pages.

---

## Author

Ritik Dhage
