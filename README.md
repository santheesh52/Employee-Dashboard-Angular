# Employee-Dashboard-Angular

<h1>Table of Contents</h1>
<ol>
   <li>Project Overview</li>
   <li>Features</li>
   <li>Getting Started</li>
   <li>Project Structure</li>
   <li>Technologies Used</li>
   <li>Usage</li>
   <li>Contributing</li>
   <li>License</li>
</ol>

<h1>Project Overview</h1>

The Employee Dashboard is an Angular-based web application designed to manage employee information, handle leave requests, and track attendance. It includes features for both employees and administrators to make employee management simple and efficient.

<h1>Features</h1>
<ul>
     <li> Employee Dashboard: Overview of employee details and key metrics.</li>
     <li>  Leave Management: Employees can apply for leave and check the status of their requests. Admins can approve or reject leave applications.</li>
     <li>  Profile Management: Employees can view and update their personal information.</li>
     <li>  Responsive Design: Mobile-friendly user interface with Angular Material components.</li>
     <li>  Admin Panel: Separate interface for admins to manage employee data and leave requests.</li>
</ul>

<h1>Getting Started</h1>
<h2>Prerequisites</h2>
Before you begin, ensure you have met the following requirements:
<ul>
   <li>Node.js (v14 or above) installed on your machine.</li>
   <li>Angular CLI (v13 or above) installed globally. You can install it using:</li>
</ul>

bash
 
npm install -g @angular/cli
Installation
Clone the repository:

bash
 
git clone https://github.com/yourusername/employee-dashboard-angular.git
cd employee-dashboard-angular
Install dependencies: Run the following command to install the required npm packages:

bash
 
npm install
Run the development server: Start the Angular development server using:

bash
 
ng serve
Open http://localhost:4200 in your browser to view the application.

Project Structure
The project follows a modular architecture to keep the codebase organized.

plaintext

src/<br>
 ├── app/<br>
 │   ├── core/               # Core services and utilities
 │   ├── shared/             # Shared components, directives, and pipes
 │   ├── employee/           # Employee-related components
 │   ├── admin/              # Admin-related components
 │   ├── leave/              # Leave management components
 │   └── app.module.ts       # Root module
 ├── assets/                 # Static assets (images, fonts, etc.)
 ├── environments/           # Environment-specific configurations
 └── styles.css              # Global styles
Technologies Used
Angular: Front-end framework
Angular Material: UI components library for building responsive, modern web applications
SweetAlert: For handling pop-up alerts and confirmation dialogs
RxJS: For handling asynchronous data streams
TypeScript: For static typing and better code structuring
SCSS/CSS: For styling the application
Usage
Employee Dashboard:

Employees can log in to view their personal dashboard with details like leave balance, personal info, and more.
Leave Management:

Employees can submit leave applications and track their status.
Admins can view, approve, or reject leave applications.
Admin Panel:

Admins can manage employee details, including adding, updating, or deleting employee records.
Contributing
Contributions are welcome! Follow these steps to contribute:

Fork the project repository.
Create a feature branch:
bash
 
git checkout -b feature-branch
Make your changes and commit:
bash
 
git commit -m "Add new feature"
Push to your branch:
bash
 
git push origin feature-branch
Open a pull request on GitHub.
License
This project is licensed under the MIT License. See the LICENSE file for more information.
