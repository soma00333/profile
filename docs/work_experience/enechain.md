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
      <td>My mission was to develop internal APIs and tools aimed at enhancing developer productivity across the organization.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li>I developed internal APIs and various tools to support development teams.</li></ul></td>
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
      <td>My primary mission was to improve the overall system reliability for over 20 microservices.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li><strong>Observability Development:</strong> I focused on developing and enhancing observability features.</li></ul></td>
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
      <td>Summary</td>
      <td><strong>EN1</strong>. I developed a generator tool for Kubernetes manifests and Terraform configurations for new microservices.</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td>
        <ul>
          <li><strong>Manual Configuration Overhead:</strong> Developers were required to manually create Kubernetes manifests and Terraform configurations for each new microservice.</li>
          <li><strong>Process Inefficiency and Error Rate:</strong> This manual process was time-consuming and highly prone to errors, slowing down deployments.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><strong>Automate Configuration Generation for Efficiency:</strong> My goal was to automate the generation of these configurations to significantly enhance development efficiency and reduce errors.</td>
    </tr>
    <tr>
      <td>Action</td>
      <td>
        <ul>
          <li><strong>Developed a Configuration Generator Tool:</strong></li>
          <ul>
            <li><strong>Go-Based Command-Line Tool:</strong> I implemented a command-line tool using Go to trigger the generation process.</li>
            <li><strong>Standardized Template System:</strong> I created a template system to ensure the generation of standardized and consistent configurations.</li>
          </ul>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>Ensuring Up-to-Date Templates:</strong> A key challenge was version management; if developers used an outdated version of the CLI tool, incorrect or deprecated templates could be generated.</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td><strong>Centralized Logic via CI Integration:</strong> I configured the CLI client to only act as a trigger for a Continuous Integration (CI) pipeline. The main generation logic was managed within the CI environment, ensuring it was always up-to-date.</td>
    </tr>
    <tr>
      <td>Result</td>
      <td><strong>Reduced Initial Deployment Time by 90%:</strong> The tool streamlined the deployment process for new microservices, achieving a 90% reduction in the initial setup and deployment time.</td>
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
      <td>Summary</td>
      <td><strong>EN2</strong>. I developed a system for local development by deploying Telepresence to the Kubernetes cluster.</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td>
        <ul>
          <li><strong>Microservice Dependencies in Local Development:</strong> Local development was heavily dependent on other microservices running in the cluster, making isolated development difficult.</li>
          <li><strong>Complex Local Environment Setup:</strong> Setting up a complete local development environment that mirrored the cluster was time-consuming and complex.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><strong>Enable Efficient, Independent Local Development:</strong> My objective was to enable developers to efficiently work on individual microservices locally without needing to run all other dependent services.</td>
    </tr>
    <tr>
      <td>Action</td>
      <td>
        <ul>
          <li><strong>Deployed Telepresence:</strong> I deployed Telepresence to the Kubernetes cluster, allowing local machines to interact with services running in the cluster as if they were local.</li>
          <li><strong>Developed a Streamlined Local Development System:</strong> I utilized Devcontainers to further streamline the local development setup and ensure consistency.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td>
        <ul>
          <li><strong>Meeting High-Security Requirements:</strong> We had robust security standards for our Kubernetes clusters, but the official Telepresence Helm charts did not natively support the required security configurations (e.g., specific security contexts, network policies).</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>
        <ul>
          <li><strong>Customized Helm Charts with Kustomize:</strong> I converted the official Telepresence Helm charts to Kustomize overlays to allow for easier customization.</li>
          <li><strong>Applied Manual Security Enhancements:</strong> I then manually added necessary security patches and configurations, including Pod Security Admission policies, NetworkPolicies, and specific Security Contexts.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Result</td>
      <td><strong>Improved Microservice Development Speed by 15%:</strong> This system accelerated local development cycles, leading to a 15% improvement in overall microservice development speed.</td>
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
