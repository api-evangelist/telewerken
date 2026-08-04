# Telewerken

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

Telewerken.be is a Belgian information platform dedicated to remote work (telewerken), operated jointly by Vias Institute and the FOD Mobiliteit en Vervoer (Federal Public Service for Mobility and Transport). The platform provides comprehensive resources on Belgian telework legislation, regulations, employer obligations, employee rights, and telework statistics. Belgium's remote work framework is governed by Collective Bargaining Agreement No. 85 (CBA 85) and the Law of 5 March 2017 on feasible and workable work.

**Website:** https://www.telewerken.be/

## Legal Framework

| Law | Scope |
|-----|-------|
| **CAO 85 / CBA 85** | Structural telework (regular, at least 1 day/week) |
| **Law of 5 March 2017** | Occasional/sporadic telework |
| **Right to Disconnect (2022)** | Employers 20+ employees must formalize right to disconnect |

## Key Facts

- Telework is **voluntary** — employers cannot force it, employees have no automatic right to demand it
- Structural teleworkers are entitled to employer-provided equipment and connectivity reimbursement
- Home office allowance: up to EUR 160.99/month (tax-free, as of March 2026)
- Equivalent rights to on-site employees under equivalence principle

## Links

- [Telewerken.be](https://www.telewerken.be/)
- [Statistics](https://www.telewerken.be/in-cijfers/telewerken-in-het-buitenland/)
- [Government Portal - Telework](https://werk.belgie.be/nl/themas/welzijn-op-het-werk/telewerk)
- [Federal Public Service Resource](https://fedweb.belgium.be/nl/verlof_afwezigheid_en_werktijd/werktijd/telewerk)

## Artifacts

| Artifact | Description |
|----------|-------------|
| [apis.yml](apis.yml) | API catalog index |
| [vocabulary/telewerken-vocabulary.yml](vocabulary/telewerken-vocabulary.yml) | Domain vocabulary (Belgian telework terms) |
| [json-ld/telewerken-context.jsonld](json-ld/telewerken-context.jsonld) | JSON-LD context |
| [json-schema/telewerken-policy-schema.json](json-schema/telewerken-policy-schema.json) | Telework policy schema |
