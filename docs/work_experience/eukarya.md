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
| Description | Eukarya develops Re:Earth (an open-source WebGIS platform), which was adopted as the base system for a project led by the Japanese Ministry of Land |
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
      <td>My mission was to develop a workflow engine and microservices for Re:Earth Flow, an open-source ETL tool for GIS data. This platform was adopted as the base system for a project led by the Japanese Ministry of Land.</td>
    </tr>
    <tr>
      <td>Task</td>
      <td>
        <ul>
          <li>I developed new features for the platform.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Term</td>
      <td>2024-10 - current</td>
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
      <td><strong>Summary</strong></td>
      <td><strong>EU1</strong>. I developed a processor that compiles user scripts into WebAssembly files and runs them efficiently on a WASM runtime.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>Users needed to add their own custom scripts (Python, Go, Rust, etc.) to the workflow engine to extend its functionality.</li>
          <li>The existing engine didn't have a way to easily add and run these user scripts.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to extend the workflow engine to safely run user scripts by compiling them to WebAssembly (WASM).</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I built the compilation system:
            <ul>
              <li>I designed a process that turned user scripts into .wasm files</li>
              <li>I supported multiple programming languages (Python, Go, Rust)</li>
            </ul>
          </li>
          <li>I integrated the runtime:
            <ul>
              <li>I added a WebAssembly runtime to the engine</li>
              <li>I created secure execution environment for .wasm scripts</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>This feature greatly improved the workflow engine's flexibility, letting users customize their workflows with their favorite scripting languages.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was giving users enough flexibility for custom scripts while strictly controlling the execution environment to prevent unwanted operations and security risks.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>I designed a clear interface for the Wasm guest modules. This interface strictly controlled how data was passed and how host functions could be called, making sure user scripts only worked within a safe and proper scope.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned how to balance flexibility and security when designing systems that can be extended, especially when running user code.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
      <td>Feature Development / Security / Quick Learn</td>
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
      <td><strong>EU2</strong>. I developed a real-time logging system for the workflow engine, using storage and cache efficiently.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>Users needed immediate visibility into how their workflows were running.</li>
          <li>The existing system didn't have a good way to log and get workflow status information in real-time.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My goal was to develop a real-time logging system that let users monitor workflow status directly from the user interface.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I built the logging infrastructure:
            <ul>
              <li>I changed the workflow engine to publish log events to a Pub/Sub topic</li>
              <li>I created a subscriber service to get logs from Pub/Sub</li>
              <li>I set up efficient data storage for log data</li>
            </ul>
          </li>
          <li>I developed the UI integration:
            <ul>
              <li>I added an API endpoint to serve logs to the UI</li>
              <li>I enabled real-time log display in the user interface</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Result</strong></td>
      <td>The system successfully gave users real-time visibility into worker execution status, greatly improving monitoring efficiency and troubleshooting capabilities.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>The main challenge was making sure the logging system could handle many logs and provide real-time updates to users without hurting overall system performance.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>
        <ul>
          <li>I used Redis as a caching layer to make retrieval fast.</li>
          <li>I used Google Cloud Storage (GCS) for cost-effective, long-term storage of historical logs.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned how important it is to use a tiered storage strategy (cache for hot data, object storage for cold data) to balance performance and cost in logging systems.</td>
    </tr>
    <tr>
      <td><strong>Skill</strong></td>
      <td>Performance Optimization / Technically Difficult</td>
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