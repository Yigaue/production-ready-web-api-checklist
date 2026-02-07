# Security Checklist

## HTTP & Browser Security
- Set `X-Frame-Options: DENY` — prevents clickjacking.
- Set `Content-Security-Policy` — limits script and asset injection.
- Set `X-Content-Type-Options: nosniff` — prevents MIME sniffing.
- Set `Referrer-Policy` — controls referrer data leakage.
- Enforce `Strict-Transport-Security` — forces HTTPS.

## Authentication
- Hash passwords using `bcrypt` or `argon2` — prevents credential exposure.
- Enforce token expiration — limits damage from token leaks.
- Rotate tokens on sensitive actions — reduces session hijacking.
- Invalidate tokens on logout — prevents reuse.

## Authorization
- Enforce permissions server-side — prevents UI bypass.
- Validate ownership of resources — prevents horizontal privilege escalation.
- Use deny-by-default access rules — minimizes exposure.

## Input & Data Protection
- Validate all inputs — prevents malformed data.
- Sanitize user-provided content — prevents injection attacks.
- Limit request body size — prevents abuse.
- Mask sensitive fields in logs — prevents leaks.

## Abuse Prevention
- Implement rate limiting — prevents brute-force attacks.
- Throttle authentication endpoints — protects credentials.
- Add retry limits — prevents automation abuse.
