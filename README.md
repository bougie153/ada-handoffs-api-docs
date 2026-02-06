# Ada Handoffs API Documentation

External-facing documentation for the Ada Handoffs API (v2).

## View the docs

**https://bougie153.github.io/ada-handoffs-api-docs/**

## What's covered

### Endpoints
- **POST** `/v2/conversations/{conversation_id}/messages/` — Send text or file messages
- **GET** `/v2/conversations/{conversation_id}/messages/` — Fetch paginated message history
- **PATCH** `/v2/conversations/{conversation_id}/` — Update conversation metadata
- **POST** `/v2/conversations/{conversation_id}/attachments/` — Upload file attachments
- **POST** `/v2/conversations/{conversation_id}/end-handoff/` — End a handoff

### Webhooks
- `v1.conversation.message` — Fired when a message is sent in a conversation
- `v1.conversation.handoff.ended` — Fired when a handoff ends

## Updating

Edit `index.html` and push to `main`. GitHub Pages will rebuild automatically.
