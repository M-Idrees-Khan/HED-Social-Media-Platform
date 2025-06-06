# HED KPK Social Media Platform

A secure, verified, role-based social media platform developed for the **Higher Education Department (HED) KPK** to bring all colleges under a unified digital space. 
Built using **ASP.NET MVC**, **SQL Server**, and **jQuery**, this platform encourages academic collaboration among students, teachers, focal persons, 
and administrators with strict access control and moderation tools.
## 🎯 Objective
This platform was designed and presented by **M. Idrees** during a Higher Education Department project competition.
Its main goal is to connect all colleges under **HED KPK** to encourage verified academic interactions and responsible collaboration.
## 👥 User Roles
### 1. Admin
- Approves or rejects focal persons from colleges.
- Monitors all activities across the platform.
- Can issue **warnings**, **suspend**, **Approve**, **Reject** or **ban** users.
- Full access and control over system moderation.
### 2. Focal Person
- Assigned to each college after admin approval.
- Can approve/reject/suspend/warned/ban **students** and **teachers** of their respective colleges.
- Responsible for maintaining decorum at the institutional level.
### 3. Teacher / Student
- Can interact with other verified users, participate in academic discussions.
- Subject to moderation by the focal person and admin.
## 🌟 Key Features
- Role-based access and approval workflows.
- Real-time moderation (warnings, suspensions, bans).
- Secure login and registration system.
- Admin and Focal Person dashboards.
- College-wise user grouping and management.
- Verified account system for safe and meaningful engagement.
- jQuery-powered interactive UI and smooth AJAX operations.
## 📚 Benefits
- Bridges communication gaps between colleges under HED KPK.
- Promotes secure and focused academic dialogue.
- Eliminates anonymous or irresponsible usage with verified identities.
- Encourages academic growth, project sharing, and collaboration.
## 🛠️ Technologies Used
| Layer        | Technology            |
|--------------|------------------------|
| Frontend     | HTML5, CSS3, Bootstrap, jQuery, AJAX |
| Backend      | ASP.NET MVC (C#)       |
| Database     | SQL Server             |
| ORM          | Entity Framework / ADO.NET |
| Architecture | Layered (MVC + DAL + BLL) |
| Tools        | Visual Studio          |
## 🖥️ Project Structure
HEDPlatform/
│
├── Controllers/
├── Models/
├── Views/
│   ├── Admin/
│   ├── FocalPerson/
│   ├── Student/
│   ├── Teacher/
├── Scripts/       # jQuery and AJAX
├── Content/       # CSS, Bootstrap
├── DAL/           # Data Access Layer
├── BLL/           # Business Logic Layer
├── App_Start/
├── Web.config
