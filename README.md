# Plasmic

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Plasmic is a visual builder and headless CMS for front-end development. Designers and developers compose pages and components in Plasmic Studio, then ship them via either the Headless API (Loader) for runtime fetching or the Codegen pipeline for generated React/Next.js/Gatsby source. The platform also exposes a CMS for structured content, a CLI for code synchronization, and a REST API for programmatic access. Open source components live under the plasmicapp GitHub organization.

**Areas:** Visual Builder · Headless CMS · React · Next.js · Gatsby · Low-Code · Frontend

## Plasmic on APIs.io

Everything profiled for Plasmic is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/plasmic/](https://apis.io/providers/plasmic/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Plasmic Studio](https://apis.io/apis/plasmic/studio/) — Browser-based visual builder where designers and developers compose pages, components, and design systems. Outputs are consumed downstream by the Loader,…
- [Plasmic Loader (Headless API)](https://apis.io/apis/plasmic/loader/) — Runtime fetching API used by React, Next.js, and Gatsby integrations to pull Studio-published pages and components into a host app. Supports server-side…
- [Plasmic Codegen API](https://apis.io/apis/plasmic/codegen/) — Generates React source code from a Plasmic project, synced into the host repository via the Plasmic CLI. Produces editable presentational components…
- [Plasmic CMS API](https://apis.io/apis/plasmic/cms/) — Headless content API for structured data managed inside Plasmic. Supports reading and writing rows in models defined in Studio, used to power data bindings…
- [Plasmic CLI](https://apis.io/apis/plasmic/cli/) — Command-line tool (plasmicapp/cli) for authenticating against Plasmic and syncing generated code into a repository. Commands include `plasmic auth`,…
- [Plasmic React Integration](https://apis.io/apis/plasmic/react/) — React loader and components for embedding Plasmic-built pages inside React apps.
- [Plasmic Next.js Integration](https://apis.io/apis/plasmic/nextjs/) — Next.js loader supporting both pages and app router. Used to render Plasmic-managed pages with SSR/SSG/ISR.
- [Plasmic Gatsby Integration](https://apis.io/apis/plasmic/gatsby/) — Gatsby plugin loader for embedding Plasmic-built pages inside Gatsby sites.
- [Plasmic MCP Server](https://apis.io/apis/plasmic/mcp/) — Model Context Protocol server exposing Plasmic project context to AI agents and IDE assistants.
- [Plasmic Items API](https://apis.io/apis/plasmic/plasmic-items-api/) — Query and count items in a CMS model.
- [Plasmic Rows API](https://apis.io/apis/plasmic/plasmic-rows-api/) — Create, update, publish, and delete CMS rows.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Plasmic Agentic Access](https://apis.io/agentic-access/plasmic/plasmic-agentic-access/)

#### Collections (3)

Postman and Open Collection request collections.

- [Plasmic CMS API](https://apis.io/collections/plasmic/open-plasmic/)
- [Plasmic CMS Items API](https://apis.io/collections/plasmic/open-plasmic-items-api/)
- [Plasmic CMS Items Rows API](https://apis.io/collections/plasmic/open-plasmic-rows-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Plasmic Authentication](https://apis.io/security/plasmic/plasmic-authentication/)
- [Plasmic Domain Security](https://apis.io/security/plasmic/plasmic-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Plasmic Plans Pricing](https://apis.io/plans/plasmic/plasmic-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Plasmic Rate Limits](https://apis.io/rate-limits/plasmic/plasmic-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Plasmic Finops](https://apis.io/finops/plasmic/plasmic-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.plasmic.app/)
- [Documentation](https://docs.plasmic.app/)
- [Blog](https://www.plasmic.app/blog/feed.xml)

## API Evangelist rating

**Kin Score 24.8** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 45.3 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 28.6 |
| Access clarity | 5.3 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/plasmic/](https://apis.io/providers/plasmic/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Plasmic: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/plasmic/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
