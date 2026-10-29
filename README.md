# Coder

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

Coder is a self-hosted and cloud platform for remote cloud development environments (CDEs) and AI coding agents, where workspaces are defined using Terraform and connected via a secure WireGuard tunnel. It serves individual developers and enterprises in industries such as automotive, finance, government, and technology, providing governed, reproducible workspaces with IDE integrations for VS Code, JetBrains, Cursor, and others. Coder exposes a comprehensive REST API (v2) covering workspaces, templates, users, organizations, agents, and enterprise management, with a published Swagger 2.0 specification. SDKs include a built-in Go client (codersdk) and a Terraform provider; a CLI with 40+ subcommands is also available for full programmatic control.

**Areas:** Developer Tools · Remote Development · Cloud Development Environments · AI Agents · Infrastructure · Workspace

## Coder on APIs.io

Everything profiled for Coder is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/coder/](https://apis.io/providers/coder/)** — or go straight to one of the APIs or properties below.

### APIs (32)

- [Coder Workspaces API](https://apis.io/apis/coder/workspaces-api/) — Endpoints for creating, retrieving, updating, and managing workspace lifecycle including autostart schedules, time-to-live settings, dormancy controls,…
- [Coder Templates API](https://apis.io/apis/coder/templates-api/) — Endpoints for creating, listing, updating, and archiving workspace templates and template versions within organizations; supports examples, daily active…
- [Coder Users API](https://apis.io/apis/coder/users-api/) — Endpoints for user management including creation, authentication, SSH key management, API token/key lifecycle, role assignment, organization membership, and…
- [Coder Workspace Agents API](https://apis.io/apis/coder/agents-api/) — Endpoints for workspace agent lifecycle, authentication (AWS/Azure/GCP instance identity), PTY terminal access, container management, listening-port…
- [Coder Enterprise API](https://apis.io/apis/coder/enterprise-api/) — Enterprise-only endpoints covering OAuth2 provider management, licensing and entitlements, group and RBAC management, AI spending budgets,…
- [Coder Agents API](https://apis.io/apis/coder/coder-agents-api/) — The Agents API from Coder — 28 operation(s) for agents.
- [Coder AI Bridge API](https://apis.io/apis/coder/coder-ai-bridge-api/) — The AI Bridge API from Coder — 4 operation(s) for ai bridge.
- [Coder AI Providers API](https://apis.io/apis/coder/coder-ai-providers-api/) — The AI Providers API from Coder — 2 operation(s) for ai providers.
- [Coder Applications API](https://apis.io/apis/coder/coder-applications-api/) — The Applications API from Coder — 2 operation(s) for applications.
- [Coder Audit API](https://apis.io/apis/coder/coder-audit-api/) — The Audit API from Coder — 2 operation(s) for audit.
- [Coder Authorization API](https://apis.io/apis/coder/coder-authorization-api/) — The Authorization API from Coder — 7 operation(s) for authorization.
- [Coder Builds API](https://apis.io/apis/coder/coder-builds-api/) — The Builds API from Coder — 9 operation(s) for builds.
- [Coder Chats API](https://apis.io/apis/coder/coder-chats-api/) — The Chats API from Coder — 20 operation(s) for chats.
- [Coder Debug API](https://apis.io/apis/coder/coder-debug-api/) — The Debug API from Coder — 14 operation(s) for debug.
- [Coder Enterprise API](https://apis.io/apis/coder/coder-enterprise-api/) — The Enterprise API from Coder — 67 operation(s) for enterprise.
- [Coder Files API](https://apis.io/apis/coder/coder-files-api/) — The Files API from Coder — 2 operation(s) for files.
- [Coder General API](https://apis.io/apis/coder/coder-general-api/) — The General API from Coder — 10 operation(s) for general.
- [Coder Git API](https://apis.io/apis/coder/coder-git-api/) — The Git API from Coder — 3 operation(s) for git.
- [Coder InitScript API](https://apis.io/apis/coder/coder-initscript-api/) — The InitScript API from Coder — 1 operation(s) for initscript.
- [Coder Insights API](https://apis.io/apis/coder/coder-insights-api/) — The Insights API from Coder — 5 operation(s) for insights.
- [Coder Members API](https://apis.io/apis/coder/coder-members-api/) — The Members API from Coder — 7 operation(s) for members.
- [Coder Notifications API](https://apis.io/apis/coder/coder-notifications-api/) — The Notifications API from Coder — 13 operation(s) for notifications.
- [Coder Organizations API](https://apis.io/apis/coder/coder-organizations-api/) — The Organizations API from Coder — 4 operation(s) for organizations.
- [Coder PortSharing API](https://apis.io/apis/coder/coder-portsharing-api/) — The PortSharing API from Coder — 1 operation(s) for portsharing.
- [Coder Prebuilds API](https://apis.io/apis/coder/coder-prebuilds-api/) — The Prebuilds API from Coder — 1 operation(s) for prebuilds.
- [Coder Provisioning API](https://apis.io/apis/coder/coder-provisioning-api/) — The Provisioning API from Coder — 1 operation(s) for provisioning.
- [Coder Secrets API](https://apis.io/apis/coder/coder-secrets-api/) — The Secrets API from Coder — 2 operation(s) for secrets.
- [Coder Tasks API](https://apis.io/apis/coder/coder-tasks-api/) — The Tasks API from Coder — 9 operation(s) for tasks.
- [Coder Templates API](https://apis.io/apis/coder/coder-templates-api/) — The Templates API from Coder — 33 operation(s) for templates.
- [Coder Users API](https://apis.io/apis/coder/coder-users-api/) — The Users API from Coder — 28 operation(s) for users.
- [Coder WorkspaceProxies API](https://apis.io/apis/coder/coder-workspaceproxies-api/) — The WorkspaceProxies API from Coder — 1 operation(s) for workspaceproxies.
- [Coder Workspaces API](https://apis.io/apis/coder/coder-workspaces-api/) — The Workspaces API from Coder — 20 operation(s) for workspaces.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Coder Agentic Access](https://apis.io/agentic-access/coder/coder-agentic-access/)

#### JSON Schema (8)

The data models the API reads and writes.

- [AuditLog](https://apis.io/schemas/coder/coder-auditlog/)
- [Organization](https://apis.io/schemas/coder/coder-organization/)
- [Template](https://apis.io/schemas/coder/coder-template/)
- [TemplateVersion](https://apis.io/schemas/coder/coder-templateversion/)
- [User](https://apis.io/schemas/coder/coder-user/)
- [Workspace](https://apis.io/schemas/coder/coder-workspace/)
- [WorkspaceAgent](https://apis.io/schemas/coder/coder-workspaceagent/)
- [WorkspaceBuild](https://apis.io/schemas/coder/coder-workspacebuild/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Coder Context](https://apis.io/jsonld/coder/coder-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Coder API Vocabulary](https://apis.io/vocabularies/coder/coder-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Coder Create Workspace Example](https://apis.io/examples/coder/coder-create-workspace-example/)
- [Coder Get Template Example](https://apis.io/examples/coder/coder-get-template-example/)
- [Coder Get User Example](https://apis.io/examples/coder/coder-get-user-example/)
- [Coder Get Workspace Example](https://apis.io/examples/coder/coder-get-workspace-example/)
- [Coder List Workspaces Example](https://apis.io/examples/coder/coder-list-workspaces-example/)

#### Collections (27)

Postman and Open Collection request collections.

- [Coder Agents API](https://apis.io/collections/coder/open-coder-agents-api/)
- [Coder Agents AI Bridge API](https://apis.io/collections/coder/open-coder-ai-bridge-api/)
- [Coder Agents AI Providers API](https://apis.io/collections/coder/open-coder-ai-providers-api/)
- [Coder Agents Applications API](https://apis.io/collections/coder/open-coder-applications-api/)
- [Coder Agents Audit API](https://apis.io/collections/coder/open-coder-audit-api/)
- [Coder Agents Authorization API](https://apis.io/collections/coder/open-coder-authorization-api/)
- [Coder Agents Builds API](https://apis.io/collections/coder/open-coder-builds-api/)
- [Coder Agents Chats API](https://apis.io/collections/coder/open-coder-chats-api/)
- [Coder Agents Debug API](https://apis.io/collections/coder/open-coder-debug-api/)
- [Coder Agents Enterprise API](https://apis.io/collections/coder/open-coder-enterprise-api/)
- [Coder Agents Files API](https://apis.io/collections/coder/open-coder-files-api/)
- [Coder Agents General API](https://apis.io/collections/coder/open-coder-general-api/)
- [Coder Agents Git API](https://apis.io/collections/coder/open-coder-git-api/)
- [Coder Agents InitScript API](https://apis.io/collections/coder/open-coder-initscript-api/)
- [Coder Agents Insights API](https://apis.io/collections/coder/open-coder-insights-api/)
- [Coder Agents Members API](https://apis.io/collections/coder/open-coder-members-api/)
- [Coder Agents Notifications API](https://apis.io/collections/coder/open-coder-notifications-api/)
- [Coder Agents Organizations API](https://apis.io/collections/coder/open-coder-organizations-api/)
- [Coder Agents PortSharing API](https://apis.io/collections/coder/open-coder-portsharing-api/)
- [Coder Agents Prebuilds API](https://apis.io/collections/coder/open-coder-prebuilds-api/)
- [Coder Agents Provisioning API](https://apis.io/collections/coder/open-coder-provisioning-api/)
- [Coder Agents Secrets API](https://apis.io/collections/coder/open-coder-secrets-api/)
- [Coder Agents Tasks API](https://apis.io/collections/coder/open-coder-tasks-api/)
- [Coder Agents Templates API](https://apis.io/collections/coder/open-coder-templates-api/)
- [Coder Agents Users API](https://apis.io/collections/coder/open-coder-users-api/)
- …and 2 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Coder — jsonschema rules](https://apis.io/rules/coder/coder-jsonschema-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Coder Authentication](https://apis.io/security/coder/coder-authentication/)
- [Coder Domain Security](https://apis.io/security/coder/coder-domain-security/)
- [Coder Trust Center](https://apis.io/security/coder/coder-trust-center/)
- [Coder Vulnerability Disclosure](https://apis.io/security/coder/coder-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Coder Plans Pricing](https://apis.io/plans/coder/coder-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Coder Rate Limits](https://apis.io/rate-limits/coder/coder-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Coder Finops](https://apis.io/finops/coder/coder-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://coder.com)
- [Documentation](https://coder.com/docs)
- [Pricing](https://coder.com/pricing)
- [Changelog](https://coder.com/changelog)
- [Blog](https://coder.com/blog)
- [GitHub](https://github.com/coder)

## API Evangelist rating

**Kin Score 37.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 50.3 |
| Contract governance | 9.8 |
| Operational transparency | 26.3 |
| Developer ergonomics | 31.0 |
| Access clarity | 23.7 |

**Agent readiness 28.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | verified |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
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

**Regulatory alignment 27.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/coder/](https://apis.io/providers/coder/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Coder: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/coder/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
