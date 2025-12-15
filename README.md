# AWS 3-Tier Application Deployment (DevOps Learning Project)

## 🚀 Project Overview
This repository demonstrates the **manual deployment of a 3-tier application on AWS** as part of DevOps learning.  
The original application code was provided during training. My contribution focused on **AWS infrastructure setup, database provisioning, and deployment**.

The project showcases:
- Frontend (React) hosted on EC2
- Backend (Spring Boot) hosted on EC2
- Database (MariaDB) hosted on AWS RDS

## 🏗️ Architecture
      ┌────────────┐
      │  Frontend  │
      │  React App │
      └─────┬──────┘
            │ HTTP
      ┌─────▼──────┐
      │  Backend   │
      │ Spring Boot│
      └─────┬──────┘
            │ JDBC
      ┌─────▼──────┐
      │   Database │
      │  MariaDB   │
      │   RDS      │
      └────────────┘
**3-Tier Overview:**
1. **Frontend:** React application (EC2)  
2. **Backend:** Spring Boot application (EC2)  
3. **Database:** MariaDB (RDS)

## ☁️ AWS Services Used
- **EC2:** Hosting frontend and backend applications  
- **RDS (MariaDB):** Managed database service  
- **Security Groups:** Network access control  
- **IAM Roles:** Secure access management

## ⚙️ Deployment Details
- Manual deployment on a single EC2 instance for frontend and backend  
- Database hosted on AWS RDS  
- Security groups configured for HTTP, HTTPS, and database access  
- Verified connectivity between frontend, backend, and database  

## 📚 Learning Outcomes
- Understanding **3-tier architecture** in practice  
- AWS EC2 instance provisioning and configuration  
- AWS RDS database setup and connectivity  
- Security group and IAM role management  
- Manual deployment process for full-stack apps  

## 🔮 Future Improvements
- Separate EC2 instances for frontend and backend for better scalability  
- Add **CI/CD pipeline** using GitHub Actions or Jenkins  
- Dockerize applications for containerized deployment  
- Implement Infrastructure as Code (Terraform)  

## 📝 Notes
- The project code was provided during training; the focus here is **DevOps deployment**  
- Database schemas are included for reference (`database_schema.sql` and `simple_schema.sql`)  
- All deployment and configuration steps are **manually performed on AWS**

