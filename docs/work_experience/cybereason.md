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
| Description | A global cybersecurity company operating in 40+ countries, providing EDR, XDR, and MDR solutions to combat cyberattacks |
| Location    | San Diego, US - Japan Office                                                                                      |

## Team (Software Engineer)

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
      <td>Software Engineer</td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Develop new features and refactor legacy microservices for a distributed system operating across 12k+ servers and processing 80M+ events/sec</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li>Develop features</li><li>Refactor legacy microservices</li></ul></td>
    </tr>
    <tr>
      <td>Term</td>
      <td>March 1, 2025 - current</td>
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
      <td>As a cross-functional global team, develop custom metrics and distributed tracing to enhance the reliability of a distributed system operating across 12k+ servers and processing 80M+ events/sec</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li>**Ovservability Development**: Develop custom metrics and distributed tracing to improve observability</li><li>**Incident Response**: Troubleshoot cross-microservices issues to identify the root cause</li></ul></td>
    </tr>
    <tr>
      <td>Term</td>
      <td>October 1, 2024 - March 31, 2025</td>
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
      <td>Key</td>
      <td>CR1</td>
    </tr>
    <tr>
      <td>Summary</td>
      <td>Designed and developed custom metrics and improved observability across 3k servers</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li>**Complex Troubleshooting**: The API server had multiple interconnected components, making troubleshooting difficult</li><li>**High MTTR**: Existing monitoring lacked sufficient insights, leading to long MTTR</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Improve observability, streamline debugging, and reduce MTTR</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li>**Develop custom metrics**:
        <ul>
          <li>**API**: Latency and Error Rate</li>
          <li>**Elasticsearch**: Throughput</li>
          <li>**MongoDB**: Query Performance</li>
        </ul>
      </li><li>**Dashboard**: Improved real-time dashboards to provide actionable insights for engineers</li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td>**Design**: Designing meaningful custom metrics that provide actionable insights</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>**Communication**: Fostered cross-functional communication between SRE, DevOps, and Product teams</td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Enhanced troubleshooting efficiency and reduced MTTR by 50% for enterprise customers</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td>Observability / Monitoring</td>
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
      <td>CR2</td>
    </tr>
    <tr>
      <td>Summary</td>
      <td>CR2. Analyzed thread dumps and heap dumps to troubleshoot a server with 2k concurrent threads</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li>**Crash**: A UI server crashed occasionally for an enterprise customer with 100k employees</li><li>**Troubleshooting Difficulty**: The root cause was unknown, and conventional monitoring tools provided insufficient insights</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Identify the performance bottleneck and ensure system stability</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li>**Root Cause Analysis**:
          <ul>
            <li>Fetched and analyzed thread dumps and heap dumps</li>
            <li>Found that a legacy API blocked HTTP threads, triggering health check failures and causing automatic restarts</li>
          </ul>
        </li><li>**Response**: Migrated the legacy API to an efficient v2 API, resolving the issue</li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td>**Fetching Data**: Since an automated pipeline restarted the UI server upon failure, manual thread and heap dumps could not be obtained</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>**Pipeline**: Added an automated pipeline to collect thread and heap dumps before restart</td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Successfully resolved critical availability issues, enhancing system reliability for the enterprise customer with 100k employees</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td>Incident Response / Troubleshooting</td>
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