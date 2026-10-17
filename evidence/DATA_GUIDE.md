# Commercial evidence — dictionary and extraction basis
**Mettelo BA-045 · Stage 3 · Snapshot 30 June 2026, 18:00 UK**
All company names, registrations, sites, leads, contract values and events are synthetic.

## Populations
operational_data.csv contains 1,200 lead rows first captured in April (300), May (400) and June (500). account_records.csv has 750 account/site records; lead_source_events.csv 1,394 source interactions; opportunity_records.csv 662 opportunities; lost_opportunity_records.csv 94 loss records; forecast_snapshot.csv 627 rows at 26 June; accepted_order_records.csv 165 accepted orders.

These are different units. A company can have multiple accounts/sites, leads and opportunities. One record is not a unique person. The source population is constructed for teaching, not a real commercial census. Older cohorts have more time to progress.

## Leads, accounts and source events
lead_id is unique; account_id links to an existing account record. created_date is the first included capture. current_source_code is the latest source retained in the source system, not necessarily acquisition cause. owner can be blank. recorded_status and next_action_date are existing usage, not an approved lifecycle; future planned action dates are allowed.

contact_use_evidence is reference_held/unknown/review_needed. None is itself a legal conclusion. No contact details or full permission record are provided.

Account company_registration uses an invented SYNCO prefix, never a real registry claim. Names/sites can differ for a shared registration. The source provides candidates for investigation, not merge instructions. source_event_id is unique; lead_id joins events. Repeated source/campaign interactions are not necessarily duplicate leads or independent acquisitions.

## Opportunities, losses and orders
opportunity_id is unique and links to lead/account. opened_date is distinct from lead creation. stage_label, probability_pct and expected_close_date are seller/source inputs. They are unvalidated definitions/probabilities, not predictive model outputs. value_gbp is proposed total contract value, not recognised revenue.

actual_close_date/status record won/lost outcomes. An open opportunity may have an expected date already past; that is retained source evidence, not automatically a data-cleaning error. erp_order_id joins won records to the supplied accepted orders.

Loss reasons are seller labels and customer_confirmed records evidence status. Do not infer causal lost margin from them alone. Accepted order value/date and service_start_date do not establish invoicing, service readiness or recognised revenue. A blank handover_note_reference is unverified retained context, not proof no communication occurred.

## Forecast snapshot
The forecast is frozen 26 June, earlier than the 30 June pipeline. Only opportunities opened by the snapshot are included. forecast_value_gbp, forecast_probability_pct and forecast_close_month are author inputs. Differences can reflect timing, stale versions, errors or a different commercial assumption. Investigate rather than silently force equality.

O0411's forecast is £25,000 while the current opportunity/accepted order is £15,000. O0416's forecast is £40,000 at 80% while the current opportunity is £30,000 at 80% and labelled discovery. These are source questions, not supplied cause conclusions or corrected figures.

## Measurement limits
No complete meeting-event, recognised-revenue, invoice, margin, customer-person, contact-use or full campaign-cost population exists. Qualified is not automatically a meeting. Conversion needs explicit unit/cohort, stage/event and observation window. Source touch is not proven attribution.

Dates have day precision. Preserve missing owner/action data, open work and inconsistent inputs. Explain transformations and what evidence is missing. Loaded effort rates are capacity values, not automatic payroll or revenue uplift.

## Later observations
pilot_observations.csv contains 80 tasks from 40 historical leads L0701–L0740, baseline replay 17 August and CRM trial 19 August. paired_case_id links modes; task_seconds is operator task time. Source/forecast/contact-review visibility flags and assistance are observations, not legal permission, forecast accuracy or acceptance. Read the compiled Stage 6 pack released 24 August.
