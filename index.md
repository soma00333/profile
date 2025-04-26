---
layout: default
---

* TOC
{:toc}

# Soma Utsumi

# About

### Summary

- Role: Software engineer with 7+ years of experience in site reliability and backend development
- Experience: Designed and developed distributed systems and enterprise applications, ensuring high performance and scalability
- Skill: Go, Python, Java, Kubernetes

### About Me

Hello and welcome! I'm Soma, a Software Engineer passionate about building reliable and scalable systems that empower businesses worldwide. I work as a Software Engineer at Cybereason, a US-based cybersecurity company operating across 40+ countries. My role focuses on ensuring the reliability of a distributed system handling 80M+ events per second and managing 12,000+ servers. Beyond my full-time role, I actively contribute to open-source projects, including initiatives like Kubernetes, etcd, Raft, and ETL tool. I'm also enrolled in the Master of Science in Computer Science program at the University of Colorado Boulder, studying online from Japan.

### Early Career

I earned my Bachelor of Engineering from the University of Tokyo, where I developed statistical models in Python to improve medical decision-making, culminating in a published paper. During this time, I interned at several startups in Tokyo, where I began honing my backend development skills. My professional journey started as a Data Analyst at Gunosy, one of Japan's most prominent media app companies, with 40M+ users. Here, I worked on large-scale data analysis to optimize ads. After that, I co-founded Industry Technology, a Tokyo-based company providing enterprise applications for real estate companies. As the CTO, I led the development team, built backend systems from the ground up, and introduced SRE practices to ensure the reliability and scalability of our platforms. I've also contributed as a Software Engineer for several AI/LLM-focused startups, designing and improving backend systems and infrastructure as part of side projects.

### Vision

I firmly believe that reliability is a product's core feature, and my mission is to advance the reliability of distributed systems at scale. With a focus on modern cloud-native technologies, I'm continuously growing and expanding my expertise in reliability. I'm passionate about learning and embracing new challenges along the way.

# Experience

### Work

| Company                 | Title                                                  | Start           | End                 | Type      |
| ----------------------- | ------------------------------------------------------ | --------------- | ------------------- | --------- |
| [Cybereason Inc.](cybereason.md)         | Site Reliability Engineer / Software Engineer          | October 1, 2024 |                     | Permanent |
| [Eukarya Inc.](eukarya.md)            | Software Engineer (Backend)                          | October 1, 2024 |                     | Freelance |
| [LayerX Inc.](layerx.md)             | Site Reliability Engineer                              | April 1, 2024   | September 30, 2024  | Freelance |
| [enechain Corporation](enechain.md)    | Site Reliability Engineer / Software Engineer (Platform) | November 1, 2023| October 31, 2024    | Freelance |
| [Industry Technology Inc.](industry_technology.md)| CTO / Software Engineer (Backend)                      | April 1, 2019   | September 30, 2024  | Permanent |
| [Algomatic Inc.](algomatic.md)          | Software Engineer (Platform)                         | August 1, 2023  | April 30, 2024      | Freelance |
| [Gunosy Inc.](gunosy.md)             | Data Engineer                                          | April 1, 2018   | June 30, 2019       | Permanent |
| [ZUU Co., Ltd.](zuu.md)           | Software Engineer (Backend)                          | January 1, 2018 | March 31, 2018      | Intern    |

### Project

## Cybereason

- CR1. Designed and developed custom metrics and improved observability across 3k servers, which enhanced troubleshooting efficiency and reduced MTTR by 50% for enterprise customers
- CR2. Analyzed thread dumps and heap dumps to troubleshoot a server with 2k concurrent threads, which successfully resolved critical availability issues, enhancing system reliability for the enterprise customer with 100k employees

## Eukarya

- EU1. Developed a processor that compiles user scripts into WebAssembly files and executes them efficiently on a WASM runtime, which enhanced system extensibility, allowing users to customize workflows efficiently
- EU2. Developed a real-time logging system for the workflow engine, leveraging storage and cache efficiently, which provided real-time visibility of worker execution status, enhancing monitoring efficiency

## LayerX

- LX1. Developed an event-driven notification system within a closed network, which enabled secure and scalable workflow notifications while ensuring compliance with high-security standards

## enechain

- EN1. Developed a generator tool for manifests and Terraform configurations for new microservices, which streamlined the deployment process, achieving a 90% reduction in the initial deployment time for new microservices
- EN2. Developed a system for local development by deploying Telepresence to the Kubernetes cluster, which accelerated local development, achieving a 15% improvement in microservice development speed

## Industry Technology

- IT1. Designed SLI/SLO and developed custom metrics and tracing to enhance system reliability, which strengthened customer trust, securing a major enterprise contract
- IT2. Developed a group chat service and notification system enabling the exchange of photos, videos, and texts, which improved user engagement and productivity by 25% with a seamless chat and notification experience
- IT3. Tuned indexes and optimized queries to improve database performance, which reduced slow query occurrences by 70%, stabilizing peak-hour performance
- IT4. Migrated from a modular monolith to a microservices architecture to improve scalability, distributed traffic to core features across microservices, reducing the write load on the database
- IT5. Migrated from MySQL 5.7 to MySQL 8.0 to ensure reliability and maintainability, which increased query performance by 20%

## Algomatic

- AL1. Developed a serverless training pipeline for fine-tuning LLMs, which enabled fine-tuning of LLMs efficiently, optimizing compute resource utilization

## Gunosy

- GU1. Analyzed data from millions of users and designed A/B testing strategies to improve user retention, which improved new user experience, increasing 7-day user retention by 10%

### Education

| Institute                       | Degree                             | Detail                                                                                                                            | Start           | End              |
| ------------------------------- | ---------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | --------------- | ---------------- |
| University of Colorado Boulder  | Master of Science in Computer Science | - Coursework: Foundations of Data Structures and Algorithms, Machine Learning                                                     | January 1, 2025 |                  |
| The University of Tokyo         | Bachelor of Engineering            | - Designed a preoperative evaluation system for elderly patients by developing statistical models with Python, which improved medical decision-making | April 1, 2014   | March 31, 2018   |
| EF International Language Campus| English courses in Los Angeles     | - Studied English in LA, US                                                                                                     | July 1, 2014    | September 30, 2014|

### OSS

| Repository                                                 | Role        | Detail                                                                                                                                                                                                                                                        | 
| ---------------------------------------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | Committer   | - Developed a processor that compiles user scripts into WebAssembly files and executes them efficiently on a WASM runtime, which enhanced system extensibility, allowing users to customize workflows efficiently<br>- Developed a real-time logging system for the workflow engine, leveraging storage and cache efficiently, which provided real-time visibility of worker execution status, enhancing monitoring efficiency |
| [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | Contributor | - Implementing https://github.com/kubernetes/enhancements/tree/master/keps/sig-instrumentation/1602-structured-logging and https://github.com/kubernetes/enhancements/tree/master/keps/sig-instrumentation/3077-contextual-logging for multiple packages, which increase system reliability and debugging efficiency |
| [etcd-io/raft](https://github.com/etcd-io/raft)             | Contributor | - Refining the snapshot management logic by removing inefficiencies and streamlining related state transitions, which enhance clarity, maintainability, and robustness                                                                              |
| [etcd-io/etcd-operator](https://github.com/etcd-io/etcd-operator) | Contributor | - Added a workflow to guarantee that the import items are properly grouped and ordered, which improved code consistency and maintainability<br>- Enhanced the reconciliation logic to ensure that the number of replicas in the StatefulSet matches the number of etcd members in the cluster, which improved cluster consistency |
| [kubernetes/test-infra](https://github.com/kubernetes/test-infra) | Contributor | - Added post-submit workflows that run test and test-e2e, ensuring that CI runs even after merging to main in etcd-io/etcd-operator, which enhanced its stability                                                                             |
| [envoyproxy/ai-gateway](https://github.com/envoyproxy/ai-gateway) | Contributor | - Added a workflow to check the issue title and provide feedback, which improved the overall consistency of the project                                                                                                                       |

# Skill

| Name          | Year | Experience                                                                           |
| ------------- | ---- | ------------------------------------------------------------------------------------ |
| AWS           | 7+   | Algomatic, Cybereason, Gunosy, Industry Technology, LayerX, enechain                   |
| Go            | 7+   | Eukarya, Industry Technology, ZUU, enechain, etcd-io/raft, kubernetes/kubernetes, reearth/reearth-flow |
| Datadog       | 4-6  | Gunosy, Industry Technology, enechain                                                |
| Google Cloud  | 4-6  | Cybereason, Eukarya, Industry Technology, ZUU, enechain                              |
| gRPC          | 4-6  | Cybereason, Industry Technology, enechain                                                |
| Kubernetes    | 4-6  | Cybereason, Gunosy, ZUU, enechain, kubernetes/kubernetes                             |
| MySQL         | 4-6  | Gunosy, Industry Technology                                                          |
| PostgreSQL    | 4-6  | Algomatic, Cybereason, Industry Technology, LayerX, ZUU, enechain                      |
| Prometheus    | 4-6  | Cybereason, Industry Technology, enechain                                                |
| Python        | 4-6  | Algomatic, Cybereason, Gunosy, LayerX, The University of Tokyo, University of Colorado Boulder |
| Redis         | 4-6  | Cybereason, Eukarya, Industry Technology, LayerX, enechain                           |
| Terraform     | 4-6  | Algomatic, Cybereason, Industry Technology, LayerX, enechain                           |
| AI/LLM        | 1-3  | Algomatic, Industry Technology, LayerX                                               |
| Apache Kafka  | 1-3  | Cybereason                                                                           |
| Azure         | 1-3  | Algomatic, LayerX                                                                    |
| Elasticsearch | 1-3  | Cybereason, Gunosy, Industry Technology                                              |
| ELK           | 1-3  | Cybereason                                                                           |
| Grafana       | 1-3  | Cybereason                                                                           |
| GraphQL       | 1-3  | Algomatic, Cybereason, Eukarya, LayerX, enechain                                     |
| Java          | 1-3  | Cybereason, The University of Tokyo, University of Colorado Boulder                |
| MongoDB       | 1-3  | Algomatic, Cybereason, Eukarya                                                       |
| Oracle Cloud  | 1-3  | Cybereason                                                                           |
| Rust          | 1-3  | Cybereason, Eukarya, reearth/reearth-flow                                            |

# Basic Info

| Key         | Value                    |
| ----------- | ------------------------ |
| Name        | Soma Utsumi              |
| Handle name | soma00333                |
| Mail        | soma03432303@gmail.com   |
| Location    | Tokyo, Japan             |
| Gender      | Male                     |
| Race        | Japanese                 |

# Contact

| Key      | Value                                  |
| -------- | -------------------------------------- |
| GitHub   | https://github.com/soma00333           |
| LinkedIn | https://www.linkedin.com/in/soma00333/ |

# Language

| Key      | Value                           |
| -------- | ------------------------------- |
| Japanese | Native or bilingual proficiency |
| English  | Professional working proficiency|

# Certification

| Name                                                                                                                               | Issuer                       | Date               |
| ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------- | ------------------ |
| [Link](https://www.credly.com/badges/0d97e296-a55d-4011-b14a-3e07c4748f07)                                                          | Google                       | June 1, 2024       |
| [Link](https://www.credly.com/badges/d05509b3-46c5-4c65-884a-715286ede739)                                                          | Google                       | June 1, 2024       |
| [Link](https://courses.edx.org/certificates/94617e9c52fc4156a46f02c80c20e865?_gl=1*igdpb1*_gcl_au*MTE0MjMyNzI2My4xNzE5NzMwMzIz*_ga*NzE4NjE4NTQ4LjE3MTk3MzAzMjA.*_ga_D3KS4KMDT0*MTcxOTczMzc0Mi4yLjEuMTcxOTczMzc5NS43LjAuMA) | Georgia Institute of Technology | August 1, 2022     |
| [Link](https://courses.edx.org/certificates/92856839862b49cb8f7a7787518a758e?_gl=1*igdpb1*_gcl_au*MTE0MjMyNzI2My4xNzE5NzMwMzIz*_ga*NzE4NjE4NTQ4LjE3MTk3MzAzMjA.*_ga_D3KS4KMDT0*MTcxOTczMzc0Mi4yLjEuMTcxOTczMzc5NS43LjAuMA) | Georgia Institute of Technology | August 1, 2023     |
| [Link](https://courses.edx.org/certificates/552428f8f51e4e179d462e2b1d95102b?_gl=1*igdpb1*_gcl_au*MTE0MjMyNzI2My4xNzE5NzMwMzIz*_ga*NzE4NjE4NTQ4LjE3MTk3MzAzMjA.*_ga_D3KS4KMDT0*MTcxOTczMzc0Mi4yLjEuMTcxOTczMzc5NS43LjAuMA) | Georgia Institute of Technology | February 1, 2023   |
| [Link](https://courses.edx.org/certificates/d213c16d0d63407595cd7e61224eba3d?_gl=1*1y4v41k*_gcl_au*MTE0MjMyNzI2My4xNzE5NzMwMzIz*_ga*NzE4NjE4NTQ4LjE3MTk3MzAzMjA.*_ga_D3KS4KMDT0*MTcxOTczMzc0Mi4yLjEuMTcxOTczMzc5NS43LjAuMA) | Georgia Institute of Technology | June 1, 2023       |
| [Link](https://www.credly.com/badges/394fc1a7-d193-4c0e-b202-0e9b150bc8a9)                                                          | HashiCorp                    | July 1, 2024       |
| [Link](https://www.credly.com/badges/0cbd42dd-3d10-486e-b935-145dffbd670b)                                                          | Datadog                      | July 1, 2024       |
| [Link](https://www.credly.com/badges/759a6dc9-5917-46bf-b291-1e3c8e254914)                                                          | The Linux Foundation         | September 1, 2024  |
| [Link](https://www.credly.com/badges/3a8f1346-b5fa-40bd-8d17-460cbdfa6b25)                                                          | The Linux Foundation         | September 1, 2024  |
| [Link](https://tier1app.com/training/academy/2024_12_1ka3pg.pdf)                                                                   | yCrash                       | December 1, 2024   |
| [Link](https://coursera.org/share/11f8f5fb4545998fa63652a5c90e0da5)                                                                 | Packt                        | December 1, 2024   |
| [Link](https://www.udemy.com/certificate/UC-18e6ca80-d033-474e-8b69-65ef3eea9abb/)                                                  | Top Developer Academy LLC    | December 1, 2024   |

# Course

| Name                                                    | Category   | Organization                    | Date            |
| ------------------------------------------------------- | ---------- | ------------------------------- | --------------- |
| Advanced Data Structures, RSA and Quantum Algorithms    | CSCA 5454  | University of Colorado Boulder  | January 1, 2025 |
| Approximation Algorithms and Linear Programming         | CSCA 5424  | University of Colorado Boulder  | January 1, 2025 |
| Dynamic Programming, Greedy Algorithms                | CSCA 5414  | University of Colorado Boulder  | January 1, 2025 |
| Introduction to Machine Learning - Supervised Learning  | CSCA 5622  | University of Colorado Boulder  | March 1, 2025   |
| Unsupervised Algorithms in Machine Learning             | CSCA 5632  | University of Colorado Boulder  | March 1, 2025   |
| Introduction to Deep Learning                           | CSCA 5642  | University of Colorado Boulder  | March 1, 2025   |
| Modeling of Autonomous Systems                           | CSCA 5834  | University of Colorado Boulder  | May 1, 2025   |

# Behavioral Question

[Behavioral Questions](behavioral_questions.md)

# Leadership Principles

[Leadership Principles](leadership_principles.md)

# Activity

| Name                                                                          | Category     | At                                            | Date               |
| ----------------------------------------------------------------------------- | ------------ | --------------------------------------------- | ------------------ |
| [Link](https://github.com/reearth/reearth-flow/pull/1167)                     | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | April 19, 2025     |
| [Link](https://github.com/reearth/reearth-flow/pull/1156)                     | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | April 12, 2025     |
| [Link](https://github.com/reearth/reearth-flow/pull/1132)                     | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | March 27, 2025     |
| [Link](https://github.com/reearth/reearth-flow/pull/1100)                     | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | March 22, 2025     |
| [Link](https://github.com/reearth/reearth-flow/pull/1097)                     | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | March 20, 2025     |
| [Link](https://github.com/reearth/reearth-flow/pull/1045)                     | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | March 15, 2025     |
| [Link](https://github.com/reearth/reearth-flow/pull/976)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | March 5, 2025      |
| [Link](https://github.com/reearth/reearth-flow/pull/943)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | February 28, 2025  |
| [Link](https://github.com/reearth/reearth-flow/pull/901)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | February 24, 2025  |
| [Link](https://github.com/reearth/reearth-flow/pull/888)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | February 20, 2025  |
| [Link](https://github.com/envoyproxy/ai-gateway/pull/273)                     | Pull Request | [envoyproxy/ai-gateway](https://github.com/envoyproxy/ai-gateway) | February 2, 2025   |
| [Link](https://github.com/kubernetes/test-infra/pull/34233)                   | Pull Request | [kubernetes/test-infra](https://github.com/kubernetes/test-infra) | January 29, 2025   |
| [Link](https://github.com/etcd-io/etcd-operator/pull/53)                      | Pull Request | [etcd-io/etcd-operator](https://github.com/etcd-io/etcd-operator) | January 25, 2025   |
| [Link](https://github.com/reearth/reearth-flow/pull/780)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | January 18, 2025   |
| [Link](https://github.com/etcd-io/etcd-operator/pull/40)                      | Pull Request | [etcd-io/etcd-operator](https://github.com/etcd-io/etcd-operator) | January 15, 2025   |
| [Link](https://github.com/etcd-io/etcd-operator/pull/35)                      | Pull Request | [etcd-io/etcd-operator](https://github.com/etcd-io/etcd-operator) | January 14, 2025   |
| [Link](https://github.com/etcd-io/etcd-operator/pull/24)                      | Pull Request | [etcd-io/etcd-operator](https://github.com/etcd-io/etcd-operator) | January 13, 2025   |
| [Link](https://github.com/reearth/reearth-flow/pull/735)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | January 12, 2025   |
| [Link](https://github.com/reearth/reearth-flow/pull/681)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | December 7, 2024   |
| [Link](https://github.com/etcd-io/raft/pull/243)                              | Pull Request | [etcd-io/raft](https://github.com/etcd-io/raft)         | November 27, 2024  |
| [Link](https://github.com/reearth/reearth-flow/pull/636)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | November 22, 2024  |
| [Link](https://github.com/etcd-io/raft/pull/239)                              | Pull Request | [etcd-io/raft](https://github.com/etcd-io/raft)         | November 18, 2024  |
| [Link](https://github.com/etcd-io/raft/pull/237)                              | Pull Request | [etcd-io/raft](https://github.com/etcd-io/raft)         | November 17, 2024  |
| [Link](https://github.com/reearth/reearth-flow/pull/594)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | October 27, 2024   |
| [Link](https://github.com/reearth/reearth-flow/pull/583)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | October 19, 2024   |
| [Link](https://github.com/reearth/reearth-flow/pull/568)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | October 14, 2024   |
| [Link](https://github.com/kubernetes/kubernetes/pull/128027)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | October 13, 2024   |
| [Link](https://github.com/kubernetes/kubernetes/pull/128024)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | October 12, 2024   |
| [Link](https://github.com/reearth/reearth-flow/pull/566)                      | Pull Request | [reearth/reearth-flow](https://github.com/reearth/reearth-flow) | October 12, 2024   |
| [Link](https://github.com/kubernetes/kubernetes/pull/127887)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | October 6, 2024    |
| [Link](https://github.com/kubernetes/kubernetes/pull/127885)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | October 6, 2024    |
| [Link](https://github.com/kubernetes/kubernetes/pull/127875)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | October 5, 2024    |
| [Link](https://github.com/kubernetes/kubernetes/pull/127873)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | October 5, 2024    |
| [Link](https://github.com/kubernetes/kubernetes/pull/127856)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | October 4, 2024    |
| [Link](https://github.com/kubernetes/kubernetes/pull/127741)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | September 30, 2024 |
| [Link](https://github.com/kubernetes/kubernetes/pull/127727)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | September 29, 2024 |
| [Link](https://github.com/kubernetes/kubernetes/pull/127722)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | September 28, 2024 |
| [Link](https://github.com/kubernetes/kubernetes/pull/127708)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | September 27, 2024 |
| [Link](https://github.com/kubernetes/kubernetes/pull/127658)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | September 26, 2024 |
| [Link](https://techblog.enechain.com/entry/sre-join)                          | Blog         | [enechain TechBlog](https://techblog.enechain.com/) | August 6, 2024     |
| [Link](https://github.com/kubernetes/kubernetes/pull/125193)                  | Pull Request | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | June 2, 2024       |
| [Link](https://techblog.enechain.com/entry/networkpolicy)                     | Blog         | [enechain TechBlog](https://techblog.enechain.com/) | May 28, 2024       |
| [Link](https://speakerdeck.com/soma00333/introduction-to-gke-x-llm)           | Speaker      | [k8s-novice-jp](https://k8s-novice-jp.connpass.com/) | April 9, 2024      |
| [Link](https://sre-magazine.net/articles/1/soma00333/)                        | Publication  | [SRE Magazine](https://sre-magazine.net/)       | April 1, 2024      |
| [Link](https://techblog.enechain.com/entry/pod-security-admission)            | Blog         | [enechain TechBlog](https://techblog.enechain.com/) | March 1, 2024      | 