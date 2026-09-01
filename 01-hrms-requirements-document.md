# HRMS Requirements Document (Like greytHR / Zoho People)

## 1. Project Overview
Develop a cloud-based Human Resource Management System (HRMS) consisting of:
- Web Application
- Mobile Application (Android & iOS)
- Admin Panel

The system should manage the complete employee lifecycle from recruitment to exit.

## User Roles

**1. Super Admin**
- Manage company settings
- Manage users and permissions
- Access all modules
- Configure workflows

**2. HR Admin**
- Employee management
- Payroll management
- Recruitment
- Reports

**3. Manager**
- Team attendance
- Leave approvals
- Performance reviews

**4. Employee**
- View profile
- Apply leave
- Mark attendance
- View payslips

## Website Modules

### 1. Dashboard
**Features:** Total Employees, Present Employees, Absent Employees, New Joiners, Birthdays, Announcements, Upcoming Holidays, Quick Actions

**Reports:** Attendance Summary, Leave Summary, Payroll Summary

### 2. Employee Management
**Features:** Add Employee, Edit Employee, Employee Directory, Employee Profile, Employee Documents, Emergency Contacts, Family Details, Work History

**Documents:** Aadhaar, PAN, Passport, Resume, Educational Certificates

### 3. Attendance Management
**Features:** Check In / Check Out, Biometric Integration, GPS Attendance, Geofencing, Attendance Regularization, Shift Management, Overtime Management

**Reports:** Daily Attendance, Monthly Attendance, Late Coming Report, Overtime Report

### 4. Leave Management
**Features:** Apply Leave, Leave Approval, Leave Cancellation, Leave Policies, Holiday Calendar

**Leave Types:** Casual Leave, Sick Leave, Earned Leave, Maternity Leave, Paternity Leave, Loss of Pay

### 5. Payroll Management
**Features:** Salary Structure, Payroll Processing, Payslip Generation, Tax Calculation, Bonus Processing, Incentive Management

**Compliance:** PF, ESI, Professional Tax, TDS

**Reports:** Salary Register, Payroll Summary, Tax Reports

### 6. Recruitment Management (ATS)
**Features:** Job Requisitions, Job Posting, Career Portal, Candidate Database, Resume Upload, Interview Scheduling, Offer Letter Generation

**Reports:** Open Positions, Candidate Status, Hiring Reports

### 7. Onboarding
**Features:** Joining Forms, Document Collection, Welcome Kit, Induction Checklist, Policy Acceptance

### 8. Performance Management
**Features:** Goal Setting, KPI Management, OKR Management, Appraisal Process, 360 Degree Feedback

**Reports:** Performance Ratings, Goal Achievement Reports

### 9. Learning Management (LMS)
**Features:** Course Management, Training Programs, Employee Certifications, Skill Tracking

### 10. Expense Management
**Features:** Travel Claims, Reimbursements, Expense Approvals, Expense Reports

### 11. Asset Management
**Features:** Laptop Allocation, Mobile Allocation, Asset Tracking, Asset Return Process

### 12. Employee Self Service (ESS)
**Features:** View Profile, Attendance, Leave Requests, Payslips, Documents, Tax Information

### 13. Helpdesk & Ticketing
**Features:** Raise Ticket, Track Ticket, HR Support, IT Support, Complaint Management

### 14. Announcement Center
**Features:** Company News, Events, Holidays, Birthdays, Work Anniversaries

### 15. Reports & Analytics
- **HR Reports:** Employee Headcount, Department Reports, Attrition Reports
- **Attendance Reports:** Daily Attendance, Monthly Attendance, Shift Reports
- **Payroll Reports:** Salary Reports, Tax Reports, Compliance Reports
- **Leave Reports:** Leave Utilization, Leave Balance

### 16. Offboarding
**Features:** Resignation Request, Exit Interview, Asset Return, Full & Final Settlement, Experience Letter

## Mobile App Modules — Employee App

**Dashboard:** Attendance Status, Leave Balance, Announcements

**Attendance:** Check In, Check Out, GPS Tracking

**Leave:** Apply Leave, Cancel Leave, Leave History

**Payroll:** Payslips, Tax Information

**Profile:** Personal Information, Documents

**Notifications:** Leave Approvals, Payroll Updates, Announcements

## Admin Settings

**Company Settings:** Company Profile, Locations, Departments, Designations

**User Management:** Users, Roles, Permissions

**Workflow Management:** Leave Approval Workflow, Payroll Workflow, Recruitment Workflow

**Templates:** Email Templates, SMS Templates, Offer Letter Templates

## Third-Party Integrations
- **Attendance:** Biometric Devices, RFID Devices
- **Communication:** Email Integration, SMS Gateway, WhatsApp Notifications
- **Productivity:** Microsoft Teams, Slack, Google Workspace
- **Accounting:** Tally, ERP Systems

## Non-Functional Requirements

**Security:** Role-Based Access Control, Data Encryption, Audit Logs, Two-Factor Authentication

**Performance:** 10,000+ Employees Support, Fast Dashboard Loading, Real-Time Notifications

**Scalability:** Multi-Company Support, Multi-Location Support, Cloud Deployment

## Approximate Development Scope

| Item | Scope |
|---|---|
| Website | 120–150 Screens |
| Mobile App | 40–60 Screens |
| APIs | 200+ APIs |
| User Roles | Super Admin, HR, Manager, Employee |
| Total Modules | 16 Major Modules |
