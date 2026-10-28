# FinPath
### Personal Finance Management Platform

**Full Stack Software Engineering | Product Ownership | Financial Technology**

FinPath is an independent fintech project focused on building a modern personal finance management platform.

The application helps users organize financial accounts, track income and expenses, monitor balances, and gain better visibility into their financial lives.

The project combines software engineering, product management, financial domain knowledge, and cloud technologies.

> **Project Status:** Active Development  
> **Source Code:** Private — Proprietary Product  
> **Portfolio:** Public Technical Documentation

---

## 1. Project Overview

FinPath was conceived as a scalable digital financial management solution, initially focused on personal finance.

The platform is being developed as a responsive web application, with future plans for Android and iOS applications.

The long-term product vision includes financial automation, artificial intelligence, receipt processing, and Open Finance integrations.

## Technical Documentation

Explore the architecture, engineering decisions, and technical challenges behind FinPath.

| Document | Description |
|----------|-------------|
| [Software Architecture](ARCHITECTURE.md) | Explore the layered architecture, JWT authentication, PostgreSQL persistence, AWS integrations, and key engineering decisions. |
| [Case Study 01 — Secure Financial Data Isolation](CASE_STUDY_01.md) | Learn how user-level authorization was implemented and validated through 14 successful integration tests. |

These documents provide insight into my work as a **Full Stack Developer and Product Owner**, connecting business requirements, software architecture, implementation, and automated testing.

## Application Screenshots

FinPath features a web interface developed with React and TypeScript, designed to help users monitor their financial activities and make informed decisions.

### Financial Dashboard

The dashboard provides an overview of the user's financial position, including account balances, monthly income, expenses, and spending distribution by category.

![FinPath Financial Dashboard](screenshots/dashboard.png)

*FinPath financial dashboard displaying sample data for demonstration purposes.*

### Account Management

FinPath allows users to manage financial accounts, monitor their current balances, and maintain an initial balance reference for accurate financial tracking.

![FinPath Account Management](screenshots/accounts.png)

*Account management interface displaying fictional financial data.*

**Key capabilities:**
- Create, view, update, and delete financial accounts.
- Track initial and current account balances.
- Configure balance reference dates.
- Monitor account balances based on recorded financial transactions.


### Key Features Demonstrated

- Monthly financial overview.
- Current account balance.
- Income and expense summaries.
- Monthly financial results.
- Expense distribution by category.
- Month and year selection.
- Navigation between financial management modules.


### Business Objectives

- Simplify personal financial management.
- Provide visibility into financial accounts and transactions.
- Help users understand their financial behavior.
- Support financial planning and decision-making.
- Build a scalable platform for future intelligent financial services.

---

## 2. My Role

**Founder | Product Owner | Full Stack Developer**

I am responsible for the product lifecycle, from initial concept and requirements definition to architecture, development, testing, and technical documentation.

### Product Ownership

- Define product vision and business objectives.
- Identify user needs and translate them into functional requirements.
- Define and prioritize the Minimum Viable Product (MVP).
- Manage the product backlog and development roadmap.
- Write user stories and acceptance criteria.
- Evaluate technical feasibility and business value.
- Plan future product monetization strategies.

### Software Engineering

- Design the application architecture.
- Develop RESTful APIs using Java and Spring Boot.
- Implement authentication and authorization mechanisms.
- Design relational database models using PostgreSQL.
- Develop frontend components using React and TypeScript.
- Implement business rules for financial transactions.
- Create automated tests.
- Integrate external services and cloud technologies.

---

## 3. Technology Stack

### Backend
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- REST APIs
- JWT Authentication
- Maven

### Frontend
- React
- TypeScript
- Vite

### Database
- PostgreSQL
- Flyway
- SQL

### Cloud & Infrastructure
- Amazon Web Services (AWS)
- Amazon SES
- Docker
- Git
- GitHub

### Development Practices
- Agile Product Development
- Product Backlog Management
- API Design
- Relational Data Modeling
- Automated Testing
- Technical Documentation

---

## 4. Solution Architecture

FinPath follows a layered application architecture that separates user interfaces, business logic, persistence, and external integrations.

```text
                  USERS
                    |
                    v
              WEB APPLICATION
              React + TypeScript
                    |
                    v
                 REST APIs
                    |
                    v
              SPRING BOOT
                  Java 21
                    |
          +---------+---------+
          |         |         |
          v         v         v
      Security   Business    External
        JWT      Services  Integrations
          |         |         |
          +---------+---------+
                    |
                    v
               PostgreSQL
                    |
                    v
                 Flyway
```

The architecture is designed to support future scalability, cloud deployment, and integration with additional financial services.

---

## 5. Product Features

### Implemented Features

- User registration.
- User authentication using JWT.
- Secure password storage.
- Financial account management.
- Financial transaction management.
- Financial dashboard.
- Historical balance calculations.
- Monthly financial history.
- Backend validation and error handling.

### Implemented — Validation Pending

- Password recovery and reset flow.

### Features Under Development or Planned

- Recurring financial transactions.
- Financial projections.
- Savings goals.
- Receipt storage and processing.
- OCR-based financial data extraction.
- Email verification.
- Open Finance integration.
- AI-powered financial automation.
- Android and iOS applications.

Feature availability may change as development progresses.

---

## 6. Product Management

FinPath is developed using an iterative product delivery approach.

### MVP Strategy

The initial MVP focuses on delivering essential personal financial management capabilities.

Core priorities include:

1. Secure user registration and authentication.
2. Financial account management.
3. Income and expense tracking.
4. Financial dashboard and transaction history.
5. Password recovery.
6. Application usability and stability.

### Product Roadmap

**Phase 1 — Core Platform**
- Backend architecture.
- Authentication and authorization.
- Financial accounts and transactions.
- Web dashboard.

**Phase 2 — Financial Management**
- Recurring transactions.
- Financial projections.
- Savings goals.
- Receipt management.

**Phase 3 — Cloud Deployment**
- AWS infrastructure.
- Development and production environments.
- Security and monitoring.
- Public web application.

**Phase 4 — Intelligent Financial Services**
- OCR processing.
- Open Finance.
- AI-powered automation.
- Messaging integrations.
- Mobile applications.

---

## 7. Product Strategy

FinPath is designed with a freemium business model.

### Free Version

The initial release will provide essential financial management features to attract users, validate the product, and collect feedback.

### Future Premium Version

Potential premium capabilities include:

- Intelligent receipt processing.
- AI-assisted transaction registration.
- Advanced financial insights.
- Messaging-based financial automation.
- Additional integrations.

These capabilities are part of the product vision and are not commitments to a specific release date.

---

## 8. Technical Challenges

The project addresses engineering challenges commonly found in financial applications:

- Designing secure authentication flows.
- Maintaining consistency in financial calculations.
- Modeling transactions and account balances.
- Managing recurring financial events.
- Integrating frontend and backend services.
- Handling application errors consistently.
- Designing maintainable and scalable APIs.
- Preparing infrastructure for cloud deployment.

Technical decisions and implementation details will be documented through architecture notes and case studies.

---

## 9. Source Code Availability

FinPath is being developed as a proprietary commercial product.

The source code is maintained in a private repository.

This public repository provides technical documentation, architecture overviews, selected implementation examples, product management artifacts, and development case studies.

Sensitive information, credentials, proprietary business logic, and production configurations are not publicly disclosed.

---

## 10. Project Evolution

FinPath is an actively evolving project.

Future updates to this portfolio will include:

- Architecture diagrams.
- Application screenshots.
- API documentation examples.
- Product backlog examples.
- Technical case studies.
- Testing strategies.
- Cloud deployment architecture.

---

**FinPath — Building smarter personal financial experiences.**
