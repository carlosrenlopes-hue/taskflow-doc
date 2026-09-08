# TaskFlow API Documentation

Public-facing Mintlify documentation for the TaskFlow API technical writing test.

## Documentation architecture

- **Get started**: introduction, authentication, and a task-oriented quickstart
- **Guides**: projects, tasks, and error handling
- **API Reference**: generated from the official OpenAPI specification

The API reference is intentionally generated from OpenAPI rather than maintained as duplicate hand-written endpoint pages. This keeps endpoint details aligned with the specification while the MDX guides focus on explanation and user workflows.

## OpenAPI source

The API reference uses the challenge repository's published OpenAPI document:

`https://raw.githubusercontent.com/writechoiceorg/Technical-Writing-Test-TaskFlow-API/main/openapi.yaml`

## Live API

`https://test-writechoice.onrender.com`

The hosted API may take up to 60 seconds to respond to the first request after a period of inactivity.

## Local preview

Install the current Mintlify CLI and run:

```bash
npm i -g mintlify
mint dev
```

Validate the project before committing:

```bash
mint validate
mint broken-links
```

## Security

Use `YOUR_API_KEY` in documentation examples. Never commit the challenge API key or another real credential to the repository.

For local testing, prefer an environment variable or another secret-management mechanism.
