# ZaiNar

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

ZaiNar is a Positioning, Navigation and Timing (PNT) company that turns existing wireless networks into a sensing system. Patented digital signal processing achieves sub-nanosecond time synchronization across commodity radios, yielding sub-meter 3D positioning for any device that emits a radio signal — indoors, outdoors, through walls and around corners — with no reliance on GPS/GNSS, cameras or extra device power. Deployed today in healthcare equipment tracking, construction safety and site monitoring, and coordinated autonomous operations. ZaiNar emerged from nine years of stealth in February 2026 with more than $100M raised at a $1B+ valuation.

- Website: https://zainartech.com/
- News: https://zainartech.com/news
- Help Center: https://zps.support.zainartech.com/servicedesk/customer/portals
- GitHub: https://github.com/zainar

## API posture

ZaiNar has **no public developer program** — no developer portal, no OpenAPI definition, no reference documentation, no SDKs, no sandbox and no self-service sign-up. Its location platform is a private, credential-gated REST + real-time streaming service, and the only public description of that surface is ZaiNar's own open-source [latency measurement tool](https://github.com/zainar/locate-latency-measurement-script).

Artifacts in this repo record what is genuinely observable:

| Artifact | Method |
|---|---|
| `authentication/` | derived from ZaiNar's first-party client |
| `conventions/` | derived from ZaiNar's first-party client |
| `asyncapi/zainar-event-surface.yml` | derived — a catalog of the real-time surface, **not** an authored AsyncAPI spec |
| `lifecycle/` | derived — records the absent policy surface |
| `packages/` | searched — no first-party SDKs in any registry |
| `well-known/` | probed — no discovery documents on any host |
| `security/zainar-domain-security.yml` | probed — TLS/HSTS/DNSSEC/CAA/SPF/DMARC |
| `llms/` | generated by the API Evangelist enrichment pipeline |

No A2A agent card was found on any host; per pipeline policy none was authored.
