# Employee Attendance and Payroll System

This project is a complete web-based Employee Attendance and Payroll System developed for academic use. It helps manage employee information, daily attendance, leave records, salary calculations, payroll details, and reports through a simple and user-friendly dashboard.

## Features
- Admin login authentication
- Employee registration and management
- Add, edit, view, and delete employee records
- Daily employee attendance tracking
- Present, Absent, Leave, and Half-Day status management
- Employee check-in and check-out time management
- Leave request and approval management
- Automatic salary and payroll calculation
- Allowance, bonus, overtime, and deduction management
- Monthly salary slip generation
- Attendance and payroll reports
- Dashboard with employee and attendance statistics
- Search and filter functionality
- LocalStorage-based data persistence
- Responsive and user-friendly interface

## Technology Stack
- Frontend: HTML5, CSS3, JavaScript
- Styling: Custom CSS
- Data Storage: Browser LocalStorage
- Visualization: Chart.js
- Icons: Font Awesome

## Folder Structure
- index.html: Admin login page
- dashboard.html: Main admin dashboard
- employees.html: Employee management page
- attendance.html: Attendance management page
- leave.html: Leave management page
- payroll.html: Payroll management page
- reports.html: Attendance and payroll reports
- settings.html: System settings
- css/style.css: Main application styles
- js/auth.js: Login and authentication functionality
- js/dashboard.js: Dashboard statistics and charts
- js/employees.js: Employee management functionality
- js/attendance.js: Attendance management functionality
- js/leave.js: Leave management functionality
- js/payroll.js: Payroll and salary calculations
- js/storage.js: LocalStorage data management
- assets/: Images, icons, and other project resources

## Installation

Clone or download the project and open the project folder in Visual Studio Code.

No additional backend installation is required because the application is developed using HTML, CSS, and JavaScript.

For the best development experience, install the **Live Server** extension in Visual Studio Code.

## Start the Application

Open the project folder in Visual Studio Code.

Right-click:
```text
index.html
```

Select:
```text
Open with Live Server
```

The application will open automatically in your browser.

Example:
```text
http://127.0.0.1:5500/index.html
```

## Default Admin Account

Use the following demo credentials:

- Username: admin
- Password: admin123

## Payroll Calculation

The system automatically calculates employee salary using:

```text
Gross Salary = Basic Salary + Allowance + Bonus + Overtime
```

```text
Net Salary = Gross Salary - Deductions - Leave Deduction
```

## Main Modules

1. Admin Login
2. Dashboard
3. Employee Management
4. Attendance Management
5. Leave Management
6. Payroll Management
7. Salary Slip
8. Reports
9. Settings

## Testing Workflow

1. Log in using the default admin account.
2. Add new employee details.
3. View, edit, search, or delete employee records.
4. Mark daily employee attendance.
5. Add and manage employee leave records.
6. Generate monthly payroll for employees.
7. Verify automatic gross salary and net salary calculations.
8. Generate and print employee salary slips.
9. View attendance and payroll reports.
10. Check dashboard statistics and charts.

## Project Purpose

The Employee Attendance and Payroll System is designed to simplify employee record management, attendance monitoring, leave tracking, and salary calculation. The system reduces manual work and provides an organized way to maintain employee and payroll information.

## Academic Use

This project is developed for educational and academic purposes to demonstrate the practical implementation of HTML, CSS, JavaScript, LocalStorage, data management, and payroll calculation in a web-based application.
