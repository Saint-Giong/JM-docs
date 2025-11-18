# SGJM - Saint Giong Job Manager Documentation

**RMIT Classification: Protected**

This repository contains the official documentation for the **DEVision Job Manager Subsystem (SGJM)**, developed by **Team Saint Giong** for the EEET2582/ISYS3461 Software Engineering course at RMIT University.

## About the Project

**DEVision** is a comprehensive job matching platform that bridges job applicants in Computer Science fields with their potential employers. The platform embodies the Vietnamese proverb "An Cư Lạc Nghiệp" (Settled and Flourished), emphasizing the importance of establishing a solid and fulfilling career.

### Team Saint Giong - Job Manager Subsystem

Our team is responsible for developing the **Job Manager Subsystem**, which provides companies with tools to:

- Register and authenticate securely (including SSO support)
- Create and manage company profiles
- Post and manage job listings
- Search for qualified applicants
- Access premium features with real-time candidate notifications
- Process subscription payments

## Project Timeline

- **Milestone 1**: November 28, 2025 - Design Documentation (Data Model & System Architecture)
- **Milestone 2**: January 13, 2026 - Full Implementation & Deployment

## Technology Stack

### Frontend
- React-based frameworks (React, Vite, Next.js)
- Vanilla HTML, CSS, and JavaScript

### Backend
- Spring Boot or MEN Stack (MongoDB, ExpressJS, NodeJS)
- Redis for caching
- Kafka for message streaming

### Deployment
- Docker
- Kubernetes (Bonus)

## Architecture Levels

The project requirements are organized into three complexity levels:

- **Simplex (Basic)**: N-Tier architecture with fundamental features
- **Medium**: Modular Monolith with componentized frontend
- **Ultimo (Advanced)**: Microservices with Headless UI and advanced features

## Key Features

### Core Features
1. Company Registration with email validation
2. Secure Login with JWE tokens
3. Profile Management with media uploads
4. Job Post Management with skills tagging
5. Applicant Search with full-text search
6. Premium Subscription with real-time notifications

### Integration
- API provision to Job Applicant subsystem
- API consumption from Job Applicant subsystem
- Payment service for both subsystems

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the documentation locally:

```bash
npm i -g mint
```

Run the development server:

```bash
mint dev
```

View at `http://localhost:3000`

## Documentation Structure

- `/project` - Project overview and requirements
- `/features` - Functional requirements documentation
- `/technical` - Architecture and technical specifications
- `/api-reference` - API documentation
- `/guides` - Development guides and best practices

## Course Information

- **Course**: EEET2582/ISYS3461
- **Project**: Software Requirements Specification v1.1
- **Institution**: RMIT University
- **Classification**: RMIT Protected

## Team Collaboration

We follow an iterative development approach using:
- SCRUM/Kanban methodology
- GitHub for version control and collaboration
- [Tuturuuu](https://tuturuuu.com/d38c5b88-7e9a-46e3-9752-9cff835eff24/tasks/boards/be15d431-b796-4394-b340-c78890de3e79) for task management and Kanban board
- Bi-weekly sprint reviews with the lecturer

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [Project Requirements Specification](./project/requirements.mdx)
