# Database Checklist

- Use transactions for multi-step writes — ensures consistency.
- Enforce constraints at DB level — prevents invalid data.
- Add indexes for frequent queries — improves performance.
- Avoid N+1 queries — reduces load.
- Use migrations with rollback — enables safe changes.
- Separate read and write concerns — improves scalability.
