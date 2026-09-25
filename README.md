<div align="center">

# Hi, I'm Omar Mohamed 👋

<img src="https://raw.githubusercontent.com/OmarDiv/portfolio/main/signature.svg" width="72" alt="Omar Mohamed monogram signature" />

### .NET Backend Developer | Building Scalable Solutions

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">
<img src="https://user-images.githubusercontent.com/74038190/212749447-bfb7e725-6987-49d9-ae85-2015e3e7cc41.gif" width="500">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=2+Years+of+Backend+Development;ASP.NET+Core+Specialist;Modular+Monolith+%26+Clean+Architecture;Building+Scalable+APIs)](https://git.io/typing-svg)

<p align="center">
  <a href="https://linkedin.com/in/omar-mohamed-mamon">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/OmarDiv">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://omardiv.github.io/portfolio">
    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="mailto:omaar88mohamed@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://flowcv.com/resume/n1comunpab">
    <img src="https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=google-drive&logoColor=white" alt="Resume"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=OmarDiv&label=Profile%20Views&color=6366F1&style=flat" alt="Profile views"/>
</p>

</div>

---

## 🚀 About Me

.NET Backend Developer with **2 years of hands-on experience** building scalable and maintainable web applications. Passionate about **Clean Architecture, Modular Monolith Architecture, and CQRS**, and implementing best practices that deliver real business value.

Specialized in crafting production-ready systems with focus on **performance optimization**, **security**, and **code quality**. Currently developing enterprise applications for UAE government projects while building diverse personal projects spanning e-commerce (Modular Monolith), healthcare, food delivery, IoT, surveys, and digital libraries.

---

## 💼 Work Experience

### .NET Developer

**Smart Vision** | Full-Time, On-Site
📅 Jan 2026 – Present | 📍 Cairo, Egypt

- **Resolved critical production security vulnerabilities**, including a refresh token reuse attack and a broken access control issue caused by a missing user ID in Redis cache keys, and added JWT blacklisting on logout
- **Refactored a per-action audit logging system** applied across 9 controllers into a global, opt-out logging pipeline backed by a bilingual (AR/EN) operation-type lookup, and designed a localization architecture combining Redis-cached static messages with database-driven dynamic entity translations
- **Built permission-based authorization** per endpoint and unified error handling across the Result-pattern and exception-based paths for consistent HTTP status codes
- **Developing end-to-end ASP.NET Core MVC applications** for UAE government projects including Fougera Club (Al Fujairah Sports Club) and Al Metsaweq (Secret Shopper Platform), including authentication workflows (2FA) and dashboard/reporting features

### .NET Developer

**Codex Plans** | Full-Time, Remote
📅 Jul 2025 – Jan 2026

- **Contributed to multiple enterprise systems** across different business domains — ERP, Legal Case Management, and Real Estate — built on Multi-Tenant architecture with Clean Architecture principles
- **Implemented per-page Role & Permission authorization**, applied URL ID Hashing (Hashids) for API security, and built multiple independent modules ensuring clean separation of concerns
- **Worked with SignalR** for real-time live data updates, and expanded knowledge in IdentityServer and DB-per-Tenant multi-tenancy strategies
- **Expanded technical mindset** by working with new architectural patterns and enterprise-level design approaches beyond previous experience

### .NET Developer

**ITS Technologies** | Full-Time, On-Site
📅 Sep 2024 – Jul 2025 | 📍 Port Said, Egypt

- **Developed scalable web applications and RESTful APIs** using ASP.NET Core and .NET Core MVC, implementing responsive UIs with HTML5, CSS3, and Bootstrap to enhance user experience
- **Built technical support website and mobile integration APIs** - Created comprehensive backend APIs enabling seamless iOS and Android app connectivity, improving customer support accessibility
- **Implemented secure authentication and authorization** using ASP.NET Identity and JWT tokens with role-based access control
- **Optimized database operations** using Entity Framework Core and LINQ, improving query performance and data access efficiency
- **Integrated background job processing** using Hangfire for automated notifications, scheduled tasks, and asynchronous operations
- **Applied Clean Architecture principles** with Repository Pattern, Dependency Injection, and SOLID principles for maintainable code

---

## 🎯 Featured Projects

<details open>
<summary><b>🛒 EShop - Modular Monolith E-Commerce Platform</b></summary>
<br>

> Modular monolith backend architected around independent, loosely-coupled business modules, built to explore large-scale system design patterns

**✨ Key Features:**

- Modular monolith backend with isolated Catalog, Basket, Identity, and Ordering modules, each with its own database schema
- Vertical Slice Architecture and CQRS (MediatR) for clean, feature-focused request handling
- Domain-Driven Design (DDD) tactical patterns for rich domain models
- Outbox Pattern with RabbitMQ/MassTransit for reliable, eventually-consistent cross-module messaging
- Eliminated dual-write inconsistency risk in the Basket Checkout flow
- API security secured with Keycloak (OAuth2/OpenID Connect, JWT)
- Structured logging with Serilog and Seq
- Containerized deployment with Docker

**🛠️ Tech Stack:**
```
ASP.NET Core • EF Core • CQRS (MediatR) • PostgreSQL • Redis
RabbitMQ • MassTransit • Keycloak • Serilog • Seq • Docker
```

📂 [View Repository →](https://github.com/OmarDiv/Eshop)

</details>

<details>
<summary><b>🏥 Hospital Management System (Sehaty-Plus)</b></summary>
<br>

> Advanced healthcare platform for comprehensive patient and doctor management with appointment scheduling and consultations

**✨ Key Features:**

- Multi-role authentication (Patients, Doctors, Admins) with permission-based access
- Medical specializations and doctor profiles management system
- Patient health records with complete medical history tracking
- Email verification and SMS-based OTP authentication
- JWT authentication with secure refresh token mechanism
- Real-time appointment booking system (in progress)
- Rate limiting and CORS protection for API security
- Distributed caching with Redis for high performance
- Containerized deployment with Docker Compose

**🛠️ Tech Stack:**
```
ASP.NET Core 9.0 • Clean Architecture • CQRS • Web API • Entity Framework Core • SQL Server
JWT • Identity Framework • FluentValidation • Mapster • MailKit • Twilio SMS • Hangfire
Dapper • Serilog • CORS • Rate Limiting • Audit Logging • Redis • Docker • Docker Compose
```

📂 [View Repository →](https://github.com/OmarDiv/Sehaty-Plus-CleanArchitecture)

</details>

<details>
<summary><b>🍔 FoodFlow - Food Delivery Platform</b></summary>
<br>

> Comprehensive backend system for restaurant management and food delivery operations

**✨ Key Features:**

- Restaurant browsing and menu management system
- Complete order processing and real-time tracking pipeline
- Secure JWT authentication with role-based authorization
- Performance optimization with intelligent caching strategies (HybridCache)
- Automated API documentation with Swagger
- Background jobs for order notifications via Hangfire

**🛠️ Tech Stack:**
```
ASP.NET Core 9 • Web API • Entity Framework Core • SQL Server • Identity
JWT • Repository Pattern • FluentValidation • Mapster • Hangfire
Swagger • Serilog • Geoapify API • HybridCache • CORS • HealthChecks
```

📂 [View Repository →](https://github.com/OmarDiv/FoodFlow)

</details>

<details>
<summary><b>🅿️ Raknah - Smart Parking System</b> <code>Graduation Project || IOT</code></summary>
<br>

> IoT-integrated intelligent parking solution with hardware integration — **Graduated with Very Good** 🎓

**✨ Key Features:**

- Real-time parking spot reservation and availability management
- ESP32 hardware integration for automated gate control
- MQTT protocol for live IoT communication
- Automated SMTP email notification system
- Secure user authentication and account management
- Hybrid caching strategy for optimal performance
- Robust concurrency handling to prevent double-booking
- Comprehensive audit logging for compliance

**🛠️ Tech Stack:**
```
ASP.NET Core • Web API • EF Core • SQL Server • Identity • JWT
Result Pattern • Hangfire • Mapster • MailKit • FluentValidation
Rate Limiting • Hybrid Caching • ESP32 • SMTP • MQTT • HttpClient
```

📂 [View Repository →](https://github.com/OmarDiv/Raknah)

</details>

<details>
<summary><b>📊 Survey Basket - Survey Management Platform</b></summary>
<br>

> Enterprise survey platform for creating, sharing, and analyzing surveys at scale

**✨ Key Features:**

- Handle thousands of survey responses with comprehensive analytics dashboard
- Secure role-based user authentication protecting sensitive data
- Performance optimization through query improvements and caching
- Automated notification system increasing survey participation rates
- API versioning for backward compatibility

**🛠️ Tech Stack:**
```
ASP.NET Core • Web API • EF Core • SQL Server • Identity • JWT
Result Pattern • Repository Pattern • Hangfire • Mapster • Serilog
MailKit • FluentValidation • API Versioning • Hybrid Caching
```

📂 [View Repository →](https://github.com/OmarDiv/SurveyBasket)

</details>

<details>
<summary><b>📚 Bookify - Digital Library Management System</b></summary>
<br>

> Comprehensive solution for managing books, subscribers, and rental operations

**✨ Key Features:**

- Digital library system for books, subscribers, and rental management
- Secure role-based authentication using Identity Framework
- Multilingual support with localization capabilities
- Advanced reporting system using ClosedXML for Excel export
- Automated rental notifications via Hangfire (email and WhatsApp)
- Cloud-based file storage with Cloudinary integration

**🛠️ Tech Stack:**
```
ASP.NET Core MVC • EF Core • SQL Server • Identity • JWT • Hangfire
AutoMapper • Serilog • Cloudinary • ClosedXML • Repository Pattern
Clean Architecture • FluentValidation • Bootstrap • jQuery
```

📂 [View Repository →](https://github.com/OmarDiv/Bookify)

</details>

---

## 🛠️ Technical Skills

<table>
<tr>
<td width="50%" valign="top">

### 🔧 Backend Development

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![Web API](https://img.shields.io/badge/Web_API-512BD4?style=flat&logo=dotnet&logoColor=white)
![MVC](https://img.shields.io/badge/MVC-512BD4?style=flat&logo=dotnet&logoColor=white)

### 💾 Database & ORM

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoft-sql-server&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity_Framework-512BD4?style=flat&logo=dotnet&logoColor=white)
![LINQ](https://img.shields.io/badge/LINQ-512BD4?style=flat&logo=dotnet&logoColor=white)
![Dapper](https://img.shields.io/badge/Dapper-512BD4?style=flat&logo=dotnet&logoColor=white)
![ADO.NET](https://img.shields.io/badge/ADO.NET-512BD4?style=flat&logo=dotnet&logoColor=white)

### 🎨 Frontend Technologies

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jquery&logoColor=white)

</td>
<td width="50%" valign="top">

### ⚙️ DevOps & Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat&logo=azure-devops&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)

### 🔐 Identity & Access

![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat&logo=keycloak&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)

### 💻 Development Environment

![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=flat&logo=visual-studio&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)

</td>
</tr>
</table>

### 🏗️ Architecture & Design Patterns
```
✓ Clean Architecture         ✓ Modular Monolith Architecture   ✓ Vertical Slice Architecture (VSA)
✓ Domain-Driven Design (DDD) ✓ CQRS (MediatR)                  ✓ SOLID Principles
✓ Repository Pattern         ✓ Unit of Work                    ✓ Result Pattern
✓ Dependency Injection       ✓ RESTful API Design              ✓ Design Patterns
```

### 📡 Messaging & Background Processing
```
✓ RabbitMQ    ✓ MassTransit    ✓ Outbox Pattern    ✓ Background Jobs (Hangfire)
```

### 🔒 Security & Authentication
```
✓ ASP.NET Identity          ✓ JWT Authentication          ✓ Refresh Tokens
✓ Keycloak (OAuth2/OpenID Connect)  ✓ Role-Based Access Control  ✓ Permission-Based Access
✓ Data Protection
```

### ⚡ Performance & Monitoring
```
✓ Hybrid Caching              ✓ Distributed Caching (Redis)   ✓ Pagination
✓ Background Jobs (Hangfire)  ✓ Logging (Serilog, Seq)        ✓ Health Checks
✓ Rate Limiting               ✓ Query Optimization
```

### 🧪 Testing & Quality
```
✓ Unit Testing (xUnit)     ✓ Integration Testing   ✓ FluentValidation
```

### 📦 Additional Technologies & Integrations
```
MailKit/MimeKit  •  Swagger/OpenAPI  •  API Versioning  •  CORS
Cloudinary  •  ClosedXML  •  AutoMapper  •  Mapster  •  OneOf
Twilio SMS  •  MQTT  •  Redis  •  ADO.NET  •  HttpClient  •  Docker Compose
```

---

## 💡 Core Competencies
```yaml
🎯 Problem Solving: Analytical thinking and debugging complex issues
📝 Clean Code: Writing maintainable and scalable solutions
👥 Team Collaboration: Collaborative development and code reviews
📢 Technical Communication: Clear documentation and stakeholder interaction
⏰ Time Management: Meeting deadlines and managing priorities
📚 Continuous Learning: Staying updated with latest .NET ecosystem
🚀 Adaptability: Quick learner of new technologies and frameworks
```

---

## 🎓 Education

**Bachelor's Degree in Information Technology and Systems**
**Port Said University** | 2021 – 2025

- Graduated with **Very Good** grade 🎖️
- **Graduation Project:** Raknah - Smart parking IoT system integrated with ESP32 hardware

---

## 📜 Certificates

**ITI Summer Training 2023 - Web Development using ASP.NET Core**

- ✓ SQL Server Database Management
- ✓ C# Programming Language
- ✓ LINQ & Entity Framework Core
- ✓ ASP.NET Core MVC Development

---

## 🌍 Languages

| Language    | Proficiency         |
| ----------- | -------------------- |
| **Arabic**  | Native 🇪🇬           |
| **English** | Good (Technical) 💼 |

---

## 📊 GitHub Activity

<div align="center">

[![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=OmarDiv&bg_color=0d1117&color=58a6ff&line=30363d&point=58a6ff&area=true&hide_border=true)](https://github.com/OmarDiv)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=OmarDiv&layout=compact&theme=dark&hide_border=true&bg_color=0d1117)](https://github.com/OmarDiv)

</div>

---

## 🤝 Connect With Me

<div align="center">

**I'm always open to discussing new projects, creative ideas, or opportunities to collaborate.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/omar-mohamed-mamon)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OmarDiv)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://omardiv.github.io/portfolio)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:omaar88mohamed@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=google-drive&logoColor=white)](https://flowcv.com/resume/n1comunpab)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/201041204519)

<br>

<img src="./assets/signature.svg" width="44" alt="OM monogram" />
<br>
<sub><i>Designed, coded &amp; signed — Omar Mohamed</i></sub>

---

### ⭐ If you find my projects useful, please consider starring them!

</div>
