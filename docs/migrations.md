# Migration Conventions

## Rules
1. Never modify existing migrations
2. One migration per structural change
3. Always include down() method
4. Large table changes: batched
5. Index changes: separate migration
