# API Design Checklist

- Version APIs (`/api/v1`) — avoids breaking clients.
- Use consistent HTTP status codes — improves predictability.
- Standardize error responses — simplifies client handling.
- Avoid leaking internal errors — prevents information disclosure.
- Validate request schemas — prevents invalid requests.
- Use pagination for collections — avoids large payloads.
- Make write operations idempotent — prevents duplicates.
