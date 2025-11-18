# Enterprise-level Borussia Dortmund Forum

Personal Semester Project. Extended a previously developed fan forum into an enterprise-grade, cloud-native platform focused on non-functional requirements, including scalability, security, performance, and usability. Designed the system to support thousands of concurrent users while maintaining high availability and responsive performance. Change frontend framework to Angular.

Key highlights:
• Re-architected the forum as a monorepo microservice platform with event-driven architecture using Azure Service Bus for asynchronous communication.
• Designed and implemented a fully automated CI/CD pipeline using GitLab CI, writing custom YAML scripts for build, test, package, security scanning, and deployment to Azure Kubernetes Service (AKS) with auto-scaling pods.
• Ensured robust security using RBAC, API Gateway, JWT-based cookie validation, and secure cookies.
• Integrated Azure Blob Storage for efficient and scalable image management.
• Engineered the system for high performance, handling 10,000 concurrent users with pages loading under 3 seconds on average.
• Optimized usability and accessibility, keeping all tasks reachable within 3 clicks.
• Maintained 95% reliability in production-simulated use cases, ensuring the platform could operate without failure in the vast majority of scenarios.
• Leveraged Docker to containerize services, simplifying deployment, testing, and scalability across environments.
