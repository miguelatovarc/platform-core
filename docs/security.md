# Security Checklist

## Headers
- X-Content-Type-Options: nosniff
- X-Frame-Options: DENY
- Strict-Transport-Security
- Content-Security-Policy

## Input
- All input validated
- SQL parameterized
- XSS escaped on output
