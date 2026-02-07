# Background Jobs Checklist

- Retry jobs with limits — avoids infinite loops.
- Make jobs idempotent — prevents duplicates.
- Log job failures — enables debugging.
- Use dead-letter queues — isolates poison jobs.
