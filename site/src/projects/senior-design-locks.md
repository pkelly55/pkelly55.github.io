---
title: Senior Design Locks - Data Protection System
emoji: 🔐
metaDescription: Full-stack web application for secure company data management with role-based access control
date: 2024-05-01T00:00:00.000Z
summary: Enterprise-grade deployable web application designed to securely store and manage company records with admin privileges, audit trails, and RESTful API architecture.
tags:
  - Python
  - Django
  - React
  - Material UI
  - MySQL
  - RESTful API
  - Full-Stack Development
---

## 🎯 Project Overview

**Senior Design Locks** is a comprehensive data protection system developed to meet business requirements for securely storing and managing sensitive company records. This full-stack application addresses the critical need for secure data access, role-based permissions, and complete audit traceability in corporate environments.

Built as my senior capstone project at Allegheny College, this system demonstrates enterprise-level software architecture and security best practices.

## 🚀 Key Features

### Security & Access Control
- **Role-Based Access Control**: Admin privileges with granular permission management
- **Secure Data Storage**: Encrypted storage for sensitive company records (web or local database)
- **IP Address Monitoring**: Track and log all data access attempts with IP information
- **User Authentication**: Secure login system with session management

### Data Management
- **CRUD Operations**: Complete Create, Read, Update, Delete functionality via RESTful APIs
- **Audit Trail**: Complete traceability of all data modifications and access
- **Real-Time Monitoring**: Live tracking of data access patterns and user activities
- **Search & Filter**: Powerful search capabilities to quickly locate specific records

### Administrative Features
- **Spring Boot Admin Dashboard**: Centralized monitoring and management interface
- **User Management**: Add, modify, or revoke user access privileges
- **System Health Monitoring**: Real-time application performance metrics
- **Database Analytics**: Connected to MySQL for comprehensive data insights

## 🛠️ Technical Architecture

### Backend Stack
**Framework Options**: Rails or Django (demonstrated proficiency in both)
- RESTful API design following industry best practices
- Secure authentication and authorization middleware
- Database ORM for efficient data operations
- Input validation and sanitization for security

**Admin Interface**: Spring Boot Admin
- Connected to MySQL database for centralized monitoring
- Real-time health checks and metrics
- Automated alerting for system issues
- Service registry and discovery

### Frontend Stack
**Framework**: React.js with Material UI
- Modern, responsive user interface design
- Component-based architecture for maintainability
- Material Design principles for professional appearance
- Form validation and error handling
- Real-time updates and notifications

### Database
**MySQL Database**
- Normalized schema design for data integrity
- Indexed queries for optimal performance
- Backup and recovery procedures
- Transaction management for data consistency

## 💡 Technical Highlights

### RESTful API Design
```
Endpoints for Shipment and ShipmentUpdate entities:
POST   /api/records           - Create new secure record
GET    /api/records           - Retrieve all accessible records
GET    /api/records/:id       - Retrieve specific record
PUT    /api/records/:id       - Update existing record
DELETE /api/records/:id       - Delete record (admin only)
GET    /api/audit/:id         - View complete audit trail
```

### Security Implementation
- **Encryption**: Data encrypted at rest and in transit
- **Authentication**: JWT-based authentication system
- **Authorization**: Role-based middleware for endpoint protection
- **Audit Logging**: Every action logged with timestamp, user, and IP address
- **Input Validation**: Comprehensive validation to prevent injection attacks

### Monitoring Capabilities
- Track last-viewing information for each record
- Monitor IP addresses accessing sensitive data
- Real-time dashboards for system administrators
- Automated alerts for suspicious access patterns

## 📊 Project Specifications

**Development Focus**: 
- Deployable web application ready for production environments
- Scalable architecture to handle growing data volumes
- Cross-platform compatibility (web and local database options)
- Comprehensive documentation for deployment and maintenance

**Business Value**:
- Meets compliance requirements for data security
- Provides complete audit trail for regulatory purposes
- Reduces risk of unauthorized data access
- Streamlines data management workflows

## 🎓 What I Learned

### Full-Stack Development
- Integrated multiple technologies into a cohesive system
- Implemented complex authentication and authorization logic
- Designed and consumed RESTful APIs
- Built responsive, user-friendly interfaces

### Security Best Practices
- Implemented industry-standard encryption methods
- Designed role-based access control systems
- Created comprehensive audit logging
- Understood OWASP security principles

### Database Management
- Designed efficient database schemas
- Optimized queries for performance
- Implemented proper indexing strategies
- Managed database migrations and versioning

### Project Management
- Gathered and analyzed business requirements
- Planned and executed a large-scale project
- Documented system architecture and APIs
- Delivered production-ready software

## 🔗 Technologies Used

**Backend**: Python/Django or Ruby/Rails, Spring Boot Admin, MySQL  
**Frontend**: React, Material UI, JavaScript  
**Security**: JWT, Encryption Libraries, Input Validation  
**Tools**: Git, REST API Testing Tools, Database Management Systems  
**Deployment**: Production-ready architecture with scalability considerations

---

## 🏆 Project Impact

This senior design project demonstrates my ability to:
- Architect and build enterprise-level applications
- Implement critical security features for sensitive data
- Work with modern full-stack technologies
- Deliver production-ready software solutions
- Think critically about business requirements and user needs

*This capstone project showcases my readiness for professional software engineering roles, combining technical expertise with practical business application.*
