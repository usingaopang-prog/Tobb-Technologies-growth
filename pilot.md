# Pilot Plan — 4-Week Cardano Family QR Experience

> **Goal:** prove the funnel works — from physical scan to wallet creation — before scaling spend.
> **Duration:** 4 weeks
> **Owner:** [Bernard Sibanda]
> **Status:** Ready to execute
> **Last updated:** [30 October 2026]

---

## 1. Pilot Objective

Validate that a **physical QR code** can convert curiosity into a **measurable family onboarding funnel** on Cardano — at acceptable cost per wallet.

The pilot answers four questions:

1. **Does the child experience hold attention?** → game completion rate
2. **Does play convert into ownership?** → NFT mint rate
3. **Does the child pull the parent in?** → parent-path entry rate
4. **Does education convert into action?** → wallet creation rate

If the answer to all four is **yes**, we scale. If not, we iterate before spending more.

---

## 2. Success Criteria

| Metric | Target | Stretch | Below this = pause |
|---|---|---|---|
| Game completion rate | ≥ 30% | ≥ 45% | < 15% |
| NFT mint rate | ≥ 15% | ≥ 25% | < 7% |
| Parent-path entry rate | ≥ 20% | ≥ 30% | < 10% |
| Wallet creation rate | ≥ 10% | ≥ 20% | < 5% |
| 7-day retention | ≥ 15% | ≥ 25% | < 7% |
| Cost per wallet | ≤ R[X] | ≤ R[Y] | > R[Z] |

> **Rule:** if any core metric is below **half** its target after Week 2, pause and iterate before continuing spend.

---

## 3. Pilot Scope

### In scope
- 1 landing page (two-door design)
- 1 H5 mini-game (single level, single NFT reward)
- NFT minting on **Cardano testnet first**, then mainnet for a small cohort
- 20 QR T-shirts/stickers
- 2–3 pilot sites
- Full funnel tracking (see [`metrics.md`](metrics.md))

### Out of scope
- Multiple games or levels
- Premium/paid content
- Brand partnerships
- Vehicle advertising (LED/light-box)
- Multi-city rollout

---

## 4. Week-by-Week Plan

### Week 1 — Build the game prototype

| Day | Task | Owner | Deliverable |
|---|---|---|---|
| 1–2 | Choose H5 mini-game tooling (e.g. Phaser, Construct, or a no-code builder) | | Decision doc |
| 2–3 | Design game loop: collect fragments → synthesize NFT | | Wireframe |
| 3–5 | Build playable prototype | | Link to prototype |
| 5 | Internal playtest with 3–5 people (including at least 1 child with parent present) | | Feedback notes |

**Exit criteria:** a playable game that a child can finish in under 3 minutes without help.

---

### Week 2 — Connect NFT minting

| Day | Task | Owner | Deliverable |
|---|---|---|---|
| 1–2 | Set up no-code minting (e.g. NMKR Studio) on **testnet** | | Testnet policy ID |
| 2–3 | Connect game completion → mint trigger | | End-to-end test on testnet |
| 3–4 | Test with 3–5 users on testnet | | Mint success rate |
| 4–5 | Prepare mainnet policy and small mint allocation | | Mainnet ready |
| 5 | **Go/no-go review** for mainnet | | Signed checklist |

**Exit criteria:** end-to-end mint confirmed on testnet; mainnet policy ready; compliance checklist signed off (see [`docs/compliance.md`](../docs/compliance.md)).

---

### Week 3 — Parent explainer page + compliance review

| Day | Task | Owner | Deliverable |
|---|---|---|---|
| 1–2 | Write parent explainer copy (90-second, plain language) | | Draft copy |
| 2 | Draft risk warning (use approved text from compliance doc) | | Approved warning |
| 3 | Build landing page (two doors) | | Staging link |
| 3–4 | Compliance review against `compliance.md` | | Signed checklist |
| 4 | Legal counsel review (external) | | Sign-off |
| 5 | Landing page live on production | | Live URL |

**Exit criteria:** landing page live, compliance checklist fully signed, risk warning visible.

---

### Week 4 — Physical placement + pilot launch

| Day | Task | Owner | Deliverable |
|---|---|---|---|
| 1 | Produce 20 QR T-shirts/stickers (unique UTM per placement) | | Physical assets |
| 2 | Brief pilot site staff on the experience and FAQ | | Briefing doc |
| 2 | Set up analytics dashboard | | Live dashboard |
| 3 | **Pilot launch** at 2–3 sites | | Live |
| 3–7 | Monitor daily; log issues | | Daily log |
| 7 | **Week 1 results review** | | Report in [`results.md`](results.md) |

**Exit criteria:** pilot live, first week of funnel data captured, issues logged.

---

## 5. Pilot Sites

| Site | Type | Why chosen | Contact | Status |
|---|---|---|---|---|
| [Site A] | [e.g. family café] | [reason] | [name] | ☐ confirmed |
| [Site B] | [e.g. community centre] | [reason] | [name] | ☐ confirmed |
| [Site C] | [e.g. school event] | [reason] | [name] | ☐ confirmed |

**Site requirements:**
- Family-friendly audience
- Safe place to scan (not while driving)
- Staff willing to explain the experience
- Permission to place posters/table cards

---

## 6. QR Placement Matrix

| Placement | Quantity | UTM source | UTM medium | UTM campaign |
|---|---|---|---|---|
| T-shirt | 10 | `tshirt` | `qr` | `pilot-w1` |
| Wall poster | 5 | `poster` | `qr` | `pilot-w1` |
| Table card | 5 | `tablecard` | `qr` | `pilot-w1` |
| Event booth | [n] | `event` | `qr` | `pilot-w1` |
| Car magnet | [n] | `carmagnet` | `qr` | `pilot-w1` |

> Every QR code must carry a **unique UTM tag** so we can compare which placement produces the best wallet-creation rate per rand spent.

---

## 7. Team & Responsibilities

| Role | Name | Responsibility |
|---|---|---|
| Pilot lead | | Overall coordination, daily monitoring |
| Game developer | | Mini-game build and fixes |
| Landing page developer | | Landing page build and fixes |
| Compliance reviewer | | Sign-off on all copy and materials |
| Legal counsel (external) | | Final legal review |
| Site coordinator | | Site relationships, staff briefing |
| Data analyst | | Dashboard, weekly reporting |

---

## 8. Budget

| Item | Estimated cost | Notes |
|---|---|---|
| H5 game tooling | R | [tool] |
| NFT minting (testnet + mainnet allocation) | R | |
| Landing page hosting | R | |
| QR T-shirts/stickers (20 units) | R | |
| Design (mascot, brand kit) | R | |
| Pilot site incentives | R | |
| Analytics tooling | R | |
| Legal review | R | |
| Contingency (15%) | R | |
| **Total** | **R** | |

---

## 9. Risk Register

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| Low game completion | Medium | High | Playtest in Week 1; iterate on real data |
| NFT mint friction | Medium | High | Testnet first; keep first mint free |
| Compliance delay | Medium | High | Start review in Week 1, not Week 3 |
| Low site foot traffic | Medium | Medium | Choose high-traffic family venues |
| Parent distrust | High | High | Education-first path; no return promises |
| Child data privacy | Low | High | No personal data collected; parent-gated |
| Regulatory query | Low | High | Strict language rules; incident response plan |

---

## 10. Daily Monitoring Checklist

Run every day during the pilot:

- [ ] Scans recorded per placement (UTM breakdown)
- [ ] Landing view rate checked
- [ ] Game start and completion rates checked
- [ ] NFT mints confirmed on-chain
- [ ] Parent-path entries logged
- [ ] Wallet creations logged
- [ ] Any user-reported issues logged
- [ ] Any compliance concerns logged and escalated

---

## 11. Weekly Review Template

At the end of each pilot week, fill this in and copy the summary to [`results.md`](results.md):

| Metric | Week 1 | Week 2 | Week 3 | Week 4 | Target |
|---|---|---|---|---|---|
| Scans | | | | | baseline |
| Landing views | | | | | — |
| Game starts | | | | | — |
| Completions | | | | | — |
| Mints | | | | | — |
| Parent entries | | | | | — |
| Wallets | | | | | — |
| 7-day returns | | | | | — |
| Revenue (R) | | | | | — |
| Spend (R) | | | | | — |
| Completion rate | | | | | ≥ 30% |
| Mint rate | | | | | ≥ 15% |
| Parent entry rate | | | | | ≥ 20% |
| Wallet rate | | | | | ≥ 10% |
| Retention | | | | | ≥ 15% |
| Cost per wallet | | | | | ≤ R[X] |

**Qualitative notes:**
- What worked:
- What didn't:
- What to change next week:

---

## 12. Go / No-Go Decision (End of Week 4)

**Scale if:**
- All four core metrics meet target
- Cost per wallet is within budget
- No compliance incidents
- Site partners willing to continue

**Iterate if:**
- 1–2 core metrics are below target but trending up
- Cost per wallet is above budget but improving

**Pause if:**
- Any core metric is below half its target
- Any compliance incident occurred
- Cost per wallet is unsustainable

**Decision owner:** [name]
**Decision date:** [date]
**Recorded in:** [`results.md`](results.md)

---

## 13. Post-Pilot Deliverables

At the end of Week 4, produce:

- [ ] Completed [`results.md`](results.md) with full funnel data
- [ ] 1-page summary for partners and investors
- [ ] Lessons-learned document
- [ ] Recommendation: scale / iterate / pause
- [ ] Updated roadmap (if scaling)

---

## 14. References

- [Compliance checklist](compliance.md)
- [Messaging library](messaging.md)
- [Metrics definitions](metrics.md)
- [Main README](README.md)

---

*Pilot plan v1.0 — [30 October 2026]*
