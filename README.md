# PocketHealth (pockethealth)

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

PocketHealth is a patient-centric medical imaging platform that lets patients access, view, store, and share their diagnostic imaging (DICOM) and reports online, and lets healthcare providers exchange imaging across institutions and networks. PocketHealth also publishes an open, RESTful developer API aimed at RIS/PACS/VNA vendors, letting them embed PocketHealth's patient enrollment, electronic consent, and background record-delivery workflows natively into their own clinical software.

**API access model (read this first):** The PocketHealth developer API is real but **partner-gated**. It is advertised as free forever for RIS/PACS vendors, healthcare providers, and physicians, but the full technical reference - base URL, endpoint paths, and authentication - is **not published on the open web**. Engaged vendors are assigned a dedicated integration rep who provides testing resources and detailed documentation. Because there is no public API reference or OpenAPI definition, the APIs listed below are **logical capabilities modeled from PocketHealth's public developer-program and product descriptions**, not confirmed endpoints. No public WebSocket API exists.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pockethealth/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pockethealth/refs/heads/main/apis.yml)

## Tags

- Medical Imaging
- Healthcare
- DICOM
- Image Exchange
- RIS
- PACS
- Interoperability
- Patient Access
- Health IT

## Timestamps

- **Created:** 2026-07-05
- **Modified:** 2026-07-05

## APIs (modeled, not confirmed)

### PocketHealth Patient Enrollment API

Enroll patients for PocketHealth access natively from within a RIS/PACS/VNA vendor's own clinical software, with no change to the end-user clinical workflow. Endpoint paths, base URL, and authentication are provided to engaged vendors by a dedicated integration rep and are not published publicly.

- **Human URL:** [https://www.pockethealth.com/developers/](https://www.pockethealth.com/developers/)

### PocketHealth Electronic Consent API

Capture and manage electronic patient consent for sharing diagnostic imaging and reports, so release-of-records workflows can run automatically and securely. Not publicly documented at the endpoint level.

- **Human URL:** [https://www.pockethealth.com/developers/](https://www.pockethealth.com/developers/)

### PocketHealth Record Delivery API

Automate secure background delivery of DICOM imaging studies and associated reports from any DICOM-compliant RIS, PACS, or VNA system to a patient's PocketHealth account, without requiring UI or workflow changes. Not publicly documented at the endpoint level.

- **Human URL:** [https://www.pockethealth.com/developers/](https://www.pockethealth.com/developers/)

### PocketHealth Image Exchange API

Provider-to-provider imaging exchange across external hospitals and out-of-province networks, with an automated ingestion engine (patient matching, order creation, tag morphing) that centralizes inbound and outbound imaging workflows. No public API reference is published for this surface.

- **Human URL:** [https://www.pockethealth.com/providers/pockethealth-image-exchange/](https://www.pockethealth.com/providers/pockethealth-image-exchange/)

## Pricing

- **Patients:** Free Basic account (access, download, share); paid subscription tiers (Flex, Unlimited) add features such as online image viewing, family members, and CD/USB uploads. A Financial Assistance Program waives paid-plan fees where cost is a barrier.
- **RIS/PACS developers / providers / physicians:** The developer API and provider integration are described as free forever, with access granted through PocketHealth's integration team rather than self-serve signup.

See [plans/pockethealth-plans-pricing.yml](plans/pockethealth-plans-pricing.yml). Patient tiers and names have changed over time; re-verify against [https://www.pockethealth.com/patients/pricing/](https://www.pockethealth.com/patients/pricing/).

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/pockethealth)
- [Website](https://www.pockethealth.com)
- [Documentation](https://www.pockethealth.com/developers/)
- [Plans](plans/pockethealth-plans-pricing.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
