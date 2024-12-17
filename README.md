# Dream Job Portal  

## Overview  
The Dream Job Portal is a full-stack application designed to connect job seekers with employers efficiently. It provides dedicated functionalities for job seekers, recruiters, and administrators. The platform ensures a seamless experience from job search and application to candidate management and hiring, with real-time updates and efficient profile and job post management.  

---  

## Features  

### **Job Seeker Functionality:**  
- Register, login, and manage personal profiles.  
- Search for jobs based on filters like location, role, and industry.  
- Submit job applications and upload resumes.  
- Track application status in real-time.  
- Save jobs for later and view application history.  

### **Recruiter Functionality:**  
- Post and manage job listings.  
- View and filter candidate applications.  
- Manage company profiles and recruitment analytics.  
- Shortlist candidates and schedule interviews.  

### **Admin Functionality:**  
- Manage users (job seekers and recruiters) and job posts.  
- Oversee platform activity and ensure compliance with terms.  
- Access detailed analytics for platform performance.  
- Handle escalations and user feedback.  

---  

## Technology Stack  
- **Backend:** Node.js, Express.js  
- **Frontend:** React.js, Tailwind CSS  
- **Database:** MongoDB  
- **Authentication:** JWT for secure role-based access control  

---  

## Requirement Analysis  

### **Stakeholder Needs:**  

#### **Job Seekers:**  
- Seamless registration and login.  
- A user-friendly interface to browse and apply for jobs.  
- Real-time updates on application status.  

#### **Recruiters:**  
- Tools for creating and managing job posts.  
- Efficient candidate filtering and management.  
- Access to recruitment analytics.  

#### **Admins:**  
- Robust user and job post management tools.  
- Access to platform-wide data for analytics and decision-making.  

### **Platform Requirements:**  
- Secure authentication with role-based access.  
- Scalable backend to handle increasing users and job posts.  
- Efficient data handling for user profiles, applications, and analytics.  

---  

## Functional Requirements  
- User registration and secure role-based authentication.  
- CRUD operations for user profiles, job posts, and applications.  
- Real-time updates for job applications.  
- Advanced search and filtering for job seekers and recruiters.  

## Non-Functional Requirements  
- High scalability to support growing user base.  
- Reliable performance with minimal downtime.  
- Secure handling of sensitive user data (e.g., resumes, personal information).  
- Intuitive and responsive UI/UX design.  

---  

## API Documentation  

### **Authentication Endpoints**  

#### **Job Seeker Authentication:**  
- `POST /jobseeker-register`: Register a new job seeker.  
- `POST /jobseeker-login`: Login for job seekers.  
- `POST /jobseeker-logout`: Logout from the platform.  

#### **Recruiter Authentication:**  
- `POST /recruiter-register`: Register a new recruiter.  
- `POST /recruiter-login`: Login for recruiters.  
- `POST /recruiter-logout`: Logout from the platform.  

#### **Admin Authentication:**  
- `POST /admin-register`: Register a new admin.  
- `POST /admin-login`: Login for admins.  
- `POST /admin-logout`: Logout from the platform.  

### **Job Management Endpoints (Recruiters)**  
- `POST /create-job`: Add a new job post.  
- `POST /update-job`: Update job details.  
- `POST /delete-job`: Remove a job post.  
- `GET /jobs`: Retrieve all job listings.  

### **Application Management Endpoints**  

#### **Job Seekers:**  
- `POST /apply-job`: Apply for a job.  
- `GET /applications`: View application history.  
- `GET /application-status/:id`: Check the status of a specific application.  

#### **Recruiters:**  
- `GET /job-applications/:jobId`: View applications for a job.  
- `POST /update-application-status`: Update the status of a candidate's application.  

### **User Management Endpoints (Admin)**  
- `GET /users`: View all users (job seekers and recruiters).  
- `POST /update-user-role`: Update a user's role or permissions.  

---  

## Entity-Relationship Diagram (ERD)  
- Represents relationships between entities like Users, Jobs, Applications, and Feedback.  

## Data Flow Diagram (DFD)  
- Illustrates how data flows between job seekers, recruiters, and admins within the platform.  

---  

## Final Summary  

The **Dream Job Portal** is a comprehensive solution for streamlining job search and recruitment processes. It integrates role-specific functionalities for job seekers, recruiters, and administrators, ensuring an optimal user experience for all stakeholders.  

### **Key Highlights:**  
- Advanced job search and filtering capabilities.  
- Real-time updates for job applications.  
- Secure and scalable architecture using Node.js, React.js, and MongoDB.  
- Robust role-based access control with JWT.  

With its intuitive interface and efficient backend, the Dream Job Portal ensures a seamless flow of operations from job posting to final hiring.  

---  

**Thank You!**  

This documentation provides a complete overview of the platform, including requirements, API endpoints, and system diagrams.
