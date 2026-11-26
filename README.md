# The same owners sit on both sides of the climate problem

**Live site:** https://connoryqueen.github.io/Trading-the-climate-trade/

An interactive, fully sourced map of how companies and funds that produce, move or trade fossil fuels are tied — through ownership, investment, lobbying and trading — to businesses that measure, insure against or clean up after climate change. A second tab shows what the PACs of companies on the map gave current members of Congress, and how those members voted on ten named federal climate measures.

Every connection carries citations so anyone can check the work.

## The question we started with

Can the same group of owners make money at every stage of the climate problem?

The idea we set out to test has three parts:

1. **Contribute to the problem.** Produce, move, burn or trade fossil fuels.
2. **Slow the fix.** Fund trade groups, lobbying and political campaigns that oppose climate rules, and back the politicians who vote against them.
3. **Profit from the consequences.** Own, invest in or work with the businesses that measure climate risk, sell weather and climate data, insure against disasters, rebuild after them, or trade on them.

The third step is the least obvious. Weather and climate data is valuable: whoever sees a cold snap, a hurricane or a drought coming first can trade on it in natural gas, power, crops and insurance markets. A company that helps create climate risk can also be well placed to measure it, sell that information, and trade against it.

None of this would be easy to see on purpose. The links run through private equity funds, sovereign wealth funds, venture arms, trade associations and trading desks, not through the company names people know. So we asked: **if you start at a fossil-fuel company and follow documented ownership, investment, membership and trading ties, how often do you end up at a business that profits from climate change itself?**

## What the dashboard shows

- **Climate map:** fossil-fuel industries on the far left, the owners, funds, lobbying groups and traders in the middle, and climate mitigation, adaptation, insurance and data businesses on the far right. A line appears only when a documented chain runs all the way from left to right, and every link cites its source. Click any company or line to see the evidence.
- **Political giving & votes:** what the PACs of companies on the map gave current members of Congress since 2021, and how those members voted on ten named federal climate measures. Money to members who voted the other way is shown too, so you can see the full picture rather than just one side.

**What it doesn't show:** a connection here means a documented business relationship, and a contribution means a legal, publicly reported donation. Neither one proves coordination, intent or wrongdoing. The map shows that the pieces exist and are tied together; whether that adds up to a strategy is for readers to judge.

## What's in this repo

| File | What it is |
|---|---|
| `index.html` | The whole site, self-contained (data is embedded). |
| `data/climate_map_connections.json` | Every entity and connection on the map, with citations, plus connections removed by the fact-check and why. |
| `data/policy_giving_votes.json` | Per-member PAC contributions (FEC), roll-call votes, and how each vote was scored. |
| `data/fec_spot_check.json` | Independent re-check of 20 random member–PAC totals against fec.gov. |

## Method, briefly

- **Map:** connections were researched from public filings, company reports and news coverage, then independently fact-checked against their sources. Only chains running all the way from a fossil-fuel company to a mitigation, adaptation or climate-data business are shown.
- **Money:** itemized PAC disbursements from FEC records (2021–22, 2023–24 and 2025–26 cycles), counting payments tied to a member's FEC candidate ID (principal campaign committee and joint fundraising committees). Leadership PACs, party committees and state candidates are not counted. The 2025–26 cycle is incomplete.
- **Votes:** official House and Senate roll calls. The page shows money to members on both sides of each vote.

A contribution or a connection is not evidence of wrongdoing; the page shows documented relationships and votes so readers can draw their own conclusions.

## Data as of

November 25, 2026. See the dated notes at the top of each tab on the site.

## Corrections

Found an error? Please [open an issue](https://github.com/ConnorYQueen/Trading-the-climate-trade/issues) with a link to the source. Corrections are logged in the commit history.
