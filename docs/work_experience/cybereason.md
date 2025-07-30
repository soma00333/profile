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
| Employee    | 1000                                                                                                             |
| Founded     | 2012                                                                                                              |
| Web Site    | [https://www.cybereason.com/](https://www.cybereason.com/)                                                        |
| Description | Cybereason is a global cybersecurity company operating in 40 countries. We provide EDR, XDR, and MDR solutions to stop cyberattacks. The core system runs on 12,000 servers and handles 80M events per second. |
| Location    | San Diego, US                                                                                                      |

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
      <td>My mission was to develop new features and refactor legacy microservices for the core system.</td>
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
      <td>My mission was to work with a global team to improve system reliability for the core system.</td>
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
      <td><strong>CR1</strong>. I designed and developed custom metrics to improve observability across 3,000 servers, which cut problem resolution time by 50% for enterprise customers.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>An API running on 3,000 servers had many connected components, which made troubleshooting difficult.</li>
          <li>Our monitoring did not provide enough information, which took time to resolve issues.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to improve system observability, make debugging easier, and reduce problem resolution time.</td>
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
          <li>I created real-time dashboards and alerts</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>As a result, better visibility and useful dashboards made troubleshooting faster. We cut problem resolution time by 50% for enterprise customers.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was making metrics that gave engineers useful insights, not just data points.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>To solve this, I led the communication between SRE, DevOps, and Product teams. We worked together to define the most important metrics.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that effective monitoring isn't about collecting data, but providing clear, actionable insights that help engineers solve problems faster.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
      <td>Observability / Monitoring / Collaboration / Teamwork</td>
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
      <td><strong>CR2</strong>. I troubleshot and fixed a critical server issue with 2,000 concurrent threads, which resolved crashes affecting an enterprise company.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>An API server which had 2,000 concurrent threads kept crashing.</li>
          <li>Standard monitoring tools didn't provide any answers.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to find what caused the crashes and fix it urgently.</td>
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
      <td>As a result, the fix made the system reliable for the customer with 100,000 employees and we got their trust.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was that the pipeline restarted the server right after crashes automatically. This stopped me from collecting the dumps I needed.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>To solve this, I modified the pipeline to collect dumps before restarting the server.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that solving complex issues requires analyzing the system's core behavior, not just its surface-level symptoms.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
      <td>Incident Response / Troubleshooting / Automation / Difficult Problem</td>
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
      <td><strong>CR3</strong>. I fixed a critical bug in the core API that required thorough testing across various versions and feature flags, which restored the correct Malop status for millions of endpoints.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>The core API that returns Malicious Operation (Malop) information had a bug where the status was different from what was intended.</li>
          <li>The bug only occurred with specific feature flags and specific versions, making it extremely difficult to reproduce.</li>
          <li>This API affected millions of endpoints, so any fix required thorough testing.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to identify the root cause of the bug and fix it without impacting millions of endpoints.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I investigated the issue systematically:
            <ul>
              <li>I analyzed the code and documentation to understand the expected behavior</li>
              <li>I set up multiple test environments with different configurations</li>
              <li>I tested various scenarios with different versions and feature flag combinations</li>
            </ul>
          </li>
          <li>I identified the exact conditions to reproduce the bug:
            <ul>
              <li>I discovered that a critical variable used in Malop status calculation became null under specific conditions</li>
            </ul>
          </li>
          <li>I fixed the code and ensured quality:
            <ul>
              <li>I implemented the fix with minimal code changes</li>
              <li>I conducted thorough testing and QA before shipping</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>As a result, the bug was fixed successfully and deployed to production without any incidents, restoring correct Malop status for millions of endpoints.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was that the investigation took a long time because the bug only appeared under very specific conditions.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>To solve this, I systematically tested different combinations and documented each test result, which eventually led me to identify the exact reproduction conditions.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that reproducing complex bugs is both challenging and crucial - systematic testing and detailed documentation are essential for solving edge-case issues.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
      <td>Difficult Problem / Troubleshooting / Automation</td>
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