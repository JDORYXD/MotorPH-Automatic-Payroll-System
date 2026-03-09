# MotorPH Automatic Payroll System

A Java-based automatic payroll system that manages employee information, attendance records, and payroll calculations. This system demonstrates core programming skills, file handling, and payroll computation logic including SSS, PhilHealth, Pag-IBIG, and tax deductions.

---

## 📌 Team Details

### **Orlando Eria – Lead Developer**
- Designed and implemented the main program logic  
- Developed payroll processing and employee management features  
- Ensured accuracy of calculations and functionality  

### **John Vincent Illano – Repository Manager / Tester**
- Managed the GitHub repository  
- Tested and debugged the program for correctness  
- Ensured smooth integration of employee and attendance data  

---

## 💻 Program Details

The **MotorPH Automatic Payroll System** is a Java console-based application that automates payroll processing. The system reads employee information and attendance records from CSV files and calculates employee salaries based on their recorded working hours.

The program determines the total hours worked by each employee within a selected payroll cutoff period (1–15 or 16–31 of the month). Using the employee’s hourly rate, it calculates the gross salary and automatically applies government deductions such as **SSS, PhilHealth, Pag-IBIG, and withholding tax** to produce the final net salary.

The system allows users to log in either as an **employee** to view payroll details or as **payroll personnel** to process and review payroll data.

---

## 💻 Program Features

- Employee login system with username and 5-digit password  
- Payroll login for processing and reviewing employee payroll  
- Handles up to 1000 employees  
- Reads employee details from `EmployeeDetails.csv`  
- Reads attendance records from `AttendanceRecords.csv`  
- Calculates working hours, gross salary, and net salary  
- Handles cutoff periods (1–15, 16–31 of each month)  
- Computes deductions: SSS, PhilHealth, Pag-IBIG, and tax  
- Displays payroll by employee and by month  

---

## 📂 Program Files

- `MotorPH_Automatic_Payroll_System.java` – main program file  
- `EmployeeDetails.csv` – contains employee ID, name, birthday, and hourly rate  
- `AttendanceRecords.csv` – contains attendance logs with time-in and time-out  

---

## 📅 Project Plan

The project plan and development tasks were discussed and organized internally by the team during the development process.

---
