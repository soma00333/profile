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
| Description | Eukarya develops Re:Earth, an open-source WebGIS platform. It supports Project PLATEAU, a nationwide 3D digital twin project led by the Japanese Ministry of Land.  |
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
      <td>My mission was to develop a workflow engine and microservices for Re:Earth Flow, an open-source ETL tool for GIS data.</td>
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
      <td><strong>EU1</strong>. I developed a processor that compiles user scripts into WebAssembly and executes them on a WASM runtime, which enabled users to customize workflows efficiently.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>Users wanted to use their own scripts (Python, Go, Rust) to extend the workflow engine.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to make the engine run user scripts safely by compiling them to WebAssembly.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I developed the compilation system:
            <ul>
              <li>I designed a processor that turned user scripts into .wasm files</li>
              <li>I supported multiple programming languages (Python, Go, Rust)</li>
            </ul>
          </li>
          <li>I integrated a WASM runtime to the processor</li>
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
      <td><strong>EU2</strong>. I developed a real-time logging system with efficient storage and cache, which enabled users to monitor the workflow status instantly from the UI.</td>
    </tr>
    <tr>
      <td><strong>Situation</strong></td>
      <td>
        <ul>
          <li>Users needed to monitor their workflow status in real-time.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Task</strong></td>
      <td>My mission was to build a logging system so users could check workflow status instantly from the UI.</td>
    </tr>
    <tr>
      <td><strong>Action</strong></td>
      <td>
        <ul>
          <li>I built the logging infrastructure:
            <ul>
              <li>I made the engine publish logs to Pub/Sub</li>
              <li>I created a subscriber to fetch logs from Pub/Sub and store them in a datastore</li>
            </ul>
          </li>
          <li>I developed the API endpoint:
            <ul>
              <li>I created a WebSocket endpoint for real-time log streaming.</li>
              <li>I added a REST API endpoint to fetch historical logs.</li>
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
      <td>Performance Optimization / Difficult Problem / Cache / Storage</td>
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