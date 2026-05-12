# Database Schema

## Conventions
- Table names: plural snake_case
- Primary key: always `id` (bigint unsigned)
- Foreign keys: `{table}_id`
- Timestamps: `created_at`, `updated_at`
- Soft deletes: `deleted_at`
