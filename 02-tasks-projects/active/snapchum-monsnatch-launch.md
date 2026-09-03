# Snapchum / Monsnatch US Retail Launch

**Status:** Active; checkout disabled  
**Last reconciled:** 2026-09-01  
**Execution source:** [PowerLobster project](https://powerlobster.com/projects/a2bbe756-4ade-4149-9ba0-55cca30de11f#overview)  
**Repository source:** `../../../snapchum/temp-specs/monsnatch-bmos-launch-plan.md`

## Operating summary

The staging catalog, BMOS store, public out-of-stock shop page, and interest-list
plan are complete. Paid preorder is not ready. Eight PowerLobster tasks remain
open, and the repository launch gates still require authorization, exact
logistics economics, customer policies, inventory release, and a successful
test flow.

PowerLobster state on 2026-09-01: **5 completed, 1 in progress, 7 pending**.

## Next useful action

Miles reviews the drafted ECW follow-up with Mike. After Mike approves it, Miles
sends it to Janice and records the sent-message evidence and response. Do not
enable checkout or sellable inventory.

## Still to do — PowerLobster

| Status | Task | Owner | Immediate next action |
|---|---|---|---|
| In progress | [Obtain Momon Wonder authorization and complete product packet](https://powerlobster.com/t/f95c1608-70b0-48a0-a641-4cb0a8c17bb3) | Mike | Obtain written retailer/media authorization and remaining official product/compliance data. |
| Pending | [Close ECW one-box US DDP qualification](https://powerlobster.com/t/d43a147a-becc-4810-b38a-fd031b897ce4) | Miles / Mike approval | Approve and send the prepared follow-up; obtain exact rate, packaging, insurance, returns, fees, customs, API, and timing answers. |
| Pending | [Complete Snapchum junior-operator onboarding](https://powerlobster.com/t/c2426a60-4e51-46d8-a4a8-861293c480f7) | Miles | Read the operating documents, explain the flow, and post the five-line update with evidence. |
| Pending | [Maintain Snapchum launch-readiness checklist](https://powerlobster.com/t/32ed41fc-89c3-4d10-8dee-1b5b45e02612) | Miles / agent | Reconcile each gate whenever evidence changes. |
| Pending | [Prepare Monsnatch KOL attribution system](https://powerlobster.com/t/ed166a32-8d23-4455-bb46-485d7c6bbd52) | Unassigned | Obtain KOL details from Mark, then design and test unique staging links/codes. |
| Pending | [Confirm Miles's school and coach availability for Bangkok trip](https://powerlobster.com/t/f4ee31a8-5d63-4c2c-8d0e-193d2e461d32) | Miles | Ask teacher and coach; report constraints without booking or committing. |
| Pending | [Confirm Mike and Miles Bangkok world-premiere attendance](https://powerlobster.com/t/d9c28489-c8b0-4c6f-a10b-4bb656f847ea) | Mike | Confirm dates, venue details, roles, badges, and permissions after Miles reports availability. |
| Pending | [Make Snapchum paid-preorder go/hold decision](https://powerlobster.com/t/fa7fa832-528e-436b-8e09-4d39db6aae2f) | Mike | Review all gates and record GO, HOLD, or STOP. This is last in the sequence. |

## Completed — PowerLobster

| Task | Owner | Evidence / resulting state |
|---|---|---|
| [Set up private Monsnatch 51Exports catalog and Arthur access](https://powerlobster.com/t/9003278c-be22-4935-87ca-643ba61f09e3) | Mike | Existing private catalog retained; Arthur access recorded. |
| [Build and QA First Bond Booster Box catalog record](https://powerlobster.com/t/e39d5707-e854-49dd-8a44-0920c1a438a9) | Arthur | Existing record retained with verified identifiers and zero sellable inventory. |
| [Create Snapchum BMOS store and attach authorized catalog](https://powerlobster.com/t/ec3712d2-992d-418b-bb98-be4a9832b357) | Arthur | Existing store retained; catalog attached once; Stripe, checkout, feed, and agent selling disabled. |
| [Integrate BMOS catalog adapter into Snapchum staging](https://powerlobster.com/t/8627b5c7-cc4a-484f-9b70-6719abceabd5) | Arthur | Public `/shop/` is an out-of-stock, interest-only presentation. |
| [Review Snapchum Monsnatch announcement and interest-list plan](https://powerlobster.com/t/36d35fd0-be96-48b4-890c-e138ae1a760e) | Mike | Interest-only public page approved; no paid-order claim. |

## Launch gates not yet closed

These are requirements within the open tasks, not additional completed work:

- Written retailer authorization and public asset permission.
- Final approved warning, product copy, assets, and claims.
- Missing pack/token/carton facts and compliance/customs data.
- Exact packed one-box DDP price and supported delivery range.
- Packaging source/specification, fee treatment, and insurance decision.
- Customer cancellation, delay, damage, loss, refusal, return, and refund terms.
- Merchant of record, payment account, sales-tax responsibility, and support owner.
- Approved sellable inventory cap without carton/box/pack double-counting.
- KOL claims, CTA, links/codes, timing, compensation, and attribution test.
- Working test order, tracking, cancellation/refund, and reporting flow.
- Warehouse receipt, count/damage evidence, reconciliation, and release approval.
- Mike's explicit paid-preorder GO decision and a separate activation task.

## Safety boundary

Keep every sellable quantity at zero and checkout disabled until every required
gate passes and Mike explicitly approves activation.

## Source note

Live task statuses above were read from PowerLobster on 2026-09-01. Launch-gate
details were reconciled from the Snapchum repository documents last updated
2026-08-31. Repository facts and live task status are kept separate.
