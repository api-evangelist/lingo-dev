# Lingo.dev (lingo-dev)

Lingo.dev (formerly Replexica) is an AI localization platform for software teams. Its hosted Localization Engine exposes a Bearer/X-API-Key REST API and SDK for translating text, objects, chat messages, HTML, and string arrays while preserving structure, brand voice, and glossaries. Open-source tooling - the CLI and the build-time React Compiler - sits on top of the same engine.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lingo-dev/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lingo-dev/refs/heads/main/apis.yml)

## Tags

- AI
- Localization
- Translation
- i18n
- Developer Tools

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Lingo.dev Engine API (Localize)

The hosted Localization Engine REST API. Synchronous operations (localize, recognize, estimate) translate or analyze key-value content in a single request; the asynchronous jobs API creates a job group with one job per target locale and delivers results via polling, webhook, or WebSocket. Authenticated with an organization-scoped X-API-Key header.

- **Human URL:** [https://lingo.dev/en/docs/api](https://lingo.dev/en/docs/api)
- **Base URL:** `https://api.lingo.dev`

#### Tags

- Localization
- Translation
- Engine
- Async

#### Properties

- [Documentation](https://lingo.dev/en/docs/api)
- [API Reference](https://lingo.dev/en/docs/api/localization)
- [OpenAPI](openapi/lingo-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lingo-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lingo-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lingo.dev SDK

Open-source SDKs (JavaScript/TypeScript via the lingo.dev npm package, plus a PHP SDK) that wrap the Engine API. The LingoDotDevEngine client exposes localizeText, localizeObject, localizeChat, localizeHtml, localizeStringArray, batchLocalizeText, recognizeLocale, estimate, and whoami, calling the same hosted engine.

- **Human URL:** [https://lingo.dev/en/sdk/javascript](https://lingo.dev/en/sdk/javascript)
- **Base URL:** `https://api.lingo.dev`

#### Tags

- SDK
- JavaScript
- PHP
- Open Source

#### Properties

- [Documentation](https://lingo.dev/en/sdk/javascript)
- [SDK](https://www.npmjs.com/package/lingo.dev)
- [OpenAPI](openapi/lingo-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Lingo.dev CLI

Open-source command-line tool that localizes JSON, YAML, Markdown, CSV, and PO files in one command, tracking a lockfile so only new or changed content is processed. Connects to the Lingo.dev engine by default and can bring your own LLM (OpenAI, Anthropic, Google, Mistral, OpenRouter, Ollama).

- **Human URL:** [https://lingo.dev/en/cli](https://lingo.dev/en/cli)
- **Base URL:** `https://api.lingo.dev`

#### Tags

- CLI
- Open Source
- i18n
- CI/CD

#### Properties

- [Documentation](https://lingo.dev/en/cli/quick-start)
- [Source Code](https://github.com/lingodotdev/lingo.dev)

### Lingo.dev Compiler

Open-source build-time React localization. The Compiler detects translatable strings and generates localized variants at build time without i18n wrappers, translation keys, or t() function calls, using the same localization engine behind the scenes.

- **Human URL:** [https://lingo.dev/en/compiler](https://lingo.dev/en/compiler)
- **Base URL:** `https://api.lingo.dev`

#### Tags

- Compiler
- React
- Open Source
- Build Time

#### Properties

- [Documentation](https://lingo.dev/en/compiler)
- [Source Code](https://github.com/lingodotdev/lingo.dev)

## Common Properties

- [GitHub Organization](https://github.com/lingodotdev)
- [LinkedIn](https://www.linkedin.com/company/lingodotdev)
- [Website](https://lingo.dev)
- [Documentation](https://lingo.dev/en/docs)
- [Plans](plans/lingo-dev-plans-pricing.yml)
- [Rate Limits](rate-limits/lingo-dev-rate-limits.yml)
- [Fin Ops](finops/lingo-dev-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
