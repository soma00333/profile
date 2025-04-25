# Eukarya Inc.

**Type:** Freelance
**Start:** October 1, 2024
**Title:** Software Engineer (Backend)

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

## Project (WebAssembly Runtime)

| Key       | Value                                                                                                                                         |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Summary   | EU1. Developed a processor that compiles user scripts into WebAssembly files and executes them efficiently on a WASM runtime                       |
| Problem   | <ul><li>Custom Functionality: Users wanted to use their scripts (Python, Go, Rust, etc.) to create custom functions in the workflow engine</li><li>Extensibility: There was a need to extend the engine for custom script execution</li></ul> |
| Mission   | - Extend the workflow engine to support user-defined scripts via WebAssembly execution                                                      |
| Action    | <ul><li>Develop the extension:<ul><li>Compiler: Compile custom scripts into .wasm</li><li>Runtime: Execute scripts on a WebAssembly runtime</li></ul></li></ul>                     |
| Challenge | - Execution Control: If the execution environment was too flexible, unintended executions could occur, posing security risks                     |
| Overcome  | - Used the WebAssembly specification to pass variables within an appropriate scope                                                              |
| Result    | - Enhanced system extensibility, allowing users to customize workflows efficiently                                                             |
| Skill     | Feature Development                                                                                                                           |

## Project (Real-time Logging)

| Key       | Value                                                                                                                                                                       |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Summary   | EU2. Developed a real-time logging system for a workflow engine, leveraging storage and cache efficiently                                                                    |
| Problem   | <ul><li>Real-Time Monitoring Need: Users needed to monitor the execution status of the workflow engine in real time</li><li>Lack of Logging Mechanism: The system lacked an effective mechanism for logging and retrieving workflow status</li></ul> |
| Mission   | - Develop a real-time logging system that allows users to check workflow execution status from the UI                                                                       |
| Action    | <ul><li>Develop the feature:<ul><li>Workflow Engine: Added a publisher to publish logs to Pub/Sub</li><li>Subscriber: Created a subscriber to subscribe logs from Pub/Sub and write to a datastore</li><li>API: Added a resolver to read logs from the datastore</li></ul></li></ul> |
| Challenge | - High-Performance Requirement: Users needed to monitor the logs output by the workflow engine in real time                                                                  |
| Overcome  | <ul><li>Utilized optimized datastore:<ul><li>Cache: Redis for fast log retrieval</li><li>Permanent Storage: GCS for long-term log storage</li></ul></li></ul>                                         |
| Result    | - Provided real-time visibility of worker execution status, enhancing monitoring efficiency                                                                                  |
| Skill     | Performance Optimization                                                                                                                                                    |

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