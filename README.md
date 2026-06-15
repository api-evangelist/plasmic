# Plasmic (plasmic)

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
