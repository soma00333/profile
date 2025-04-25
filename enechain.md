# enechain Corporation

**Type:** Freelance
**Start:** November 1, 2023
**End:** October 31, 2024
**Title:** Site Reliability Engineer / Software Engineer (Platform)

## Company

| Key         | Value                                                                                                                                                     |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Company     | enechain Corporation                                                                                                                                      |
| Employee    | 160+                                                                                                                                                      |
| Founded     | 2019                                                                                                                                                      |
| Web Site    | https://enechain.co.jp/                                                                                                                                   |
| Description | A company collaborating with Japan's largest power companies and operating the energy exchange market, dealing with electricity, fuels, and environmental values |
| Location    | Tokyo, Japan                                                                                                                                              |

## Team (Software Engineer - Platform)

| Key       | Value                                                         |
| --------- | ------------------------------------------------------------- |
| Title     | Software Engineer (Platform)                                  |
| Mission   | Develop internal APIs and tools to enhance developer productivity |
| Task      | <ul><li>Develop internal APIs and tools</li></ul>                              |
| Term      | April 1, 2024 - October 31, 2024                             |
| Team Size | 3                                                             |
| Type      | Freelance                                                     |

## Team (Site Reliability Engineer)

| Key       | Value                                         |
| --------- | --------------------------------------------- |
| Title     | Site Reliability Engineer                     |
| Mission   | Improve the system's reliability for 20+ microservices |
| Task      | <ul><li>Ovservability Development</li></ul>                   |
| Term      | November 1, 2023 - April 30, 2024            |
| Team Size | 5                                             |
| Type      | Freelance                                     |

## Project (Manifest/Terraform Generator)

| Key       | Value                                                                                                                                         |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Summary   | EN1. Developed a generator tool for manifests and Terraform configurations for new microservices                                                |
| Problem   | <ul><li>Manual Configuration: Developers had to create manifests and Terraform configurations for each new microservice manually</li><li>Inefficiency & Errors: The process was time-consuming and error-prone</li></ul> |
| Mission   | - Automate the generation of manifests and Terraform configurations to enhance development efficiency                                          |
| Action    | <ul><li>Develop a generator tool:<ul><li>Command-Line Tool: Implemented a command line tool using Go</li><li>Template System: Created a template to generate standardized configurations</li></ul></li></ul> |
| Challenge | Version Management: If developers used an outdated CLI version, incorrect templates would be generated                                          |
| Overcome  | - CI Integration : Configured the CLI client to only trigger the CI, while managing the main logic within the CI to ensure it is always up to date |
| Result    | - Streamlined the deployment process, achieving a 90% reduction in the initial deployment time for new microservices                            |
| Skill     | Tool Development                                                                                                                              |

## Project (Local Development Environment)

| Key       | Value                                                                                                                                                                       |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Summary   | EN2. Developed a system for local development by deploying Telepresence to the Kubernetes cluster                                                                          |
| Problem   | <ul><li>Dependency on Other Microservices: Local development was dependent on other microservices</li><li>Complex Setup: Setting up a local environment was time-consuming</li></ul>                |
| Mission   | - Enable efficient local development without depending on other microservices                                                                                                |
| Action    | <ul><li>Deploy Telepresence: Enabled interaction with other microservices in the cluster from the local environment</li><li>Develop a Local Development System: Utilized Devcontainer for streamlined development</li></ul> |
| Challenge | <ul><li>High-Security Requirement:<ul><li>We had robust security standards for our Kubernetes clusters</li><li>But official Helm charts didn't support modifying security configurations</li></ul></li></ul> |
| Overcome  | <ul><li>Customizing Helm Charts: Converted Helm charts to Kustomize</li><li>Manual Security Enhancements: Added security patches manually<ul><li>Pod Security Admission</li><li>NetworkPolicy</li><li>Security Context</li></ul></li></ul> |
| Result    | - Accelerated local development, achieving a 15% improvement in microservice development speed                                                                             |
| Skill     | Kubernetes / Security                                                                                                                                                     |

## Technology

| Value           | Tag               |
| --------------- | ----------------- |
| Argo Workflows  | Backend           |
| Go              | Backend           |
| GraphQL         | Backend           |
| gRPC            | Backend           |
| Node.js         | Backend           |
| PostgreSQL      | Backend           |
| Redis           | Backend           |
| TypeScript      | Backend, Frontend |
| ArgoCD          | Infrastructure    |
| AWS             | Infrastructure    |
| Google Cloud    | Infrastructure    |
| Kubernetes      | Infrastructure    |
| Terraform       | Infrastructure    |
| BigQuery        | Data Platform     |
| Kubeflow        | Data Platform     |
| Datadog         | Monitoring        |
| Prometheus      | Monitoring        |
| React           | Frontend          |