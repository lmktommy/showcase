# Tommy LIU

**Former IT Manager at LVMH | MSP | IT Service | IT Helpdesk | IT Infrastructure | Workflow Automation | IT in Luxury Brands | ITIL**

[LinkedIn](https://www.linkedin.com/in/lmktommy) UK

---

## **Professional Summary**  

Versatile IT professional with over 15 years of experience in IT management, infrastructure, and service delivery across diverse industries, including luxury retail and managed service providers. Proven track record in implementing innovative IT solutions, optimizing processes, and driving digital transformation initiatives. Skilled in cloud technologies, workflow automation, and IT security, with a strong focus on enhancing operational efficiency and user experience. Adept at managing complex IT projects, leading cross-functional teams, and aligning technology strategies with business objectives. Committed to continuous learning and staying current with emerging technologies to deliver cutting-edge solutions in fast-paced environments.

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

### Telegram with Bot Operation (Doucmentation and Handles on json, API)

#### Bot Creation in Telegram

<img src="telegram-bot creation.gif" alt="placeholder" width="50%" height="50%">
<!-- ![alt text](<telegram-bot creation.gif>){width=40% } -->

#### Chat Group Creation in Telegram

<img src="telegram-new chat group with history.gif" alt="placeholder" width="50%" height="50%">
<!-- ![alt text](<telegram-new chat group with history.gif>){ width=40% } -->

#### Chat Group ID Collection in Telegram

<img src="telegram-add bot and chat ID.gif" alt="placeholder" width="50%" height="50%">
<!-- ![alt text](<telegram-add bot and chat ID.gif>){ width=40% } -->

### Node-RED (Automation, Montioring and Testing Tool)

![alt text](<Screenshot 2024-10-08 at 4.51.40 PM.png>)

### Helpdesk Workflow

![alt text](<Helpdesk Workflow.png>)


### Helpdesk Documentation Template

#### 📝 Article Title
(Clear and descriptive. Example: "How to Reset Your Office 365 Password")

#### 📌 Overview
(Brief purpose of this article. Example: "This guide explains how users can reset their password using the Office 365 self-service portal.")

#### 🎯 Scope & Audience
	• Applies to: (End Users / IT Staff / Admins)
	• Systems: (e.g., Windows 11, Office 365, VPN Portal)
	• Departments / Roles: (if applicable)

#### ✅ Prerequisites / Before You Begin
	• (List requirements: access, tools, permissions, account details, VPN, etc.)
	• (Example: "You must know your employee ID and have access to your recovery email.")

#### ⚙️ Procedure / Step-by-Step Instructions
	1. (Step 1 instruction here — include screenshots if possible)
	2. (Step 2 instruction here)
	3. (Step 3 instruction here)

#### 📊 Verification / Expected Outcome
	• (Describe what should happen if procedure is followed correctly)
	• (Example: "You will receive a confirmation email and be able to log in with your new password.")

#### 🛠️ Troubleshooting / Known Issues
	• (Problem 1 → Solution)
	• (Problem 2 → Solution)
	• (FAQs if relevant)

#### 📎 References / Related Articles
	• (Link to related KBs or vendor documentation)
	• (Internal IT policy references, if any)

#### 📢 Escalation / When to Contact IT
	• (When self-service does not work, provide clear escalation path)
	• (Example: "If you are unable to reset your password, contact the Service Desk at xxxxx or submit a ticket under 'Password Issues'.")

#### 🗑️ Dismiss / Decommission (if applicable)
	• Retirement Date: (dd/mm/yyyy)
	• Replacement Process / System: (new tool, new KB link, etc.)
	• Contact for Transition Support: (team or owner)

#### 🔒 Security / Compliance Notes (Optional)
	• (Any sensitive information handling requirements, GDPR notes, data classification, etc.)

#### 🕒 Review & Change History
	• Created: (dd/mm/yyyy by [Author])
	• Last Updated: (dd/mm/yyyy by [Editor])
	• Next Review Due: (dd/mm/yyyy)
	• Version Notes: (e.g., v2.0 – Updated screenshots for new portal UI)

#### 📂 Metadata (system-generated or admin fields)
	• Category / Subcategory: (e.g., Password Issues > Office 365)
	• Keywords / Tags: (to improve searchability)
	• Owner / Author: (team name or person)
	• Visibility: (Internal IT only / End-User Facing)
