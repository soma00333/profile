---
layout: default
title: Cybereason
parent: Work Experience
nav_order: 1
---

# Cybereason Inc.

## Company

| Key         | Value                                                                                                             |
| ----------- | ----------------------------------------------------------------------------------------------------------------- |
| Company     | Cybereason Inc.                                                                                                   |
| Employee    | 1000+                                                                                                             |
| Founded     | 2012                                                                                                              |
| Web Site    | [https://www.cybereason.com/](https://www.cybereason.com/)                                                        |
| Description | A global cybersecurity company operating in 40 countries. We provide EDR, XDR, and MDR solutions to stop cyberattacks |
| Location    | Tokyo, Japan                                                                                                      |

## Team (Software Engineer - Backend)

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
      <td>Software Engineer (Backend)</td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>My mission was to develop new features and refactor old microservices for a distributed system that runs on 12,000 servers and processes 80M events per second.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td>
        <ul>
          <li>I developed new features.</li>
          <li>I refactored legacy microservices.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Term</td>
      <td>2025-03 - 2025-08</td>
    </tr>
    <tr>
      <td>Team Size</td>
      <td>9</td>
    </tr>
    <tr>
      <td>Type</td>
      <td>Permanent</td>
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
      <td>I worked with a global team to improve the reliability of our system. The system runs on 12,000 servers and handles 80M events per second.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td>
        <ul>
          <li>I developed custom metrics and distributed tracing to improve system observability.</li>
          <li>I troubleshot cross-microservice issues to find their root causes.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Term</td>
      <td>2024-10 - 2025-03</td>
    </tr>
    <tr>
      <td>Team Size</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Type</td>
      <td>Permanent</td>
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
      <td><strong>CR1</strong>. I built custom metrics that improved observability across 3,000 servers.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>An API server had many connected parts. This made troubleshooting hard.</li>
          <li>Our monitoring didn't give enough information. Problems took too long to fix.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>I wanted to see the system better, debug easier, and fix problems faster.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I implemented custom metrics:
            <ul>
              <li>I implemented API server latency and error rate metrics</li>
              <li>I implemented Elasticsearch throughput metrics</li>
              <li>I implemented MongoDB query performance metrics</li>
            </ul>
          </li>
          <li>I created real-time dashboards:
            <ul>
              <li>I built visual displays showing system health</li>
              <li>I added alerts for faster problem detection</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>Better visibility and useful dashboards made troubleshooting faster. We cut problem resolution time by 50% for enterprise customers.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>The hard part was making metrics that gave engineers useful insights, not just data points.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>I led talks between SRE, DevOps, and Product teams. We worked together to define the most important metrics.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that teams must work together to define metrics that help everyone.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
      <td>Observability / Monitoring / Collaboration</td>
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
      <td><strong>CR2</strong>. I analyzed thread dumps and heap dumps to fix a critical server issue with 2,000 concurrent threads.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>An API server kept crashing for a customer with 100,000 employees.</li>
          <li>We didn't know why. Normal monitoring tools didn't help.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>I had to find what caused the crashes and fix it.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I analyzed server performance data:
            <ul>
              <li>I collected thread dumps and heap dumps from the broken server</li>
              <li>I found that an old API was blocking HTTP threads</li>
              <li>I identified that it caused health check failures and led to automatic restarts</li>
            </ul>
          </li>
          <li>I implemented the solution:
            <ul>
              <li>I migrated the problematic old API to an efficient v2 API</li>
              <li>I fixed the thread blocking issue completely</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>I fixed the availability issues and made the system reliable for the customer with 100,000 employees.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>The pipeline restarted the server right after crashes. This stopped me from collecting the dumps I needed.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>I changed the pipeline to collect dumps before restarting the server.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned to collect data automatically before systems restart. This helps find root causes during incidents.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
      <td>Incident Response / Troubleshooting / Automation</td>
    </tr>
  </tbody>
</table>

## Technology

| Value            | Tag            |
| ---------------- | -------------- |
| Aerospike        | Backend        |
| Apache Kafka     | Backend        |
| Apache ZooKeeper | Backend        |
| Consul           | Backend        |
| Elasticsearch    | Backend        |
| GraphQL          | Backend        |
| gRPC             | Backend        |
| Java             | Backend        |
| MongoDB          | Backend        |
| PostgreSQL       | Backend        |
| Python           | Backend        |
| Redis            | Backend        |
| Spring Boot      | Backend        |
| AWS              | Infrastructure |
| Google Cloud     | Infrastructure |
| Jenkins          | Infrastructure |
| Kubernetes       | Infrastructure |
| Oracle Cloud     | Infrastructure |
| Terraform        | Infrastructure |
| Elastic Stack    | Monitoring     |
| Grafana          | Monitoring     |
| Jaeger           | Monitoring     |
| Prometheus       | Monitoring     | 