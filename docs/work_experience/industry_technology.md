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
| Description | A proptech company that builds enterprise applications for Japan's largest real estate companies |
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
      <td>As CTO, I led a development team of 8 members. We created enterprise applications. I also wrote backend code from scratch myself.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td>
        <ul>
          <li>I developed new features.</li>
          <li>I introduced and implemented SRE practices in the team.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Term</td>
      <td>2019-04 - 2024-09</td>
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
      <td><strong>Summary</strong></td>
      <td><strong>IT1</strong>. I designed SLIs and SLOs. I developed custom metrics and tracing. These changes greatly improved system reliability.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>We had a chance to introduce our system to one of Japan's largest real estate companies.</li>
          <li>I realized our operations didn't meet the reliability and performance levels this enterprise client needed.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to improve system reliability to meet the strict standards expected by a major enterprise customer.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I designed SLI/SLO:
            <ul>
              <li>I designed SLIs and SLOs based on Critical User Journeys (CUJs)</li>
              <li>I set clear reliability targets that matched business needs</li>
            </ul>
          </li>
          <li>I implemented metrics and distributed tracing:
            <ul>
              <li>I implemented custom metrics to track key performance indicators</li>
              <li>I added distributed tracing to show how requests flow through the system</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>As a result, the improved system reliability built customer trust. This trust directly led to winning a major enterprise contract.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was setting the right SLOs. Breaking an SLO would mean stopping releases. This could slow down development.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>To solve this, I ran thorough load tests to see how SLIs behaved during traffic spikes. I used this data to set realistic SLOs. I adjusted them over time as needed.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that balancing reliability requirements with development velocity requires setting appropriate SLOs based on real-world data.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
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
      <td><strong>Summary</strong></td>
      <td><strong>IT2</strong>. I developed a group chat service and a notification system. Users could exchange photos, videos, and text messages.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>The system didn't have a chat function. We needed it for daily business operations and user collaboration.</td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to develop a complete group chat service and notification system to meet business needs.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I implemented media sharing
            <ul>
              <li>I implemented secure media sharing using S3 with Signed URLs</li>
              <li>I added a Content Delivery Network (CDN) for fast content delivery</li>
            </ul>
          </li>
          <li>I built chat and notification system
            <ul>
              <li>I built an event-driven architecture for efficient notifications</li>
              <li>I developed the group chat functionality to handle photos, videos, and text</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>As a result, the new system provided a smooth chat and notification experience. User engagement and productivity improved by 25%.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was the very tight schedule. We didn't have enough time to build a complex WebSocket-based real-time solution.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>To solve this, I extended the existing API using polling for near real-time updates instead of building a WebSocket server.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that practical solutions often deliver business value faster than technically perfect ones.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
      <td>Feature Development / Tigiht Schedule / Difficult Decision</td>
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
      <td><strong>IT3</strong>. I tuned database indexes and optimized queries, greatly improving database performance.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>A core feature of the application had repeated slow queries, which hurt user experience.</li>
          <li>These slow queries caused high CPU and memory usage on the database, especially during peak times.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>I needed to find the root causes of performance problems and optimize queries for better stability and speed.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I optimized database structure:
            <ul>
              <li>I analyzed query patterns. I added the right indexes to speed up data retrieval</li>
              <li>I implemented query result caching using Redis</li>
            </ul>
          </li>
          <li>I improved query efficiency:
            <ul>
              <li>I rewrote complex queries to eliminate unnecessary table joins</li>
              <li>I optimized WHERE clauses to use indexes effectively</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>As a result, these optimizations reduced slow query occurrences by 70%. System performance became stable, especially during peak hours.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was finding the exact source of slow queries. We had complex data models and complicated query patterns.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>
        To solve this:
        <ul>
          <li>I monitored and analyzed distributed tracing data. I found problems and identified bad query paths.</li>
          <li>I used EXPLAIN statements to analyze query execution plans. I looked for full table scans and poor index usage.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that using multiple diagnostic tools (tracing and EXPLAIN) together is essential to find and fix database performance issues.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
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
      <td><strong>Summary</strong></td>
      <td><strong>IT4</strong>. I led the migration from a modular monolith to microservices to improve system scalability.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>The system was first built as a modular monolith. It started showing scalability limits.</li>
          <li>User traffic to core features grew. The write load on the central database increased a lot. This hurt performance.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to create separate microservices from the main monolithic service to spread the load and improve system scalability.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I planned migration strategy
            <ul>
              <li>I migrated the system to microservices step by step to reduce risk</li>
              <li>I planned the migration to keep the system stable during transition</li>
            </ul>
          </li>
          <li>I developed microservices
            <ul>
              <li>I designed and built three initial microservices for different areas</li>
              <li>I created Work Diary, Attendance Management, and core Main services</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>As a result, the migration successfully spread traffic for core features across separate microservices. This greatly reduced the write load on the main database. System scalability improved.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was doing the migration with little or no downtime to avoid disrupting users.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>To solve this, I added a Backend-for-Frontend (BFF) layer in front of the new microservices. This let us gradually switch traffic from the monolith to each new service. We achieved a smooth and controlled migration.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that a middle layer (BFF) is valuable. It allows gradual migrations without disrupting users.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
      <td>Migration / Microservices</td>
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
      <td><strong>IT5</strong>. I managed the migration from MySQL 5.7 to MySQL 8.0 to keep the system reliable and maintainable long-term.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>The existing MySQL 5.7 database version was reaching end-of-life. We needed to upgrade to a supported version.</li>
          <li>Database migrations at this scale are complex. They can risk data loss or long downtime if not managed carefully.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to smoothly upgrade the database to MySQL 8.0. I needed to keep the system stable, data safe, and performance good.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I planned migration
            <ul>
              <li>I created a detailed, step-by-step migration plan (runbook)</li>
              <li>I made sure the process was predictable and controlled</li>
            </ul>
          </li>
          <li>I strategized deployment
            <ul>
              <li>I used a blue-green deployment strategy for the database</li>
              <li>I ensured smooth transition, minimal downtime, and clear rollback path</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>As a result, we completed the migration to MySQL 8.0. After we stabilized it, overall query performance increased by 20%.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was that unexpected issues came up after migration, affecting user experience on some service pages.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>
        To solve this:
        <ul>
          <li>I quickly found the issue after users reported seeing an error dialog on specific service pages.</li>
          <li>It was a JSON parsing error caused by an accidental data type change in a column.</li>
          <li>I deployed a hotfix to handle the JSON parsing errors smoothly. This restored service availability.</li>
          <li>I then changed the affected JSON column types back to their original UNSIGNED INT definition. This completely fixed the compatibility issues.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that thoroughly testing data type compatibility during database migrations is critical. Even small changes can cause unexpected application errors.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
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
