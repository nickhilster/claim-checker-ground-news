# Claim Checker Audit — Ground News

**Subject:** Ground News (Snapwise Inc.), ground.news
**Date of audit:** 13 November 2026 — all Ground News pages accessed live on this date
**Method:** [The Claim Checker Standard](https://github.com/nickhilster/claim-checker/blob/main/docs/STANDARD.md) — claims captured verbatim from the claimant before analysis; sources grouped by independence; every material thesis given a contradiction pass; verdicts limited to the Standard's five: Confirmed / Partially corroborated / Self-reported only / Unverifiable by design / Contradicted.
**Status:** Internal audit. Not published, not pushed to the claim-checker repo. The repo's go-public gate and hold are unchanged by this run.

---

## Summary

Ground News is a real, operating company with a real product — its legal entity, app-store scale bracket, bias-rating structure, and Blindspot feature all check out at the level it claims them. That is not where it fails.

It fails on its own pages, against its own pages:

1. **Its FAQ misstates its core methodology.** The Rating System page correctly says factuality is averaged from **2** systems, but the FAQ and the Subscribe FAQ say bias *and factuality* are averaged from **3** organisations including AllSides — and [AllSides states on its own site that it does not rate accuracy at all](https://www.allsides.com/media-bias/media-bias-chart).
2. **Its sales page denies the algorithm its FAQ describes.** The Subscribe page says "We don't use algorithms to shape what you see," while the FAQ says the My Feed tab "is algorithmically curated based on stated and observed reading behaviors."
3. **Its independence claim is contradicted by the investor record.** "Not funded by … institutional investors" / "a small group of individual investors" sits against named venture funds in multiple independent databases.
4. **Its two review counts disagree with each other on the same day** — 10,000+ 5-star reviews on the homepage, 53,000+ on the Subscribe page.
5. **Everything else headline-sized — 50,000 sources, nearly 60,000 articles a day, the NASA founding story, the founding year itself — is self-reported only**, repeated by dozens of outlets that all trace back to Ground News as their single source.

---

## Claim ledger

### GN-01 — Scale: "nearly 60,000 articles / over 50,000 sources"

- **Verbatim:** "Every day we process nearly 60,000 news articles from over 50,000 different news sources." — [About](https://ground.news/about)
- **Also:** "directly from over 50,000 major news publications … from around the world" — [FAQ](https://ground.news/frequently-asked-questions)
- **Test (Counter):** No independent audit, registry, or third-party measurement of source count or daily ingest was found. Every repetition of these figures in press, reviews, job listings and app-store copy traces to Ground News itself — under the Standard's press-laundering rule that is **one source, not corroboration**. The figures have also drifted over time in Ground-derived retellings (40,000 sources / ~30,000 articles a day in earlier coverage; 50,000 / ~60,000 now) with no dated changelog from the company.
- **Verdict: Self-reported only**

### GN-02 — "Largest news aggregator in the world"

- **Verbatim:** This claim does **not** appear on the ground.news pages visited (Homepage, About, Mission, Rating System, FAQ, Blindspot, Subscribe — searched). It appears in Ground News's own app-store listing copy, as reproduced by app-store mirrors: ["Ground News is the largest news aggregator in the world with over 50K news sources and 60K articles added daily."](https://apps.appfollow.io/ios/ground-news/1324203419?country=nl)
- **Test:** No independent ranking of news aggregators by source count was found that places Ground News first. The superlative rests entirely on GN-01's self-reported numbers.
- **Verdict: Self-reported only** — and notably, a superlative the company keeps off its own website

### GN-03 — Bias rating: averaged from 3 independent monitors

- **Verbatim:** "Our Bias rating averages the following 3 independent news monitoring organizations: AllSides, Ad Fontes Media, and Media Bias Fact Check." — [Rating System](https://ground.news/rating-system)
- **Verbatim:** "This rating does not measure the bias of specific news articles. The analysis is done at the publication level."
- **Test:** All three named organisations do rate publication-level bias on their own sites — [AllSides](https://www.allsides.com/media-bias/media-bias-chart), [Ad Fontes Media](https://adfontesmedia.com/methodology/), [Media Bias/Fact Check](https://mediabiasfactcheck.com/methodology/). The structure of the claim is accurate. Two limits: (a) the three scales are incommensurable in form (Ad Fontes −42 to +42; MBFC −10 to +10; AllSides categorical), and Ground publishes no mapping or formula for its "composite … determined by the relative position of each organization's rating" — the averaging cannot be re-run by a reader; (b) Ground also states "We also include an AI-driven bias rating," without stating how that AI rating enters the composite.
- **Verdict: Partially corroborated** — structure confirmed, computation unverifiable

### GN-04 — Factuality rating: averaged from 2 systems (Rating System page)

- **Verbatim:** "The Factuality rating averages the following 2 trusted rating systems: Ad Fontes Media and Media Bias Fact Check." — [Rating System](https://ground.news/rating-system)
- **Verbatim:** "Scores apply to each publication as a whole, not to their individual articles."
- **Test:** Consistent with the raters' own scopes: Ad Fontes rates reliability and bias; MBFC rates factual reporting and bias. The [Columbia Journalism Review's account](https://www.cjr.org/analysis/the-business-of-balance-ground-news.php) independently confirms factuality comes from these two.
- **Verdict: Confirmed** — as stated on this page. See GN-05 for the same claim stated differently elsewhere on the same site.

### GN-05 — Factuality rating: averaged from 3 organisations (FAQ / Subscribe FAQ)

- **Verbatim:** "Bias and factuality ratings are averaged from the published ratings from three third-party independent news publication monitoring organizations, when available: AllSides, Ad Fontes Media, and Media Bias Fact Check." — [FAQ](https://ground.news/frequently-asked-questions); the same formulation appears in the Subscribe page FAQ at [Subscribe](https://ground.news/subscribe)
- **Test:** [AllSides](https://www.allsides.com/media-bias/media-bias-chart) states it does not rate accuracy or credibility — it rates perspective only. A factuality average cannot include a rater that produces no factuality rating. The FAQ formulation also contradicts Ground's own Rating System page (GN-04).
- **Verdict: Contradicted** — by AllSides' own stated scope, and by Ground News's own methodology page

### GN-06 — "We don't use algorithms to shape what you see"

- **Verbatim:** "We don't use algorithms to shape what you see. You choose the stories. We show the full spectrum of coverage—left, center, and right—so you can decide for yourself what's worth believing." — [Subscribe](https://ground.news/subscribe)
- **Verbatim (same site):** "The My Feed tab offers a personalized collection of stories which is algorithmically curated based on stated and observed reading behaviors, the topics you follow, as well as the sources you've favorited." — [FAQ](https://ground.news/frequently-asked-questions)
- **Also:** The Subscribe page itself lists "Personalized story recommendations" as a feature, and the FAQ states an "unbiased editorial team picks stories" for Top Stories.
- **Test:** The narrower claim made elsewhere — freedom from *engagement-maximizing* algorithms ("break free from algorithms", [About](https://ground.news/about)) — is a positioning claim a reader cannot test. The blanket Subscribe formulation is directly contradicted by the company's own FAQ description of its product.
- **Verdict: Contradicted** (blanket form); the narrower "not engagement-maximizing" form is **Unverifiable by design**

### GN-07 — Founding: "founded the company in 2017"

- **Verbatim:** "Harleen Kaur and Sukh Singh, siblings … founded the company in 2017 out of the University of Waterloo's Velocity incubator." — [About](https://ground.news/about)
- **Verbatim (same site):** "04/27/2018 — Ground News Launch" — [History 2018](https://ground.news/history/2018)
- **Test (Drift):** The independent record supports a sequence, not a single year: Snapwise Inc. was federally incorporated on 26 March 2014 ([Corporations Canada, Corp. No. 883500-4](https://ised-isde.canada.ca/cc/lgcy/fdrlCrpDtls.html?corpId=8835004)); the USPTO trademark record gives first use of GROUND NEWS as 31 March 2018; the apps first released in April 2018; and contemporary coverage dates the launch of Ground News Pro / the current comparison platform to 15 January 2020. Outside retellings variously give 2014, 2017, 2018 and 2020 as the founding year. No contemporary 2017 product record was found — 2017 is the company's own account of its formation.
- **Verdict: Partially corroborated** — 2017 formation is self-reported; 2018 first public product and 2020 Pro launch are independently dated. The drift in secondary sources is real and uncorrected by the company

### GN-08 — Harleen Kaur: "started her career at NASA … New Horizons"

- **Verbatim:** "With a degree in aerospace engineering, Harleen started her career at NASA where she worked on the Pluto-bound spacecraft New Horizons." — [About](https://ground.news/about); FAQ shortens this to "Harleen Kaur (ex-NASA)".
- **Test:** No NASA, Johns Hopkins APL, or university primary record naming Kaur was found. The APL New Horizons team page does not list her — noted for completeness; a current roster would not be expected to list a 2005-era intern, so absence is not contradiction. Every biographical profile found repeats near-identical supplied wording tracing back to Kaur / Ground News. A LinkedIn scrape shows the NASA entry as a single month (Jan 2005 – Jan 2005), which sits awkwardly beside "started her career at NASA" — flagged as drift in the self-report, not as disproof.
- **Note:** The viral "first Sikh woman engineer at NASA" claim was **not** found attributed to Kaur by Ground News and belongs to a different person; it is not held against this subject.
- **Verdict: Self-reported only**

### GN-09 — Independence: "not funded by … institutional investors"

- **Verbatim:** "We are not funded by a media company, big tech or institutional investors. We are supported by our subscribers and a small group of individual investors who care about the problem personally." — [Mission](https://ground.news/mission)
- **Verbatim:** "Ground is backed by a handful of mission-aligned independent individual investors, with no ties to corporate media, big tech, or government affiliations." — [FAQ](https://ground.news/frequently-asked-questions)
- **Test:** Independent funding databases ([PitchBook](https://pitchbook.com/profiles/company/340782-22), [CB Insights](https://www.cbinsights.com/company/ground-1), [Crunchbase](https://www.crunchbase.com/organization/ground-news)) name venture and institutional-type investors including Techstars / Techstars Ventures, Right Side Capital Management — which [describes itself](https://www.rightsidecapital.com/by-the-numbers) as "frequently the first institutional investor" — Something Good Ventures, Velocity, and Blue Lagoon Capital. No media-company, big-tech, or government investor was found. The total-raised figure is itself unverifiable: the databases give $20K, $170K, $340K and $1.01M respectively, conflate predecessor (uCiC / Snapwise) raises with Ground News raises, and a May 2025 undisclosed venture round post-dates the frozen totals.
- **Inference, labelled:** One Ground News director, Manuel Mattke, is an employee of Joe Ricketts (per the federal corporate record and public bios). That is a board fact. No evidence was found that Ricketts funds Ground News, and this audit does not claim it.
- **Verdict: Contradicted** — the "no institutional investors / individual investors only" formulation. The softer About formulation ("raised funding from investors who value our mission, but maintain complete editorial control") is not contradicted on this record

### GN-10 — Review counts: 10,000+ vs 53,000+ 5-star reviews

- **Verbatim:** Homepage hero link: "10,000+ 5-star reviews" — [Homepage](https://ground.news/)
- **Verbatim:** "50,000+ sources • 53,000+ 5-star reviews" — [Subscribe](https://ground.news/subscribe)
- **Test (Drift):** Both figures were live on the same site on the same day (13 Nov 2026). Store records show ~49K total ratings on iOS (US) and ~33K on Google Play — total ratings, not 5-star counts — so neither site figure can be reconciled to a published store metric as stated.
- **Verdict: Contradicted** — internally; at least one of the two numbers is wrong or stale, and the company publishes no basis for either

### GN-11 — Blindspot

- **Verbatim:** "A Blindspot is a news story that has political undertones and is disproportionately covered by media sources on one side of the political spectrum." Ground publishes a qualifying formula — for a Blindspot for the Left only: fewer than 10 Left-leaning sources; Right coverage ≥ 33%; a further proportional condition; and a cap of 35% Low-factuality coverage. — [Rating System](https://ground.news/rating-system)
- **Test:** The feature exists and operates as described. The only peer-reviewed efficacy test found ([Bram, PLOS ONE, 2024](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0297808); n > 1,200 subscribers) found 3 of 4 Blindspot stories did not change readers' minds, with 1 reducing polarization in context; the author disclosed working with Ground News to implement the experiment. Ground publishes the Left example formula but no symmetric Right formula on the methodology page.
- **Verdict: Partially corroborated** — mechanism confirmed as described; efficacy modest in the single peer-reviewed test; formula disclosure asymmetric

### GN-12 — Ownership data: "hand-coded … 2,276 news outlets"

- **Verbatim:** "The ownership categories were created by Ground News. We researched, analyzed and hand-coded ownership data for 2,276 news outlets and counting." — [Rating System](https://ground.news/rating-system)
- **Test:** No independent audit of the ownership dataset was found. Arithmetic the company does not present: 2,276 hand-coded outlets is roughly 4.6% of its claimed 50,000 sources — ownership context, a headline product feature, covers a small minority of the corpus by the company's own two numbers.
- **Verdict: Self-reported only**

### GN-13 — Neutrality: "no ideology … no political agenda"

- **Verbatim:** "Ground News has no ideology, it is non-partisan and holds no agenda other than serving your curiosity." — [Mission](https://ground.news/mission); "Ground has no political agenda" — [FAQ](https://ground.news/frequently-asked-questions)
- **Test:** A self-assertion of motive with no testable referent. Structural observations that bear on it, stated without resolving the claim: the bias spectrum applied is the US left–right spectrum, including to non-US outlets; two of its three component raters are themselves the subject of published methodological criticism ([MBFC rigor critique, arXiv 2607.12108](https://arxiv.org/abs/2607.12108v2); [Ad Fontes chart criticism](https://acrlog.org/2021/02/23/complex-or-clickbait-the-problematic-media-bias-chart/)).
- **Verdict: Unverifiable by design**

### GN-14 — Superlatives: "world's first Information Utility" / "every side of every story"

- **Verbatim:** "The world's first Information Utility" — [Mission](https://ground.news/mission); "See every side of every news story" — [Homepage](https://ground.news/); "Ground News identifies every news articles written about a recent event" — [FAQ](https://ground.news/frequently-asked-questions)
- **Test:** Ground's own methodology concedes some sources carry no bias rating and "are not represented in the Bias Bar" ([Rating System](https://ground.news/rating-system)) — so not every side of every story is, by its own account, shown with context. "First Information Utility" has no definable test.
- **Verdict: Unverifiable by design** (first/utility); **Contradicted** in literal form (every)

### GN-15 — Legal entity and app scale bracket

- **Claim (implied across site):** Ground News is an operating Kitchener, Ontario company; footer: "©2026 Snapwise Inc".
- **Test:** [Corporations Canada](https://ised-isde.canada.ca/cc/lgcy/fdrlCrpDtls.html?corpId=8835004) records Snapwise Inc., federal corporation 883500-4, active, incorporated 2014-03-26, registered office in Kitchener, directors including Harleen Kaur Jolly and Sukhsagar Singh Jolly. App stores list the developer as "Snapwise Inc. (dba Ground News)" — [Google Play](https://play.google.com/store/apps/details?id=com.checkitt), [Apple App Store](https://apps.apple.com/us/app/ground-news/id1324203419). Google Play shows the **1M+ downloads bracket** — a bracket, not a count. Apple publishes no download count.
- **Verdict: Confirmed** (entity; 1M+ Play bracket)

### GN-16 — Price framing

- **Verbatim:** "We offer a premium subscription for as low as 83 cents a month" — [Mission](https://ground.news/mission) (≈ $9.99/year, the legacy Pro price)
- **Verbatim:** Vantage at "$10.42/month (billed annually)" — [Subscribe](https://ground.news/subscribe), the only plan price shown in that page's text on the audit date
- **Test:** These are different plans, so this is not a direct contradiction — but the Mission page presents the legacy entry price as *the* premium subscription without naming the plan, while the current sales page leads with a price 12.5× higher.
- **Verdict: Partially corroborated** — both prices real; framing omits that they are different tiers

---

## The seven tests, applied

1. **Counter test — Fail (by design).** Every headline metric (sources, articles/day, readers "in the millions") is self-reported and unaudited. Nobody vouches for the numbers besides the company.
2. **Drift test — Multiple hits.** Review counts 10,000+ vs 53,000+ on the same day; founding year 2014 / 2017 / 2018 / 2020 across the record; scale figures 40K/30K → 50K/60K across retellings; funding totals $20K–$1.01M across databases; location Kitchener (About) vs Waterloo (Mission); the Gospel Stats YouTube count itself appears as both 1,863 and 1,862 in the same firm's reporting.
3. **Insider-testimonial test — Not applicable in the Boardy form; distribution analogue found.** Ground's growth engine is paid creator endorsement: it was the **#1 most-sponsored brand on YouTube in H1 2025 by integrations (1,863) and views (664M)** in [Gospel Stats' sponsorship report](https://www.tubefilter.com/2025/10/22/gospel-stats-youtube-sponsorship-landscape-report/) — qualified to that report's sample (English-language channels, videos ≥25K views in 7 days; not a full-year or by-spend ranking). A product sold as the antidote to native advertising is distributed primarily through native advertising; endorsements in those integrations are paid, which is disclosed by creators under platform rules, not by Ground News in the product.
4. **Manufactured-engagement test — No direct hit.** No comment-to-unlock or giveaway mechanics were found. The algorithmic My Feed (GN-06) is the engagement surface the marketing denies.
5. **Outcome-knowledge test — Weak.** Ground knows its coverage counts; whether Blindspot changes reading behaviour rests on a single peer-reviewed study with modest results (GN-11), conducted with the company's cooperation. No public outcome reporting by the company was found.
6. **Accountability test — Weak.** When the [Columbia Journalism Review](https://www.cjr.org/analysis/the-business-of-balance-ground-news.php) asked about its rater relationships, Ground declined to comment — while AllSides' COO/CFO said on record that Ground uses AllSides ratings without "formal permission" and without compensation, MBFC's founder said there is no agreement, and Ad Fontes' CEO said Ground pays Ad Fontes. The only corrections path found for a disputed rating is "Edit Bias Rating," which changes the rating **on the user's personal account only** — it corrects nothing public.
7. **Press-laundering test — Textbook.** The 50,000 / 60,000 figures, the 2017 founding, the NASA biography and the "largest aggregator" superlative appear in dozens of outlets and reviews. Grouped by independence, they are one source: Ground News. The Wikipedia article's own citations for these claims terminate at Ground's About page.

## Contradiction pass — evidence in Ground News's favour

Logged per the Standard, including where it cuts against the findings above:

- Ground **does** disclose, on its Rating System page, that bias and factuality scores are publication-level, not article-level (GN-03, GN-04) — the disclosure exists; the criticism, made most sharply by [Malone News (22 Aug 2026)](https://www.malone.news/p/ground-news-and-the-factuality-scam), is that the "Factuality" label is nevertheless displayed beside individual stories in the product, where the disclosure does not travel. That product-presentation claim was not independently re-verified in this audit's web pass and is recorded as a critic's claim, not an audit finding.
- The Mission page states plainly: "Ground News isn't a fact-checker, because we believe in empowerment, not enablement." — [Mission](https://ground.news/mission)
- The Rating System page's factuality methodology (2 raters) is **correct**; the error is in the FAQ copies, which is consistent with copy drift rather than a designed deception. The audit records the contradiction, not a motive.
- No media-company, big-tech, or government investor was found, despite a deliberate search — that limb of GN-09's claim held.
- No evidence was found that Ground News fabricates stories, rates outlets in-house while claiming otherwise, or sells user data. Its privacy / business-model claims were out of scope for this pass.
- The Blindspot formula is published at all — most comparable products publish none.

## Founding test

**Can your AI read its own privacy policy and educate you about it?** Not run in this pass — Ground News offers no public-facing AI agent to interrogate. Recorded as not applicable, not as a pass or a fail.

## Verdict tally

| Verdict | Claims |
|---|---|
| Confirmed | GN-04, GN-15 |
| Partially corroborated | GN-03, GN-07, GN-11, GN-16 |
| Self-reported only | GN-01, GN-02, GN-08, GN-12 |
| Unverifiable by design | GN-13, GN-14 (and GN-06 narrow form) |
| Contradicted | GN-05, GN-06 (blanket form), GN-09, GN-10, GN-14 ("every," literal form) |

**One-line finding:** Ground News built a transparency product whose own transparency claims are its weakest surface — its methodology page is mostly honest, and its FAQ, sales page, and mission page contradict that methodology page on factuality, algorithms, and funding.

---

*Evidence ledger (independent sources): `independent-evidence-ledger.md` in this folder. Primary captures are the verbatim quotes above with page URLs, accessed 2026-11-13. Corrections to this audit append as dated errata; the audit is not overwritten.*


---

## Errata and validator disposition — 2026-11-13 (same day, post-validator pass)

Two independent validators (agents who did not generate this audit) re-checked every atom against primary sources. **Both filed: Cleared with exceptions.** Filings: `VALIDATOR-A-FILING-GN01-08.md`, `VALIDATOR-B-FILING-GN09-16.md`. The generator accepts the dispositions below. Per the Standard, the original text above is not overwritten; this errata supersedes the items named. Where a verdict changes, the original verdict is recorded beside the corrected one.

### Verdict changes

| Atom | As filed | Corrected | Reason |
|---|---|---|---|
| GN-06 | Contradicted + a second verdict (Unverifiable by design) for the narrow form | **Contradicted** (single verdict) | The Standard allows exactly one verdict per claim. Note, not a verdict: the narrower "not engagement-maximizing" variant is a different claim and is self-reported only on this record (Validator A). |
| GN-10 | Contradicted | **Partially corroborated** | Generator error, owned: both figures are floors ("10,000+", "53,000+"); if the true count is ≥53,000 the 10,000+ claim is also true. A stale floor is drift, not contradiction. Play's published histogram (78% of ~33.4K ratings are 5-star) makes a ~53K combined figure arithmetically plausible. The surviving finding: Ground says "reviews" where stores publish "ratings," and publishes no basis or date for either figure. The "53,000+" figure is generator-capture only (Validator B flag). |
| GN-14 | Unverifiable by design + Contradicted (dual) | **Unverifiable by design** (single verdict) | Dual verdict breached the Standard. The Bias Bar concession ("some sources… are not represented") is recorded as a limiting note on the slogan, not a second verdict. |
| GN-16 | Partially corroborated | **Confirmed** (claim as stated) | Generator error, owned: "as low as 83 cents a month" is entry-tier language and the tier is live — Pro at $9.99/yr is a current App Store in-app purchase, not a legacy price. The $10.42/month Vantage figure captured on the Subscribe page is **flagged unverified**: three independent readings of the same page/checkout (Aug–Oct 2026) give $8.33/month, $99.99/yr. Re-capture with region/currency recorded is required before any price-ratio claim is used. The 12.5× framing is withdrawn; on the attested price the ratio is 10.0×. |

### Reasoning corrections (verdicts unchanged)

- **GN-02:** The "largest news aggregator" phrase is in Ground's **primary** Google Play listing, not only a mirror — citation upgraded. The "not on the website" limb is generator-capture only; both validators flag absence claims as uncheckable by them.
- **GN-03:** AllSides is not purely categorical — it also publishes a numeric Media Bias Meter (−6 to +6). The incommensurability point is overstated for AllSides and stands for the set as a whole only in weaker form; the load-bearing point (no published composite mapping) was independently verified. Ad Fontes rates individual articles and aggregates to source level. Add: Ad Fontes calls its axis **"reliability,"** not "factuality" — the "Factuality" label is Ground's relabelling (also applies to GN-04).
- **GN-05:** Fairness note added: the FAQ sentence admits a collective grammatical reading (the three organisations between them supply both ratings). The natural reading, every secondary source's reading, and the conflict with Ground's own Rating System page support the verdict. Also logged: an older mirrored FAQ described the three raters as "non-profit," which was also wrong — the FAQ's methodology copy has drifted repeatedly.
- **GN-07:** Add the University of Waterloo news service statement ("In 2017, the brother-sister team launched Ground News") — founder-sourced and non-contemporary, grouped as Ground-derived, but it is the strongest third-party repetition and should have been cited. Sharpened point: read as "founded **the company**," 2017 is contradicted by Snapwise's 2014 incorporation (for the predecessor uCiC); it is defensible only as the founding of the Ground News venture. **The Summary's point 5 is corrected:** the founding year is Partially corroborated per GN-07, not "self-reported only" as the summary lumped it.
- **GN-08:** The source chain traces to Kaur herself as interview subject (earliest profile: Story Exchange, Jan 2017, predating Ground News, about uCiC), not to "Kaur / Ground News." Recorded in Ground's favour: a Jan 2005 integration-test role is temporally coherent with New Horizons' Jan 2006 launch. Neither changes the verdict.
- **GN-09:** Stronger primary evidence added by Validator B: the University of Waterloo's Velocity Fund II release describes that fund as aiming "to be the **first institutional investor**" in its startups and names Ground News among companies that benefited from its investments. Fairness caveat added: known checks are $20K–$150K, pre-seed scale — the *letter* of the claim is contradicted; the economic substance (funders too small to control the company) is not tested by this atom. Mattke correction: president/COO of Ricketts-founded Opportunity Education, and an advisory-board member of Ricketts-owned Straight Arrow News.
- **GN-11:** Bram (2024) tested the weekly Blindspot Report **newsletter**, not the in-app feed — the atom's phrasing is corrected accordingly. Bram's own conclusion (highlighting cross-partisan coverage "can, in certain contexts, reduce polarization"; the approach is "promising") is added to the contradiction pass. The Blindspot formula specifics and the "no symmetric Right formula" negative are generator-capture only.
- **GN-12:** The 2,276 / 50,000 ratio is an **inference, labelled as such**, with its denominator assumption stated: it assumes the 50,000-source corpus as the base; Ground never claimed ownership data for all 50,000 (the corpus includes social/blogs, and ownership is a paid-tier feature for rated outlets). On a rated-outlets base the coverage share is unknown. The rhetorical payload ("covers a small minority of the corpus") is withdrawn as written; the inference and its assumption remain for the reader.
- **GN-13:** Evidence added (Validator B): Straight Arrow News, a Ricketts-owned outlet with the same "unbiased" positioning, "operates in partnership with Ground News for some of its news output," and a Snapwise director advises it. A structural, checkable tie bearing on the neutrality atom. Precision note: the MBFC critique is a preprint and the Ad Fontes critique a professional-association blog; neither is peer-reviewed and neither should be upgraded downstream.

### Seven-tests corrections

- **Test 1 (Counter):** Add, in Ground's favour: CJR reported Similarweb traffic of just under 8 million visits in July 2025 — "millions of readers" is not wholly unvouched (visits ≠ readers).
- **Test 2 (Drift):** Category corrections — the $20K–$1.01M funding spread is *databases disagreeing with each other*, not the claimant changing its number, and is removed from Ground's drift column (it remains in GN-09 as an unverifiability finding). The Gospel Stats 1,862 vs 1,863 discrepancy is Gospel Stats' own, not Ground's, and is removed. Kitchener vs Waterloo is a twin-city artefact and is dropped as a drift hit. Surviving drift: scale figures across Ground's own retellings (40K/30K in its Jan 2020 Product Hunt launch post → 50K/60K), the review floors, the founding-year spread in Ground-derived retellings, and the FAQ methodology copy drift (GN-05).
- **Test 3 (Insider-testimonial/distribution):** "Growth engine" and "distributed primarily through native advertising" are **inferences, labelled as such** — #1 sponsorship intensity in one sample does not by itself prove distribution primacy, and no channel-mix denominator is offered.
- **Test 6 (Accountability):** Fairness restored: Ground gave CJR a quotable reason — it does not disclose ongoing business relationships and arrangements — which the original paraphrase erased; and Ground answers users publicly at scale (developer replies on its Play listing, substantive staff replies on Trustpilot, including on ratings methodology). The "Weak" assessment survives on the rater-relationship record and the personal-account-only edit path, not on silence.

### Contradiction pass — reopened item

The original pass declared the "no media / big tech / government investor" limb of GN-09 clean. That was one search too early. **Unresolved lead, logged:** CB Insights lists a "Digital News Innovation Challenge" among Ground's investors, and a Carleton University journal article (Guida, *Facts & Frictions*, Fall 2021) documents Ground's participation in that programme — a Canadian initiative partnered with the Facebook Journalism Project — recording $100,000 in funding and Facebook ad credits in connection with Ground's participation, from Kaur's own account. That is **not** a big-tech equity investment and does not change GN-09's verdict. It is recorded here as an unresolved lead a challenger could use, exactly as the Standard's contradiction pass requires. Also added: CJR's criticism that factuality ratings sit behind a paywall, which the original pass did not engage.

### Corrected verdict tally (supersedes the tally above)

| Verdict | Claims | Count |
|---|---|---|
| Confirmed | GN-04, GN-15, GN-16 | 3 |
| Partially corroborated | GN-03, GN-07, GN-10, GN-11 | 4 |
| Self-reported only | GN-01, GN-02, GN-08, GN-12 | 4 |
| Unverifiable by design | GN-13, GN-14 | 2 |
| Contradicted | GN-05, GN-06, GN-09 | 3 |

Total: 16 atoms, one verdict each. **The one-line finding is unchanged** — both validators confirmed it rests on GN-05, GN-06 and GN-09, none of which was re-verdicted: Ground News's methodology page is mostly honest, and its FAQ, sales page, and mission page contradict that methodology page on factuality, algorithms, and funding.

### Validation status

- Agent-validator seat: **Cleared with exceptions, exceptions dispositioned in this errata** (Validator A: GN-01–GN-08; Validator B: GN-09–GN-16, seven tests, contradiction pass).
- Nik's personal-validation seat: **pending — his by design.**
- Flagged for re-capture before any external use: the Subscribe Vantage price (region/currency), the "53,000+" review figure, the Blindspot formula page, and the GN-02 website-absence limb — all generator-capture only.
