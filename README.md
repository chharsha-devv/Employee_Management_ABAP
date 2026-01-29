# Employee Management & Analytics Dashboard

This project is an SAP ABAP Module Pool application designed to manage employee information, attendance, performance, and overtime, along with generating interactive ALV reports for analytics and reporting.

## Features

### Employee Dashboard Module (Z104_EMP_DASHBOARD)
- Search employee details by Employee ID
- Update employee status in real-time
- Navigate to Attendance Entry screen
- Mark attendance with F4 calendar help
- Run Employee Report and Analytics Report
- Exit program gracefully

### Reports (SE38 Programs)
- **Employee Report (Z104_EMPLOYEE_REPORT)**
  - Displays employee master details in ALV table format
- **Analytics Report (Z104_EMP_ANALYTICS)**
  - Displays Attendance, Performance, and Overtime in separate ALV tables
  - Select report type using radio buttons

##Technical Concepts Used

- ABAP Module Pool Programming  
- Multiple Screens (0100 – Dashboard, 0200 – Attendance Entry, 300 – Analytics ALVs)  
- ALV Grid (CL_GUI_ALV_GRID, 2 ALVs on one screen using custom containers)  
- Custom Tables:  
  - Z104_EMP_MASTER  
  - Z104_ATTENDANCE  
  - Z104_EMP_PERF  
  - Z104_EMP_OT  
- CRUD Operations on Employee Status and Attendance  
- F4 Help for date selection  
- Modular PBO/PAI programming with function codes (Search, Update, Save, Back, Exit)

## Files in This Repository

- `Z104_EMP_DASHBOARD.abap` → Main module pool program (Dashboard & Attendance)  
- `Z104_EMPLOYEE_REPORT.abap` → Employee Report (SE38)  
- `Z104_EMP_ANALYTICS.abap` → Analytics Report (SE38)  
- `Project_Report_Employee_Management.pdf` → Project documentation and design  
- `Test_Cases_Employee_Management.pdf` → Sample test data and validation  

## Academic Project  
Focus on real-world HR workflow automation and employee data analytics using SAP ABAP.
