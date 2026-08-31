# Transparency

Effective date: 31 August 2026

## What is open

This repository contains the Career Centre packages distributed by
HopLittleBunny for supported ChatGPT and Claude installation paths. It includes
the skills, evidence and conversation contracts, local scripts, document
templates, schemas, synthetic evaluations, packaging logic, public-site source
and tests. There is no separate closed-source Career Centre model behind the
published packages.

Career Centre uses the [Apache License 2.0](LICENSE). Third-party material and
its licensing are recorded in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)
and the repository's licence-compatibility documentation.

## Data flow

The user intentionally supplies CVs, preferences, role links or application
context to the selected AI host. That host processes conversations,
attachments, searches and generated files under its own policies and account
settings. External job sites have their own data practices.

The package does not include a publisher API key, account system, analytics
SDK, advertising SDK, CV database, authentication service or application-
submission backend. Career Passport and application files remain in the host
conversation, connected workspace or location chosen by the user.

## Claims and limits

- CV statements are candidate-supplied evidence, not independently verified
  facts.
- Job availability, salary and eligibility can change and require live checks.
- Career Centre does not guarantee interviews, offers or employment.
- It does not auto-submit applications or send messages on the user's behalf.
- Provider capabilities, plans and regional availability can vary.
- Synthetic and scripted tests do not prove universal host-model behaviour.

## Security and secrets

Do not publish real CVs, private employer information, identity or work-right
documents, cookies, tokens or login information in issues. Follow
[SECURITY.md](SECURITY.md) for sensitive reports.

Repository-history and current-tree secret checks are part of storefront and
release review. A zero-alert check means no matching alert was open at the time
of review; it is not a guarantee that future commits are safe.

On 31 August 2026, a high-confidence credential-pattern scan found no matches
in the tracked tree or Git history, and GitHub's secret-scanning API reported
zero open alerts. GitHub secret scanning, push protection and Dependabot
security updates were enabled. Broader non-provider and validity checks were
not reported as enabled by GitHub for this repository.

## Changes

Material changes are recorded through Git history, release notes and dated
audits. Public comparisons should name the exact product version and disclose
the test method, failures and limitations.
