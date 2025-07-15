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
| Description | A company that works with Japan's largest power companies. It runs the energy exchange market. It handles electricity, fuels, and environmental values |
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
      <td>My mission was to develop internal APIs and tools to improve developer productivity across the organization.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td>
        <ul>
          <li>I developed internal APIs and various tools to support development teams.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Term</td>
      <td>2024-04 - 2024-10</td>
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
      <td>My main mission was to improve system reliability for over 20 microservices.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td>
        <ul>
          <li>I developed and enhanced observability features.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Term</td>
      <td>2023-11 - 2024-04</td>
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
      <td><strong>Summary</strong></td>
      <td><strong>EN1</strong>. I developed a generator tool to create Kubernetes manifests and Terraform configurations for new microservices.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>Developers had to manually create Kubernetes manifests and Terraform configurations for each new microservice.</li>
          <li>This manual process was slow and caused many errors. This slowed down deployments.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to automate creating these configurations to greatly improve development efficiency and reduce errors.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I developed tools
            <ul>
              <li>I implemented a command-line tool using Go to trigger the generation process</li>
              <li>I designed the CLI interface to be simple and user-friendly for developers</li>
            </ul>
          </li>
          <li>I created template system
            <ul>
              <li>I created a template system to ensure we generated standard configurations</li>
              <li>I made sure all generated configurations followed consistent patterns</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>As a result, the tool made deploying new microservices much smoother. Initial setup and deployment time decreased by 90%.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was version management. If developers used an old version of the CLI tool, they could create wrong or outdated templates.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>To solve this, I set up the CLI client to only trigger a CI pipeline. The main generation logic stayed in the CI environment. This made sure it was always up-to-date.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that centralizing logic in CI/CD pipelines is important to keep consistency across developer environments.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
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
      <td><strong>Summary</strong></td>
      <td><strong>EN2</strong>. I built a system for local development by adding Telepresence to the Kubernetes cluster.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>Local development depended heavily on other microservices running in the cluster. This made isolated development hard.</li>
          <li>Setting up a complete local development environment took a long time. Matching the cluster was complex.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to let developers work efficiently on individual microservices locally without needing to run all other dependent services.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I deployed Telepresence
            <ul>
              <li>I deployed Telepresence to the Kubernetes cluster</li>
              <li>I configured it so local machines could interact with cluster services as if they were local</li>
            </ul>
          </li>
          <li>I set up development environment
            <ul>
              <li>I used Devcontainers to make the local development setup smoother</li>
              <li>I ensured the development environment was consistent across the team</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>As a result, this system sped up local development cycles. Overall microservice development speed improved by 15%.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was our strong security standards for Kubernetes clusters. The official Telepresence Helm charts didn't support these security configurations by default.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>
        To solve this:
        <ul>
          <li>I converted the official Telepresence Helm charts to Kustomize overlays. This made customization easier.</li>
          <li>I manually added needed security patches and configurations. These included Pod Security Admissions, NetworkPolicies, and specific Security Contexts.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that balancing developer productivity tools with enterprise security needs requires customizing open-source solutions.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
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
