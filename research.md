# Research — Ground News (a Claim Checker audit, told as a story)

## Scope (step 1)

- **Subject:** Ground News (Snapwise Inc.), the Kitchener, Ontario news-comparison platform — kind: company.
- **Angle:** A transparency product whose own transparency claims are its weakest surface. A Claim Checker audit captured Ground's claims verbatim from its own pages, tested each against independent sources, and was then itself checked by two validators who did not generate it. This story lets a reader *see* that structure: the promise, the method, the places where the site argues with itself (modelled standing side by side, never resolved), the money, the company's dates, and the audit — ending on the questions the audit leaves open.
- **Audience/use:** Readers of Claim Checker / TeamBotics work; an explorable, shareable summary of the Ground News audit. Not published (playbook step 6 not asked, not done); built locally only.
- **Boundaries:** The audit record of 13 November 2026 is the boundary. Claims are Ground's as captured that day. Verdict language is Claim Checker's five verdicts, as corrected by the validator errata (the errata supersedes the original ledger). Round 2 questions are modelled as open questions, not findings. Inferences are labelled `inferred` — in particular, nothing in this story asserts that Joe Ricketts funds Ground News: the board fact is a node, the funding inference is explicitly not made.
- **Affiliation:** Independent study. Not affiliated with or endorsed by Ground News / Snapwise Inc. Credit and disclaimer in `story.json` say so.
- **Research base:** This story was built from the completed, validated Claim Checker audit record, read in full on 2026-11-13 (same day as the audit — the record is fresh, not re-crawled):
  - `GROUND-NEWS-AUDIT-2026-11-13.md` (in this repository) — 16 atoms, seven tests, contradiction pass, and the validator errata (which supersedes: corrected tally Confirmed 3 / Partially corroborated 4 / Self-reported only 4 / Unverifiable by design 2 / Contradicted 3; corrected verdicts for GN-06, GN-10, GN-14, GN-16).
  - `independent-evidence-ledger.md` (in this repository) — the independent-sources line (ground.news not visited by that line).
  - `VALIDATOR-A-FILING-GN01-08.md`, `VALIDATOR-B-FILING-GN09-16.md` (in this repository) — both "Cleared with exceptions."
  - `ROUND-2-NEXT-QUESTIONS.md` (in this repository) — 15 questions, 5 threads.
  Every node cites the **original source URL** recorded in that record (Ground's own pages, the raters' own sites, CJR, Corporations Canada, the funding databases, PLOS ONE, Tubefilter/Gospel Stats, UWaterloo, and the rest), not the audit file. The audit itself appears as one source (`cc-record`) for the audit-cluster nodes — the tally, the validator pass, the corrections — which are facts about the audit, with the Claim Checker repo as the product's home; the full audit document is published in this repository, beside this story. Brand evidence was probed live today with `scripts/brand-probe.mjs` (see `theme.json` brandSources).

All sources below were read by the audit team on **2026-11-13** (live browser capture of ground.news; independent lines via search and page reads) unless noted; tiers per playbook step 2. Facts are lifted from the audit record precisely; numbers and short quotes are copied as the record copies them.

## Source log

### gn-home — Ground News homepage (tier 1)
- https://ground.news/ · Ground News · accessed 2026-11-13
- Slogan: "See every side of every news story."
- Hero link: "10,000+ 5-star reviews" (captured live; cf. reviews-53k).

### gn-about — Ground News, About (tier 1)
- https://ground.news/about · Ground News
- "Every day we process nearly 60,000 news articles from over 50,000 different news sources."
- "break free from algorithms" (platform definition); mission: "well inform the world."
- "Harleen Kaur and Sukh Singh, siblings … founded the company in 2017 out of the University of Waterloo's Velocity incubator."
- Kaur: "started her career at NASA where she worked on the Pluto-bound spacecraft New Horizons."
- Singh: IBM/KPMG, then Bain & Company, then his own company Watchful; BA Waterloo, master's Oxford (Decision Science).
- Investors, softer form: "raised funding from investors who value our mission, but maintain complete editorial control."

### gn-mission — Ground News, Mission (tier 1)
- https://ground.news/mission · Ground News
- "Ground News has no ideology, it is non-partisan and holds no agenda other than serving your curiosity."
- "We are not funded by a media company, big tech or institutional investors. We are supported by our subscribers and a small group of individual investors."
- Principle: "Subscription not Ads… We prefer to make our money by selling solutions to our users instead of selling users to advertisers."
- "We offer a premium subscription for as low as 83 cents a month."
- "Ground News isn't a fact-checker, because we believe in empowerment, not enablement."
- "The world's first Information Utility."

### gn-rating — Ground News, Rating System / methodology (tier 1)
- https://ground.news/rating-system · Ground News
- "Our Bias rating averages the following 3 independent news monitoring organizations: AllSides, Ad Fontes Media, and Media Bias Fact Check."
- "The Factuality rating averages the following 2 trusted rating systems: Ad Fontes Media and Media Bias Fact Check."
- "Scores apply to each publication as a whole, not to their individual articles."
- Blindspot definition: a story with political undertones "disproportionately covered by media sources on one side of the political spectrum"; a qualifying formula is published for a Blindspot for the Left only (fewer than 10 Left-leaning sources; Right coverage ≥ 33%; a proportional condition; ≤ 35% Low-factuality coverage) — formula specifics are generator-capture only per the validators.
- "The ownership categories were created by Ground News. We researched, analyzed and hand-coded ownership data for 2,276 news outlets and counting."
- Some sources carry no bias rating and "are not represented in the Bias Bar."

### gn-faq — Ground News, FAQ (tier 1)
- https://ground.news/frequently-asked-questions · Ground News
- "Bias and factuality ratings are averaged from the published ratings from three third-party independent news publication monitoring organizations, when available: AllSides, Ad Fontes Media, and Media Bias Fact Check."
- "The My Feed tab offers a personalized collection of stories which is algorithmically curated based on stated and observed reading behaviors…"
- "Ground has no political agenda." "The Ground team takes no part in evaluating a Bias or Factuality Rating."

### gn-subscribe — Ground News, Subscribe (tier 1)
- https://ground.news/subscribe · Ground News
- "We don't use algorithms to shape what you see. You choose the stories."
- Lists "Personalized story recommendations" as a feature; shows "53,000+ 5-star reviews" (generator-capture only per Validator B).
- The Vantage price captured that day ($10.42/month billed annually) is **flagged unverified** by the validator errata — three independent readings give $8.33/month, $99.99/year. This story therefore makes no price-ratio claim.

### gn-history — Ground News, History 2018 (tier 1)
- https://ground.news/history/2018 · Ground News
- "04/27 /2018 — Ground News Launch."

### gn-blindspot — Ground News, Blindspot feed (tier 1)
- https://ground.news/blindspot · Ground News
- "Stories disproportionately covered by one side of the political spectrum."

### allsides — AllSides, Media Bias Chart / FAQ (tier 1, the rater on itself)
- https://www.allsides.com/media-bias/media-bias-chart
- "We don't rate accuracy or credibility, because we're not a Ministry of Truth." FAQ: "AllSides does not rate outlets based on accuracy. We rate perspective only."
- AllSides also publishes a numeric Media Bias Meter, −6 to +6 (validator correction to the audit's "categorical" shorthand).

### adfontes — Ad Fontes Media, Methodology (tier 1)
- https://adfontesmedia.com/methodology/
- Rates reliability (0–64) and bias (−42 to +42); analysts score individual articles/episodes and aggregate to source level. Its axis is named "reliability," not "factuality."

### mbfc — Media Bias/Fact Check, Methodology (tier 1)
- https://mediabiasfactcheck.com/methodology/
- Rates bias (−10 to +10, U.S.-centric) and Factual Reporting (Very High to Very Low).

### cjr — Columbia Journalism Review, "The Business of Balance" (tier 2)
- https://www.cjr.org/analysis/the-business-of-balance-ground-news.php · Sep 2025
- Confirms factuality scores come from Ad Fontes + MBFC.
- On record: AllSides COO/CFO — Ground uses AllSides ratings without "formal permission" and without compensation; MBFC founder — no agreement; Ad Fontes CEO — Ground pays Ad Fontes. Ground's reply: it does not disclose ongoing business relationships and arrangements (restored by validator errata).
- Similarweb: just under 8 million visits, July 2025. Criticises factuality ratings being paywalled.

### corp-canada — Corporations Canada / ISED, Snapwise Inc. (tier 1, registry)
- https://ised-isde.canada.ca/cc/lgcy/fdrlCrpDtls.html?corpId=8835004
- Snapwise Inc., Corp. No. 883500-4, Canada Business Corporations Act, incorporated 2014-03-26, active, Kitchener ON; directors include Harleen Kaur Jolly and Sukhsagar Singh Jolly; Manuel Mattke is also listed in the corporate record (registry mirrors).

### pitchbook — PitchBook, Ground News profile (tier 3, database)
- https://pitchbook.com/profiles/company/340782-22
- "Ground News has raised $1.01M"; 10 investors; deal list includes a Later Stage VC dated 15-May-2025 (amount undisclosed; Velocity, per Silverwood's transactions review as recorded in the audit).

### cbinsights — CB Insights, Ground News (tier 3, database)
- https://www.cbinsights.com/company/ground-1
- Total $340K; investors include Techstars Ventures, Right Side Capital Management, Something Good Ventures — and a "Digital News Innovation Challenge" listing (the DNIC lead).

### tracxn — Tracxn, Ground News (tier 3, database)
- https://tracxn.com/d/companies/ground/__HoPNp-FNqJJq2NTYGg_UHbTM6GR6Tkb5t6pxCWGlAmo
- Total $20K from Techstars, 1 round. (BounceWatch's $170K figure is recorded in the audit; three databases plus PitchBook span $20K–$1.01M.)

### rightside — Right Side Capital Management, By the Numbers (tier 1, the investor on itself)
- https://www.rightsidecapital.com/by-the-numbers
- "frequently the first institutional investor" (a founder has ever had).

### uw-velocity — University of Waterloo, Velocity Fund II release (tier 1/2)
- https://uwaterloo.ca/news/media/velocity-fund-ii-closes-financing-round
- The fund "aims to be the first institutional investor in promising early-stage startups" and names Ground News among companies that "have benefited from its investments." (Surfaced by Validator B; stronger than anything the original audit cited.)

### uw-2017 — University of Waterloo, "Combatting misinformation" (tier 2)
- http://uwaterloo.ca/news/combatting-misinformation
- "In 2017, the brother-sister team launched Ground News." (Non-contemporary, almost certainly founder-sourced — grouped as Ground-derived in the audit; cited here because it is the strongest third-party repetition of 2017.)

### play-store — Google Play, Ground News (tier 1, store record)
- https://play.google.com/store/apps/details?id=com.checkitt
- Developer: "Snapwise Inc.(dba Ground News)"; installs bracket 1,000,000+; rating ~4.55 from ~33K ratings; the listing copy carries "Ground News is the largest news aggregator in the world…" (validator upgrade: the superlative is in the primary listing, not only mirrors). Play's histogram: 78% of 33,353 ratings are five stars.

### apple-store — Apple App Store, Ground News (tier 1, store record)
- https://apps.apple.com/us/app/ground-news/id1324203419
- Seller Snapwise Inc.; 4.7 out of 5, 49K ratings (US). In-app purchases still list "Ground News Pro Monthly $0.99 / Pro Yearly $9.99" (Oct 2026 version) — the 83¢ tier is live, not legacy (Validator B).

### plosone — Bram, PLOS ONE (2024) (tier 2, peer-reviewed)
- https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0297808
- Experiment with >1,200 subscribers of the weekly Blindspot **Report newsletter** (not the in-app feed — errata correction): 3 of 4 stories did not change minds; 1 (Cuban refugees) reduced polarization in context. Author's conclusion: highlighting cross-partisan coverage "can, in certain contexts, reduce polarization" — the approach is "promising." Disclosure: the author worked with Ground News to implement the experiment (no compensation).

### tubefilter — Tubefilter on Gospel Stats' YouTube Sponsorship Landscape Report (tier 2 reporting of tier-1 data)
- https://www.tubefilter.com/2025/10/22/gospel-stats-youtube-sponsorship-landscape-report/
- H1 2025: Ground News #1 by integrations (1,863, +202% YoY) and #1 by views (664M). Sample: 65,759 sponsored videos, English-language channels, videos ≥25,000 views within 7 days. All other reports derive from this same dataset — one source. (Gospel Stats' own later release says 1,862 — its discrepancy, not Ground's; errata.)

### malone — Malone News, "Ground News and the Factuality Scam" (tier 3/4, advocacy critique)
- https://www.malone.news/p/ground-news-and-the-factuality-scam · 22 Aug 2026
- Argues the publication-level "Factuality" label is displayed beside individual stories as if the article were fact-checked. Recorded in the audit as a critic's claim — the audit did not verify the in-product presentation. Its statistics are preliminary and unaudited; this story cites it only for the existence and shape of the criticism.

### carleton — Guida, Facts & Frictions (Carleton University journal), Fall 2021 (tier 2, peer-reviewed)
- https://ojs.library.carleton.ca/index.php/ff/issue/download/331/173
- Documents Ground's participation in the Digital News Innovation Challenge (a Canadian programme partnered with the Facebook Journalism Project), recording "$100,000 in funding and the Facebook ad [credits]" in connection with that participation, from Kaur's own account. An unresolved lead — not an equity investment, and this story models it as open.

### story-exchange — The Story Exchange, profile of Harleen Kaur (tier 2)
- https://thestoryexchange.org/woman-reaching-startup-stars/ · 10 Jan 2017
- Earliest detailed link in the NASA chain: Ryerson aerospace 2004; "she secured an internship at NASA, which turned into a job supporting the New Horizons mission." The profile is about the predecessor company uCiC and predates Ground News; Kaur is the interview subject — the chain traces to her.

### mediavillage — MediaVillage, Kaur interview (tier 2)
- https://www.mediavillage.com/article/ground-news-founder-harleen-kaur-on-addressing-media-bias/amp/ · 18 Feb 2020
- "on January 15, she launched Ground News" — the Pro / current-platform launch, 15 January 2020.

### producthunt — Product Hunt, Ground News Pro launch post (tier 1, claimant)
- https://www.producthunt.com/p/ground-news-from-the-source/ground-news-pro · Jan 2020
- Ground's own launch post gave 40,000 media outlets and ~30,000 stories a day — the baseline for the scale figures' later growth to 50,000 / ~60,000 (growth-plausible drift, per Validator A; Editor & Publisher was already reporting 50,000+ by April 2020).

### trustpilot — Trustpilot, Ground News company profile (tier 3; Ground-authored description)
- https://nz.trustpilot.com/review/ground.news
- Ground's own company description reads "over 10,000 5-star reviews in the App Store and Play Store" — independent corroboration that the 10,000+ figure is Ground-authored text. Ground staff also reply substantively to reviewers here, including on ratings methodology (errata, accountability fairness).

### opportunity-ed — Opportunity Education, About (tier 1, the organisation on itself)
- https://opportunityeducation.org/us/about/
- Lists Manuel Mattke as President and COO, under founder Joe Ricketts.

### literatemachine — Literate Machine, "Is Ground News a Right-Wing Psy-Op?" (tier 3/4, essay — used only for documented ties)
- https://literatemachine.com/2026/08/16/is-ground-news-a-right-wing-psy-op/
- Records: Mattke is an advisory-board member of Ricketts-owned Straight Arrow News; Straight Arrow "operates in partnership with Ground News for some of its news output." Used for those two checkable ties only, not for the essay's argument. No evidence anywhere in the record that Ricketts funds Ground News.

### cc-standard — The Claim Checker Standard (tier 1, the method)
- https://github.com/nickhilster/claim-checker/blob/main/docs/STANDARD.md
- Five verdicts (Confirmed / Partially corroborated / Self-reported only / Unverifiable by design / Contradicted); seven tests; evidence rules — claims captured verbatim before analysis, inferences labelled, contradiction pass mandatory, audits never overwritten (corrections append as errata); generator ≠ validator is structural in the go-public gate.

### cc-record — Claim Checker audit of Ground News (the audit itself)
- https://github.com/nickhilster/claim-checker · Claim Checker / TeamBotics · 13 Nov 2026
- The audit document (16 atoms, seven tests, contradiction pass, validator errata) is published in full in this repository, beside this story; the method's home is the Claim Checker repository. Cited only for audit-cluster facts (tally, validator dispositions, Round 2 questions) — every subject claim in this story cites its original source above.

## Conflicts and gaps (named, per playbook)

- **Factuality, 2 vs 3:** Ground's Rating System page (2 raters) vs its FAQ and Subscribe FAQ (3, including AllSides). Modelled as standing nodes, not resolved — though AllSides' own scope statement is also a node, and readers can see which side it supports.
- **Algorithms:** Subscribe's blanket denial vs the FAQ's algorithmic My Feed. Standing pair.
- **Reviews:** 10,000+ vs 53,000+ are both floors ("+"), so they do not contradict; the corrected verdict is Partially corroborated. Standing pair, with the logic shown.
- **Price:** the Subscribe Vantage price is contested ($10.42 captured vs $8.33 attested). This story makes **no** price claim beyond the confirmed live Pro tier ($9.99/yr, App Store).
- **Captures only one agent could reach:** the 53,000+ figure, the Blindspot formula specifics, the "no Right formula" negative, and the "largest is not on the website" absence — all flagged in the audit's validation status and hedged in the nodes that use them.
- **Not covered:** Ground's privacy practices (a Round 2 question), the in-product placement of the Factuality label (Round 2 Q7), Blindspot symmetry in practice (Q8), any revenue or subscriber counts (not public), and DNIC's full terms (Q1). These appear, if at all, as open-question nodes.
