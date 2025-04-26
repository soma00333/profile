---
layout: default
title: Eukarya
parent: Work Experience
nav_order: 2
---

# Eukarya Inc.

## Company

| Key         | Value                                                                                                                                                           |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Company     | Eukarya Inc.                                                                                                                                                    |
| Employee    | 50+                                                                                                                                                             |
| Founded     | 2017                                                                                                                                                            |
| Web Site    | https://eukarya.io/                                                                                                                                             |
| Description | Eukarya develops Re:Earth (an open-source WebGIS platform), which has been adopted as the base system for a project led by the Japanese Ministry of Land |
| Location    | Tokyo, Japan                                                                                                                                                    |

## Team

| Key       | Value                                                                                                                                                                  |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Title     | Software Engineer (Backend)                                                                                                                                            |
| Mission   | Develop a workflow engine and microservices of Re:Earth Flow (an open-source ETL tool for GIS data), which has been adopted as the base system for a project led by the Japanese Ministry of Land |
| Task      | <ul><li>Feature Development</li></ul>                                                                                                                                                   |
| Term      | October 1, 2024 - current                                                                                                                                             |
| Team Size | 10                                                                                                                                                                     |
| Type      | Freelance                                                                                                                                                              |

## Projects

| Key       | Value                                                                                              |
| --------- | -------------------------------------------------------------------------------------------------- |
| Key       | EU1                                                                                                |
| Summary   | Developed a processor that compiles user scripts into WebAssembly files and executes them on a WASM runtime |
| Problem   | Users needed custom script execution (Python, Go, Rust) in the workflow engine                     |
| Mission   | Extend the engine to support user scripts via WebAssembly execution                              |
| Action    | Developed extension: Compiler (scripts to .wasm), Runtime (execute .wasm)                        |
| Challenge | Execution Control: Potential security risks with overly flexible execution environment           |
| Overcome  | Used WebAssembly specification to pass variables within an appropriate scope                     |
| Result    | Enhanced system extensibility, allowing users to customize workflows efficiently                 |
| Skill     | Feature Development                                                                                |

| Key       | Value                                                                                              |
| --------- | -------------------------------------------------------------------------------------------------- |
| Key       | EU2                                                                                                |
| Summary   | Developed a real-time logging system for a workflow engine, leveraging storage and cache efficiently |
| Problem   | Real-Time Monitoring Need, Lack of effective logging mechanism                                       |
| Mission   | Develop a real-time logging system for UI monitoring                                               |
| Action    | Developed feature: Publisher (Engine->Pub/Sub), Subscriber (Pub/Sub->Datastore), API (Read logs)   |
| Challenge | High-Performance Requirement for real-time monitoring                                              |
| Overcome  | Utilized optimized datastore (Redis cache, GCS permanent storage)                                  |
| Result    | Provided real-time visibility of worker execution status, enhancing monitoring efficiency        |
| Skill     | Performance Optimization                                                                           |

## Technology

| Value        | Tag            |
| ------------ | -------------- |
| Go           | Backend        |
| GraphQL      | Backend        |
| MongoDB      | Backend        |
| Redis        | Backend        |
| Rust         | Backend        |
| WebAssembly  | Backend        |
| Google Cloud | Infrastructure |
| Terraform    | Infrastructure | 