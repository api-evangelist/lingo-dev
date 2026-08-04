# Lingo.dev (lingo-dev)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
