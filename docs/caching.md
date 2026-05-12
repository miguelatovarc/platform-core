# Caching Strategy

## Layers
1. Application cache (Redis, TTL: 1h)
2. Query cache (tagged, TTL: 15min)
3. HTTP cache (Varnish, TTL: 5min)
4. CDN (CloudFront, TTL: 24h)

## Invalidation
- Event-driven cache busting
- Tag-based selective flush
