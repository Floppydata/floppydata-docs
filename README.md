# Floppydata Client API Docs

Documentation source for Floppydata Client API. The main docs target `/v2`; `/v1` is kept as a legacy API reference.

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
- `api-reference/v2/endpoint/*.mdx`: primary v2 endpoint pages wired to OpenAPI operations
- `api-reference/v1/endpoint/*.mdx`: legacy v1 endpoint pages linked from `/legacy-v1`
- `guides/*.mdx`: practical usage guides based on API reference
