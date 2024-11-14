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