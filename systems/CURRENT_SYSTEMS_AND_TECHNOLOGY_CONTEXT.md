# Commercial systems and integration source context
**Mettelo BA-045 · Stage 3 · Oliver King's note, 20 July**

## Current landscape
LeadSheet contains captured lead rows; sellers maintain local opportunity workbooks; CampaignMail holds interactions; CoreERP stores accounts/orders/invoices; ServiceDesk holds post-sale contacts. Finance freezes a forecast, while sellers may continue changing local files.

The analysis extract uses reconciled IDs and is not proof the production sources share a universal key. A company, site, lead, contact, opportunity and order are different business concepts. Names alone are not safe join keys.

## Interface constraints
The current CoreERP contract provides a nightly export and 5,000 API calls/day, without a guaranteed real-time event feed. Supplier demos used seeded responses. No contracted order-status latency, mapping, write-back or recovery criterion is supplied.

A successful technical import does not prove account/site identity, source-history preservation or order reconciliation. Missing/duplicated/out-of-order records and wrong-role access need business expectations before a useful test.

## Existing capability hypothesis
IT has not fully assessed CoreERP's sales capabilities. Existing account/order functions and a shared workflow might be useful, but the participant should not assume there is a suitable CRM module until later evidence. Current tools still require configuration, data work, access review, adoption and support.

Indicative internal effort is 15 analyst days at £450/day plus 8 interface days at £650/day; £5,000–£8,000 annual additional support. No resource booking or complete feature/assurance scope is committed.

## Commercial evidence and dependencies
The [raw options source pack](../procurement/OPTIONS_SOURCE_PACK.md) contains quoted inputs and exclusions. It is not a weighted comparison or recommended option. A process/definition/ownership intervention, staged use of current tools or deferral can also be considered by the BA.

September security and reporting work competes for the integration specialist. Business owners must review account/site treatment, source history, forecast and handover needs. A vendor feature catalogue does not establish contracted fit.

## Data, access and deployment
No broad personal-inbox migration is approved. Imported contact-use evidence, restricted notes and service information need distinct purpose/access review. The August experiment has synthetic records only and no production order write-back or outreach.

A new view does not decide customer commitments, permission or revenue. Staff adoption, open opportunities, existing orders, support, reconciliation and rollback matter whichever option is chosen.

## Unestablished information
Final entitlement/licence coverage, data mapping, hierarchy, migration scope, audit/retention, latency/recovery, peak load, user count and total delivery cost remain incomplete. The BA should define and validate business needs and acceptance evidence, not copy supplier claims into a completed architecture.
