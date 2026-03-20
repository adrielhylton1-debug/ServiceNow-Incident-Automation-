Automating Servicenow Incident tickets using Powershell
# ServiceNow Incident Automation (PowerShell REST API)

**Walkthrough (Loom):** PASTE_LOOM_LINK_HERE

---

## 🧩 Objective
Automate the creation of ServiceNow incident tickets using **PowerShell** and the **ServiceNow REST API**, eliminating manual ticket entry and demonstrating scripting skills relevant to IT support and operations roles.

---

## 🧠 Skills Practiced
- Writing and executing PowerShell scripts  
- Authenticating to REST APIs using Basic Auth  
- Constructing and sending JSON payloads via HTTP POST  
- Parsing API responses to extract incident numbers  
- Validating automated workflows in ServiceNow  

---

## 🧰 Tools Used
- PowerShell  
- ServiceNow Developer Instance  
- ServiceNow REST API (Table API)  
- JSON  

---

## 🪜 Steps Performed (with screenshots)

### 1) Prepared the PowerShell script (credentials, headers, JSON payload)
![PowerShell script setup](images/ticket-automation-01-script.png)

---

### 2) Executed the script and captured the created incident number
![Incident number returned](images/ticket-automation-02-output.png)

---

### 3) Verified the incident was created in ServiceNow (Incidents list)
![Incident appears in list](images/ticket-automation-03-list.png)

---

### 4) Confirmed the incident record fields were populated from the JSON body
![Incident record populated](images/ticket-automation-04-record.png)

---

## ✅ Outcome
Successfully automated incident creation in ServiceNow using PowerShell and REST API calls, demonstrating the ability to streamline repetitive Help Desk tasks through scripting.
