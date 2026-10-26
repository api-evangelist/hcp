# HashiCorp Cloud Platform (hcp)

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

HashiCorp Cloud Platform (HCP) is a fully managed platform for HashiCorp products including Vault, Consul, Packer, Boundary, Waypoint, and Terraform. HCP provides a unified set of APIs for managing infrastructure, secrets, service networking, and image pipelines across cloud and on-premises environments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hcp/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hcp/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cloud
- Infrastructure
- DevOps
- Secrets Management
- Service Networking

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### HCP Vault Secrets API

The HCP Vault Secrets API enables programmatic management of applications, secrets, and integrations within HashiCorp Cloud Platform Vault Secrets, a multi-tenant secrets management service.

- **Human URL:** [https://developer.hashicorp.com/hcp/api-docs/vault-secrets](https://developer.hashicorp.com/hcp/api-docs/vault-secrets)
- **Base URL:** `https://api.cloud.hashicorp.com`

#### Tags

- Secrets Management
- Vault
- Cloud

#### Properties

- [Documentation](https://developer.hashicorp.com/hcp/api-docs/vault-secrets)
- [OpenAPI](openapi/hcp-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hcp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HCP Packer API

The HCP Packer API provides programmatic access to manage image buckets, channels, and iterations, enabling automated image pipelines and golden image management across cloud providers.

- **Human URL:** [https://developer.hashicorp.com/hcp/api-docs/packer](https://developer.hashicorp.com/hcp/api-docs/packer)
- **Base URL:** `https://api.cloud.hashicorp.com`

#### Tags

- Packer
- Images
- DevOps

#### Properties

- [Documentation](https://developer.hashicorp.com/hcp/api-docs/packer)
- [Postman Collection](collections/hcp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HCP Consul API

The HCP Consul API enables management of HCP Consul clusters, including provisioning, scaling, and federation for service networking and service mesh deployments.

- **Human URL:** [https://developer.hashicorp.com/hcp/api-docs/consul](https://developer.hashicorp.com/hcp/api-docs/consul)
- **Base URL:** `https://api.cloud.hashicorp.com`

#### Tags

- Consul
- Service Mesh
- Service Networking

#### Properties

- [Documentation](https://developer.hashicorp.com/hcp/api-docs/consul)
- [Postman Collection](collections/hcp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HCP Boundary API

The HCP Boundary API provides programmatic access to identity-based secure remote access for managing users, hosts, sessions, and access policies in HashiCorp Cloud Platform Boundary.

- **Human URL:** [https://developer.hashicorp.com/hcp/api-docs/boundary](https://developer.hashicorp.com/hcp/api-docs/boundary)
- **Base URL:** `https://api.cloud.hashicorp.com`

#### Tags

- Boundary
- Remote Access
- Identity

#### Properties

- [Documentation](https://developer.hashicorp.com/hcp/api-docs/boundary)
- [Postman Collection](collections/hcp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HCP Waypoint API

The HCP Waypoint API enables programmatic management of application templates, add-ons, and deployment workflows for delivering golden patterns to developer teams.

- **Human URL:** [https://developer.hashicorp.com/hcp/api-docs/waypoint](https://developer.hashicorp.com/hcp/api-docs/waypoint)
- **Base URL:** `https://api.cloud.hashicorp.com`

#### Tags

- Waypoint
- Application Delivery
- DevOps

#### Properties

- [Documentation](https://developer.hashicorp.com/hcp/api-docs/waypoint)
- [Postman Collection](collections/hcp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hcp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/hashicorp)
- [Website](https://cloud.hashicorp.com)
- [Developer](https://developer.hashicorp.com/hcp)
- [Documentation](https://developer.hashicorp.com/hcp/docs)
- [A P I  Documentation](https://developer.hashicorp.com/hcp/api-docs)
- [Status Page](https://status.hashicorp.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
