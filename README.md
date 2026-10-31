# Webhook and API Services

Small API endpoints built in n8n that return clean JSON.

## Files

- `workflows/student_info_finder__webhook___http_request.json` — importable n8n workflow (3 nodes)

## How it works

- A webhook endpoint receives a request (e.g. `/student?id=1`)
- An HTTP Request node fetches the matching record from an API
- The workflow responds with clean JSON

## Setup

1. In n8n, go to Workflows → Import from File and import the JSON above.
2. Replace every `YOUR_...` placeholder with your own webhook ID.
3. No credentials are included in this repo.

> Sanitized for public sharing: webhook IDs were replaced with placeholders. The workflow logic is unchanged.

More of my work: https://hafizwork.lovable.app
