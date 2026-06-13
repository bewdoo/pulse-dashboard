# Westin Intel — Methodology

*How the competitive-intelligence suite for Whiteland / Westin Residences works, end to end.*

---

## 1. What this answers

A single question, broken into five views: **Where should Westin spend attention and budget to win in the luxury-Gurugram market — and where are rivals exposed?**

We answer it by listening to every public channel (ours and competitors'), scoring what we hear against a fixed set of buyer themes, and turning that into a ranked list of plays.

---

## 2. Where the data comes from

| Source | What we pull | How | Volume |
|---|---|---|---|
| **Our owned channels** (Whiteland + Westin) | Posts, captions, videos, engagement | Instagram, Facebook, YouTube, LinkedIn, Reddit, News | 308 unique posts |
| **Competitor ads** | Live ad creatives, offers, price, channel partners | Meta Ad Library (official, free) | 697 active ads, 18 rivals |
| **Competitor organic — YouTube** | Videos, titles, transcripts, views | YouTube Data API | 321 videos, 14 company channels |
| **Competitor organic — IG/FB** | Posts + engagement | Same scrapers we use for ourselves | 84 IG + 59 FB |
| **Competitor chatter** | Third-party opinion | Reddit + LinkedIn + News search | 42 Reddit + 110 LinkedIn + 140 news |
| **Market trends** | What buyers/press are talking about | Blog + news search, 12 topic clusters | 232 articles |

Two deliberate choices here:
- **Company-level, not project-level.** Competitors are tracked as companies (e.g., *Oberoi Realty*, not one tower), so we treat our side the same way — **Whiteland + Westin combined** — to keep the comparison fair.
- **One source of truth.** All numbers for our own brand trace back to the same dataset that powers the Pulse Feed, so every page agrees.

---

## 3. How raw data becomes signal

1. **De-duplicate** every item by its URL (scrapers often return the same post many times).
2. **Score sentiment** on a −1 to +1 scale using AI judgment rather than a keyword dictionary (dictionaries miss tone, sarcasm, and Hindi/Hinglish). For *our* posts and third-party chatter this is **audience tone**; for *ads* it is **messaging tone** (a brand can't be negative about itself) — and we label the two differently so they're never confused.
3. **Tag themes** against a fixed **9-theme taxonomy** — the 8 priority real-estate themes (delivery/possession, price/value, construction quality, amenities, location/connectivity, builder reputation, assured rental, NRI/GCC demand) plus *luxury/branded* as the category axis. Every post, video, and ad is tagged.
4. **Measure engagement** as likes + comments + shares (plus views for video).
5. **Use the median, not the average, for reach.** A single paid-promoted video (1M+ views) drags an average wildly off the truth; the median shows the *typical* video's reach. This is the difference between "Whiteland gets 68k views" (wrong, one ad) and "~320 views" (right).

---

## 4. The analytical engine (the part worth explaining)

Six frameworks turn signal into decisions.

### a) Campaign comparison
For every brand: how many ads, how many organic posts, which channels, top themes, and engagement-weighted audience sentiment. *Shows who is loud, where, and how the audience feels.*

### b) Sentiment matrix (brand × theme)
Each cell is the engagement-weighted average sentiment for that brand on that theme. *Shows where the audience is warm or cold on each topic — per competitor.*

### c) Theme correlation matrix
Using the **phi coefficient** (a statistical co-occurrence measure), we find which themes appear together in content. A high score means two themes "travel together" and should be **bundled into one campaign** instead of splitting spend (e.g., *assured-rental ↔ NRI/GCC*).

### d) The Verdict Engine — turning numbers into a play
Each theme is run through a fixed priority ladder. The first rule that matches wins:

| Verdict | Trigger | Meaning |
|---|---|---|
| **DEFEND** | *Our* audience sentiment is negative on it | A soft spot rivals can exploit — pre-empt with proof, never lead |
| **ATTACK** | Rivals push it but *their* audience is negative | Convert their disaffected, high-intent shoppers |
| **OWN IT / WHITESPACE** | Near-zero rival ad presence | Uncontested lane — claim it first (OWN if we already post there) |
| **DIFFERENTIATE** | 60%+ of rivals crowd it | Table-stakes — match, then win on the one thing only we have |
| **DE-PRIORITISE** | High volume but near-zero engagement | Wasted effort — reallocate |
| **AMPLIFY** | We're credible (positive + engaging) | Double down on what's working |

This is what produced: *defend possession, own assured-rental/NRI, amplify amenities, differentiate luxury on "Marriott-operated," de-prioritise location.*

### e) Law of diminishing returns
Posting cadence (x) vs median views per video (y). The data shows **volume does not buy reach** — channels posting 60×/month sit at the bottom; reach comes from quality and paid amplification.

### f) Reach × engagement quadrant
Median views (x) vs engagement rate (y), split by the category median. It separates **"paid reach, low loyalty"** (big brands buying views at ~0% engagement) from **"genuine community."** It found that nobody owns the high-reach-*and*-high-loyalty corner — and that Westin already has the **highest engagement rate (2.5%)**, just at small scale.

---

## 5. Synthesis — the Opportunity Candidates

The Pulse Feed's ranked opportunities are the output of all the above. Each candidate is:
- **Typed** — demand (whitespace), competitor (threat), sentiment (audience), or creative (content).
- **Scored for confidence** — based on the strength of the evidence and *how many independent frameworks point to the same conclusion*. An opportunity flagged by the ad data **and** the sentiment data **and** the trend data scores higher than one seen in a single place.
- **Made actionable** — every card states the specific next move.

---

## 6. The five dashboards

| Dashboard | The question it answers |
|---|---|
| **Pulse Feed** | What are the top opportunities right now? *(the executive summary)* |
| **Campaign Strategy** | For paid: which themes to attack, defend, own, differentiate? |
| **Organic Growth** | How do we grow the brand organically and out-content rivals? |
| **Competitor Ads** | Who's advertising what, at what price, through which partners? |
| **Opportunity Matrix** | Where should we create content and run ads (engagement vs competition)? |

---

## 7. Integrity & limits (what we're honest about)

- **Cost-per-click / bid / budget is never obtainable.** It's private auction data; no tool exposes it. We measure *ad volume* as a share-of-voice proxy instead.
- **Competitor Instagram/Facebook organic is partial.** Login walls limit coverage; YouTube is the scalable owned-content window, and third-party chatter (Reddit, news) fills the audience-sentiment gap.
- **Median over average** everywhere reach is involved, to avoid paid-amplified outliers.
- **Self-authored vs audience sentiment are kept separate** and labelled.
- **One source of truth** for our own brand, so the five pages never disagree.

---

*Prepared for the Whiteland / Westin Residences marketing team. All competitor data is from public sources (Meta Ad Library, public social channels, press). Dashboards are private (noindex).*
