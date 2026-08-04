# AdRoute Fleet — Complete Role & Task Breakdown

Team of 5 humans + AI agent workforce + 4 contractors. Phases: **P0** Foundations (wks 1–2) · **P1** Validation (wks 1–4) · **P2** Broker launch, revenue on (wks 3–8) · **P3** Platform build (wks 6–16) · **P4** Pilot → soft launch (wks 12–20).

## The five humans

| # | Role | Owns |
|---|------|------|
| H1 | **Founder / CEO** | Vision, investor, legal, geography decision, anchor-fleet relationships, final approval gates |
| H2 | **Product & Design Lead** | PRD, prototype, brand, site UX, pricing display, recap-report design, interview scripts |
| H3 | **Tech Lead / Architect** | Architecture, payments, data model, security, GPS evidence pipeline, infra |
| H4 | **Full-stack + AI Engineer** | Frontend build, all AI agents, internal tooling, analytics instrumentation |
| H5 | **Market Operations Lead** | Operator recruiting, campaign fulfillment desk, support, pilot execution |

## Contractors
C1 GA + FL land-use attorney · C2 CPA/bookkeeper · C3 commercial insurance broker · C4 brand/visual designer (short engagement)

## AI agents (built by H4; each reports to a human owner; human review gates during pilot)
A1 Prospector (operator + advertiser outreach) → H5 · A2 Onboarding/verification (docs, insurance checks) → H5 · A3 Creative assistant (EN/ES ad copy, layout, QR) → H2 · A4 Scheduling/routing assistant → H5 · A5 Support agent → H5 · A6 Content/SEO agent → H2 · A7 Compliance monitor (per-city rules engine) → H3 · A8 Reporting agent (weekly KPI + investor report) → H1

---

## Workstream 1 — Legal & company foundations (P0)
1.1 Confirm LLC standing, EIN, FL+GA registrations — H1
1.2 IP-assignment + NDAs for team and contractors — H1/C1
1.3 Engage C1; commission 6-city sign-ordinance review (Atlanta, Savannah, Orlando, Tampa, Jacksonville, Miami/Miami-Dade) incl. LED brightness, parking, route rules — H1
1.4 **Geography decision memo** (Miami-first vs Atlanta-first) off counsel results — H1, gate
1.5 Advertiser Terms of Service + refund/cancellation policy — C1/H1
1.6 Operator Agreement (commission %, fulfillment SLA, evidence duties, insurance minimums, non-circumvention clause) — C1/H1
1.7 Privacy policy + GPS-tracking consent language — C1/H3
1.8 Business insurance (GL + E&O) — C3/H1
1.9 Payment/tax compliance: 1099-K posture, FL+GA sales-tax check on ad services — C2/H1
1.10 Company owns all repos, cloud, domains, design files, credentials — H3

## Workstream 2 — Market validation (P1)
2.1 Interview script for operators (idle days, commission tolerance, payment terms, evidence practices) — H2
2.2 Interview script for advertisers (budget, urgency, proof expectations, booking preference) — H2
2.3 Recruit + run 5+ operator interviews from the 48-operator database — H5 (A1 assists)
2.4 Run 10+ advertiser interviews across politics, events, restaurants, real estate, legal — H5
2.5 Collect sample quotes, invoices, campaign briefs, proof-of-performance reports — H5
2.6 Validate rate card per metro against interview data — H2
2.7 **Anchor-fleet LOIs ×2** (targets: Mobile Billboard Miami, ILUM adTECH) — H1, gate
2.8 Hand-verify AdQuick Go $25K minimum + monitor competitors quarterly — H2
2.9 Decision memo: instant-book vs quotes, confirmed by interviews — H2/H1, gate

## Workstream 3 — Supply side (P1–P2, ongoing)
3.1 Load all 48 operators into CRM with fleet/pricing/contact data — H5
3.2 Build A1 prospector agent + outreach sequences — H4
3.3 Vetting checklist: insurance cert, vehicle reg, photos, W-9, references — H5
3.4 Build A2 verification agent (doc collection + checks, human approval) — H4
3.5 White-glove onboard first 5 operators (rate card, availability, service area, payout) — H5
3.6 Per-operator rate cards + availability capture (shared calendar OK at first) — H5
3.7 Standby/backup fulfillment arrangement for peak dates — H5
3.8 Stripe Connect payout onboarding per operator — H3
3.9 Operator playbook: response times, evidence requirements, escalations — H5
3.10 Track fill-rate/coverage per metro; recruit ahead of demand — H5 (A8 reports)

## Workstream 4 — Demand side (P2, ongoing)
4.1 Brand identity, name/domain/socials — H2/C4
4.2 Marketing site: transparent pricing page + instant-quote calculator + booking request — H2/H4
4.3 Wedge landing pages: political (GA/FL 2026), conventions (OCCC, Miami Beach Convention Ctr adjacents), per-city pages — H2 (A6 drafts)
4.4 Outbound list: political consultants/media buyers GA+FL — H5 (A1 runs)
4.5 Outbound list: exhibitor lists for major 2026 Orlando/Miami conventions — H5 (A1 runs)
4.6 Partnership pipeline: local agencies, chambers, event planners (referral fee) — H1/H5
4.7 Limited Google Ads tests with strict CAC caps (SERPs are broker-owned; don't outbid) — H2
4.8 Case-study engine: recap → testimonial → published case study per pilot campaign — H2 (A6)
4.9 Referral codes for operators, advertisers, agencies — H4
4.10 Source-tracking on every lead (channel → quote → booking → rebooking) — H4

## Workstream 5 — Product: broker stack first (P2)
5.1 Architecture brief: modules, data model, audit trail, RBAC — H3, gate
5.2 Campaign request form (5-min completion target) — H4
5.3 Instant-price engine v0 (rate card × metro × truck type × duration) — H3
5.4 Internal ops CRM/pipeline (request → operator match → confirm → live → evidence → paid) — H4
5.5 Stripe payments: authorize/capture, refunds, receipts, commission split — H3
5.6 E-sign contract flow from templates — H4
5.7 Proof-of-play v0: timestamped photos + GPS trace (phone-based or existing trackers), operator upload link — H3
5.8 Auto-generated campaign recap report (route map, photos, hours) — H2/H4
5.9 Notification set: booking confirmed, campaign live, evidence in, recap ready — H4
5.10 A3 creative assistant (brief → EN/ES headline/layout/QR drafts, human approval) — H4/H2

## Workstream 6 — Product: platform proper (P3)
6.1 Advertiser accounts + dashboard (status, history, rebook) — H4
6.2 Self-serve checkout on posted prices — H3/H4
6.3 Availability calendar with conflict prevention — H3
6.4 Quote path for complex/multi-truck jobs (the exception flow) — H4
6.5 Admin console: approval queues, status edits, refunds, disputes, fee config, full audit log — H3/H4
6.6 Operator portal (after ~25 campaigns): opportunity feed, calendar, evidence upload, payout statements — H4
6.7 A7 compliance engine: per-city rules gating serviceable areas/hours — H3
6.8 QA pass: roles/permissions, payment edge cases (duplicate webhooks, interrupted checkout), uploads, mobile — H3/H4
6.9 Security review: authz, sensitive data, admin actions, session mgmt — H3, gate
6.10 Backups, monitoring, incident basics — H3

## Workstream 7 — Finance & metrics (P0–ongoing)
7.1 Operating model: 15% launch take → 18–20% blended; burn plan vs runway — H1/C2
7.2 Refund/cancellation/no-show money rules documented before payment code — H1/C1
7.3 Weekly reconciliation (Stripe ↔ ledger ↔ payouts) — C2/H3
7.4 KPI dashboard: GMV, net revenue, take %, CAC by channel, quote→book %, fill rate, on-time fulfillment, rebooking %, NPS — H4 (A8 publishes weekly)
7.5 Monthly investor report — H1 (A8 drafts)

## Workstream 8 — Pilot → soft launch (P4)
8.1 Pilot charter: 5 operators, 10–20 advertisers, one metro — H1
8.2 Ops runbook: booking, day-of monitoring, exceptions, disputes — H5
8.3 Run first 10 campaigns with post-transaction review each (response time, quote quality, payment, evidence, both-sides satisfaction, support load) — H5
8.4 **Economic gate:** operators accept 15% AND ≥25% of advertisers rebook/refer within 60 days — H1
8.5 Scale to 30–50 campaigns; fix defects; document repeatable onboarding — H5/H3
8.6 Soft-launch readiness report → go/no-go on metro #2 — H1, gate
8.7 Post-launch: quarterly competitor + regulatory re-scan — H2/A7

## Explicitly deferred (backlog, do not build now)
Car wraps/AdRoute Drive (partner with Wrapify/Wrapmate if ever) · boats/aircraft/street teams (after truck playbook repeats) · auctions/bidding engine · impression analytics beyond GPS+photos · native mobile apps (responsive web first) · programmatic/DSP integrations.
