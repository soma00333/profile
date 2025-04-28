---
layout: default
title: Enechain
parent: Work Experience
nav_order: 4
---

# enechain Corporation

## Company

| Key         | Value                                                                                                                                                     |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Company     | enechain Corporation                                                                                                                                      |
| Employee    | 160+                                                                                                                                                      |
| Founded     | 2019                                                                                                                                                      |
| Web Site    | [https://enechain.co.jp/](https://enechain.co.jp/)                                                                                                    |
| Description | A company collaborating with Japan's largest power companies and operating the energy exchange market, dealing with electricity, fuels, and environmental values |
| Location    | Tokyo, Japan                                                                                                                                              |

## Team (Software Engineer - Platform)

<table>
  <thead>
    <tr>
      <th>Key</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Title</td>
      <td>Software Engineer (Platform)</td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Develop internal APIs and tools to enhance developer productivity</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li>Develop internal APIs and tools</li></ul></td>
    </tr>
    <tr>
      <td>Term</td>
      <td>April 1, 2024 - October 31, 2024</td>
    </tr>
    <tr>
      <td>Team Size</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Type</td>
      <td>Freelance</td>
    </tr>
  </tbody>
</table>

## Team (Site Reliability Engineer)

<table>
  <thead>
    <tr>
      <th>Key</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Title</td>
      <td>Site Reliability Engineer</td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Improve the system's reliability for 20+ microservices</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li>Ovservability Development</li></ul></td>
    </tr>
    <tr>
      <td>Term</td>
      <td>November 1, 2023 - April 30, 2024</td>
    </tr>
    <tr>
      <td>Team Size</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Type</td>
      <td>Freelance</td>
    </tr>
  </tbody>
</table>

## Projects

<table>
  <thead>
    <tr>
      <th>Key</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Key</td>
      <td>EN1</td>
    </tr>
    <tr>
      <td>Summary</td>
      <td>EN1. Developed a generator tool for manifests and Terraform configurations for new microservices</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Manual Configuration</strong>: Developers had to create manifests and Terraform configurations for each new microservice manually</li><li><strong>Inefficiency & Errors</strong>: The process was time-consuming and error-prone</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Automate the generation of manifests and Terraform configurations to enhance development efficiency</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li>Develop a generator tool</li><li>**Command-Line Tool**: Implemented a command line tool using Go</li><li>**Template System**: Created a template to generate standardized configurations</li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td>**Version Management**: If developers used an outdated CLI version, incorrect templates would be generated</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>**CI Integration**: Configured the CLI client to only trigger the CI, while managing the main logic within the CI to ensure it is always up to date</td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Streamlined the deployment process, achieving a 90% reduction in the initial deployment time for new microservices</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td>Tool Development</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>Key</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Key</td>
      <td>EN2</td>
    </tr>
    <tr>
      <td>Summary</td>
      <td>EN2. Developed a system for local development by deploying Telepresence to the Kubernetes cluster</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Dependency on Other Microservices</strong>: Local development was dependent on other microservices</li><li><strong>Complex Setup</strong>: Setting up a local environment was time-consuming</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Enable efficient local development without depending on other microservices</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li>**Deploy Telepresence**: Enabled interaction with other microservices in the cluster from the local environment</li><li>**Develop a Local Development System**: Utilized Devcontainer for streamlined development</li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><ul><li><strong>High-Security Requirement</strong>:<ul><li>We had robust security standards for our Kubernetes clusters</li><li>But official Helm charts didn't support modifying security configurations</li></ul></li></ul></td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td><ul><li>**Customizing Helm Charts**: Converted Helm charts to Kustomize</li><li>**Manual Security Enhancements**: Added security patches manually</li><li>**Pod Security Admission**</li><li>**NetworkPolicy**</li><li>**Security Context**</li></ul></td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Accelerated local development, achieving a 15% improvement in microservice development speed</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td>Kubernetes / Security</td>
    </tr>
  </tbody>
</table>

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
