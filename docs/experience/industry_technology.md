---
title: Industry Technology Inc.
parent: Experience
nav_order: 5
layout: default
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

| Key       | Value                                                                                                                                   |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Title     | CTO / Software Engineer (Backend)                                                                                                       |
| Mission   | As a CTO, lead the development team of 8 members for enterprise applications, personally writing 100k+ lines backend codes from scratch |
| Task      | <ul><li>Feature Development</li><li>Introduce SRE practices</li></ul>                                                                                     |
| Term      | April 1, 2019 - September 30, 2024                                                                                                     |
| Team Size | 8                                                                                                                                       |
| Type      | Permanent                                                                                                                               |

## Projects

| Key       | Value                                                                                 |
| --------- | ------------------------------------------------------------------------------------- |
| Key       | IT1                                                                                   |
| Summary   | Designed SLI/SLO and developed custom metrics and tracing to enhance system reliability |
| Problem   | Business Opportunity required higher operational level, Existing operation had gaps     |
| Mission   | Improve system reliability to meet expected operational level                           |
| Action    | Designed SLI/SLO using CUJ, Implemented custom metrics and tracing                    |
| Challenge | SLO Tuning: Adjusting threshold properly to avoid stopping releases                     |
| Overcome  | Load Testing & Optimization: Checked SLI during spikes, set appropriate objectives      |
| Result    | Strengthened customer trust, securing a major enterprise contract                       |
| Skill     | SLI/SLO / Observability / Monitoring / Load Test                                        |

| Key       | Value                                                                                            |
| --------- | ------------------------------------------------------------------------------------------------ |
| Key       | IT2                                                                                              |
| Summary   | Developed a group chat service and notification system enabling exchange of photos, videos, texts |
| Problem   | User Requirement for chat/notification, Lack of existing features                                  |
| Mission   | Develop group chat service and notification system                                               |
| Action    | Developed chat (S3+Signed URL, CDN), notification (event-driven architecture)                    |
| Challenge | Tight Schedule prevented WebSocket server development                                              |
| Overcome  | Polling-Based Approach: Extended existing API using polling                                      |
| Result    | Improved user engagement and productivity by 25%                                                 |
| Skill     | Feature Development                                                                              |

| Key       | Value                                                                                              |
| --------- | -------------------------------------------------------------------------------------------------- |
| Key       | IT3                                                                                                |
| Summary   | Tuned indexes and optimized queries to improve database performance                                  |
| Problem   | Frequent Slow Queries impacting UX, High CPU/Memory utilization during peak hours                |
| Mission   | Diagnose performance bottlenecks, Optimize query execution                                         |
| Action    | Index Optimization, Query Refactoring (eliminated unnecessary joins, optimized index usage)      |
| Challenge | Root Cause Analysis: Identifying source of slow queries due to complex execution patterns            |
| Overcome  | Query Tracing for anomaly detection, EXPLAIN Analysis for identifying full table scans               |
| Result    | Reduced slow query occurrences by 70%, stabilizing peak-hour performance                           |
| Skill     | Performance Optimization                                                                           |

| Key       | Value                                                                                              |
| --------- | -------------------------------------------------------------------------------------------------- |
| Key       | IT4                                                                                                |
| Summary   | Migrated from a modular monolith to a microservices architecture to improve scalability              |
| Problem   | Monolithic Architecture, Increased DB write load due to traffic growth to core features              |
| Mission   | Create independent microservices to handle increasing load                                         |
| Action    | Migrated step-by-step: Created three microservices (Work Diary, Attendance, Main)                  |
| Challenge | Downtime Minimization during migration                                                               |
| Overcome  | BFF-Based Traffic Management: Gradually switched traffic using BFF layer                           |
| Result    | Distributed traffic, reducing database write load                                                  |
| Skill     | Migration                                                                                          |

| Key       | Value                                                                                              |
| --------- | -------------------------------------------------------------------------------------------------- |
| Key       | IT5                                                                                                |
| Summary   | Migrated from MySQL 5.7 to MySQL 8.0 to ensure reliability and maintainability                     |
| Problem   | MySQL 5.7 approaching end of support                                                               |
| Mission   | Seamlessly upgrade to MySQL 8.0 ensuring stability and performance                               |
| Action    | Developed runbook, Implemented Blue-Green deployment                                               |
| Challenge | Incident during migration impacting user experience                                                |
| Overcome  | Investigation (JSON unmarshal error due to column type change), Hotfix, Permanent Fix (revert type) |
| Result    | Increased query performance by 20%                                                                 |
| Skill     | Incident Response / Migration                                                                      |

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