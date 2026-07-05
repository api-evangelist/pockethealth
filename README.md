# PocketHealth (pockethealth)

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
