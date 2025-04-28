---
layout: default
title: Industry Technology
parent: Work Experience
nav_order: 5
---

# Industry Technology Inc.

## Company

| Key         | Value                                                                                        |
| ----------- | -------------------------------------------------------------------------------------------- |
| Company     | Industry Technology Inc.                                                                     |
| Employee    | 30+                                                                                          |
| Founded     | 2018                                                                                         |
| Web Site    | https://industrytechnology.co/                                                               |
| Description | A proptech company delivering enterprise applications for Japan's largest real estate companies |
| Location    | Tokyo, Japan                                                                                 |

## Team

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
      <td>CTO / Software Engineer (Backend)</td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>As a CTO, lead the development team of 8 members for enterprise applications, personally writing 100k+ lines backend codes from scratch</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li>Feature Development</li><li>Introduce SRE practices</li></ul></td>
    </tr>
    <tr>
      <td>Term</td>
      <td>April 1, 2019 - September 30, 2024</td>
    </tr>
    <tr>
      <td>Team Size</td>
      <td>8</td>
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
      <td>IT1</td>
    </tr>
    <tr>
      <td>Summary</td>
      <td>IT1. Designed SLI/SLO and developed custom metrics and tracing to enhance system reliability</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Business Opportunity</strong>: Got a chance to introduce the system to Japan's largest real estate company</li><li><strong>Operational Gaps</strong>: Realized that the existing operation does not meet the required level</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Improve system reliability to satisfy expected operational level</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li>**SLI/SLO Design**: Designed SLI/SLO using CUJ</li><li>**Observability Development**
          <ul>
            <li>Implemented custom metrics</li>
            <li>Implemented tracing</li>
          </ul>
        </li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td>**SLO Tuning**: Since violating the SLO requires stopping releases, I had to adjust the objective threshold properly</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>**Load Testing & Optimization**: By conducting load tests, I checked the SLI during traffic spikes and set appropriate objectives</td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Strengthened customer trust, securing a major enterprise contract</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td>SLI/SLO / Observability / Monitoring / Load Test</td>
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
      <td>IT2</td>
    </tr>
    <tr>
      <td>Summary</td>
      <td>IT2. Developed a group chat service and notification system enabling the exchange of photos, videos, and texts</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><strong>Need for Chat Functionality</strong>: The system lacked a chat function required for business operations</td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Develop a group chat service and notification system</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li>Develop the group chat feature
          <ul>
            <li>Implemented S3 + Signed URL for media sharing</li>
            <li>Integrated CDN for optimized content delivery</li>
          </ul>
        </li><li>Develop a notification system
          <ul>
            <li>Built an event-driven architecture for efficient notifications</li>
          </ul>
        </li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td>**Tight Schedule**: There was not enough time to build a WebSocket server</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>**Polling-Based Approach**: Extended the existing API using polling instead of WebSocket</td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Improved user engagement and productivity by 25% with a seamless chat and notification experience</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td>Feature Development</td>
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
      <td>IT3</td>
    </tr>
    <tr>
      <td>Summary</td>
      <td>IT3. Tuned indexes and optimized queries to improve database performance</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Frequent Slow Queries</strong>: A core feature suffered from repeated slow queries, impacting user experience.</li><li><strong>High CPU & Memory Utilization</strong>: Slow queries led to CPU and memory spikes, especially during peak hours (09:00 AM)</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><ul><li>Diagnose performance bottlenecks</li><li>Optimize query execution</li></ul></td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li>**Index Optimization**: Implemented appropriate indexes to improve query performance</li><li>**Query Refactoring**:
          <ul>
            <li>Eliminated unnecessary joins</li>
            <li>Optimized queries to utilize indexes efficiently</li>
          </ul>
        </li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td>**Root Cause Analysis**: Identifying the exact source of slow queries was challenging due to complex query execution patterns</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td><ul><li>**Query Tracing**: Monitored and analyzed tracing to detect anomalies</li><li>**EXPLAIN Analysis**: Used EXPLAIN statements to identify queries performing full table scans without indexes</li></ul></td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Reduced slow query occurrences by 70%, stabilizing peak-hour performance</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td>Performance Optimization</td>
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
      <td>IT4</td>
    </tr>
    <tr>
      <td>Summary</td>
      <td>IT4. Migrated from a modular monolith to a microservices architecture to improve scalability</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Monolithic Architecture</strong>: The system was initially built as a modular monolith</li><li><strong>Increased Database Load</strong>: Traffic to core features grew, leading to increased write load on the database</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Create independent microservices from the primary service to address the increasing load</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li>Migrated to microservices step-by-step</li><li>Created three microservices:
          <ul>
            <li>Work Diary</li>
            <li>Attendance Management</li>
            <li>Main</li>
          </ul>
        </li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td>**Downtime Minimization**: We needed to achieve the migration while minimizing downtime</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>**BFF-Based Traffic Management**: Added a BFF layer in front of the microservices and gradually switched traffic to each service, enabling a seamless migration</td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Distributed traffic to core features across microservices, reducing the write load on the database</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td>Migration</td>
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
      <td>IT5</td>
    </tr>
    <tr>
      <td>Summary</td>
      <td>IT5. Migrated from MySQL 5.7 to MySQL 8.0 to ensure reliability and maintainability</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>End-of-Life Version</strong>: MySQL 5.7 was approaching its end-of-life, necessitating an upgrade</li><li><strong>Migration Complexity</strong>: The migration process involved complexities and potential risks</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Seamlessly upgrade to MySQL 8.0 while ensuring system stability and performance</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li>Developed a runbook: Documented a step-by-step migration plan.</li><li>Implemented Blue-Green deployment: Ensured a smooth transition with minimal downtime and a rollback strategy.</li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td>**Incident during migration**: Unexpected issues surfaced, impacting user experience</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td><ul><li>**Investigation & Root Cause Analysis**:
          <ul>
            <li>Users encountered an error dialog on service pages</li>
            <li>**Root cause**: JSON unmarshal error due to a change in column type from UNSIGNED to DOUBLE</li>
            <li>**Temporary Fix**: Deployed a hotfix to handle JSON parsing errors</li>
            <li>**Permanent Fix**: Reverted JSON column type back to UNSIGNED, resolving compatibility issues</li>
          </ul>
        </li></ul></td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Increased query performance by 20%</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td>Incident Response / Migration</td>
    </tr>
  </tbody>
</table>

## Technology

| Value        | Tag            |
| ------------ | -------------- |
| Go           | Backend        |
| gRPC         | Backend        |
| MySQL        | Backend        |
| PostgreSQL   | Backend        |
| Redis        | Backend        |
| AWS          | Infrastructure |
| Google Cloud | Infrastructure |
| Terraform    | Infrastructure |
| Datadog      | Monitoring     |
| Prometheus   | Monitoring     |
| Next.js      | Frontend       |
| React        | Frontend       |
| TypeScript   | Frontend       | 