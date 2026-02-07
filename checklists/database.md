# Database Checklist

- Use transactions for multi-step writes to ensure consistency.
- Enforce constraints at DB level to prevent invalid data.
- Add indexes for frequent queries to improve performance.
- Avoid N+1 queries to reduce load.
- Use migrations with rollback to enable safe changes.
- Separate read and write concerns to improve scalability.
