![SBOMinator Logo - Secure Your Software Supply Chain](https://github.com/sbominator/docs/blob/main/images/Logo.png?raw=true)

# SBOMinator 3000: Secure Your Software Supply Chain

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](#)]

---

## 📚 Table of Contents
- [Introduction](#introduction)
- [What is an SBOM?](#what-is-an-sbom)
- [The Problem](#the-problem)
- [Our Solution](#our-solution)
- [Key Use Cases](#key-use-cases)
- [How It Works](#how-it-works)
- [Getting Started](#getting-started)
- [License](#license)

---

## 🤔 Introduction
SBOMinator is an open source tool designed to simplify the creation and management of Software Bills of Materials (SBOMs). It enhances the security of your software supply chain by tracking every component—whether it's a plugin, theme, or library—used in your website or application. With modern CMS platforms and PHP frameworks in mind, SBOMinator empowers site owners and developers to manage vulnerabilities proactively.

📄 **Learn more:** [Overview](overview/overview.md)

---

## 🔍 What is an SBOM?
An **SBOM (Software Bill of Materials)** is a detailed "ingredients list" for software. It includes every code component used in your project, version details, and security information. This comprehensive inventory makes it easier to:
- Identify outdated or vulnerable components.
- Verify the integrity of each dependency.
- Comply with security standards and audits.

📄 **Learn more:** [What is an SBOM?](overview/What-is-an-SBOM.md)  

📖 **SBOM Standards:**  
- [SPDX](https://spdx.dev)  
- [CycloneDX](https://cyclonedx.org)  

---

## ⚠️ The Problem
Modern web projects often rely on a myriad of third-party components, which introduces several risks:
- **Compromised Ingredients:**  
  If one piece of code is tampered with or contains a hidden flaw, the entire website can be exposed to attacks (e.g., a hacked plugin allowing malicious code injection).  
- **Outdated Components:**  
  Relying on legacy or unsupported libraries makes your site susceptible to known exploits.
- **Repository Hijacking:**  
  Attackers may compromise trusted code repositories, potentially infecting every project that uses the affected component.

📄 **Learn more:** [Software Supply Chain](overview/Software-Supply-Chain.md)

---

## 🚀 Our Solution
**SBOMinator** automates the generation, ingestion, and ongoing monitoring of SBOMs to ensure your software remains secure:
- **Automated SBOM Generation:** Quickly compile a comprehensive list of all dependencies.
- **Seamless Integration:** Built for popular CMS platforms like WordPress and TYPO3, as well as PHP frameworks like Laravel and Symfony.
- **Real-Time Insights:** Provides continuous security data so you can act swiftly when vulnerabilities are discovered.

📄 **Learn more:** [Use Case](overview/use-case.md)

---

## 👥 Key Use Cases
- **Site Owners:**  
  Generate or review SBOMs during deployment, updates, and routine maintenance to ensure that every code component is secure and current. Increased adoption expected by governmental organizations, civic organizations, and enterprise agencies. 
- **Compliance Officers:**  
  Leverage SBOMs during audits to verify that all components meet regulatory and industry standards.
- **Web Hosts & Agencies:**  
  Monitor multiple websites through automated SBOM reports to proactively identify and remediate vulnerabilities.

📄 **Learn more:** [Users & Personas](overview/users-personas.md)

---

## ⚙️ How It Works
SBOMinator scans your project’s dependencies to produce an SBOM that details:
- Component names and versions.
- Source and licensing information.
- Known vulnerabilities and security advisories.

This "ingredients list" serves as a checklist for maintaining the integrity and security of your entire software supply chain.

📄 **Learn more:** [Keep Going](overview/keep-going.md)

---
