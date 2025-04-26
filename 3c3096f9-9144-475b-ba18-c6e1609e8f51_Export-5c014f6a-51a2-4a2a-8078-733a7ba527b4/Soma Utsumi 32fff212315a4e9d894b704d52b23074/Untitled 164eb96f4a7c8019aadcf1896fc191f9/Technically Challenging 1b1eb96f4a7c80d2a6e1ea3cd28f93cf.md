# Technically Challenging

Value1: - Summary: EU2. Developed a real-time logging system for the workflow engine, leveraging storage and cache efficiently at Eukarya
- Problem:
  - Real-Time Monitoring Need: Users needed to monitor the execution status of the workflow engine in real time
  - Lack of Logging Mechanism: The system lacked an effective mechanism for logging and retrieving workflow status
- Mission: Develop a real-time logging system that allows users to check workflow execution status from the UI
- Action: Developed the feature utilizing Pub/Sub, Subscriber, and Publisher
- Challenge: High-Performance Requirement: Users needed to monitor the logs output by the workflow engine in real time
- Overcome:
  - Utilized optimized data storage:
    - Cache: Redis for fast log retrieval
    - Permanent Storage: GCS for long-term log storage
- Result: Enabled users to monitor worker status in real-time