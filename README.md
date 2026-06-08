# salesforce-servicenow-deal-to-support-map

Salesforce ServiceNow Deal To Support Map is a Kinetic Gain portfolio proof repo for **Salesforce, ServiceNow** across Revenue Operations.

It turns deal-to-support handoff, SLA readiness, contract exceptions, and post-sale ownership proof into a small board-readable intelligence packet: where risk is building, where money is leaking, what deserves investment, and what story leaders can tell with evidence.

## Platform and company signals

- Salesforce
- ServiceNow

## What it includes

- runnable Node CLI for summarizing synthetic control-plane lanes
- JSON fixture with exposure, savings, and investment lanes
- static proof page in site/index.html
- lightweight CI using Node's built-in test runner
- no production credentials, no customer data, no external API calls

## Local run

`powershell
npm test
npm run demo
npm run build
`

## Output shape

`json
{
  "product": "Salesforce ServiceNow Deal To Support Map",
  "signals": ["Salesforce", "ServiceNow"],
  "averageScore": 82,
  "priorityLane": "investment"
}
`

## Kinetic Gain fit

This repo supports the Platform and Company Signals layer of the portfolio atlas. It is intentionally small, readable, and evidence-oriented so executives can see the operating pattern without requiring access to live enterprise systems.