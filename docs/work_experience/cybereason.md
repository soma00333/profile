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
      <td>My mission was to develop new features and refactor legacy microservices for a distributed system that operates across 12,000+ servers and processes 80M+ events per second.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li>I developed new features.</li><li>I refactored legacy microservices.</li></ul></td>
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
      <td>As a member of a cross-functional global team, my mission was to enhance the reliability of a distributed system (operating across 12k+ servers, processing 80M+ events/sec) by developing custom metrics and distributed tracing.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li><strong>Observability Development:</strong> I developed custom metrics and distributed tracing to improve system observability.</li><li><strong>Incident Response:</strong> I troubleshooted cross-microservice issues to identify their root causes.</li></ul></td>
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
      <td>Summary</td>
      <td><strong>CR1</strong>. I designed and developed custom metrics, significantly improving observability across 3,000 servers.</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Complex Troubleshooting Environment:</strong> The API server consisted of multiple interconnected components, making troubleshooting a complex task.</li><li><strong>High Mean Time to Resolution (MTTR):</strong> Existing monitoring capabilities lacked sufficient insights, resulting in unacceptably long MTTR.</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><strong>Enhance Observability and Reduce MTTR:</strong> My objective was to improve system observability, streamline the debugging process, and significantly reduce MTTR.</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li><strong>Developed Custom Metrics:</strong>
        <ul>
          <li><strong>API Server:</strong> I implemented metrics for latency and error rates.</li>
          <li><strong>Elasticsearch:</strong> I developed metrics to monitor throughput.</li>
          <li><strong>MongoDB:</strong> I created metrics for query performance.</li>
        </ul>
      </li><li><strong>Improved Dashboards:</strong> I enhanced real-time dashboards to provide engineers with actionable insights for quicker issue identification.</li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>Designing Actionable Metrics:</strong> The main challenge was to design custom metrics that were not just data points but provided truly actionable insights for engineers.</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td><strong>Fostered Cross-Team Communication:</strong> I initiated and facilitated communication between SRE, DevOps, and Product teams to collaboratively define the most impactful metrics.</td>
    </tr>
    <tr>
      <td>Result</td>
      <td><strong>Reduced MTTR by 50% for Enterprise Customers:</strong> The enhanced observability and actionable dashboards significantly improved troubleshooting efficiency, leading to a 50% reduction in MTTR for enterprise customers.</td>
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
      <td>Summary</td>
      <td><strong>CR2</strong>. I analyzed thread dumps and heap dumps to troubleshoot a critical server issue involving 2,000 concurrent threads.</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Intermittent Server Crashes:</strong> A UI server for an enterprise customer (with 100,000 employees) was crashing intermittently.</li><li><strong>Insufficient Monitoring Data:</strong> The root cause was unknown, and conventional monitoring tools did not provide adequate insights for diagnosis.</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><strong>Identify Bottleneck and Ensure Stability:</strong> My mission was to pinpoint the performance bottleneck causing the crashes and implement a solution to ensure system stability.</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li><strong>Conducted Root Cause Analysis:</strong>
          <ul>
            <li>I fetched and meticulously analyzed thread dumps and heap dumps from the affected server.</li>
            <li>I discovered that a legacy API was blocking HTTP threads, which in turn triggered health check failures and led to automatic server restarts.</li>
          </ul>
        </li><li><strong>Implemented Solution:</strong> I migrated the problematic legacy API to an efficient v2 API, which resolved the blocking issue.</li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>Automated Restarts Hindered Data Collection:</strong> An automated pipeline would restart the UI server immediately upon failure, preventing manual collection of necessary thread and heap dumps for analysis.</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td><strong>Enhanced Data Collection Pipeline:</strong> I modified the pipeline to automatically collect thread dumps and heap dumps before initiating a server restart.</td>
    </tr>
    <tr>
      <td>Result</td>
      <td><strong>Resolved Critical Availability Issues:</strong> My actions successfully resolved the critical availability issues, significantly enhancing system reliability for the enterprise customer with 100,000 employees.</td>
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