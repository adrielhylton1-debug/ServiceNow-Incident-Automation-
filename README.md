# ServiceNow-Incident-Automation-
Automating Servicenow Incident tickets using Powershell
# ServiceNow Incident Automation (PowerShell REST API)

**Walkthrough (Loom):** PASTE_LOOM_LINK_HERE

---

## 🧩 Objective
Automate ServiceNow incident creation using a PowerShell script that sends a structured JSON payload to the ServiceNow Table API and returns the newly created incident number.

## 🧠 Skills Practiced
- Building REST API requests in PowerShell (Basic Auth, headers, JSON body)
- Creating incidents via ServiceNow Table API (`/api/now/table/incident`)
- Validating API success via returned incident number
- Verifying data integrity in ServiceNow (list view + incident record)

## 🧰 Tools Used
- Windows PowerShell
- ServiceNow Personal Developer Instance (PDI)
- ServiceNow Table API (Incident)

---

## 🪜 Steps Performed (with screenshots)

### 1) Prepared the PowerShell script (credentials, headers, JSON payload)
Configured credentials (redacted), encoded Basic Auth, set request headers, and defined an incident JSON body to match manual ticket entry fields.
![PowerShell script setup](images/ticket-automation-01-script.png)

---

### 2) Executed the script and captured the created incident number
Ran the script and confirmed success by printing the returned incident number from the API response.
![Incident number returned](images/ticket-automation-02-output.png)

---

### 3) Verified the incident was created in ServiceNow (Incidents list)
Refreshed the incident list and confirmed the new ticket appears with matching incident number and short description.
![Incident appears in list](images/ticket-automation-03-list.png)

---

### 4) Confirmed the incident record fields were populated from the JSON body
Opened the incident record to verify the short description, urgency/impact, and other fields were populated as expected from the script payload.
![Incident record populated](images/ticket-automation-04-record.png)

---

## ✅ Outcome
Successfully automated incident creation in ServiceNow using PowerShell. The script generated a valid incident number and the incident record was confirmed in ServiceNow with the expected fields populated from the JSON request body.
