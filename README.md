# Ticket Manager

Ticket Manager is a web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) designed to replace the existing sticky note system for managing tasks and tickets at a local computer reapir shop.

## Features

- **Public Facing Page**: Basic contact information accessible to the public.
  
- **Employee Login**: Secure login system for employees to access the ticket application.
  
- **Welcome Page**: Personalized welcome page after successful login.
  
- **Intuitive Navigation**: Easy-to-use navigation for seamless user experience.
  
- **User Authentication**: Mandatory login at least once per week for security.
  
- **Immediate Access Removal**: Quick removal of employee access as needed.
  
- **Ticket Management**:
  - Tickets are assigned to specific employees.
  - Each ticket includes a ticket number, title, description, creation date, and last update date.
  - Tickets can be OPEN or COMPLETED.
  - Managers and Admins have permission to delete tickets.
  
- **User Roles**:
  - Employees, Managers, and Admins have distinct roles.
  - Permissions are role-based:
    - Employees can view and edit their assigned tickets.
    - Managers and Admins can view, edit, and delete all tickets.
    - Only Managers and Admins have access to User Settings and can create new users.
  
- **Secure Logout**: Option for users to securely log out from the application.
  
- **Responsive Design**: Primarily designed for desktop use but mobile-friendly.

## Technologies Used

- **Frontend**: React.js for building the user interface.
- **Backend**: Node.js and Express.js for server-side logic.
- **Database**: MongoDB for storing tickets and user information.
- **Authentication**: JWT (JSON Web Tokens) for secure authentication and authorization.

## Demo
You can view a live demo of the project here: [Ticket Manager](https://ticket-manager-g9ib.onrender.com)

### Sample User Data

To test the different views and permissions within the application, you can use the following sample user data:

- **Manager**:
  - **Username**: `Shrey`
  - **Password**: `Spike123`
  - **Role**: Manager
  - **Permissions**: Can view all tickets and user settings.

- **Employee**:
  - **Username**: `Puji`
  - **Password**: `Spike123`
  - **Role**: Employee
  - **Permissions**: Can only view and edit the tickets assigned to her and cannot access user settings.

Use these credentials to log in and explore the application from the perspectives of different user roles.


