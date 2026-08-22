# Coder (coder)

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

Coder is a self-hosted and cloud platform for remote cloud development environments (CDEs) and AI coding agents, where workspaces are defined using Terraform and connected via a secure WireGuard tunnel. It serves enterprises in automotive, finance, government, and technology with governed, reproducible workspaces and IDE integrations for VS Code, JetBrains, Cursor, and others. Coder exposes a comprehensive REST API (v2) with a published Swagger 2.0 specification covering workspaces, templates, users, organizations, agents, and enterprise management.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/coder/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/coder/refs/heads/main/apis.yml)

Naftiko Run: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=coder-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=coder-api-evangelist&utm_content=repo)

## Tags

- Developer Tools
- Remote Development
- Cloud Development Environments
- AI Agents
- Infrastructure
- Workspaces

## APIs

- **Coder REST API** — Core v2 REST API for all platform operations. [Documentation](https://coder.com/docs/reference/api) | [OpenAPI Spec](https://raw.githubusercontent.com/coder/coder/main/coderd/apidoc/swagger.json)
- **Coder Workspaces API** — Workspace lifecycle, ACLs, schedules, and real-time monitoring. [Documentation](https://coder.com/docs/reference/api/workspaces)
- **Coder Templates API** — Template and template version management across organizations. [Documentation](https://coder.com/docs/reference/api/templates)
- **Coder Users API** — User management, authentication, tokens, roles, and OAuth. [Documentation](https://coder.com/docs/reference/api/users)
- **Coder Workspace Agents API** — Agent lifecycle, PTY access, container management, and networking. [Documentation](https://coder.com/docs/reference/api/agents)
- **Coder Enterprise API** — Licensing, RBAC, groups, IdP sync, and AI governance. [Documentation](https://coder.com/docs/reference/api/enterprise)

## Plans / Rate Limits / FinOps

- [Plans & Pricing](plans/coder-plans-pricing.yml)
- [Rate Limits](rate-limits/coder-rate-limits.yml)
- [FinOps](finops/coder-finops.yml)

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://coder.com |
| Documentation | https://coder.com/docs |
| GitHub Organization | https://github.com/coder |
| LinkedIn | https://www.linkedin.com/company/coderhq |
| X / Twitter | https://x.com/coderhq |
| Blog | https://coder.com/blog |
| Changelog | https://coder.com/changelog |
| Pricing | https://coder.com/pricing |
| CLI | https://coder.com/docs/reference/cli |

## Maintainers

- Kin Lane / kin@apievangelist.com
