# 🚆 South Central Railways – Incident Management System (Academic Simulation using ServiceNow)

This repository showcases an academic simulation built as part of a pre-final year college project. It models a customized **Incident & Problem Management System** for **South Central Railways**, using ServiceNow to organize and resolve common passenger issues across five trains.

> ⚠️ **Disclaimer**: This project uses **mock data** and is intended solely for educational demonstration purposes. It does not represent actual incidents or official railway operations.

---

## 🎯 Project Objective

The goal of this simulation was to build a real-world use case for applying ITSM principles to railway operations. Using ServiceNow, we created a system that:

- Tracks passenger complaints and escalates them as incidents.
- Assigns roles (like Food Inspector, Medical Help, Electrician) to resolve them.
- Groups trains and passengers into subgroups for organizational clarity.
- Generates reports to visualize common problems and their frequency.
- Links relevant knowledge articles for passenger guidance and awareness.

---

## 🚆 Train Groups Simulated

South Central Railways (Parent Group) 
 ├── Ratnachal Express 
 ├── Godavari Express 
 ├── Seshadri Express 
 ├── Amaravathi Express 
 └── Sarkar Express


Each train group includes:
- 10 passengers
- 1 Train Controller (TC)
- Incident records based on mock data
- Assigned railway officers (based on role and category)

---

## 🛠️ Technologies Used

- **ServiceNow Classic UI**
- Incident & Problem Management Modules
- Role-based Access Controls
- Knowledge Base Articles
- Reporting & Data Visualization

---

## 💡 Problem Categories Simulated

|           Problem          | Total Incidents |     Assigned Role      |
|----------------------------|-----------------|------------------------|
| Food Related Issues        | 15              | Food Inspector         |
| Power Issues               | 10              | Electrician            |
| Health Emergencies         | 10              | Medical Help           |
| Sanitation/Water Problems  | 6               | Train Supervisor       |
| Chain Pulling Incidents    | 5               | Protection Manager     |

---

## 📊 Reporting Dashboard Summary

Sample chart breakdown (mock data):

- 🥘 Food Issue: **29.17%**
- ⚡ Power Issue: **20.83%**
- ❤️ Health Issue: **14.58%**
- 💧 Water & Cleanliness: **8.33%**
- 🔗 Chain Pulling: **8.33%**

Reports were generated using ServiceNow's visualization tools.

---

## 📚 Sample Knowledge Articles

- `KB0010033 – How Can We Prevent Health Issues?`
- `KB0010038 – Food in Railway Stations`
- `KB0010041 – ServiceNow for Central Railways Overview`

These articles were linked to incident records to provide real-time guidance to passengers.

---

## 📁 Repository Structure

/railway-incident-management-servicenow
├── Documentation/
│   └── ServiceNow for railways(problems).pdf     
├── KnowledgeArticles/
│   └──  screenshots
├── Reports/
│   └── Incident charts and summaries             ← Mock visualizations or analytics
├── README.md                                     ← Project overview & guide


---

## 👥 Project Contributors

This simulation project was developed as part of our **final year academic curriculum**.

**Team Members:**
- Raj Kumar Pammi – System Architecture, Group Management, Incident Modeling
- Sai Anil  – Reporting Dashboard, Problem Management, Knowledge Articles
- Siva Charan – UI Navigation, User Roles, Data Organization
- Bharath – Documentation, Presentation Design, QA


---

## 📝 Notes

- This is a simulation project, not a production environment.
- All content is educational, with no real passenger or railway data involved.
- Designed to showcase how ServiceNow can be customized for non-IT sectors.

---

Thank you for visiting this project! If you have suggestions or would like to collaborate on public sector simulations using ITSM platforms, feel free to connect.