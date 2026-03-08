## Note for Evaluators / Reviewers

Thank you for reviewing this project.

This repository represents the core entry point of the system. The application is built using a **microservices architecture**, and each service is maintained in its own dedicated repository for modularity and independent deployment.

For easier navigation, the **repository URLs for all microservices have been listed below in this README**. Each service repository contains:

* Service-specific documentation
* Setup and deployment instructions
* API specifications
* Environment configuration details

To understand the complete system workflow, you may review the services in the following order:

1. API Gateway / Backend Service
2. Authentication & User Service
3. Core Application Service(s)
4. Supporting Infrastructure Services (storage, messaging, etc.)

Please refer to the provided repository links to explore the implementation details of each microservice.

If any clarification is required while reviewing the architecture or setup, feel free to reach out.


Mudda-Backend: https://github.com/Cipher3003/Mudda-backend.git
Mudda-Fronend: https://github.com/DivSaumil/mudda_frontend.git
Mudda-AI-Workflow: https://github.com/ShubhPundir/Mudda-AI-Workflow.git
Mudda-Dashboard: https://github.com/ShubhPundir/Mudda-AI-Workflow.git

## About Mudda

**Mudda** is a platform designed to help people raise, discuss, and track important issues ("mudda" means *issue* or *matter of concern*). The goal of the platform is to create a structured space where individuals and communities can highlight problems, engage in meaningful discussions, and work collectively toward solutions.

The platform allows users to:

* **Raise issues (Mudda)** related to social, civic, or community concerns.
* **Engage in discussions** through comments and community participation.
* **Support or follow issues** to increase visibility and awareness.
* **Track progress** of discussions and proposed resolutions.

Mudda is built using a **scalable microservices architecture**, where different components of the platform are separated into independent services. This approach allows the system to be modular, maintainable, and easily scalable as the platform grows.

The repositories for the individual microservices are linked in this README to help evaluators explore the system architecture and implementation details.

The project focuses on:

* **Scalable backend architecture**
* **Cloud-native deployment**
* **Modular service design**
* **Community-driven issue engagement**

