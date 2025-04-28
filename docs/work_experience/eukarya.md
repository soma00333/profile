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
| Web Site    | [https://eukarya.io/](https://eukarya.io/)                                                                                                              |
| Description | Eukarya develops Re:Earth (an open-source WebGIS platform), which has been adopted as the base system for a project led by the Japanese Ministry of Land |
| Location    | Tokyo, Japan                                                                                                                                                    |

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
      <td>Software Engineer (Backend)</td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Develop a workflow engine and microservices of Re:Earth Flow (an open-source ETL tool for GIS data), which has been adopted as the base system for a project led by the Japanese Ministry of Land</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li>Feature Development</li></ul></td>
    </tr>
    <tr>
      <td>Term</td>
      <td>October 1, 2024 - current</td>
    </tr>
    <tr>
      <td>Team Size</td>
      <td>10</td>
    </tr>
    <tr>
      <td>Type</td>
      <td>Freelance</td>
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
      <td>EU1</td>
    </tr>
    <tr>
      <td>Summary</td>
      <td>Developed a processor that compiles user scripts into WebAssembly files and executes them on a WASM runtime</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li>Users needed custom script execution (Python, Go, Rust) in the workflow engine</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Extend the engine to support user scripts via WebAssembly execution</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li>Developed extension: Compiler (scripts to .wasm), Runtime (execute .wasm)</li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td>Execution Control: Potential security risks with overly flexible execution environment</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>Used WebAssembly specification to pass variables within an appropriate scope</td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Enhanced system extensibility, allowing users to customize workflows efficiently</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td><ul><li>Feature Development</li></ul></td>
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
      <td>EU2</td>
    </tr>
    <tr>
      <td>Summary</td>
      <td>Developed a real-time logging system for a workflow engine, leveraging storage and cache efficiently</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li>Real-Time Monitoring Need, Lack of effective logging mechanism</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Develop a real-time logging system for UI monitoring</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li>Developed feature: Publisher (Engine->Pub/Sub), Subscriber (Pub/Sub->Datastore), API (Read logs)</li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td>High-Performance Requirement for real-time monitoring</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>Utilized optimized datastore (Redis cache, GCS permanent storage)</td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Provided real-time visibility of worker execution status, enhancing monitoring efficiency</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td><ul><li>Performance Optimization</li></ul></td>
    </tr>
  </tbody>
</table>

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