# Campaign Strategy — focal: Westin Residences  *(real scraped corpus)*
_Built from the actual pulse-ingest corpus: 286 Claude-scored Westin posts (incl. Reddit/news) + 697 rival Meta-Ad-Library ads across 18 rivals + ~20 leaked rival organic posts. Sentiment = audience tone for posts; rival ad cells (ᵃᵈ) are self-authored messaging tone._

## 1. Campaign comparison
| Entity | Ads | Posts | Audience sentiment | Top themes | Channels |
|---|--:|--:|--:|---|---|
| **Westin Residences** | — | 308 | +0.43 (n=286) | T9, T5, T6 | facebook, instagram, linkedin, news, reddit, youtube |
| Godrej Samaris | 151 | — | — | T6, T5, T9 | meta_ads |
| Tonino Lamborghini Residences | 147 | — | — | T9 | meta_ads |
| Oberoi Realty (Sec 58) | 88 | 12 | +0.49 (n=12) | T4, T6, T9 | instagram, meta_ads |
| DLF Arbour | 53 | — | — | T6, T9, T2 | meta_ads |
| Central Park Delphine | 52 | — | — | T4, T9 | meta_ads |
| Experion The Trillion | 37 | — | — | T4, T9, T2 | meta_ads |
| Sobha Crescent | 30 | — | — | T4, T9 | meta_ads |
| Godrej Miraya | 27 | — | — | T5, T9, T2 | meta_ads |
| DLF Privana | 25 | 1 | +0.40 (n=1) | T2, T6, T9 | facebook, meta_ads |
| Trump Towers (DXP) | 21 | — | — | T9 | meta_ads |
| TARC Ishva | 18 | — | — | T9, T2 | meta_ads |
| Max Estate 360/361 | 16 | — | — | T4 | meta_ads |
| Elie Saab Residences | 15 | — | — | T9, T2 | meta_ads |
| Sobha Altus | 7 | — | — | T4, T9 | meta_ads |
| Signature Global | — | 7 | +0.54 (n=7) | T6, T4, T5 | facebook |
| Elan Presidential | 5 | — | — | T9 | meta_ads |
| Krisumi Waterfall Residences | 3 | — | — | T1, T5, T9 | meta_ads |
| Birla Arika | 2 | — | — | T9 | meta_ads |

## 2. Sentiment matrix (entity × theme, engagement-weighted)
| Entity | T1 | T2 | T3 | T4 | T5 | T6 | T7 | T8 | T9 |
|---|---|---|---|---|---|---|---|---|---|
| Westin Residences | -0.60 | -0.47 | · | +0.72 | +0.47 | +0.27 | +0.27 | +0.51 | +0.74 |
| Godrej Samaris | · | +0.35ᵃᵈ | · | · | +0.35ᵃᵈ | +0.35ᵃᵈ | · | · | +0.35ᵃᵈ |
| Tonino Lamborghini Residences | · | · | · | · | · | · | · | · | +0.35ᵃᵈ |
| Oberoi Realty (Sec 58) | · | +0.35ᵃᵈ | · | +0.52 | +0.35ᵃᵈ | +0.39 | +0.40 | · | +0.55 |
| DLF Arbour | · | +0.35ᵃᵈ | · | · | · | +0.35ᵃᵈ | · | · | +0.35ᵃᵈ |
| Central Park Delphine | · | · | · | +0.40ᵃᵈ | · | · | · | · | +0.40ᵃᵈ |
| Experion The Trillion | · | +0.35ᵃᵈ | · | +0.35ᵃᵈ | · | · | · | · | +0.35ᵃᵈ |
| Sobha Crescent | · | · | · | +0.35ᵃᵈ | · | · | · | · | +0.35ᵃᵈ |
| Godrej Miraya | · | +0.35ᵃᵈ | · | · | +0.35ᵃᵈ | · | · | · | +0.35ᵃᵈ |
| DLF Privana | · | +0.40 | · | +0.40 | +0.40 | +0.35ᵃᵈ | · | · | +0.35ᵃᵈ |
| TARC Ishva | · | +0.35ᵃᵈ | · | · | · | · | · | · | +0.35ᵃᵈ |
| Max Estate 360/361 | · | · | · | +0.35ᵃᵈ | · | · | · | · | · |
| Elie Saab Residences | · | +0.35ᵃᵈ | · | · | · | · | · | · | +0.35ᵃᵈ |
| Trump Towers (DXP) | · | · | · | · | · | · | · | · | +0.35ᵃᵈ |
| Sobha Altus | · | · | · | +0.35ᵃᵈ | · | · | · | · | +0.35ᵃᵈ |
| Elan Presidential | · | · | · | · | · | · | · | · | +0.35ᵃᵈ |
| Krisumi Waterfall Residences | +0.45ᵃᵈ | · | · | · | +0.45ᵃᵈ | · | · | · | +0.45ᵃᵈ |
| Birla Arika | · | · | · | · | · | · | · | · | +0.35ᵃᵈ |
| Signature Global | · | · | +0.55 | +0.48 | +0.49 | +0.54 | · | · | +0.50 |

## 3. Theme correlation matrix (phi — co-occurrence → bundle)
| | T1 | T2 | T3 | T4 | T5 | T6 | T7 | T8 | T9 |
|---|---|---|---|---|---|---|---|---|---|
| T1 | 1.00 | 0.16 | -0.00 | -0.04 | 0.03 | 0.05 | -0.03 | -0.01 | 0.00 |
| T2 | 0.16 | 1.00 | -0.01 | 0.01 | -0.03 | 0.15 | 0.00 | -0.02 | 0.06 |
| T3 | -0.00 | -0.01 | 1.00 | -0.03 | -0.04 | 0.10 | -0.02 | -0.01 | -0.05 |
| T4 | -0.04 | 0.01 | -0.03 | 1.00 | -0.21 | -0.17 | -0.18 | -0.05 | 0.09 |
| T5 | 0.03 | -0.03 | -0.04 | -0.21 | 1.00 | -0.17 | 0.02 | -0.06 | 0.21 |
| T6 | 0.05 | 0.15 | 0.10 | -0.17 | -0.17 | 1.00 | 0.11 | 0.03 | -0.20 |
| T7 | -0.03 | 0.00 | -0.02 | -0.18 | 0.02 | 0.11 | 1.00 | 0.06 | 0.02 |
| T8 | -0.01 | -0.02 | -0.01 | -0.05 | -0.06 | 0.03 | 0.06 | 1.00 | 0.03 |
| T9 | 0.00 | 0.06 | -0.05 | 0.09 | 0.21 | -0.20 | 0.02 | 0.03 | 1.00 |

_Theme key: T1=delivery/possession; T2=price/value; T3=construction quality; T4=amenities; T5=location/connectivity; T6=builder reputation; T7=assured rental; T8=nri/gcc demand; T9=luxury/branded_

## 4. Content & campaign playbook (ranked)
| Theme | Verdict | Objective | Your sent | Rival ad pressure | Saturation | Play |
|---|---|---|--:|--:|--:|---|
| T1 delivery/possession | **DEFEND** | Conversion | -0.60 | 3 | 5% | Construction-progress proof film + completion-timeline + side-by-side |
| T2 price/value | **DEFEND** | Conversion | -0.47 | 414 | 44% | Value-per-sqft explainer + payment-plan creative (reframe off sticker price) |
| T7 assured rental | **OWN IT** | Awareness | +0.27 | 0 | 5% | ROI / rental-yield calculator carousel + investor testimonial |
| T8 nri/gcc demand | **WHITESPACE** | Awareness | +0.51 | 0 | 0% | GCC roadshow reel, NRI testimonial, multi-language creative |
| T3 construction quality | **WHITESPACE** | Awareness | — | 0 | 5% | Third-party quality audit + RERA/escrow transparency proof |
| T4 amenities | **AMPLIFY** | Consideration | +0.72 | 142 | 44% | Amenity + lifestyle walkthrough reel (your top-engaging content) |
| T6 builder reputation | **AMPLIFY** | Consideration | +0.27 | 229 | 27% | Whiteland+Marriott legacy film + handover/track-record proof |
| T9 luxury/branded | **DIFFERENTIATE** | Consideration | +0.74 | 681 | 94% | Marriott-operated hospitality differentiator (own the ONE thing rivals can't claim) |
| T5 location/connectivity | **DE-PRIORITISE** | Consideration | +0.47 | 269 | 33% | Connectivity map reel + drive-time to airport/business district |

## TL;DR for Westin
- **Defend** (your audience is negative — rivals can exploit): delivery/possession, price/value. Possession is hit directly by Krisumi's *Ready-to-Move*; price by 414 ads of pressure. Pre-empt with proof, never lead.
- **Own the paid whitespace** (zero/near-zero rival ads): assured rental, nri/gcc demand, construction quality. You already publish assured-rental content organically — just put budget behind it.
- **Amplify** (your strongest, highest-engagement content): amenities, builder reputation. Amenities/lifestyle score +0.72 sentiment and your best engagement.
- **Differentiate, don't outspend** on luxury/branded (94% of rivals claim it, 681 ads) — lead with the one thing only you have: Marriott-operated.
- **De-prioritise** location content (100 posts, 0.02× engagement — dead weight).
- **Bundle** correlated themes (assured-rental ↔ NRI/GCC; construction-quality ↔ builder-reputation) into single campaigns.