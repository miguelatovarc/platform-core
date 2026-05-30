# Webhooks

## Outgoing
- Events: order.created, payment.completed
- Retry: 3 attempts exponential backoff
- Signature: HMAC-SHA256
- Timeout: 30s
