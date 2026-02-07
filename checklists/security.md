# Security Checklist

## HTTP Headers
- Add `X-Frame-Options: DENY` — prevents clickjacking via iframe embedding.
- Set `Content-Security-Policy` — restricts allowed script and asset sources.
- Set `X-Content-Type-Options: nosniff` — prevents MIME sniffing attacks.
- Enforce `Strict-Transport-Security` — forces HTTPS connections.

## Authentication
- Hash passwords using `bcrypt` or `argon2` — prevents credential disclosure.
- Set token expiration for JWTs — limits damage from token leaks.
- Rotate tokens on sensitive actions — reduces session hijacking risk.
