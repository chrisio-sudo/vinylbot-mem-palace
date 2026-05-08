# Memory Palace Schema

## Frontmatter Fields
- id: kebab-case memory ID (required)
- title: Human-readable title (required)
- category: feedback-rules|ebay-api-patterns|architecture-decisions|error-logs|sandbox-gotchas|quick-ref (required)
- severity: CRITICAL|HIGH|MEDIUM|LOW (required)
- status: ACTIVE|ARCHIVED|DEPRECATED (required)
- tags: array of 2+ tags (required)
- search_keywords: array of keywords (required)
- created: ISO-8601 timestamp (required)
- last_validated: ISO-8601 timestamp (required)

Each memory is a markdown file with YAML frontmatter + content body.
