# Configuration Checklist

- Separate configs per environment — prevents accidental misuse.
- Validate required env vars on startup — fails fast.
- Never commit secrets — prevents leaks.
- Provide sane defaults for non-sensitive values — improves DX.
