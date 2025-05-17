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
      <td>My mission was to develop a workflow engine and microservices for Re:Earth Flow, an open-source ETL tool for GIS data. This platform has been adopted as the base system for a project led by the Japanese Ministry of Land.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td><ul><li>I developed new features for the platform.</li></ul></td>
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
      <td><strong>EU1</strong>. I developed a processor that compiles user scripts into WebAssembly files and executes them efficiently on a WASM runtime.</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Need for User-Defined Functions:</strong> Users required the ability to integrate their own custom scripts (Python, Go, Rust, etc.) into the workflow engine to extend its functionality.</li><li><strong>Lack of Extensibility for Custom Scripts:</strong> The existing engine lacked a mechanism to easily incorporate and execute these user-provided scripts.</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><strong>Enable Custom Script Execution via WebAssembly:</strong> My mission was to extend the workflow engine to securely execute user-defined scripts by compiling them to WebAssembly (WASM).</td>
    </tr>
    <tr>
      <td>Action</td>
      <td><ul><li><strong>Developed the WASM Extension:</strong>
          <ul>
            <li><strong>WASM Compilation Process:</strong> I designed and implemented a compilation process that transformed user scripts into .wasm files.</li>
            <li><strong>WASM Runtime Integration:</strong> I integrated a WebAssembly runtime into the engine to execute the compiled .wasm scripts.</li>
          </ul>
        </li></ul></td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>Ensuring Secure Execution Environment:</strong> A key challenge was to provide enough flexibility for users' custom scripts while strictly controlling the execution environment to prevent unintended operations and potential security risks.</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td><strong>Secured Wasm Execution with a Well-Defined API:</strong> I designed a well-defined API for the Wasm guest modules. This API strictly controlled how data (like variables) was passed and how host functions could be called, ensuring user scripts operated only within a secure and appropriate scope.</td>
    </tr>
    <tr>
      <td>Result</td>
      <td><strong>Significantly Enhanced System Extensibility:</strong> This feature greatly enhanced the workflow engine's extensibility, empowering users to efficiently customize their workflows with their preferred scripting languages.</td>
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
      <td><strong>EU2</strong>. I developed a real-time logging system for the workflow engine, leveraging storage and cache efficiently.</td>
    </tr>
    <tr>
      <td>Problem</td>
      <td><ul><li><strong>Demand for Real-Time Workflow Monitoring:</strong> Users required immediate visibility into the execution status of their workflows.</li><li><strong>Absence of Effective Logging System:</strong> The existing system lacked a robust mechanism for real-time logging and retrieval of workflow status information.</li></ul></td>
    </tr>
    <tr>
      <td>Mission</td>
      <td><strong>Implement Real-Time Workflow Logging:</strong> My objective was to develop a real-time logging system enabling users to monitor workflow execution status directly from the user interface.</td>
    </tr>
    <tr>
      <td>Action</td>
      <td>
        <ul>
          <li><strong>Developed the Real-Time Logging Feature:</strong>
            <ul>
              <li><strong>Integrated Pub/Sub for Log Publishing:</strong> I modified the workflow engine to publish log events to a Pub/Sub topic.</li>
              <li><strong>Developed Log Subscription Service:</strong> I created a subscriber service to consume logs from Pub/Sub and persist them to a data store.</li>
              <li><strong>Exposed Logs via API:</strong> I added an API endpoint (resolver) to enable the UI to fetch and display logs from the data store.</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Challenge</td>
      <td><strong>Meeting Real-Time Performance Demands:</strong> The primary challenge was to ensure the logging system could handle a high volume of logs and provide real-time updates to users without impacting overall system performance.</td>
    </tr>
    <tr>
      <td>Overcome</td>
      <td>
        <ul>
          <li><strong>Utilized Optimized Datastore Strategy:</strong>
            <ul>
              <li><strong>Implemented Redis for Log Caching:</strong> I utilized Redis as a caching layer to ensure fast retrieval.</li>
              <li><strong>Utilized GCS for Archival Storage:</strong> Google Cloud Storage (GCS) was used for cost-effective, long-term storage of historical logs.</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Result</td>
      <td><strong>Achieved Real-Time Visibility and Enhanced Monitoring:</strong> The system successfully provided users with real-time visibility into worker execution status, significantly improving monitoring efficiency and troubleshooting capabilities.</td>
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