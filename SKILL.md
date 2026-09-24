# TT Rubber Scout

Reusable research workflow for finding table-tennis rubber alternatives using multilingual evidence, recursive candidate discovery, blade-specific fit, price, durability, and long-term cost.

## Inputs
- Reference rubber
- Blade
- Side: FH or BH
- Budget
- Tackiness preference
- Booster allowed: yes/no
- Purchase region

## Core Principle: Review → Discover → Verify → Expand
Research must not stop after the first shortlist. User reviews are also candidate-discovery data.

Whenever a review compares the target or a candidate with another rubber, record that comparison rubber as a **second-order candidate**. Validate it against the user's hard constraints, then research it through the same multilingual review workflow. Repeat until additional rounds stop producing credible new candidates.

This prevents the search from being limited by the initial candidate list and allows strong alternatives to emerge organically from real-user comparisons.

## Research Workflow

### Phase 1 — Reference Profile
1. Analyze the reference rubber: speed, spin, hardness feel, tackiness, catapult, throw, dwell, short game, opening vs backspin, block, counter, weight, durability.
2. Separate manufacturer specifications from real-user behavior.
3. Define hard filters before discovery: price ceiling, tackiness, booster requirement, blade, side, purchase region.

### Phase 2 — First-Order Candidate Discovery
4. Discover candidates broadly. Do not lock onto prior candidates, familiar brands, or previously recommended rubbers.
5. Search using English, Japanese, Chinese, and when useful European-language terms.
6. Prefer recent evidence and exact rubber variants/hardnesses.
7. Reject candidates that clearly violate hard filters, but retain near-misses in a separate reference list if they are useful comparison anchors.

### Phase 3 — Multiregional Review Investigation
For every surviving candidate, actively investigate user reviews from:
- YouTube reviews and comparison videos
- Reddit / r/tabletennis
- English/European forums such as TableTennisDaily and other specialist communities
- Chinese sources: Bilibili, 乒乓网, 精英乒乓, 知乎, 小红书, specialist blogs/forums
- Japanese sources: 卓球ナビ, 卓球グッズWEB, WRM-TV, わった, note/blogs, Japanese YouTube and forums
- Other European user communities/review sites when relevant

For each source, extract actual observations rather than merely counting recommendations:
- blade used
- FH/BH
- player level/style when stated
- comparison rubber(s)
- speed
- spin/grip
- catapult
- throw/arc
- hardness/feel
- dwell
- serve/receive and short game
- opening against backspin
- counterloop
- passive/active block
- smash/flat hit
- weight
- durability
- QC/batch variation
- booster status
- price/value

### Phase 4 — Comparison-Rubber Expansion
8. While reading/watching reviews, maintain a **Comparison Candidate Graph**:
   - Reference rubber → first-order candidate
   - Candidate → every rubber reviewers directly compare with it
   - Record why it was compared: similar feel, harder/softer, faster/slower, more spin, better value, same use case, etc.
9. Promote newly discovered comparison rubbers to **second-order candidates** when they plausibly satisfy the hard filters.
10. Do not promote a rubber merely because its name appears. Require a meaningful performance comparison or recommendation.

### Phase 5 — Second-Order Verification
11. Research each promoted second-order candidate independently using the same multilingual source set.
12. Search same-blade + same-side evidence. For Viscaria use aliases: Viscaria / VIS / ビスカリア / 蝴蝶王.
13. Search direct comparisons against:
   - the original reference rubber
   - the first-order candidate that revealed it
   - other high-confidence candidates
14. Record contradictions. Do not average away meaningful disagreements; explain likely causes such as hardness variant, blade, booster, technique, batch/QC, or player level.

### Phase 6 — Recursive Expansion
15. Reviews of second-order candidates may reveal third-order candidates. Repeat the discovery/verification cycle.
16. Continue expansion until a saturation condition is reached:
   - a full round produces no credible new in-budget candidates, or
   - new candidates are clearly weaker/duplicative, or
   - evidence quality falls to D with no independent corroboration.
17. Normally perform at least **two discovery-validation rounds** when enough evidence exists.

## Evidence Hierarchy
Separate:
1. Manufacturer claims/specifications
2. Instrumented measurements
3. Same-blade + same-side direct user reports
4. Direct comparison reviews
5. Multi-user/community consensus
6. Single-user anecdote
7. Unverified seller/marketing claims

Evidence grade:
- A: multiple direct reports on same blade and same side, preferably across independent regions/sources
- B: same/similar blade plus multi-country agreement or several strong direct comparisons
- C: strong general rubber evidence but limited blade-specific data
- D: sparse evidence, unresolved contradictions, QC/counterfeit concerns, or mostly indirect claims

## Regional Consensus Rule
Do not treat ten copied opinions from one community as stronger than independent evidence.

Where possible, identify:
- Global/English consensus
- Chinese-user consensus
- Japanese-user consensus
- European-user consensus
- YouTube reviewer observations

Explicitly flag when regions disagree.

## Comparison Rules
Compare:
- speed
- spin/grip
- catapult
- throw/arc
- hardness feel
- dwell
- short game
- serve/receive
- opening vs backspin
- counterloop
- passive/active block
- smash/flat hit
- weight
- booster need
- durability
- QC
- price/value

Do not equate Chinese sponge degrees directly with ESN degrees.

## Cost Normalization
Calculate:
- real purchase price
- expected replacement cycle
- annual cost
- cost per playing hour

Always show assumptions. A cheaper sheet is not better value if it degrades much faster.

## Required Research Output
The report should include:
- Reference-rubber profile
- First-order shortlist
- Candidate discovery graph: which review led to which new candidate
- Second/third-order candidates discovered from reviews
- Multiregional review findings
- Same-blade/same-side evidence
- Contradictions and uncertainty
- Expanded comparison matrix
- Evidence grade
- Price/lifetime analysis
- Rejected candidates and explicit reasons
- Saturation note explaining why candidate expansion stopped

Final recommendation buckets:
- Closest replacement
- Best value
- Best performance
- Easiest transition
- Alternative playing style
- Experimental/dark-horse candidate


## Market Price, Lifespan, and Savings Analysis
Every final candidate report must include a current-market cost comparison between the reference rubber and each replacement candidate.

### Price Collection Rules
For the reference rubber and every finalist:
1. Record the research date.
2. Collect **current real street price**, not only MSRP/list price.
3. For Korea, prefer current Korean price-comparison sites and reputable table-tennis retailers. Record official MSRP separately when available.
4. For AliExpress/overseas candidates, record the realistic delivered purchase price when possible. Separate item price, shipping, coupon/discount assumptions, tax/duty if relevant, and currency conversion assumptions.
5. Use multiple current sellers/sources when possible. Report a range and a representative price (prefer median/typical street price over a temporary extreme low).
6. Flag temporary coupons, member/card-only prices, suspicious listings, counterfeit risk, and stale prices.
7. Never compare the reference rubber's MSRP against a candidate's discounted street price without clearly labeling the mismatch.

### Lifespan Estimation
For each rubber, estimate practical performance lifespan from user reviews, not merely physical survival:
- months of acceptable competitive performance
- playing hours when evidence allows
- frequency assumptions (sessions/week and hours/session)
- whether FH and BH lifespan may differ
- loss mode: grip loss, sponge softening, shrinkage, edge damage, bubbling, QC failure, etc.

Give lifespan as a range when evidence is uncertain, e.g. 4–6 months. Attach an evidence/confidence grade.

### Annual Cost Model
Calculate independently per side when FH/BH use different rubbers.

Definitions:
- replacements_per_year = 12 / lifespan_months
- annual_cost = representative_street_price × replacements_per_year
- annual_savings = reference_annual_cost − candidate_annual_cost
- savings_rate = annual_savings / reference_annual_cost × 100
- cost_per_playing_hour = annual_cost / estimated_annual_playing_hours

For lifespan ranges, calculate conservative / midpoint / optimistic scenarios rather than hiding uncertainty behind one number.

### Multi-Year Savings
Show at minimum:
- 1-year cost and savings
- 3-year cost and savings

When useful, also show 5-year projections, but do not imply prices will remain unchanged. Label multi-year numbers as constant-price projections.

### Required Cost Table
Every final report must include a table with:
- Rubber / configuration
- Side
- Current street-price range
- Representative price
- Official MSRP when available
- Estimated lifespan
- Replacements/year
- Annual cost
- Annual savings vs reference
- Savings %
- 3-year projected savings
- Cost/hour when playing-time assumptions are available
- Price date
- Cost-confidence grade

### Reporting Rules
Distinguish three questions:
1. **Cheapest sheet price**
2. **Lowest annual ownership cost**
3. **Best performance-per-cost**

Do not automatically recommend the cheapest sheet. A candidate that costs less initially but wears twice as fast may save little or nothing annually.

The final web report in `docs/` must include a dedicated **Price · Lifespan · Annual Savings** section containing:
- current reference-rubber market price
- each finalist's current market price
- lifespan evidence/range
- annual replacement-cost comparison
- annual savings in KRW and percentage
- 3-year constant-price projection
- assumptions and price-research date
- citations/source links for price and lifespan evidence

Whenever a new research report is generated, update the web report with the latest price/cost analysis rather than leaving historical prices unlabeled.

## Source Priority
See references/sources.md.

## Search Patterns
See references/search-patterns.md.

## Scoring
See references/scoring.md.

## Report Format
See references/report-template.md.
