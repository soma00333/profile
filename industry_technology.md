# Industry Technology Inc.

**Type:** Permanent
**End:** September 30, 2024
**Start:** April 1, 2019
**Title:** CTO / Software Engineer (Backend)

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

| Key       | Value                                                                                                                                   |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Title     | CTO / Software Engineer (Backend)                                                                                                       |
| Mission   | As a CTO, lead the development team of 8 members for enterprise applications, personally writing 100k+ lines backend codes from scratch |
| Task      | <ul><li>Feature Development</li><li>Introduce SRE practices</li></ul>                                                                                     |
| Term      | April 1, 2019 - September 30, 2024                                                                                                     |
| Team Size | 8                                                                                                                                       |
| Type      | Permanent                                                                                                                               |

## Project (Reliability Enhancement)

| Key       | Value                                                                                                                                         |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Summary   | IT1. Designed SLI/SLO and developed custom metrics and tracing to enhance system reliability                                                    |
| Problem   | <ul><li>Business Opportunity: Got a chance to introduce the system to Japan's largest real estate company</li><li>Operational Gaps: Realized that the existing operation does not meet the required level</li></ul> |
| Mission   | - Improve system reliability to satisfy expected operational level                                                                            |
| Action    | <ul><li>SLI/SLO Design: Designed SLI/SLO using CUJ</li><li>Observability Development:<ul><li>Implemented custom metrics</li><li>Implemented tracing</li></ul></li></ul>         |
| Challenge | - SLO Tuning: Since violating the SLO requires stopping releases, I had to adjust the objective threshold properly                             |
| Overcome  | <ul><li>Load Testing & Optimization: By conducting load tests, I checked the SLI during traffic spikes and set appropriate objectives</li></ul>                |
| Result    | - Strengthened customer trust, securing a major enterprise contract                                                                           |
| Skill     | SLI/SLO / Observability / Monitoring / Load Test                                                                                            |

## Project (Group Chat & Notification)

| Key       | Value                                                                                                                                         |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Summary   | IT2. Developed a group chat service and notification system enabling the exchange of photos, videos, and texts                                 |
| Problem   | <ul><li>User Requirement: Users wanted a group chat service and notification system for exchanging photos, videos, and texts</li><li>Lack of Existing Features: But the system did not have these capabilities</li></ul> |
| Mission   | - Develop a group chat service and notification system                                                                                        |
| Action    | <ul><li>Develop the group chat feature:<ul><li>Implemented S3 + Signed URL for media sharing</li><li>Integrated CDN for optimized content delivery</li></ul></li><li>Develop a notification system:<ul><li>Built an event-driven architecture for efficient notifications</li></ul></li></ul> |
| Challenge | - Tight Schedule: There was not enough time to build a WebSocket server                                                                     |
| Overcome  | <ul><li>Polling-Based Approach: Extended the existing API using polling instead of WebSocket</li></ul>                                                          |
| Result    | - Improved user engagement and productivity by 25% with a seamless chat and notification experience                                           |
| Skill     | Feature Development                                                                                                                           |

## Project (Database Performance Tuning)

| Key       | Value                                                                                                                                         |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Summary   | IT3. Tuned indexes and optimized queries to improve database performance                                                                       |
| Problem   | <ul><li>Frequent Slow Queries: A core feature suffered from repeated slow queries, impacting user experience.</li><li>High CPU & Memory Utilization: Slow queries led to CPU and memory spikes, especially during peak hours (09:00 AM)</li></ul> |
| Mission   | <ul><li>Diagnose performance bottlenecks</li><li>Optimize query execution</li></ul>                                                                             |
| Action    | <ul><li>Index Optimization: Implemented appropriate indexes to improve query performance</li><li>Query Refactoring:<ul><li>Eliminated unnecessary joins</li><li>Optimized queries to utilize indexes efficiently</li></ul></li></ul> |
| Challenge | - Root Cause Analysis: Identifying the exact source of slow queries was challenging due to complex query execution patterns                    |
| Overcome  | <ul><li>Query Tracing: Monitored and analyzed tracing to detect anomalies</li><li>EXPLAIN Analysis: Used EXPLAIN statements to identify queries performing full table scans without indexes</li></ul> |
| Result    | - Reduced slow query occurrences by 70%, stabilizing peak-hour performance                                                                    |
| Skill     | Performance Optimization                                                                                                                      |

## Project (Monolith to Microservices Migration)

| Key       | Value                                                                                                                                         |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Summary   | IT4. Migrated from a modular monolith to a microservices architecture to improve scalability                                                    |
| Problem   | <ul><li>Monolithic Architecture: The system was initially built as a modular monolit</li><li>Increased Database Load: Traffic to core features grew, leading to increased write load on the database</li></ul> |
| Mission   | - Create independent microservices from the primary service to address the increasing load                                                     |
| Action    | <ul><li>Migrated to microservices step-by-step:<ul><li>Created three microservices:<ul><li>Work Diary</li><li>Attendance Management</li><li>Main</li></ul></li></ul></li></ul> |
| Challenge | - Downtime Minimization: We needed to achieve the migration while minimizing downtime                                                          |
| Overcome  | <ul><li>BFF-Based Traffic Management: Added a BFF layer in front of the microservices and gradually switched traffic to each service, enabling a seamless migration</li></ul> |
| Result    | - Distributed traffic to core features across microservices, reducing the write load on the database                                          |
| Skill     | Migration                                                                                                                                     |

## Project (MySQL Migration)

| Key       | Value                                                                                                                                         |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Summary   | IT5. Migrated from MySQL 5.7 to MySQL 8.0 to ensure reliability and maintainability                                                            |
| Problem   | <ul><li>End of Support Notice: MySQL 5.7 was approaching its end of support</li></ul>                                                                         |
| Mission   | - Seamlessly upgrade to MySQL 8.0 while ensuring system stability and performance                                                            |
| Action    | <ul><li>Developed a runbook: Documented a step-by-step migration plan.</li><li>Implemented Blue-Green deployment: Ensured a smooth transition with minimal downtime and a rollback strategy.</li></ul> |
| Challenge | - Incident during migration: Unexpected issues surfaced, impacting user experience                                                             |
| Overcome  | <ul><li>Investigation & Root Cause Analysis:<ul><li>Users encountered an error dialog on service pages</li><li>Root cause: JSON unmarshal error due to a change in column type from UNSIGNED to DOUBLE</li></ul></li><li>Temporary Fix: Deployed a hotfix to handle JSON parsing errors</li><li>Permanent Fix: Reverted JSON column type back to UNSIGNED, resolving compatibility issues</li></ul> |
| Result    | - Increased query performance by 20%                                                                                                          |
| Skill     | Incident Response / Migration                                                                                                               |

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