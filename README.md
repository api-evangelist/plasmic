# Plasmic (plasmic)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/plasmic/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/plasmic/refs/heads/main/apis.yml)

## Tags

- Visual Builder
- Headless CMS
- React
- Next.js
- Gatsby
- Low-Code
- Frontend

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Plasmic Studio

Browser-based visual builder where designers and developers compose pages, components, and design systems. Outputs are consumed downstream by the Loader, Codegen, and CMS APIs.

- **Human URL:** [https://studio.plasmic.app/](https://studio.plasmic.app/)
- **Base URL:** `https://studio.plasmic.app/`

#### Tags

- Studio
- Visual Editor

#### Properties

- [Website](https://studio.plasmic.app/)
- [Postman Collection](collections/plasmic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plasmic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plasmic Loader (Headless API)

Runtime fetching API used by React, Next.js, and Gatsby integrations to pull Studio-published pages and components into a host app. Supports server-side rendering, incremental static regeneration, and on-demand revalidation. Available via @plasmicapp/loader-react, @plasmicapp/loader-nextjs, and @plasmicapp/loader-gatsby.

- **Human URL:** [https://docs.plasmic.app/learn/loader/](https://docs.plasmic.app/learn/loader/)
- **Base URL:** `https://codegen.plasmic.app`

#### Tags

- Headless
- Loader
- SSR

#### Properties

- [Documentation](https://docs.plasmic.app/learn/loader/)
- [Postman Collection](collections/plasmic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plasmic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plasmic Codegen API

Generates React source code from a Plasmic project, synced into the host repository via the Plasmic CLI. Produces editable presentational components alongside skeleton wrappers for app code.

- **Human URL:** [https://docs.plasmic.app/learn/codegen-guide/](https://docs.plasmic.app/learn/codegen-guide/)
- **Base URL:** `https://codegen.plasmic.app`

#### Tags

- Codegen
- React

#### Properties

- [Documentation](https://docs.plasmic.app/learn/codegen-guide/)
- [Postman Collection](collections/plasmic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plasmic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plasmic CMS API

Headless content API for structured data managed inside Plasmic. Supports reading and writing rows in models defined in Studio, used to power data bindings inside Plasmic pages or external apps.

- **Human URL:** [https://docs.plasmic.app/learn/plasmic-cms/](https://docs.plasmic.app/learn/plasmic-cms/)
- **Base URL:** `https://data.plasmic.app/api/v1/cms`

#### Tags

- CMS
- Headless Content

#### Properties

- [Documentation](https://docs.plasmic.app/learn/plasmic-cms/)
- [Postman Collection](collections/plasmic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plasmic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plasmic CLI

Command-line tool (plasmicapp/cli) for authenticating against Plasmic and syncing generated code into a repository. Commands include `plasmic auth`, `plasmic sync`, and `plasmic watch`.

- **Human URL:** [https://www.npmjs.com/package/@plasmicapp/cli](https://www.npmjs.com/package/@plasmicapp/cli)
- **Base URL:** `https://github.com/plasmicapp/plasmic`

#### Tags

- CLI
- Tooling

#### Properties

- [Repository](https://github.com/plasmicapp/plasmic)
- [Postman Collection](collections/plasmic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plasmic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plasmic React Integration

React loader and components for embedding Plasmic-built pages inside React apps.

- **Human URL:** [https://docs.plasmic.app/learn/react-quickstart/](https://docs.plasmic.app/learn/react-quickstart/)
- **Base URL:** `https://www.npmjs.com/package/@plasmicapp/loader-react`

#### Tags

- React
- Integration

#### Properties

- [Documentation](https://docs.plasmic.app/learn/react-quickstart/)
- [Postman Collection](collections/plasmic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plasmic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plasmic Next.js Integration

Next.js loader supporting both pages and app router. Used to render Plasmic-managed pages with SSR/SSG/ISR.

- **Human URL:** [https://docs.plasmic.app/learn/nextjs-quickstart/](https://docs.plasmic.app/learn/nextjs-quickstart/)
- **Base URL:** `https://www.npmjs.com/package/@plasmicapp/loader-nextjs`

#### Tags

- Next.js
- Integration

#### Properties

- [Documentation](https://docs.plasmic.app/learn/nextjs-quickstart/)
- [Postman Collection](collections/plasmic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plasmic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plasmic Gatsby Integration

Gatsby plugin loader for embedding Plasmic-built pages inside Gatsby sites.

- **Human URL:** [https://docs.plasmic.app/learn/gatsby-quickstart/](https://docs.plasmic.app/learn/gatsby-quickstart/)
- **Base URL:** `https://www.npmjs.com/package/@plasmicapp/loader-gatsby`

#### Tags

- Gatsby
- Integration

#### Properties

- [Documentation](https://docs.plasmic.app/learn/gatsby-quickstart/)
- [Postman Collection](collections/plasmic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plasmic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plasmic MCP Server

Model Context Protocol server exposing Plasmic project context to AI agents and IDE assistants.

- **Human URL:** [https://docs.plasmic.app/](https://docs.plasmic.app/)
- **Base URL:** `https://github.com/plasmicapp/plasmic`

#### Tags

- MCP
- AI

#### Properties

- [Repository](https://github.com/plasmicapp/plasmic)
- [Postman Collection](collections/plasmic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plasmic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.plasmic.app/)
- [Documentation](https://docs.plasmic.app/)
- [Git Hub](https://github.com/plasmicapp/plasmic)
- [Forum](https://forum.plasmic.app/)
- [Slack](https://plasmic.app/slack)
- [LinkedIn](https://www.linkedin.com/company/plasmicapp)
- [Twitter](https://twitter.com/plasmicapp)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
