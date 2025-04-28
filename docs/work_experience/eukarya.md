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
      <td><ul><li>Develop features</li></ul></td>
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
      <td>Summary</td>
      <td><strong>EU1</strong>. Developed a processor that compiles user scripts into WebAssembly files and executes them efficiently on a WASM runtime</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Custom Functionality</strong>: Users wanted to use their scripts (Python, Go, Rust, etc.) to create custom functions in the workflow engine</li><li><strong>Extensibility</strong>: There was a need to extend the engine for custom script execution</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Extend the workflow engine to support user-defined scripts via WebAssembly execution</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li><strong>Develop the extension</strong>:
          <ul>
            <li><strong>Compiler</strong>: Compile custom scripts into .wasm</li>
            <li><strong>Runtime</strong>: Execute scripts on a WebAssembly runtime</li>
          </ul>
        </li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>Execution Control</strong>: If the execution environment was too flexible, unintended executions could occur, posing security risks</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>Used the WebAssembly specification to pass variables within an appropriate scope</td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Enhanced system extensibility, allowing users to customize workflows efficiently</td>
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
      <td><strong>EU2</strong>. Developed a real-time logging system for the workflow engine, leveraging storage and cache efficiently</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Real-Time Monitoring Need</strong>: Users needed to monitor the execution status of the workflow engine in real time</li><li><strong>Lack of Logging Mechanism</strong>: The system lacked an effective mechanism for logging and retrieving workflow status</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td>Develop a real-time logging system that allows users to check workflow execution status from the UI</td>
    </tr>
    <tr>
      <td>Action</td>
      <td>
        <ul>
          <li>Develop the feature</li>
          <li><strong>Workflow Engine</strong>: Added a publisher to publish logs to Pub/Sub</li>
          <li><strong>Subscriber</strong>: Created a subscriber to subscribe logs from Pub/Sub and write to a datastore</li>
          <li><strong>API</strong>: Added a resolver to read logs from the datastore</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>High-Performance Requirement</strong>: Users needed to monitor the logs output by the workflow engine in real time</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>
        <ul>
          <li>Utilized optimized datastore</li>
          <li><strong>Cache</strong>: Redis for fast log retrieval</li>
          <li><strong>Permanent Storage</strong>: GCS for long-term log storage</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Result</td>
      <td>Provided real-time visibility of worker execution status, enhancing monitoring efficiency</td>
    </tr>
    <tr>
      <td>Skill</td>
      <td>Performance Optimization</td>
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