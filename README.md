# 🎓 Educational Organisation Using ServiceNow 
### Naan Mudhalvan Project | Team ID: NM2025TMID01468

This project demonstrates how an educational institution can automate and streamline student-related operations 
using the ServiceNow platform. The system includes student master creation, admission management, academic 
progress tracking, automated number generation, client-side validations, and workflow automation.

---

## ✅ Project Objectives
- Automate student lifecycle operations  
- Reduce manual data entry and errors  
- Implement structured tables for student, admission, and progress data  
- Enable dynamic form behavior using client scripts  
- Use Flow Designer for admission process automation  
- Improve academic tracking through auto calculations  
- Provide clean UI with form layouts and sections  

---

## ✅ System Architecture 
User → ServiceNow UI → Server-Side Tables → Client Scripts → Process Flow → Output Forms

---


---

## ✅ Features Implemented

### ✅ Custom Tables
- **Salesforce Table (Student Master)**
- **Admission Table**
- **Student Progress Table**

### ✅ Number Maintenance
- Auto-generation of Admin Number using *Get Next Padded Number*

### ✅ Form Design
- Drag-and-drop forms with proper field arrangement  
- Tabbed & section-based layouts  

### ✅ Client Scripts
- Auto Populate Script  
- Dynamic Pincode → State/District update  
- Disable Fields script  
- Total Marks Calculation  
- Percentage Calculation  
- Result (Pass/Fail) Script  

### ✅ Process Flow
- Admission Approval Flow  
- Status update automation  

---

## ✅ Project Modules Overview

### 📌 Salesforce Table (Student Master)
Fields included:
- Admin Number (Auto generated)
- Student Name  
- DOB  
- Gender  
- Grade (Choice values)
- Contact Details  

### 📌 Admission Table
Fields included:
- Student Reference  
- Address  
- Pincode → Auto State/District  
- Admission Status (Choice)  
- Aadhaar, Mail, Mobile No.  

### 📌 Student Progress Table
Fields included:
- Student Reference  
- Subject Marks  
- Total  
- Percentage  
- Result (Auto-calculated)  

---

## ✅ How to Execute the Project

### ✅ Step 1 — Login to ServiceNow Personal Developer Instance
1. Go to https://developer.servicenow.com  
2. Launch your PDI  

### ✅ Step 2 — Create Update Set
- Navigate → *System Update Sets → Local Update Sets*  
- Create new update set & mark as **Current**  

### ✅ Step 3 — Create Required Tables
- Salesforce (Student Master)  
- Admission  
- Student Progress  

### ✅ Step 4 — Apply Number Maintenance
- Go to *Number Maintenance*  
- Configure prefix, padding & sequence  

### ✅ Step 5 — Build Forms Using Form Designer
- Add sections  
- Drag and arrange fields  

### ✅ Step 6 — Add Client Scripts
- Auto populate  
- Pincode update  
- Disable fields  
- Total, percentage, result  

### ✅ Step 7 — Build Process Flow
- Use **Flow Designer**  
- Trigger on record update  
- Add approval/action steps  

### ✅ Step 8 — Test End-to-End Workflow
1. Create Student Record  
2. Create Admission Record  
3. Create Student Progress Record  
4. Validate automation  

---


---

## ✅ Technologies Used
- ServiceNow Platform  
- JavaScript (Client Scripts)  
- Flow Designer  
- UI Policies & Form Layouts  
- Number Maintenance Module  

---

## ✅ Team Details
**Team ID:** NM2025TMID01468  
**Project:** Educational Organisation Using ServiceNow
**Program:** Naan Mudhalvan  

---

## ✅ Conclusion
This project successfully demonstrates how ServiceNow can transform educational institution management 
by automating admissions, student tracking, and academic performance management using tables, forms, 
scripts, and workflows.

