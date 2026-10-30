# Lancaster University

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

Lancaster University is a collegiate public research university in Lancaster, United Kingdom, a member of the N8 Research Partnership and, at the time of writing, not a Russell Group member. It operates no central developer portal, no API gateway, no API key programme and no published API programme, and this profile records that plainly. What it does operate, on hosts it owns, is a small but genuine set of machine-readable surfaces: the Lancaster EPrints institutional repository answers a complete, unauthenticated OAI-PMH 2.0 interface at eprints.lancs.ac.uk with seven metadata formats including RIOXX and uketd_dc, and Lancaster runs its own Shibboleth Identity Provider at idp.lancs.ac.uk, self-publishing SAML 2.0 metadata and registered with the UK Access Federation since 2014 and exported to eduGAIN. Both are institution-operated and both are recorded here as such. Two further surfaces look like Lancaster's and are not: the research directory at research.lancaster-university.uk CNAMEs to lancaster.elsevierpure.com and the OneSearch discovery layer CNAMEs to lancaster.primo.exlibrisgroup.com, so Elsevier Pure and Ex Libris Primo VE wrote those contracts, not Lancaster — they are recorded as tenant relationships and their specifications are deliberately not saved under this slug. Lancaster's most substantial public engineering output is not an API at all: the github.com/lancaster-university organisation is where the BBC micro:bit runtime (microbit-dal) and its successor CODAL were written, and github.com/lulibrary holds the University Library's own open-source Alma, Pure and research-data tooling.

**Areas:** University · Higher Education · Education · United Kingdom · N8 Research Partnership · Research Data · Institutional Repository · Identity Federation · Library · Open Source

## Lancaster University on APIs.io

Everything profiled for Lancaster University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lancaster/](https://apis.io/providers/lancaster/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Lancaster EPrints OAI-PMH 2.0 Interface](https://apis.io/apis/lancaster/lancaster-oai2-api/) — The one unambiguous, institution-operated public API Lancaster runs. A single HTTP endpoint that dispatches on the OAI-PMH `verb` parameter and returns…
- [Lancaster Research Directory (Elsevier Pure) — tenant](https://apis.io/apis/lancaster/pure-research-directory/) — Lancaster's research information system and public research directory. The data — outputs, people, projects, impact — is Lancaster's; the platform and the…
- [Lancaster Library Discovery and Services (Ex Libris Alma / Primo VE) — tenant](https://apis.io/apis/lancaster/library-discovery/) — Lancaster University Library runs on the Ex Libris platform: Primo VE for discovery (OneSearch, view identifier 44LAN_INST:LUL_VU1) and Alma for the library…
- [Lancaster Library Alma Webhook Handler (open source)](https://apis.io/apis/lancaster/alma-webhook-handler/) — An AWS serverless application written and maintained by Lancaster University Library that listens for Ex Libris Alma webhook events and forwards them to…
- [Lancaster University Idp API](https://apis.io/apis/lancaster/lancaster-idp-api/) — The Idp API from Lancaster University — 1 operation(s) for idp.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Lancaster Agentic Access](https://apis.io/agentic-access/lancaster/lancaster-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Lancaster EPrints OAI Identify](https://apis.io/schemas/lancaster/lancaster-identify/)
- [Lancaster EPrints OAI Record](https://apis.io/schemas/lancaster/lancaster-record/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Lancaster Record Structure](https://apis.io/json-structure/lancaster/lancaster-record-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Lancaster Context](https://apis.io/jsonld/lancaster/lancaster-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Lancaster EPrints OAI-PMH Vocabulary](https://apis.io/vocabularies/lancaster/lancaster-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Lancaster Getrecord Example](https://apis.io/examples/lancaster/lancaster-getrecord-example/)
- [Lancaster Identify Example](https://apis.io/examples/lancaster/lancaster-identify-example/)

#### Collections (1)

Postman and Open Collection request collections.

- [Lancaster EPrints OAI-PMH 2.0 Interface Oai2 API](https://apis.io/collections/lancaster/open-lancaster-oai2-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Lancaster University — jsonschema rules](https://apis.io/rules/lancaster/lancaster-jsonschema-spectral-rules/)
- [Lancaster University API Rules](https://apis.io/rules/lancaster/lancaster-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Lancaster Authentication](https://apis.io/security/lancaster/lancaster-authentication/)
- [Lancaster Domain Security](https://apis.io/security/lancaster/lancaster-domain-security/)
- [Lancaster Vulnerability Disclosure](https://apis.io/security/lancaster/lancaster-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Lancaster Plans Pricing](https://apis.io/plans/lancaster/lancaster-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Lancaster Rate Limits](https://apis.io/rate-limits/lancaster/lancaster-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Lancaster Finops](https://apis.io/finops/lancaster/lancaster-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.lancaster.ac.uk/)
- [Documentation](https://eprints.lancs.ac.uk/cgi/oai2?verb=Identify)
- [API reference](https://eprints.lancs.ac.uk/cgi/oai2?verb=ListMetadataFormats)
- [Support](https://www.lancaster.ac.uk/iss/)
- [Blog](https://www.lancaster.ac.uk/news/)
- [Terms of service](https://www.lancaster.ac.uk/terms/)
- [Privacy policy](https://www.lancaster.ac.uk/privacy/)
- [GitHub](https://github.com/lancaster-university)

## API Evangelist rating

**Kin Score 35.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 52.9 |
| Contract governance | 13.6 |
| Operational transparency | 7.9 |
| Developer ergonomics | 35.7 |
| Access clarity | 26.3 |

**Agent readiness 20.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lancaster/](https://apis.io/providers/lancaster/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Lancaster University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lancaster/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
