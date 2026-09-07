# Feature status — Investment & wealth operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 404 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 3 | 0 | Native records/view |
| Work items & projects | records | 1 | 0 | Native records/view |
| Contacts & parties | records | 2 | 0 | Native records/view |
| Tasks | records | 1 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 9 | 0 | Native records/view |
| Activity & audit trail | audit | 14 | 0 | Native records/view |
| Provider connections | integration | 3 | 0 | Provider request records only |
| Recordkeeping agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investment option registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Participant balance ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue-sharing rate mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| 12b-1 calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sub-TA fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shareholder service fee | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gross-to-net expense review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Required revenue credit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recordkeeper statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Participant allocation method | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Excess fee detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit correction workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fiduciary evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plan option analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Administration agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fund share-class registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Daily monthly NAV ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset tier calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investor account counts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction volume counts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Base administration fee | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fund accounting fee | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer agency fee | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance fee support | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service credit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Administrator dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fund vendor analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Allocation policy library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fund entity registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor invoice ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expense category classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Manager versus fund test | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shared service allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Time-record allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Broken-deal allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Co-investment treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cross-fund allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Class-level allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Policy exception workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reimbursement calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NAV correction reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fund expense analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prime agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Account entity hierarchy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Daily cash balance ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Margin loan calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Benchmark rate validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Spread tier calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Day-count convention | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Currency basis adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cross-account netting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit interest calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stock borrow fee linkage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Statement charge matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Broker dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Broker fund analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| LPA fee terms | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investor commitment registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investment period control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fee base calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Step-down calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction fee ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Monitoring fee ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Director fee ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Offset percentage calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Broken-deal expense review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Waiver and rebate control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Capital account allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quarterly statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| GP correction workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fund investor analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligible security inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loan transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collateral balance validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Borrower fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate rate calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collateral reinvestment income | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Specials premium analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Indemnification fee control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue share calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Custodian statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Corporate action treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exception dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program security analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bank agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Account and service registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analysis statement ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AFP code normalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unit-price validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume and usage validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate service detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Closed-account fee detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Earnings credit validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compensating balance calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deposit assessment review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wire ACH and lockbox audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bank exception workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Relationship scorecard | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Account service optimization analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Families | records | 1 | 0 | Native records/view |
| Beneficiaries | records | 1 | 0 | Native records/view |
| Advisors | records | 2 | 0 | Native records/view |
| Trusts | records | 1 | 0 | Native records/view |
| Distributions | records | 2 | 0 | Native records/view |
| Succession Plans | records | 1 | 0 | Native records/view |
| Holdings | records | 1 | 0 | Native records/view |
| Illiquid Assets | records | 1 | 0 | Native records/view |
| Real Estate | records | 1 | 0 | Native records/view |
| Art Collection | records | 1 | 0 | Native records/view |
| Private Investments | records | 1 | 0 | Native records/view |
| LP Interests | records | 1 | 0 | Native records/view |
| Valuation Reports | records | 1 | 0 | Native records/view |
| Tax Filings | records | 1 | 0 | Native records/view |
| Charitable Gifts | records | 1 | 0 | Native records/view |
| Education Grants | records | 1 | 0 | Native records/view |
| Governance Docs | records | 1 | 0 | Native records/view |
| AI · Estate Tax Scenario | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Trust Distribution | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Illiquid Valuation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Charitable Vehicle | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Executive Brief | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI · Governance Memo | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Succession Readiness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Tax-Loss Harvest | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Generational Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Art Provenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Education Rule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Compliance Check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Charitable Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Meeting Agenda | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Allocation Rebalance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Beneficiary Onboarding | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Webhooks | integration | 3 | 0 | Provider request records only |
| Liquidity ladder | records | 1 | 0 | Native records/view |
| Family missions | records | 1 | 0 | Native records/view |
| Mission milestones | records | 1 | 0 | Native records/view |
| Education milestones | records | 1 | 0 | Native records/view |
| Learning plans | records | 1 | 0 | Native records/view |
| Nextgen portal | records | 1 | 0 | Native records/view |
| Philanthropic grant score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deals | records | 1 | 0 | Native records/view |
| Pipeline Notes | records | 1 | 0 | Native records/view |
| Intros | records | 1 | 0 | Native records/view |
| Term Sheets | records | 1 | 0 | Native records/view |
| Companies | records | 2 | 0 | Native records/view |
| Founders | records | 1 | 0 | Native records/view |
| Funds | records | 1 | 0 | Native records/view |
| LP Reports | records | 1 | 0 | Native records/view |
| Capital Calls | records | 1 | 0 | Native records/view |
| IC Memos | records | 1 | 0 | Native records/view |
| Investments | records | 2 | 0 | Native records/view |
| Follow-Ons | records | 1 | 0 | Native records/view |
| Portfolio Metrics | records | 1 | 0 | Native records/view |
| Board Meetings | records | 1 | 0 | Native records/view |
| Exits | records | 1 | 0 | Native records/view |
| AI · IC Memo Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Founder Call Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Comp Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Valuation Band | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · LP Report Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Exit Scenario | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Portfolio Flag | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Follow-On Recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Term Sheet Compare | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Intro Message Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Market Mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Founder Red-Flag Extract | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Cap Table Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Distribution Waterfall | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Fund Strategy Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pitch deck extract | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dd qa generate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market size estimate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Founder background summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Thesis fit score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cap tables | records | 1 | 0 | Native records/view |
| Lp comms templates | records | 1 | 0 | Native records/view |
| Kpi ingest sources | records | 1 | 0 | Native records/view |
| Kpi ingest records | records | 1 | 0 | Native records/view |
| Data room documents | records | 1 | 0 | Native records/view |
| Diligence tasks | records | 1 | 0 | Native records/view |
| Lp contacts | records | 1 | 0 | Native records/view |
| Fundraising pipeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio updates | records | 1 | 0 | Native records/view |
| Fund expenses | records | 1 | 0 | Native records/view |
| Reserve plans | records | 1 | 0 | Native records/view |
| Collaboration comments | records | 1 | 0 | Native records/view |
| Access rules | records | 1 | 0 | Native records/view |
| Saved searches | records | 1 | 0 | Native records/view |
| Global search | records | 1 | 0 | Native records/view |
| Client Insights | records | 1 | 0 | Native records/view |
| Portfolio Analysis | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Transaction Insights | records | 1 | 0 | Native records/view |
| Asset Strategy | records | 1 | 0 | Native records/view |
| Watchlist Intel | records | 1 | 0 | Native records/view |
| Goal Planning | records | 2 | 0 | Native records/view |
| Alert Intelligence | records | 1 | 0 | Native records/view |
| Fee Optimization | records | 1 | 0 | Native records/view |
| Document Review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance Deep Dive | records | 1 | 0 | Native records/view |
| Risk Assessment | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Investment Recs | records | 1 | 0 | Native records/view |
| Market Sentiment | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Tax Optimization | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Retirement Planning | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Rebalancing | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| ESG Analysis | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Estate Planning | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Households | records | 1 | 0 | Native records/view |
| Portfolios | records | 2 | 0 | Native records/view |
| Model Portfolios | records | 1 | 0 | Native records/view |
| Transactions | records | 1 | 0 | Native records/view |
| Asset Classes | records | 1 | 0 | Native records/view |
| Custodian Accounts | records | 1 | 0 | Native records/view |
| Watchlist | records | 2 | 0 | Native records/view |
| Financial Goals | records | 1 | 0 | Native records/view |
| Cash Flow Plans | records | 1 | 0 | Native records/view |
| Insurance Plans | records | 1 | 0 | Native records/view |
| Alerts | records | 2 | 0 | Native records/view |
| Fee Management | records | 1 | 0 | Native records/view |
| Performance | records | 2 | 0 | Native records/view |
| Investment Policies | records | 1 | 0 | Native records/view |
| Trust Beneficiaries | records | 1 | 0 | Native records/view |
| Meeting Notes | records | 1 | 0 | Native records/view |
| Advisor Tasks | records | 1 | 0 | Native records/view |
| Compliance Reviews | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax Packages | records | 1 | 0 | Native records/view |
| Client Messages | records | 1 | 0 | Native records/view |
| Invest Recs | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Churn Prediction | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Behavioral Coach | records | 2 | 0 | Native records/view |
| AI Goal Planning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi generational wealth planning with trust structure opti | records | 1 | 0 | Native records/view |
| Behavioral finance coaching track bias suggest interventions | records | 1 | 0 | Native records/view |
| Real time rebalancing via options strategies covered calls f | records | 1 | 0 | Native records/view |
| Predictive client churn modeling with retention ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Institutional research integration for etfstock filtering | integration | 1 | 0 | Provider request records only |
| White label co branding api | records | 1 | 0 | Native records/view |
| Voice advisory for natural language goal setting | records | 1 | 0 | Native records/view |
| Accountanttax preparer collaboration for end to end tax plan | records | 1 | 0 | Native records/view |
| Regulatory reporting form adv reg bi | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance audit trail and reviewer queue | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Beneficiary and trust account management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| External brokercustodian account aggregation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Granular notification preference center | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax form generation 1099 k 1 and downloads | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Client meeting notes crm integration | integration | 1 | 0 | Provider request records only |
| Multi gen wealth | records | 1 | 0 | Native records/view |
| Options rebalance | records | 1 | 0 | Native records/view |
| Inst research filter | records | 1 | 0 | Native records/view |
| White label | records | 1 | 0 | Native records/view |
| Voice goal | records | 1 | 0 | Native records/view |
| Tax collab | records | 1 | 0 | Native records/view |
| Market Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio Review | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Trade Idea | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Options Strategy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Politician Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trailing Stops | records | 1 | 0 | Native records/view |
| Copy Trading | records | 1 | 0 | Native records/view |
| Wheel Strategy | records | 1 | 0 | Native records/view |
| Trade Journal | records | 1 | 0 | Native records/view |
| Price Alerts | records | 1 | 0 | Native records/view |
| Trade Signals | records | 1 | 0 | Native records/view |
| Stock Screener | records | 1 | 0 | Native records/view |
| Risk Calculator | records | 2 | 0 | Native records/view |
| Sentiment | records | 1 | 0 | Native records/view |
| Options Chain | records | 1 | 0 | Native records/view |
| Market News | records | 1 | 0 | Native records/view |
| Docs | records | 1 | 0 | Native records/view |
| Signal charts | records | 1 | 0 | Native records/view |
| Alpaca trading | records | 1 | 0 | Native records/view |
| Broker governance | records | 1 | 0 | Native records/view |
| Auto trader | records | 1 | 0 | Native records/view |
| Strategy lab | records | 1 | 0 | Native records/view |
| Event calendar | records | 1 | 0 | Native records/view |
| Trade replay | records | 1 | 0 | Native records/view |
| Themes | records | 1 | 0 | Native records/view |
| Hyperopt | records | 1 | 0 | Native records/view |
| Strategy audit | records | 1 | 0 | Native records/view |
| Protections | records | 1 | 0 | Native records/view |
| Edge | records | 1 | 0 | Native records/view |
| Saved backtests | records | 1 | 0 | Native records/view |
| Strategy migrator | records | 1 | 0 | Native records/view |
| Freqai models | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exchanges | records | 1 | 0 | Native records/view |
| Plots | records | 1 | 0 | Native records/view |
| Producer consumer | records | 1 | 0 | Native records/view |
| Freqtrade api | records | 1 | 0 | Native records/view |
| Strategy editor | records | 1 | 0 | Native records/view |
| Leverage | records | 1 | 0 | Native records/view |
| Backtest analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Utilities | records | 1 | 0 | Native records/view |
| Hyperopt advanced | records | 1 | 0 | Native records/view |
| Orderflow | records | 1 | 0 | Native records/view |
| Rl lite | records | 1 | 0 | Native records/view |
| Freqai sidecar | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Strategy ab | records | 1 | 0 | Native records/view |
| Slippage attribution | records | 1 | 0 | Native records/view |
| Predictive equity curve drawdown recovery time | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Strategy correlation analysis to avoid redundancy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Walk forward analysis automation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trade journal nlp lesson extraction | records | 1 | 0 | Native records/view |
| Broker integration for live trading alpaca already partial | integration | 1 | 0 | Provider request records only |
| Real time strategy monitoring with anomaly alerts | records | 1 | 0 | Native records/view |
| Community strategy marketplace with performance filtering | records | 1 | 0 | Native records/view |
| Regulatory reporting automation | records | 1 | 0 | Native records/view |
| Walk forward curve fitting detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trade journal lesson extractor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax lot wash sale tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory compliance finra mifid reporting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi account allocation pmm style | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Strategy marketplace with monetization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Kycaml workflow for paid users | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equity curve forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Strategy correlation | records | 1 | 0 | Native records/view |
| Walk forward | records | 1 | 0 | Native records/view |
| Trade journal lessons | records | 1 | 0 | Native records/view |
| Broker readiness | records | 1 | 0 | Native records/view |
| Realtime monitor | records | 1 | 0 | Native records/view |
| Marketplace rank | records | 1 | 0 | Native records/view |
| Regulatory report | records | 1 | 0 | Native records/view |
| Investment work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partners | records | 1 | 0 | Native records/view |
| Meetings | records | 1 | 0 | Native records/view |
| Proposals | records | 1 | 0 | Native records/view |
| Orders | records | 1 | 0 | Native records/view |
| Pipeline | records | 1 | 0 | Native records/view |
| Talent Pool | records | 1 | 0 | Native records/view |
| Candidates | records | 1 | 0 | Native records/view |
| Executive Search | records | 1 | 0 | Native records/view |
| Services | records | 2 | 0 | Native records/view |
| Payments | records | 1 | 0 | Native records/view |
| Revenue | records | 1 | 0 | Native records/view |
| KPIs | records | 1 | 0 | Native records/view |
| Strategy Plans | records | 1 | 0 | Native records/view |
| Case Studies | records | 1 | 0 | Native records/view |
| Insights | records | 2 | 0 | Native records/view |
| Strategy Advisor | records | 1 | 0 | Native records/view |
| Market Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Talent Matcher | records | 1 | 0 | Native records/view |
| Report Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proposal Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investment Thesis | records | 1 | 0 | Native records/view |
| Talent Brief | records | 1 | 0 | Native records/view |
| Proposal Writing | records | 1 | 0 | Native records/view |
| Due Diligence | records | 1 | 0 | Native records/view |
| Role Spec | records | 1 | 0 | Native records/view |
| Meeting Summarizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| KPI Anomaly | records | 1 | 0 | Native records/view |
| Deal-Stage Auto | records | 1 | 0 | Native records/view |
| Doc Management | records | 2 | 0 | Native records/view |
| Subscriptions | records | 2 | 0 | Native records/view |
| CRM Sync | records | 2 | 0 | Native records/view |
| Calendar Sync | integration | 2 | 0 | Provider request records only |
| Pipeline Tracker | records | 1 | 0 | Native records/view |
| Proposal Workflow | records | 1 | 0 | Native records/view |
| RAG Literature | records | 1 | 0 | Native records/view |
| Voice Strategy | records | 1 | 0 | Native records/view |
| Multi-Tenant | records | 1 | 0 | Native records/view |
| Value Delivery System | records | 1 | 0 | Native records/view |
| Industries | records | 1 | 0 | Native records/view |
| Markets | records | 1 | 0 | Native records/view |
| Partnerships | records | 1 | 0 | Native records/view |
| proposal writing assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| due diligence analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| role spec generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| kpi anomaly explainer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| deal stage automation | records | 1 | 0 | Native records/view |
| Join talent network | records | 1 | 0 | Native records/view |
| sentiment analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| correlation analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| alert optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| research summarizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| realtime websocket | records | 1 | 0 | Native records/view |
| options strategies | records | 1 | 0 | Native records/view |
| tax loss harvesting | records | 1 | 0 | Native records/view |
| paper trading sim | records | 1 | 0 | Native records/view |
| social trading | records | 1 | 0 | Native records/view |
| risk management rules | records | 1 | 0 | Native records/view |
| Paper trading | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 404 feature pages were visited in the browser; 402 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 200 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

200 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
