# Cybereason Inc.

**Type:** Permanent
**Start:** October 1, 2024
**Title:** Site Reliability Engineer / Software Engineer

## Company

| Key         | Value                                                                                                             |
| ----------- | ----------------------------------------------------------------------------------------------------------------- |
| Company     | Cybereason Inc.                                                                                                   |
| Employee    | 1000+                                                                                                             |
| Founded     | 2012                                                                                                              |
| Web Site    | https://www.cybereason.com/                                                                                       |
| Description | A global cybersecurity company operating in 40+ countries, providing EDR, XDR, and MDR solutions to combat cyberattacks |
| Location    | San Diego, US - Japan Office                                                                                      |

## Team (Software Engineer)

| Key       | Value                                                                                                                             |
| --------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Title     | Software Engineer                                                                                                               |
| Mission   | Develop new features and refactor legacy microservices for a distributed system operating across 12k+ servers and processing 80M+ events/sec |
| Task      | <ul><li>Feature Development</li><li>Refactoring legacy microservices</li></ul>                                                     |
| Term      | March 1, 2025 - current                                                                                                         |
| Team Size | 9                                                                                                                               |
| Type      | Permanent                                                                                                                       |

## Team (Site Reliability Engineer)

| Key       | Value                                                                                                                                                           |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Title     | Site Reliability Engineer                                                                                                                                       |
| Mission   | As a cross-functional global team, develop custom metrics and distributed tracing to enhance the reliability of a distributed system operating across 12k+ servers and processing 80M+ events/sec |
| Task      | <ul><li>Ovservability Development: Develop custom metrics and distributed tracing to improve observability</li><li>Incident Response: Troubleshoot cross-microservices issues to identify the root cause</li></ul> |
| Term      | October 1, 2024 - March 31, 2025                                                                                                                               |
| Team Size | 5                                                                                                                                                               |
| Type      | Permanent                                                                                                                                                       |

## Project (Observability Improvement)

| Key       | Value                                                                                                                                         |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Summary   | CR1. Designed and developed custom metrics and improved observability across 3k servers                                                         |
| Problem   | <ul><li>Complex Troubleshooting: The API server had multiple interconnected components, making troubleshooting difficult</li><li>High MTTR: Existing monitoring lacked sufficient insights, leading to long MTTR</li></ul> |
| Mission   | <ul><li>Improve observability, streamline debugging, and reduce MTTR</li></ul>                                                                |
| Action    | <ul><li>Develop custom metrics:<ul><li>API: Latency and Error Rate</li><li>Elasticsearch: Throughput</li><li>MongoDB: Query Performance</li></ul></li><li>Dashboard: Improved real-time dashboards to provide actionable insights for engineers</li></ul> |
| Challenge | <ul><li>Design: Designing meaningful custom metrics that provide actionable insights</li></ul>                                                   |
| Overcome  | <ul><li>Communication: Fostered cross-functional communication between SRE, DevOps, and Product teams</li></ul>                               |
| Result    | <ul><li>Enhanced troubleshooting efficiency and reduced MTTR by 50% for enterprise customers</li></ul>                                         |
| Skill     | <ul><li>Observability / Monitoring</li></ul>                                                                                                 |

## Project (Incident Response)

| Key       | Value                                                                                                                                                                       |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Summary   | CR2. Analyzed thread dumps and heap dumps to troubleshoot a server with 2k concurrent threads                                                                              |
| Problem   | <ul><li>Crash: A UI server crashed occasionally for an enterprise customer with 100k employees</li><li>Troubleshooting Difficulty: The root cause was unknown, and conventional monitoring tools provided insufficient insights</li></ul> |
| Mission   | <ul><li>Identify the performance bottleneck and ensure system stability</li></ul>                                                                                           |
| Action    | <ul><li>Root Cause Analysis:<ul><li>Fetched and analyzed thread dumps and heap dumps</li><li>Found that a legacy API blocked HTTP threads, triggering health check failures and causing automatic restarts</li></ul></li><li>Response: Migrated the legacy API to an efficient v2 API, resolving the issue</li></ul> |
| Challenge | <ul><li>Fetching Data: Since an automated pipeline restarted the UI server upon failure, manual thread and heap dumps could not be obtained</li></ul>                         |
| Overcome  | <ul><li>Pipeline: Added an automated pipeline to collect thread and heap dumps before restart</li></ul>                                                                     |
| Result    | <ul><li>Successfully resolved critical availability issues, enhancing system reliability for the enterprise customer with 100k employees</li></ul>                          |
| Skill     | <ul><li>Incident Response / Troubleshooting</li></ul>                                                                                                                     |

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