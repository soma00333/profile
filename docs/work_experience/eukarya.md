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
| Description | Eukarya develops Re:Earth, an open-source WebGIS platform. The Japanese Ministry of Land uses it for their project |
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
      <td>I developed a workflow engine and microservices for Re:Earth Flow, an open-source ETL tool for GIS data. The Japanese Ministry of Land uses this platform for their project.</td>
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
      <td><strong>EU1</strong>. I built a processor that turns user scripts into WebAssembly files and runs them on WASM.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>Users wanted to use their own scripts (Python, Go, Rust) to extend the workflow engine.</li>
          <li>The engine couldn't run user scripts.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>I needed to make the engine run user scripts safely by compiling them to WebAssembly.</td>
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
      <td>As a result, this feature made the engine more flexible. Users could now customize workflows with their favorite languages.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was giving users flexibility while keeping the system secure.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>To solve this, I made a clear interface for Wasm modules. It controlled how data passes and how functions are called. This kept user scripts safe.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that I must balance flexibility and security when running user code.</td>
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
      <td><strong>EU2</strong>. I built a real-time logging system for the workflow engine using efficient storage and cache.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>Users needed to see their workflows running in real-time.</li>
          <li>The system couldn't show workflow status right away.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to build a logging system so users could see workflow status in the UI instantly.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I built the logging infrastructure:
            <ul>
              <li>I made the engine send logs to Pub/Sub</li>
              <li>I created a subscriber to get logs from Pub/Sub</li>
              <li>I set up good storage for log data</li>
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
      <td>As a result, users could now see worker status in real-time. This made monitoring and troubleshooting much better.</td>
    </tr>
    <tr>
      <td><strong>Challenge</strong></td>
      <td>A key challenge was designing a logging system that was fast for real-time viewing and cheap for long-term storage.</td>
    </tr>
    <tr>
      <td><strong>Solution</strong></td>
      <td>
        To solve this:
        <ul>
          <li>I used Redis cache to make it fast.</li>
          <li>I used Google Cloud Storage for cheap long-term storage.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td>I learned that using different storage types - cache for recent data, object storage for old data - balances speed and cost.</td>
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