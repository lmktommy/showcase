# Tommy LIU

**Former IT Manager at LVMH | MSP | IT Service | IT Helpdesk | IT Infrastructure | Workflow Automation | IT in Luxury Brands | ITIL**

[LinkedIn](https://www.linkedin.com/in/lmktommy) UK

---

## **Professional Summary**  

Versatile IT professional with over 15 years of experience in IT management, infrastructure, and service delivery across diverse industries, including luxury retail and managed service providers. Proven track record in implementing innovative IT solutions, optimizing processes, and driving digital transformation initiatives. Skilled in cloud technologies, workflow automation, and IT security, with a strong focus on enhancing operational efficiency and user experience. Adept at managing complex IT projects, leading cross-functional teams, and aligning technology strategies with business objectives. Committed to continuous learning and staying current with emerging technologies to deliver cutting-edge solutions in fast-paced environments.

---

## **Core Competencies**

- **IT Infrastructure Management**: Extensive experience in managing and optimizing complex IT infrastructures, including cloud services, on-premises systems and hybrid environments.

- **Cloud Services Administration**: Proficient in administering and managing cloud services, particularly Microsoft Azure, including resource provisioning, configuration, monitoring, and optimization.

- **Network Security & Management**: Strong skills in maintaining and updating network equipment, including firewalls, routers, switches, and access points from various vendors like SonicWall, UniFi, DrayTek, and Cisco.

- **Workflow Automation**: Expertise in developing scripts and automation tools using PowerShell, JavaScript, and other languages to streamline IT processes and improve efficiency.
IT Service Management: Proven ability to implement and manage IT service systems like ServiceNow, enhancing service delivery and user satisfaction.

- **Mobile Device Management**: Skilled in deploying and managing mobile devices using platforms like AirWatch, Intune, and Apple Business Manager.

- **Data Backup & Recovery**: Experience with data backup and restoration using systems like Purview, Veeam and Datto.

- **IT Security**: Proficient in implementing and managing IT security measures, including email security (Mimecast), Active Directory management, and multi-factor authentication.
Project Management: Demonstrated ability to lead and complete complex IT projects, often within tight timeframes and exceeding performance expectations.

- **Vendor Management**: Experience in managing relationships with multiple clients and vendors, ensuring service delivery within SLAs.

- **Cloud Migration**: Successful track record in migrating on-premises systems to cloud platforms, improving accessibility and reducing costs.

- **IT Asset Management**: Developed and implemented IT inventory systems, improving compliance and reducing audit times.

- **Continuous Improvement**: Consistently seeks and implements innovative solutions to enhance IT operations and user experience.

---

## **Technical Proficiencies**  

### **Cloud & Infrastructure**

- **Enterprise Cloud Platforms**: Advanced implementation and management of Microsoft Azure, AWS, and Google Cloud Platform
SaaS & Collaboration: Expert-level administration of Office 365 ecosystem, including Exchange Online, SharePoint, and MS Teams

- **Low-Code Development**: Proficient in PowerApps, Power BI, and Power Automate for business process automation

### **Network Architecture & Security**

- **Network Infrastructure**: Design and optimization of complex networks using SonicWall, UniFi, DrayTek, and Cisco technologies

- **Advanced Networking Protocols**: In-depth knowledge of TCP/IP stack, VoIP implementation, and enterprise WiFi solutions

- **Cybersecurity**: Implementation of multi-layered security strategies, including MFA and email security (Mimecast, Darktrace)

### **Systems & Virtualization**

- **Cross-Platform Expertise**: Proficient in Windows Server, Linux distributions, and macOS environments

- **Virtualization Technologies**: Advanced usage of VMware suite and containerization with Docker
- **Database Management**: Skilled in Microsoft SQL Server and MySQL optimization and administration

### **DevOps & Automation**

- **Scripting & Development**: Advanced scripting in PowerShell and Node.js

- **Version Control**: Experienced with Git (source control and versioning)

- **Infrastructure as Code**: Implementing automated deployment and configuration management

### **Enterprise Mobility & Device Management**

- **MDM Solutions**: Expert configuration of Intune, AirWatch, and Apple Business Manager
- **BYOD Strategies**: Implementation of secure, scalable BYOD policies and infrastructure

### **IT Service Management & Governance**

- **ITSM Platforms**: Advanced configuration of ServiceNow, ManageEngine, and LANDesk
ITIL Framework: Practical application of ITIL best practices in enterprise environments

- **Compliance & Governance**: Implementation of ISO 27001 standards and IT governance frameworks

### **Data Management & Analytics**

- **Backup & Disaster Recovery**: Design of robust backup strategies using Veeam and Datto

- **Business Intelligence**: Data visualization and analytics using Power BI and custom dashboards

### **Emerging Technologies**

- **AI & Machine Learning**: Practical application of TensorFlow for IT operations and predictive analytics
- **Enterprise IAM Solutions**: Implementation and management of OKTA and InWebo for secure access control
- **Zero Trust Architecture**: Design and implementation of zero trust security such as Zscalar

---

## **Achievements**  

- **IT Inventory System Development**: Created an innovative IT Inventory system using NodeJS, MSSQL, MS Teams, and Power Automate, integrating software license and contract management. This system achieved compliance with internal audits within 6 months and reduced audit time by over 50%.

- **Deployment Optimization**: Implemented a zero-day deployment strategy for mobile devices on AirWatch, resulting in a 70% reduction in deployment time. This was accomplished within a 4-month timeframe.

- **Process Automation**: Automated equipment lifecycle management, software license, and contract management processes, leading to a 70% reduction in workload time over a 9-month period.

- **Service Management Enhancement**: Successfully introduced ServiceNow IT Service System within 4 months, increasing usage by 70%.

- **Cloud Migration**: Led the migration of shared files from on-premises servers to Cloud Storage (SharePoint / Teams) in 6 months, reducing maintenance costs by approximately 30%.
SLA Redesign: Redesigned SLA and Service Priority structures over 4 months, resulting in a boost in user acceptance rates by over 80%.

- **Business Continuity**: Established a VMware instance to ensure uninterrupted service for Government Customs Clearance in the Logistics Department within 2 weeks, enabling 100% online service provision.

- **Security Enhancement**: Deployed high-security authorization (MFA) for approximately 80 users in 3 months.

- **Data Transfer Improvement**: Implemented large data transfer with data protection (Amazon cloud), enhancing file transfer time by over 50%.
Communication Infrastructure Upgrade: Deployed Skype for Business Video Conference with Office 365 in 4 weeks, improving stabilization by over 50% (measured by ticket reduction).

---

## **Project, Showcase and Workflow**

### Automation of IT Asset Management System

![alt text](<Automated IT Helpdesk System.jpeg>)

### Automation of IT Asset Management System

![alt text](<endpoint security - client.png>)

### Cyber Security - Message Delivery (Public & Private Key)

![alt text](<Jun-01-2024 17-00-41.gif>)

### Template of Powershell script

```powershell
Set-ExecutionPolicy Bypass -Scope CurrentUser -Force

$isAdmMode = ([Security.Principal.WindowsPrincipal] [Security.Principal.WindowsIdentity]::GetCurrent()).IsInRole([Security.Principal.WindowsBuiltInRole] "Administrator")

Write-Output "**************************************************************************************"
Write-Output "Current Date        - $(Get-Date -Format 'yyyy MMM dd HH:mm K')"
Write-Output "PowerShell Version  - $($PSVersionTable.PSVersion)"
Write-Output "Computer Name       - $env:computername"
Write-Output "Is Admin Mode       - $isAdmMode"
Write-Output "Current Path        - $(Get-Location)"
Write-Output "Login Account       - $([System.Security.Principal.WindowsIdentity]::GetCurrent().Name)"
Write-Output "Current Script Name - $($MyInvocation.MyCommand.Name)"
Write-Output "Ticket              - #<ticket number>"
Write-Output "Customer            - <customer name>"
Write-Output "Script description  - <description>"
Write-Output "**************************************************************************************"

<#
**************************************************************************************
Created by: <Creator name>
Creation Date: 2023-02-02

Change History
2023-02-02 Init of this program
**************************************************************************************
#>

[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
```

### Telegram with Bot Operation (Handles on json, API)

<img src="telegram-bot creation.gif" alt="placeholder" width="50%" height="50%">
<!-- ![alt text](<telegram-bot creation.gif>){width=40% } -->

<img src="telegram-new chat group with history.gif" alt="placeholder" width="50%" height="50%">
<!-- ![alt text](<telegram-new chat group with history.gif>){ width=40% } -->

<img src="telegram-add bot and chat ID.gif" alt="placeholder" width="50%" height="50%">
<!-- ![alt text](<telegram-add bot and chat ID.gif>){ width=40% } -->
