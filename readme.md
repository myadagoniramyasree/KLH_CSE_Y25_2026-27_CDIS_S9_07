
# Cloud-Based Faculty Workload and Academic Activity Management System

## 📌 Project Overview

The **Cloud-Based Faculty Workload and Academic Activity Management System** is a cloud-based application designed to simplify and streamline faculty workload allocation and academic activity management within educational institutions.

The platform provides a centralized environment where administrators can manage faculty information, assign courses, monitor teaching workloads, and track research activities, publications, certifications, and other academic responsibilities. Faculty members can access their assigned workloads, update their academic contributions, and upload supporting documents.

The application is designed to provide secure access, efficient data management, scalability, and centralized monitoring using Amazon Web Services (AWS).

## 🎯 Objectives

- Centralize faculty information and academic records.
- Simplify faculty workload and course allocation.
- Track research activities, publications, and certifications.
- Provide separate access for administrators and faculty members.
- Enable secure document uploads and storage.
- Generate workload summaries and academic activity reports.
- Deploy a scalable and secure application using AWS cloud services.
- Monitor application performance and infrastructure health.

## ✨ Key Features

### 1. Admin Dashboard
- Manage faculty information.
- Monitor department-level activities.
- Assign courses and teaching responsibilities.
- View faculty workload summaries.

### 2. Faculty Dashboard
- View assigned courses and workload.
- Update research and publication details.
- Maintain academic activity records.
- Upload certificates and supporting documents.

### 3. Faculty Workload Allocation
- Assign courses to faculty members.
- Track teaching hours and responsibilities.
- Monitor workload distribution.
- Generate faculty-wise workload reports.

### 4. Research and Publication Management
- Maintain research activity records.
- Add publication details.
- Track academic contributions.

### 5. Certification and Document Management
- Upload and manage academic certificates.
- Store supporting documents securely.
- Access documents when required.

### 6. Reports and Monitoring
- Generate workload summaries.
- Review faculty academic activities.
- Monitor departmental responsibilities.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Frontend | React.js |
| Backend | Java Spring Boot |
| Database | MySQL |
| Containerization | Docker |
| Cloud Platform | Amazon Web Services (AWS) |

## ☁️ AWS Services

The project uses the following AWS services for cloud deployment, storage, networking, security, and monitoring.

| AWS Service | Purpose |
|---|---|
| Amazon EC2 | Hosts and runs the application |
| Amazon VPC | Provides an isolated and secure cloud network |
| VPC Subnets | Separate public and private resources |
| Application Load Balancer | Distributes incoming application traffic |
| Auto Scaling | Automatically adjusts EC2 instance capacity |
| Amazon S3 | Stores certificates and supporting documents |
| Amazon RDS | Hosts the MySQL relational database |
| AWS IAM | Manages users, roles, and permissions |
| Amazon CloudWatch | Monitors application logs, traffic, and system health |
| Amazon ECR | Stores Docker container images |

## 🏗️ Proposed System Architecture

The application follows a three-tier architecture:

1. **Presentation Layer:** React.js provides the user interface for administrators and faculty members.
2. **Application Layer:** Java Spring Boot handles business logic, authentication, workload allocation, academic activities, and communication with the database and storage services.
3. **Data Layer:** MySQL stores structured academic records, while Amazon S3 stores uploaded documents and certificates.

The application will be containerized using Docker and deployed on Amazon EC2 instances within a secure AWS VPC. An Application Load Balancer will distribute incoming requests, while Auto Scaling will support changing application demand. Amazon CloudWatch will provide infrastructure and application monitoring.

## 🔐 Security and Scalability

- IAM roles and permissions for controlled AWS resource access.
- Secure VPC and subnet segmentation.
- Security groups to control network traffic.
- Docker-based application deployment.
- Auto Scaling to support varying workloads.
- CloudWatch monitoring for application and infrastructure health.

## 📂 Main Project Modules

- Admin and Faculty Authentication
- Faculty Information Management
- Course and Workload Allocation
- Research and Publication Tracking
- Certification and Document Storage
- Academic Activity Management
- Reports and Workload Summaries
- Cloud Infrastructure and Monitoring

## 🚀 Expected Outcomes

- Reduced manual effort in faculty workload management.
- Improved visibility into faculty academic responsibilities.
- Centralized management of research and academic records.
- Secure storage of supporting documents.
- Scalable and reliable application deployment.
- Improved departmental coordination and administrative efficiency.

## 🔮 Future Enhancements

- Automated workload calculation and distribution.
- Advanced analytics and visual dashboards.
- Email notifications for workload assignments and updates.
- Academic performance and contribution reports.
- Integration with existing institutional systems.

## 👥 Project Information

**Project Title:** Cloud-Based Faculty Workload and Academic Activity Management System

**Course:** Cloud Infrastructure and Services (25CS2206E)

**Academic Year:** 2026–2027

**Team Number:** 07

**Institution:** KL University, Hyderabad

## 📌 Project Status

Currently in the planning and development stage. Application development, AWS infrastructure configuration, containerization, deployment, and monitoring will be carried out as part of the project.

---

*Developed as part of the Cloud Infrastructure and Services course project.*
