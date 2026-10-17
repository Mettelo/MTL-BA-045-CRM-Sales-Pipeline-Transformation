# Beaconbridge — commercial transformation context and sponsor brief
**Mettelo Business Analyst Project Studio · MTL-BA-045 · aligned pathway edition · Stage 1**
Issued 6 July 2026 by Emma Clarke, Commercial Director. All local companies, people, accounts, amounts and communications are synthetic.

## Organisation and commercial model
Beaconbridge Workplace Solutions Ltd is a fictional UK B2B workplace-services business with 143 staff, including 14 sellers, three marketers and four customer-service colleagues. Delivery teams implement contracted workplace support, facilities coordination and related projects. Customers include multi-site businesses and professional organisations with different purchasing and service contacts.

A sale may be a one-off project or a multi-period service contract. Proposed contract value, accepted order, invoiced amount and recognised revenue are different measures. The source data does not include a full invoicing/revenue population. The BA must not turn opportunity value into income or compare unlike contract periods.

Marketing captures web enquiries, event interactions, referrals and partner introductions. Sales qualifies and develops opportunities, sometimes for the same legal company at different sites. Finance accepts orders into CoreERP. Customer Service receives commitments and coordinates the service handover. Account hierarchy, site identity, contacts, permissions and opportunity history are not consistently separated.

## Operating environment and tools
LeadSheet contains lead rows, personal workbooks contain seller opportunities, CampaignMail holds campaign activity, CoreERP holds accounts/orders/invoices and ServiceDesk holds post-sale contacts. Sellers update the shared forecast on Fridays; Finance freezes it and compares it with orders later. Changes to personal sheets do not always reach the frozen version.

Source can mean first capture, latest interaction or the campaign a seller remembers. Qualified can mean a meeting, a viable need or an opportunity opened. Committed can mean a positive conversation rather than an accepted order. Different teams may therefore report plausible but incompatible conversion or forecast figures.

An account with the same registration may represent a different site or duplicate capture. Merging without preserving the appropriate hierarchy/history could lose attribution, service context or contact-use evidence. The source pack does not supply a merge decision or conceptual data model.

## Trigger and leadership concern
At the 29 June commercial review, Marketing and Sales could not reconcile their conversion reports, Finance disputed several forecast amounts and Customer Service could not locate a handover commitment. Emma requested a new CRM before the autumn campaign.

Sales blames lead quality and duplicate capture. Marketing blames missing follow-up and overwritten source. Finance says probability and snapshot definitions are inconsistent. IT says current ERP capabilities have not been fully assessed and interfaces are not free. Frontline sellers worry about mandatory administration; Service wants reliable agreed commitments without unrestricted access to private negotiation notes.

No source establishes that CRM purchase is the root solution. The BA is commissioned to challenge and reconcile those accounts, identify business value and support an investment/sequence decision.

## Existing board cohort extract
The constructed population has 1,200 lead rows received April–June and observed through 30 June. Older cohorts have had longer to progress. A lead row is not a unique company or person.

| Lead cohort | Lead rows | Unassigned owner | Opportunities | Won | Lost | Open | All included opportunity values, GBP | Source events |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| April | 300 | 28 | 177 | 52 | 23 | 102 | 7,131,000 | 358 |
| May | 400 | 40 | 233 | 68 | 41 | 124 | 9,352,000 | 463 |
| June | 500 | 66 | 252 | 45 | 30 | 177 | 9,621,000 | 573 |

The value column includes open, won and lost opportunities and is not active pipeline, weighted forecast or revenue. Won opportunities have an accepted-order link in the constructed data; that still does not establish recognised revenue. No meeting-event population is supplied, so Marketing's meeting-based conversion cannot be independently reconstructed from these tables.

Later evidence includes 750 account records, 662 opportunities, 1,394 source events, 94 loss records, 627 rows in the 26 June forecast snapshot and 165 accepted orders. Counts are different units and populations.

## Customer, commercial and operational impact
Customers may be contacted twice by different sellers, repeat information after handover or find a promised start date unclear. Marketing cannot reliably evaluate campaigns if history is overwritten. Sellers spend time reconciling versions. Finance cannot defend an unqualified forecast. Service receives commitments after the customer expects delivery.

Planning rates are £40/hour seller capacity, £32/hour Marketing, £42/hour Finance and £28/hour Service. These are loaded values, not guaranteed cash savings. No attributable lost-order margin, churn, conversion uplift or universal commission saving is established. Campaign spend evidence is limited and not a full acquisition-cost model.

Doing nothing may preserve missed follow-up, untrusted information and weak handover as acquisition grows. An unsuitable CRM may reproduce those definitions, add administrative burden and move contact data without appropriate review. Leadership needs a business decision, not a vendor comparison based only on demo appeal.


## Business need for this commission

Lead and opportunity information lives in shared sheets, personal workbooks and other systems. Sellers need quick follow-up, Marketing wants useful attribution, Finance questions forecasts and Service needs reliable won-order handover. A large CRM purchase could absorb the budget without delivering the first useful capability.

The business needs a coherent minimum viable product (MVP), not an undifferentiated list of every department’s request. Agile product analysis must show whose problem a release solves, what user behaviour creates value and how each included story can be accepted.

## Illustrative business situation to investigate

After a visit, a seller wants to capture the next action on a phone without completing a long form. The lead may belong to a branch of an existing legal customer. Marketing wants campaign context, the sales manager wants a meaningful forecast and Service should only act on an accepted commitment. The team must explore a small usable slice while resolving data/permission uncertainty; no approved pipeline or story solution is supplied.

This is a source scenario. Your team must analyse it; it is not an approved process, detailed use case or designed solution.

## Sponsor commission and authority

Emma Clarke, the commissioning sponsor commissions your team as agile product business analysts. The decision is: **Which coherent MVP capability should be prioritised for a six-seller release, which work should be deferred, and what backlog and acceptance evidence justify that choice?**

The requested handover is: **A product goal, evidence-backed user view, MVP/story map, prioritised backlog, low-fidelity interaction design and release recommendation ready for refinement.**

Sellers favour low-friction capture, management asks for complete reporting, Marketing wants attribution, Finance separates forecasts from revenue and Service needs accurate commitments. Mandatory fields, contact imports and account merging may help one group while harming another.

The sponsor can request analysis but cannot substitute for Sales, Finance, Service, privacy and funding owners. Identify material approvals and unknowns without fabricating named reviewers or sign-off.

## Scope and exclusions

**Included:** Lead capture/follow-up, relevant account/site context, opportunity progression, forecast inputs and sales-to-service handover to the extent justified for the chosen MVP. Consider existing ERP capability, data-use decisions and seller adoption as constraints.

**Outside this assignment:** No full FRD, enterprise data-platform design, complete API specification, production CRM implementation, bulk contact import, live marketing or approved revenue policy redesign. A prototype may be low fidelity; coding is not required.

## Constraints and evidence limitations

The initial one-off envelope is £80,000 including £6,000 committed, with an £18,000 annual incremental ceiling. Later funding, ERP and timing evidence may change scope. No team velocity or committed engineering capacity is supplied; proposed sequencing must disclose assumptions.

The learning commission lasts 5 cohort weeks. Original dates in operational records remain source history; later operational ambitions do not extend the assessed scope. Staff availability is limited: plan proportionate elicitation using supplied interviews and record follow-up questions when real access is unavailable.

The dataset is constructed, observed at its stated cutoff and incomplete for some business questions. An absent event is not always proof an event did not happen. Do not claim representative research, causality, approved targets or realised outcomes merely from these records. Use [the data guide](../evidence/DATA_GUIDE.md) and [source provenance](../reference/OFFICIAL_REFERENCES_AND_SOURCE_PROVENANCE.md).

## How the evidence supports the work

| Evidence | Analytical purpose | Relevant tasks |
|---|---|---|
| Interviews and product discovery/feedback supplement | Understand competing user goals and known interaction concerns without inventing completed research. | A1–A2, A5 |
| Leads, accounts, opportunities and forecast snapshots | Ground product outcomes and data-quality concerns in reproducible evidence. | A1–A4 |
| Orders and Service evidence | Distinguish won/forecast/accepted order and identify handover needs. | A2–A5 |
| System context and raw options pack | Evaluate existing capability and scope dependencies; supplier quotes are not priority decisions. | A3, A6 |
| Budget, ERP and timing notices | Re-slice MVP and refine release assumptions while preserving a coherent user outcome. | A3–A7 |

## What leadership needs to receive

Product decision-makers can understand the release goal, follow a realistic user journey through included stories, test their acceptance conditions and see why other requests are deferred. Prototype feedback and unresolved research are represented honestly.

| Task | Required handover content | Assessment weight |
|---|---|---|
| A1 | Product goal; proposed outcome measures; product boundary, exclusions and decision owners. | 10% |
| A2 | Evidence-backed personas; opportunity map; competing needs and explicitly unvalidated assumptions. | 15% |
| A3 | MVP definition; user-activity story map; included/deferred scope and prioritisation rationale. | 20% |
| A4 | Epics; 12–18 prioritised user stories with stable IDs, observable acceptance criteria, dependencies and research spikes where needed. | 25% |
| A5 | Low-fidelity wireframes or clickable prototype covering at least three linked interactions; error/permission states; feedback or labelled self-review. | 15% |
| A6 | Refinement log; release plan using story IDs; product acceptance approach distinguishing story criteria, Definition of Ready and Definition of Done. | 10% |
| A7 | Product playback and indexed backlog baseline; MVP narrative, trade-offs, decision requests and next learning steps. | 5% |

Use [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) for the four acceptance criteria per task and [the submission checklist](../submission/DELIVERABLES_CHECKLIST.md) for the exact handover package. These define the commission; historical stakeholder ambitions are inputs to evaluate, not extra mandatory portfolios.

No preferred solution or completed learner artefacts are provided.
