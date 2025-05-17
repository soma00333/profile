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
      <td>As CTO, I led a development team of 8 members in creating enterprise applications. I was also hands-on, personally writing over 100,000 lines of backend code from scratch.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li><strong>Feature Development:</strong> I was responsible for the development of new product features.</li><li><strong>SRE Practice Introduction:</strong> I introduced and implemented Site Reliability Engineering (SRE) practices within the team.</li></ul></td>
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
      <td>Summary</td>
      <td><strong>IT1</strong>. I designed Service Level Indicators (SLIs) and Objectives (SLOs), and developed custom metrics and tracing to significantly enhance system reliability.</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Major Business Opportunity:</strong> We had an opportunity to introduce our system to one of Japan's largest real estate companies.</li><li><strong>Operational Readiness Gap:</strong> I realized that our existing operational capabilities did not meet the reliability and performance levels required by this potential enterprise client.</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><strong>Achieve Enterprise-Grade Reliability:</strong> My goal was to elevate system reliability to meet the stringent operational standards expected by a major enterprise customer.</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li><strong>Designed SLIs/SLOs:</strong> I designed SLIs and SLOs based on Critical User Journeys (CUJs) to define and measure reliability.</li><li><strong>Developed Observability Features:</strong>
          <ul>
            <li>I implemented custom metrics to track key performance indicators.</li>
            <li>I integrated distributed tracing to provide insights into request flows.</li>
          </ul>
        </li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>Balancing SLOs and Release Velocity:</strong> A key challenge was tuning the SLOs appropriately, as violating an SLO would necessitate halting releases, potentially impacting development agility.</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td><strong>Conducted Load Testing and Iterative Optimization:</strong> I performed comprehensive load tests to observe SLI behavior under traffic spikes and used this data to set realistic and achievable SLOs, iteratively optimizing as needed.</td>
    </tr>
    <tr>
      <td>Result</td>
      <td><strong>Secured Major Enterprise Contract:</strong> The improved system reliability and demonstrated operational maturity strengthened customer trust, directly leading to securing a major enterprise contract.</td>
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
      <td>Summary</td>
      <td><strong>IT2</strong>. I developed a group chat service and a notification system, enabling users to exchange photos, videos, and text messages.</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><strong>Missing Essential Chat Functionality:</strong> The system lacked a required chat function, which was crucial for daily business operations and user collaboration.</td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><strong>Deliver Robust Chat and Notification Capabilities:</strong> My objective was to develop a comprehensive group chat service and an efficient notification system to meet business needs.</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li><strong>Developed Group Chat Feature:</strong>
          <ul>
            <li>I implemented secure media sharing (photos, videos) using S3 with Signed URLs.</li>
            <li>I integrated a Content Delivery Network (CDN) for optimized and fast content delivery.</li>
          </ul>
        </li><li><strong>Developed Notification System:</strong>
          <ul>
            <li>I built an event-driven architecture to ensure efficient and timely notifications.</li>
          </ul>
        </li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>Meeting Tight Development Schedule:</strong> The primary constraint was a very tight schedule, which did not allow sufficient time to build a more complex WebSocket-based real-time solution.</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td><strong>Adopted Pragmatic Polling-Based Approach:</strong> To meet the deadline, I extended the existing API using a polling mechanism for near real-time updates, instead of implementing a WebSocket server.</td>
    </tr>
    <tr>
      <td>Result</td>
      <td><strong>Improved User Engagement and Productivity by 25%:</strong> The new system provided a seamless chat and notification experience, resulting in a 25% improvement in user engagement and productivity.</td>
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
      <td>Summary</td>
      <td><strong>IT3</strong>. I tuned database indexes and optimized queries, significantly improving overall database performance.</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Frequent Slow Queries Impacting UX:</strong> A core feature of the application suffered from repeated slow queries, negatively impacting user experience.</li><li><strong>Resource Spikes During Peak Hours:</strong> These slow queries led to high CPU and memory utilization on the database, especially during peak usage times (e.g., 09:00 AM).</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><strong>Diagnose and Resolve Performance Bottlenecks:</strong> My goals were to diagnose the root causes of the performance bottlenecks and optimize query execution for improved stability and speed.</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li><strong>Optimized Database Indexes:</strong> I analyzed query patterns and implemented appropriate indexes to accelerate data retrieval.</li><li><strong>Refactored Inefficient Queries:</strong>
          <ul>
            <li>I identified and eliminated unnecessary table joins.</li>
            <li>I rewrote queries to ensure they effectively utilized the newly created and existing indexes.</li>
          </ul>
        </li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>Identifying Root Cause of Complex Slow Queries:</strong> Pinpointing the exact source of slow queries was challenging due to complex data models and intricate query execution patterns.</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td><ul><li><strong>Utilized Query Tracing:</strong> I monitored and analyzed distributed tracing data to detect anomalies and identify problematic query paths.</li><li><strong>Performed EXPLAIN Analysis:</strong> I used EXPLAIN statements to analyze query execution plans, specifically looking for full table scans and inefficient index usage.</li></ul></td>
    </tr>
    <tr>
      <td>Result</td>
      <td><strong>Reduced Slow Queries by 70% and Stabilized Performance:</strong> These optimizations led to a 70% reduction in slow query occurrences and stabilized system performance, especially during peak hours.</td>
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
      <td>Summary</td>
      <td><strong>IT4</strong>. I led the migration from a modular monolith to a microservices architecture to enhance system scalability.</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Scalability Limits of Monolithic Architecture:</strong> The system was initially built as a modular monolith, which began to show scalability limitations.</li><li><strong>Increased Database Load on Core Features:</strong> As user traffic to core features grew, the write load on the central database significantly increased, impacting performance.</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><strong>Improve Scalability through Microservices:</strong> My objective was to create independent microservices from the primary monolithic service to distribute the load and improve overall system scalability.</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li><strong>Executed Phased Microservice Migration:</strong> I migrated the system to microservices incrementally to minimize risk and ensure stability.</li><li><strong>Created Key Microservices:</strong> I designed and implemented three initial microservices for distinct domains: Work Diary, Attendance Management, and a core Main service.</li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>Minimizing Downtime During Migration:</strong> A critical requirement was to perform the migration with minimal or zero downtime to avoid disrupting users.</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td><strong>Implemented BFF for Gradual Traffic Switching:</strong> I introduced a Backend-for-Frontend (BFF) layer in front of the new microservices. This allowed us to gradually switch traffic from the monolith to each new service, enabling a seamless and controlled migration.</td>
    </tr>
    <tr>
      <td>Result</td>
      <td><strong>Reduced Database Load and Improved Scalability:</strong> The migration successfully distributed traffic for core features across independent microservices, significantly reducing the write load on the main database and improving overall system scalability.</td>
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
      <td>Summary</td>
      <td><strong>IT5</strong>. I managed the migration from MySQL 5.7 to MySQL 8.0 to ensure long-term system reliability and maintainability.</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Approaching End-of-Life for MySQL 5.7:</strong> The existing MySQL 5.7 database version was nearing its end-of-life, necessitating an upgrade to a supported version.</li><li><strong>Inherent Migration Complexity and Risks:</strong> Database migrations of this scale are inherently complex and carry potential risks of data loss or extended downtime if not managed carefully.</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><strong>Execute Seamless Upgrade to MySQL 8.0:</strong> My mission was to seamlessly upgrade the database to MySQL 8.0 while ensuring system stability, data integrity, and optimal performance.</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li><strong>Developed Detailed Runbook:</strong> I created a comprehensive, step-by-step migration plan (runbook) to ensure a predictable and controlled process.</li><li><strong>Implemented Blue-Green Deployment Strategy:</strong> I utilized a blue-green deployment strategy for the database, which allowed for a smooth transition, minimized downtime, and provided a clear rollback path.</li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>Unexpected Incident During Migration:</strong> Despite careful planning, unexpected issues surfaced post-migration, impacting user experience on certain service pages.</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>
        <ul>
          <li><strong>Rapid Investigation & Root Cause Analysis:</strong></li>
            <ul>
              <li>Users reported encountering an error dialog on specific service pages after the migration.</li>
              <li><strong>Identified Root Cause:</strong> I quickly determined the issue was a JSON unmarshal error caused by an unintended data type change in a column (from UNSIGNED INT to DOUBLE during the migration process for certain tables).</li>
            </ul>
          <li><strong>Immediate Temporary Fix:</strong> I deployed a hotfix to gracefully handle the JSON parsing errors, restoring service availability.</li>
          <li><strong>Definitive Permanent Fix:</strong> I then reverted the affected JSON column types back to their original UNSIGNED INT definition, fully resolving the compatibility issues and ensuring data integrity.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Result</td>
      <td><strong>Increased Query Performance by 20%:</strong> The migration to MySQL 8.0, once stabilized, resulted in a 20% increase in overall query performance.</td>
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
