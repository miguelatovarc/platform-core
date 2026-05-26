# Deployment

## Staging
- Auto-deploy on merge to develop
- URL: staging.platform-core.internal

## Production
- Manual trigger via GitHub Actions
- Blue/green deployment
- Rollback: `kubectl rollout undo`
