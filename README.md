# SMSAPI (smsapi)

SMSAPI is a European bulk business-messaging provider headquartered in Poland and part of LINK Mobility. Its REST API delivers SMS, MMS, and voice (VMS) messaging, email marketing, two-factor authentication, contact and group management, sender field registration, subuser administration, and account/profile operations, authenticated with OAuth 2.0 bearer tokens over api.smsapi.com and api.smsapi.eu.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/smsapi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/smsapi/refs/heads/main/apis.yml)

> **Corporate state:** SMSAPI is part of [LINK Mobility](https://www.linkmobility.com/), a European CPaaS group. The service continues to operate under the SMSAPI brand with its own developer platform at smsapi.com/docs and dev.smsapi.com.

## Tags

- Messaging
- SMS
- MMS
- Voice
- 2FA
- Bulk Messaging
- Communications
- CPaaS

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### SMSAPI SMS API

Send single, bulk, scheduled, and templated text messages via POST to /sms.do, with sender field, flash, personalization, opt-out links, and cut.li short-URL support, plus delivery-report callbacks.

- **Human URL:** [https://www.smsapi.com/docs/#sms-api](https://www.smsapi.com/docs/#sms-api)
- **Base URL:** `https://api.smsapi.com/sms.do`

#### Tags

- SMS
- Messaging
- Bulk Messaging

#### Properties

- [Documentation](https://www.smsapi.com/docs/#sms-api)
- [API Reference](https://www.smsapi.com/docs/)
- [OpenAPI](openapi/smsapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smsapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smsapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMSAPI MMS API

Send multimedia messages (SMIL/image content) to one or many recipients via POST to /mms.do, with scheduling and delivery reporting.

- **Human URL:** [https://www.smsapi.com/docs/#mms-api](https://www.smsapi.com/docs/#mms-api)
- **Base URL:** `https://api.smsapi.com/mms.do`

#### Tags

- MMS
- Messaging
- Multimedia

#### Properties

- [Documentation](https://www.smsapi.com/docs/#mms-api)
- [OpenAPI](openapi/smsapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smsapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smsapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMSAPI VMS Voice API

Deliver voice messages (VMS) from text-to-speech or an uploaded audio file via POST to /vms.do, with scheduling and call-result callbacks.

- **Human URL:** [https://www.smsapi.com/docs/#vms-api](https://www.smsapi.com/docs/#vms-api)
- **Base URL:** `https://api.smsapi.com/vms.do`

#### Tags

- Voice
- VMS
- Text to Speech

#### Properties

- [Documentation](https://www.smsapi.com/docs/#vms-api)
- [OpenAPI](openapi/smsapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smsapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smsapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMSAPI Contacts API

Full CRUD over the contact address book, contact groups, and custom fields via /contacts, /contacts/{id}/groups, and /contacts/groups, for building and segmenting recipient lists.

- **Human URL:** [https://www.smsapi.com/docs/#contacts-api](https://www.smsapi.com/docs/#contacts-api)
- **Base URL:** `https://api.smsapi.com/contacts`

#### Tags

- Contacts
- Groups
- Address Book

#### Properties

- [Documentation](https://www.smsapi.com/docs/#contacts-api)
- [OpenAPI](openapi/smsapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smsapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smsapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMSAPI Sender Names API

List, register, inspect, and remove alphanumeric sender fields (sender names) via /sendernames, including default sender selection for outbound SMS.

- **Human URL:** [https://www.smsapi.com/docs/#sender-names-api](https://www.smsapi.com/docs/#sender-names-api)
- **Base URL:** `https://api.smsapi.com/sendernames`

#### Tags

- Sender Names
- Sender Fields
- Branding

#### Properties

- [Documentation](https://www.smsapi.com/docs/#sender-names-api)
- [OpenAPI](openapi/smsapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smsapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smsapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMSAPI 2FA Authentication API

Generate and validate one-time passcodes for two-factor authentication via /authenticator/send_code and /authenticator/check_code, delivered over SMS or voice.

- **Human URL:** [https://www.smsapi.com/docs/#2fa-api](https://www.smsapi.com/docs/#2fa-api)
- **Base URL:** `https://api.smsapi.com/authenticator`

#### Tags

- 2FA
- Authentication
- Verification
- OTP

#### Properties

- [Documentation](https://www.smsapi.com/docs/#2fa-api)
- [OpenAPI](openapi/smsapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smsapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smsapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMSAPI Subusers API

Create and administer subaccounts (subusers) via /subusers, including credit allocation, points limits, and per-subuser permissions for delegated sending.

- **Human URL:** [https://www.smsapi.com/docs/#subusers-api](https://www.smsapi.com/docs/#subusers-api)
- **Base URL:** `https://api.smsapi.com/subusers`

#### Tags

- Subusers
- Account Management
- Administration

#### Properties

- [Documentation](https://www.smsapi.com/docs/#subusers-api)
- [OpenAPI](openapi/smsapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smsapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smsapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMSAPI Profile and Account API

Retrieve account profile details and current credit balance (points) via GET /profile for monitoring available funds before sending.

- **Human URL:** [https://www.smsapi.com/docs/#profile-api](https://www.smsapi.com/docs/#profile-api)
- **Base URL:** `https://api.smsapi.com/profile`

#### Tags

- Profile
- Account
- Balance

#### Properties

- [Documentation](https://www.smsapi.com/docs/#profile-api)
- [OpenAPI](openapi/smsapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smsapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smsapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMSAPI HLR Lookup API

Validate phone numbers and resolve carrier, portability, and reachability information via HLR lookups on /hlr.do, with results returned inline or via callback.

- **Human URL:** [https://www.smsapi.com/docs/#hlr-api](https://www.smsapi.com/docs/#hlr-api)
- **Base URL:** `https://api.smsapi.com/hlr.do`

#### Tags

- HLR
- Number Validation
- Lookup

#### Properties

- [Documentation](https://www.smsapi.com/docs/#hlr-api)
- [OpenAPI](openapi/smsapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smsapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smsapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMSAPI Blacklist API

Manage opted-out recipients via /blacklist/phone_numbers so blacklisted numbers are automatically excluded from outbound campaigns for compliance.

- **Human URL:** [https://www.smsapi.com/docs/#blacklist-api](https://www.smsapi.com/docs/#blacklist-api)
- **Base URL:** `https://api.smsapi.com/blacklist/phone_numbers`

#### Tags

- Blacklist
- Opt-Out
- Compliance

#### Properties

- [Documentation](https://www.smsapi.com/docs/#blacklist-api)
- [OpenAPI](openapi/smsapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smsapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smsapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMSAPI Short URLs API

Create and manage trackable cut.li short links via /short_urls and retrieve per-link click statistics for measuring campaign engagement.

- **Human URL:** [https://www.smsapi.com/docs/#short-urls-api](https://www.smsapi.com/docs/#short-urls-api)
- **Base URL:** `https://api.smsapi.com/short_urls`

#### Tags

- Short URLs
- cut.li
- Link Tracking

#### Properties

- [Documentation](https://www.smsapi.com/docs/#short-urls-api)
- [OpenAPI](openapi/smsapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smsapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smsapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/smsapi)
- [LinkedIn](https://www.linkedin.com/company/smsapi-com)
- [Website](https://www.smsapi.com/)
- [Documentation](https://www.smsapi.com/docs/)
- [Plans](plans/smsapi-plans-pricing.yml)
- [Rate Limits](rate-limits/smsapi-rate-limits.yml)
- [Fin Ops](finops/smsapi-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
