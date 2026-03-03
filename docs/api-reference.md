# API Reference

Base URL: `https://api.flowforge.io/api/v1`

## Authentication
All endpoints require a Bearer token in the Authorization header.

## Workflows
- `GET /workflows` - List workflows
- `POST /workflows` - Create workflow
- `GET /workflows/:id` - Get workflow
- `POST /workflows/:id/start` - Start workflow instance

## Tasks
- `GET /tasks/:id` - Get task
- `POST /tasks/:id/complete` - Complete task
