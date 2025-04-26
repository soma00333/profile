# Action

Value: - Root Cause Analysis:
  - Fetched and analyzed thread dumps and heap dumps
  - Found that a legacy API blocked HTTP threads, triggering health check failures and causing automatic restarts
- Response: Migrated the legacy API to an efficient v2 API, resolving the issue