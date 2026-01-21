# 🎟️ Ticket Management Automation Using PowerShell & ServiceNow

## 🎬 Watch Me Build This Lab!
https://www.loom.com/share/871652f4f99f42abbeb47ab3d3df7738

## 🎯 Objective
This lab documents the process of automating ticket creation and verification using **PowerShell scripts** integrated with **ServiceNow**. The goal is to demonstrate how scripting can streamline IT service management workflows and reduce manual effort.

## 🛠️ Tools Used
- **Windows PowerShell**
- **ServiceNow Developer Instance**
- **AWS Virtual Machine (Windows)**
- **Notepad (script editing)**
- **Web Browser (ServiceNow access)**


## 🧩 Lab Steps

### 💻 Environment Setup
- Log into your virtual machine hosted on AWS.
- Navigate to **This PC** and open the **Windows (C:) drive**.
- Right-click → **New** → **Folder**.
- Name the folder **`scripts`**.
- Open the **scripts** folder.

### 📄 Script Creation
- Right-click inside the folder → **New** → **Text Document**.
- Name the file **PowerShell incident**.
- Open the file in **Notepad**.
- Paste your PowerShell script into the blank document.
- Click **File → Save As**.
- Confirm the file is saved in the **scripts** folder.
- Change the file extension to **`.ps1`** and click **Save**.

### 🌐 ServiceNow Configuration
- Open a web browser and navigate to **developer.servicenow.com**.
- Log in using your temporary email.
- Select **Create or Launch My Instance**.
- Ensure the instance is running the latest version (e.g., **Zerk**).
- Click **Manage My Instance**.
- Record the following details:
  - Instance URL  
  - Username (**admin**)  
  - Password  

### ▶️ Script Execution
- Open **Windows PowerShell**.
- Copy and paste your PowerShell script into the PowerShell window.
- Press **Enter** to execute the script.
- Locate the generated **incident number** at the top of the PowerShell output.
- Copy the incident number.

### 🔍 Incident Verification
- Return to **ServiceNow**.
- Click **Start Building**.
- Navigate to **All Incidents**.
- Confirm:
  - View is set to **Default View**
  - Filters are set to **None**
- Paste the incident number into the search field.
- Verify that the incident appears in the incident list.


## ✅ Outcome
- Successfully automated incident creation using PowerShell.
- Verified real-time ticket creation within ServiceNow.
- Demonstrated integration between scripting and ITSM platforms.
- Reduced manual ticket creation steps, improving operational efficiency.
- Gained hands-on experience with ServiceNow Developer Instances and PowerShell automation.
