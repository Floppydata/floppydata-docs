# FloppyData Client API Docs

Documentation source for FloppyData Client API (`/v1`).

## Local development

Install CLI:

```bash
npm i -g mint
```

Run docs preview from this directory:

```bash
mint dev
```

## Validate

```bash
mint validate
mint openapi-check api-reference/openapi.json
```

## Structure

- `docs.json`: navigation and site config
- `api-reference/openapi.json`: local OpenAPI source snapshot
- `api-reference/endpoint/*.mdx`: endpoint pages wired to OpenAPI operations
- `guides/*.mdx`: practical usage guides based on API reference
