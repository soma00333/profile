# Difficult Decision

Value1: - Summary: EN2. Developed a system for local development by deploying Telepresence to the Kubernetes cluster at enechain
- Problem:
  - Dependency on Other Microservices: Local development was dependent on other microservices
  - Complex Setup: Setting up a local environment was time-consuming
- Mission: Enable efficient local development without depending on other microservices
- Action: 
  - Deploy Telepresence: Enabled interaction with other microservices in the cluster from the local environment
- Challenge:
  - High-Security Requirement:
    - We had robust security standards for our Kubernetes clusters
    - But official Helm charts didn’t support modifying security configurations
- Overcome
  - Manual Security Enhancements: Added security patches manually
- Result: Minimized security risks and improved the development speed