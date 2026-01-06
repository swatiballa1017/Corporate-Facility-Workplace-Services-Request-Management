# Corporate-Facility-Workplace-Services-Request-Management

# 🏢 ServiceNow Facility & Workplace Request Management

A real-time enterprise ServiceNow project designed to manage corporate facility and workplace service requests using configuration-based solutions (NO scripting).

This project demonstrates hands-on implementation of ServiceNow core modules including Service Catalog, Flow Designer, SLA, Import Sets, Data Policies, and Task-extended tables.

---

## 📌 Business Use Case

Organizations need a centralized system where employees can request:

- ID card creation  
- Office access  
- Seat allocation / desk movement  
- Maintenance support (AC, lighting, housekeeping)

The system should automatically route requests, apply SLAs based on priority, and support bulk data uploads.

---

## 🎯 Project Objectives

- Build a real-world ServiceNow application extending the Task table  
- Automate assignment without scripting  
- Enforce data rules at server level  
- Track SLAs  
- Support catalog-driven and bulk request creation  
- Follow interview-standard ServiceNow best practices  

---

## 🧩 Key Features Implemented

✔ Custom table extending Task  
✔ Service Catalog item with variables and variable sets  
✔ Dependent fields using UI Policies  
✔ Reference qualifiers  
✔ Flow Designer for auto-assignment  
✔ SLA definitions based on priority  
✔ Data Policies (server-side validation)  
✔ Import Sets for bulk upload  
✔ Role-based user and group configuration  
✔ End-to-end request lifecycle  

---

## 🏗 Architecture Overview

**User → Service Catalog → Custom Task Table → Flow Designer → Assignment Group → SLA Tracking → Closure & Reporting**

Requests can also be created via Import Sets while still enforcing Data Policies and SLAs.

---

## 🛠 Modules & Technologies Used

- ServiceNow Service Catalog  
- Custom Tables (Task extension)  
- Flow Designer  
- SLA Framework  
- Import Sets & Transform Maps  
- Data Policies  
- UI Policies  
- User & Group Administration  
- Reference Qualifiers  

---

## 📸 Screenshots Included

- Custom table extending Task  
- Service Catalog form  
- Dependent variables  
- Flow Designer logic  
- SLA configuration  
- Data policy  
- Import set and transform map  

(Refer to `/screenshots` folder)

---

## 🚀 End-to-End Flow

1. Employee submits a catalog request  
2. Dependent fields guide correct data input  
3. Record is created in a Task-extended table  
4. Flow Designer auto-assigns to the correct group  
5. SLA starts based on priority  
6. Data policy enforces mandatory rules  
7. Request is resolved and closed  

---

## 🎓 Interview-Ready Summary

“I implemented a full facility service management solution in ServiceNow using Service Catalog, Task-extended tables, Flow Designer, SLAs, and Import Sets with zero scripting, following enterprise best practices.”

---

## 👤 Author

Swati Balla 
ServiceNow Administrator & Developer  
3+ Years Experience
---

This project represents a real-world enterprise implementation focused on architecture, automation, and platform best practices rather than basic form customization.

---
