# The same owners sit on both sides of the climate problem

**Live site:** https://connoryqueen.github.io/Trading-the-climate-trade/

An interactive, fully sourced map of how companies and funds that produce, move or trade fossil fuels are tied — through ownership, investment, lobbying and trading — to businesses that measure, insure against or clean up after climate change. A second tab shows what the PACs of companies on the map gave current members of Congress, and how those members voted on ten named federal climate measures.

Every connection carries citations so anyone can check the work.

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
