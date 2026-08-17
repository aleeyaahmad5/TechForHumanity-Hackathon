# Alternative Budget Scenarios — Ticket Price & Capacity Sensitivity Analysis

**Purpose:** exploratory "what-if" modeling requested outside the confirmed plan. The confirmed budget is still [05_Budget_Revenue.md](../05_Budget_Revenue.md) ($35 ticket cap, 50–150 total-head ceiling, 2-day format) — nothing here overrides it. This file stress-tests two alternative shapes of the event: a small, higher-priced format, and the current pricing model pushed to a narrower, higher-capacity band, each run at both 2-day and 3-day length.

## Methodology (shared across all four scenarios)

Reused unchanged from [05_Budget_Revenue.md](../05_Budget_Revenue.md):

- **Venue, AV/tech, volunteer appreciation, marketing, insurance: $0** — RMIT covers venue/AV; no line item changes with price or headcount.
- **Catering is the only real cost**, via Catering At Its Finest grazing boxes, and it's the only line that moves with headcount or event length.
- **Catering rate:** ~$4/head per lunch (derived in 05_Budget_Revenue.md's box math), **one lunch per day**, plus 10% contingency on catering.
  - 2-day format = 2 lunches → **$8.80/head** (catering + contingency combined)
  - 3-day format = 3 lunches → **$13.20/head**
- **"Total heads" = everyone at the venue** (paying participants + mentors/judges/volunteers/organizers) — this is what drives catering cost. **"Paid tickets"** is the subset that generates ticket revenue. This is the same split the confirmed model uses at the 150-head ceiling.
- Ticket price is held **flat regardless of format length** in the base case (a 3rd day doesn't automatically carry a higher price) — the effect of *not* doing that is covered separately below, since it's the single biggest lever in the 3-day numbers.
- A 3-day (Fri–Sun) format converts the currently-planned **Friday evening mixer** (6–8pm, no catering budget) into a **full Friday hacking day with a catered lunch** — this is where the 3rd lunch comes from.

---

## Scenario 1 — $50 flat ticket, 40-person cap

No tiering (no early bird/group/scholarship split) — a single flat price, consistent with "normal price" framing.

**Staffing assumption:** even at a 40-head ceiling, the 8 volunteer role categories in [07_Volunteer_Staffing.md](../07_Volunteer_Staffing.md) (Venue, Tech, Mentorship, Judge Coordinator, Participant Experience, Logistics, Social/Comms, floaters) don't shrink below roughly 1 person each — so staffing doesn't scale down proportionally with a smaller cap. Assumed **8 staff / 32 paying participants** (80/20 split, vs. ~87/13 at the 150-head ceiling).

| | 2-day | 3-day |
|---|---|---|
| Total heads | 40 | 40 |
| Paying participants | 32 | 32 |
| Ticket price | $50 | $50 |
| **Revenue** | **$1,600** | **$1,600** |
| Catering + contingency (@ $8.80 / $13.20 per head) | $352 | $528 |
| **Profit** | **$1,248** | **$1,072** |
| Profit margin | 78% | 67% |
| Breakeven (paid tickets needed) | 8 | 11 |
| Profit per paying participant | $39.00 | $33.50 |

**Read:** even at only 40 people, this format is extremely low-risk — breakeven is 8–11 tickets against a 32-ticket target, so a soft launch or under-registration barely dents solvency. The 3rd day costs **$176 in pure catering** (40 heads × $4.40 marginal rate) with zero offsetting revenue in the base case, cutting profit by 14%.

---

## Scenario 2 — $35 tiered ticket (current model), 100–150 total heads

Identical structure to the confirmed budget: early bird $20 / standard $35 (hard cap) / group $25 / ~10% scholarship, blended average **$27/paid ticket**, ~90% of heads paying.

| Total heads | Format | Paid tickets | Revenue | Catering + contingency | **Profit** | Breakeven (tickets) |
|---|---|---|---|---|---|---|
| 100 | 2-day | 90 | $2,430 | $880 | **$1,550** | 33 |
| 125 | 2-day | 112 | $3,024 | $1,100 | **$1,924** | 41 |
| 150 | 2-day | 135 | $3,645 | $1,320 | **$2,325** | 49 |
| 100 | 3-day | 90 | $2,430 | $1,320 | **$1,110** | 49 |
| 125 | 3-day | 112 | $3,024 | $1,650 | **$1,374** | 62 |
| 150 | 3-day | 135 | $3,645 | $1,980 | **$1,665** | 74 |

The 2-day row matches [05_Budget_Revenue.md](../05_Budget_Revenue.md)'s existing 100/150-head scenarios exactly — cross-check confirms the shared rate model is consistent. 125 heads is the midpoint of the requested 100–150 range.

**Read:** even the worst case in this band (100 heads, 3-day) clears breakeven with room (49 of 90 paid tickets needed). But the breakeven bar roughly **doubles** in the 3-day format at every headcount, because the 3rd lunch adds cost linearly while ticket revenue doesn't move. At 150 heads, 3-day margin drops from 63.8% to 45.7%.

---

## Cross-Scenario Comparison

| Scenario | Format | Profit | Margin | Profit / paying participant |
|---|---|---|---|---|
| $50 / 40-cap | 2-day | $1,248 | 78% | **$39.00** |
| $50 / 40-cap | 3-day | $1,072 | 67% | $33.50 |
| $35 / 100–150 | 2-day | $1,550 – $2,325 | 63.8% | $17.22 |
| $35 / 100–150 | 3-day | $1,110 – $1,665 | 45.7% | $17.22 (constant — cost and revenue both scale with heads) |

**Two consistent patterns, independent of scale:**
1. **Every 3-day format loses ~15–18 margin points to the same 3rd-lunch cost** ($4.40/head, no exceptions) — this is a fixed penalty of the format choice, not the price or headcount choice.
2. **The $50/40-cap model earns ~2.3x more profit per paying participant** than the $35/100–150 model, because catering cost per head is fixed while ticket price isn't — a higher price captures more margin per plate, at the cost of a much smaller total pool of both revenue and participants reached.

---

## Pricing Strategy Notes

Framed against value-based pricing (price sits between the *next best alternative* and *perceived value*, not just cost-to-serve):

- **The $35 cap isn't just a budget input — it's a stated design principle** ("pricing has to stay accessible or people won't come," see [05_Budget_Revenue.md](../05_Budget_Revenue.md)) tied directly to the event's own "under-served communities" theme. A $50 flat price is a real tension against that principle, not just a numbers change — it trades reach and thematic consistency for margin and a more curated, resourced cohort.
- **These aren't really "the same event at a different price" — they're two different products.** $35/100–150 is a volume, low-barrier community event; $50/40 is a small, higher-touch cohort (more mentor time per participant, tighter room, easier logistics) — closer to a "flagship" format than a scaled-down version of the main plan.
- **If a 3rd day is genuinely wanted, price should move with it, not stay flat.** Holding profit constant across formats requires:
  - Scenario 1: raise the $50 ticket to **~$55–56** (~11% increase)
  - Scenario 2 at 150 heads: raise the **$27 blended average to ~$32** (i.e., push the hard cap from $35 toward **~$40**)

  This is defensible under value-based pricing — a 3rd day is a real increase in delivered value (more build time, room for an extra workshop/keynote slot), not just an added cost, so pricing it flat under-captures that value rather than "staying accessible."

## Recommendation

Neither alternative beats the confirmed plan on pure profit ceiling (150-head 2-day $35 model tops out at $2,325 — still the highest single number here), but that's not really the decision being tested. If the goal is **safety margin and simplicity** at a much smaller scale, Scenario 1 (2-day) is the strongest — a 78% margin and an 8-ticket breakeven is about as low-risk as this event structure gets. If a 3rd day is under real consideration in either scenario, **do not adopt it without also revisiting ticket price** — treated as a pure cost add, it quietly erodes margin by 15–20 points regardless of scale, which is the one number in this whole analysis worth flagging back to [02_Executive_Summary.md](../02_Executive_Summary.md)'s 2-day vs. 3-day format decision.
