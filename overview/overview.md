
# SBOMinator 3000 Overview

**Introduction**  
SBOMinator 3000 is a tool that enhances Software Bill of Materials (SBOM) management and strengthens software supply chain security for CMS platforms and PHP frameworks. It helps developers, security teams, and compliance officers quickly identify and fix vulnerabilities in third-party code.

**Problem Statement**

* **Third-Party Dependencies:**  
   Many websites rely on plugins, themes, and libraries that may become outdated or compromised, increasing security risks.  
* **Regulatory Demands:**  
  [Executive Order 14028](https://www.nist.gov/itl/executive-order-14028-improving-nations-cybersecurity) and the [EU Cyber Resilience Act](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act) require clear supply chain transparency and secure practices.  
* **Inconsistent SBOM Practices:**  
  Multiple SBOM formats (e.g., SPDX, CycloneDX) can make integration into CMS and PHP frameworks challenging.

**SBOMinator Solution**

* **SBOM Aggregator:**  
  Quickly compiles a detailed list of all software components.  
* **PHP level library CMS agnostic**  
  It works at PHP level as light library that can be integrated with other systems  
* **Seamless Integration:**  
  Designed for popular CMS (WordPress, Drupal, Joomla) and PHP frameworks (Laravel, Symfony).  
* **Accurate Insights:**  
  Provides up-to-date compliance, license information and security data to enable proactive maintenance.  
* **User-Friendly Interface:**  
  Offers a Command-Line Interface (CLI), with plans for broader support.

### Output of this library

* Dependencies tree  
* CycloneDx based file: \`sbom.json\`

**Key Use Cases**

* **CMS & PHP Developers:**  
  Can be plugged into the maintenance system to keep plugins, themes, and libraries up-to-date and track vulnerabilities and supply chain information.  
* **Compliance Officers:**  
  Leverage SBOMs for audits and to ensure regulatory compliance.  
* **Web Hosts & Agencies:**  
  Monitor multiple sites and generate automated security reports to reduce maintenance costs. Monitoring numerous sites and generating automated security reports is essential to minimize maintenance costs effectively. Closely monitoring various locations can identify and address potential security threats promptly. Automated security reports streamline this process by providing regular updates and insights without the need for constant manual oversight. This saves time and reduces the resources required for maintenance, ultimately leading to cost savings.

## Next steps

* Connect to Threat intelligence to identify vulnerabilities and threats.  
* Check for outdated dependencies.

**Conclusion**  
SBOMinator is more than a documentation tool—it’s a proactive solution for maintaining secure and compliant websites. By actively using SBOM insights, organizations can safeguard their software supply chain and meet evolving security requirements.

<details>
  <summary>📌 Click to expand image description</summary>

  A flowchart diagram illustrating the process of generating and analyzing a Software Bill of Materials (SBOM) using SBOMINATOR.

  1. **Actor** (a person icon) initiates the process by generating an SBOM for their application.
  2. The process starts with **SBOMINATOR CLI**, which takes the path of the application.
  3. The SBOMINATOR CLI forwards the path to **SBOMINATOR** (a central processing unit in the diagram).
  4. SBOMINATOR ingests various sources, including:
     - **SBOM reports (SPDX, CycloneDX)**
     - **npm files**
     - **composer.json**
     - **SCA (Static Code Analyzer)**
  5. After processing, SBOMINATOR generates an **sbom-report.json** in either CycloneDX or SPDX format.
  6. SBOMINATOR also triggers three different plugins:
     - **Typo3 plugin**
     - **Laravel plugin**
     - **WP plugin**
  7. The WP plugin connects to **Site Health** and **WP-CLI**.
  8. The overall system helps integrate SBOM reports into different ecosystems for analysis.

  The diagram uses arrows to indicate the data flow between components and labels key elements in black and blue fonts, with shaded boxes for plugins and processing steps.

</details>

![SBOMinator Flowchart - Generating and Analyzing SBOMs](https://github.com/sbominator/docs/blob/main/images/sbominator-v1.png?raw=true)


