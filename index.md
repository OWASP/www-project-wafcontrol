---

layout: col-sidebar
title: OWASP WAFControl
tags: owc
level: 2
type: code
pitch: The first modern, open-source web-based dashboard for managing ModSecurity and OWASP CRS with zero command-line complexity.

---
**The 1st Modern Web-Based GUI Dashboard for ModSecurity & OWASP CRS**

OWASP WAFControl is an open-source project that revolutionizes how security teams deploy and manage the OWASP Core Rule Set (CRS) and ModSecurity. Traditionally, setting up and tuning CRS requires deep technical knowledge and heavy command-line operations. WAFControl eliminates this barrier by providing a powerful, intuitive, and secure web-based GUI that automates installation, configuration, and management of CRS + ModSecurity, making advanced WAF protection accessible to everyone.

Our mission is to empower DevSecOps teams, security engineers, and administrators with a visual, streamlined platfor for WAF management reducing complexity while increasing security, visibility, and operational efficiency.


![owc Logo](assets/images/owclogo.png)

The official website of the project can be found at [https://wafcontrol.org](https://wafcontrol.org).

<!-- Toturials -->

## Licensing
OWASP OWC is free to use. It is licensed under the [Apache Software License version 2 (ASLv2)](https://www.apache.org/licenses/LICENSE-2.0), so you can copy, distribute and transmit the work, and you can adapt it, and use it commercially, but all provided that you attribute the work and if you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one. 

## Reporting Issues

* If you think you've found a false positive in commercially available software and want us to take a look, [submit an issue here](https://github.com/wafcontrol/wafcontrol/issues/new/choose) on our Github
* Have you found a false negative/bypass? See our [policy](https://github.com/wafcontrol/wafcontrol/security/policy) first on how to contact us.

## Key Features


✅ **Attack Control**  
- All Attacks Log : Centralized view of all incoming attacks with rich metadata (attack type, IP, country, triggered rule, targeted domain, timestamp).  
- Critical WAF Attacks : Focused dashboard for high-severity threats (SQLi, RCE, LFI, XSS, etc.) with complete forensic details.  
- Top Attackers : Identify the most aggressive IPs based on attack volume and patterns.  

✅ **Rule Management**  
- Rule Browser & Editor : Load, view, and edit all OWASP CRS rules directly in the dashboard.  
- Rule Viewer by ID : Categorized rule inspection with search and filter options.  
- Enable/Disable Controls : Quickly toggle specific rules without touching configuration files.  

✅ **CRS Control**  
- Version Switcher : Fetch and switch between CRS releases from GitHub in one click.  
- CRS & ModSecurity Settings : Full GUI control for advanced settings:  
- Custom Rules : Create and manage personalized rules with support for transformations, chaining, tags, and severity levels.  

✅ **System & Security**  
- Automated WAF Installation : WAFControl fully automates the setup of ModSecurity + OWASP CRS on both Nginx and Apache web servers.  
  With just a few clicks, administrators can prepare their servers, install all required dependencies, and deploy a production-ready WAF — without dealing with complex manual configurations.  
- Unified Dashboard Management : Once installed, both Nginx- and Apache-based environments can be managed seamlessly through the same intuitive web-based GUI.  
- Secure Authentication : Built-in admin panel with secure login (2FA-ready).  

OWASP WAFControl is ready to serve as a robust open-source GUI for ModSecurity + CRS management, with a strong long-term vision for innovation in WAF usability and security intelligence.

