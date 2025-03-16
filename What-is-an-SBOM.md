

😊 **What is an SBOM?**

* **SBOM** stands for **Software Bill of Materials**.  
  * Think of it as a detailed ingredients list for software. Just like a recipe tells you every ingredient that goes into a cake, an SBOM lists all the code components, libraries, and modules that make up a piece of software.  
  * It includes information like the version numbers, licenses, and sometimes even known security issues of each component.

---

📜 **Who Created the Concept and When?**

* The idea of having a "bill of materials" comes from manufacturing, where it’s common to list every part needed to build a product.  
* **In software,** this concept evolved gradually:  
  * **Early 2010s:** Groups in the open source and cybersecurity communities began adapting this idea to improve transparency in software development.  
  * **Key Milestones:**  
    * The **SPDX (Software Package Data Exchange) standard**, developed under the Linux Foundation, started formalizing how to list these components around 2011\.  
      * Learn more at the [SPDX website](https://spdx.dev/).  
    * Later, other standards like **CycloneDX** emerged, and the concept gained a lot more attention when supply chain attacks became a major concern.  
  * **Recent Boost:** In May 2021, the U.S. government emphasized SBOMs in Executive Order 14028 to enhance software security across federal agencies.  
    * You can read about the [Executive Order 14028 here](https://www.whitehouse.gov/briefing-room/presidential-actions/2021/05/12/executive-order-on-improving-the-nations-cybersecurity/).

---

🛠 **What Does an SBOM Involve for CMS and PHP Frameworks?**

* **For Content Management Systems (CMS)** like WordPress, Drupal, and Joomla, and PHP frameworks like Laravel and Symfony, an SBOM is particularly useful because:  
  * **Component Tracking:**  
    * To work correctly, these systems rely on many parts—like plugins, themes, modules, and external libraries.  
    * An SBOM helps developers keep track of every piece, so they know exactly what is running on their site.  
  * **Security:**  
    * If one component has a security flaw or gets compromised, an SBOM makes it easier to identify, update, or remove that vulnerable piece.  
  * **Compliance and Maintenance:**  
    * It provides transparency and documentation that can be important for audits or regulatory checks.  
    * It’s like having a checklist to ensure every ingredient in your software is safe and up-to-date.

---

🔗 **Additional Resources**

* [SPDX (Software Package Data Exchange)](https://spdx.dev/) – for detailed standards on SBOM creation.  
* [CycloneDX](https://cyclonedx.org/) – another widely used standard for SBOMs.  
* [Executive Order 14028 on Improving the Nation’s Cybersecurity](https://www.nist.gov/itl/executive-order-14028-improving-nations-cybersecurity) – U.S. government directive that boosted SBOM adoption.  
* [NTIA’s Guidance on Software Component Transparency](https://www.ntia.gov/) – insights into government efforts for supply chain security.

