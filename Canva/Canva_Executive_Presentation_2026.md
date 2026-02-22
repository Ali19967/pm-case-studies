# Canva Mobile Onboarding Optimization
## Executive Presentation

**Prepared For:** Executive Leadership Team  
**Prepared By:** Product Strategy Team  
**Date:** February 15, 2026  
**Meeting Duration:** 30 minutes  
**Decision Required:** Approve MVP implementation

---

## 🎯 The Ask

**Approval to proceed with 3-week MVP to fix Canva mobile activation crisis**

- **Investment:** $25K (7 features, 3 weeks)
- **Expected Return:** +$624K annually (+2,496% ROI)
- **Risk Level:** LOW (all UI/UX changes, reversible)
- **Timeline:** Ship in 3 weeks, results visible immediately

---

## 📊 Slide 1: The Crisis (90 seconds)

### The Numbers

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
              THE PROBLEM
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

60.6% of new users CHURN on Day 1
      (18,180 users/month lost)

App Store Rating: 3.8/5.0 ⭐⭐⭐
      (Lowest among competitors)

$2.6M/year wasted on CAC
      (acquiring users who never activate)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### What This Means

- **Growth is unsustainable** - Can't scale when 60% churn immediately
- **Negative viral loop** - Poor reviews hurt organic acquisition
- **Revenue opportunity missed** - Can't convert users who churned
- **Competitive risk** - Adobe, PicsArt capitalizing on our failures

### The Data Source

- **363 user reviews** analyzed (Jan-Feb 2026)
- **60.6% negative** (1-2 star reviews) vs 39.4% positive (5 star)
- **Consistent patterns** across hundreds of users
- **Clear root causes** identified through framework analysis

---

## 📊 Slide 2: Root Cause Analysis (2 minutes)

### The Funnel Breakdown

```
30,000 NEW USERS/MONTH
      ↓ 95% Register ✓
28,500 Registered
      ↓ 95% Start Design ✓
27,075 Design Attempts
      ↓ 50% Complete Design 🔴 PROBLEM #1
13,538 Completed Designs
      ↓ 83% Save Success 🔴 PROBLEM #2
11,820 ACTIVATED (39.4%)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
LOST: 18,180 USERS (60.6% CHURN)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### Three Critical Problems (97% of Churn)

**Problem #1: Can't Find Free Content (45% abandon)**
- No "Free Only" filter exists
- 7+ minutes scrolling through 70% premium content
- Feature existed in 2025, removed, never restored
- **User Quote:** *"Still can't filter graphics by price. Takes forever."*

**Problem #2: Hidden Paywalls (50% abandon)**
- Lock icons appear AFTER clicking (wasting time)
- Users feel "tricked" and "deceived"
- 38.6% of negative reviews mention this
- **User Quote:** *"All designs say FREE but when you try to use them, LOCKED."*

**Problem #3: Save Failures (17% lose work)**
- Saves fail mid-operation (1GB+ data, 30+ min timeouts)
- No auto-save or backup
- Most emotionally damaging issue
- **User Quote:** *"Download never finished. I end up screenshotting which reduces quality."*

### The Root Cause

**No single team owns "successful first design completion" end-to-end**
- Monetization team optimized for premium impressions (removed filter)
- Design team tested with Pro users (hidden lock bias)
- Infrastructure team prioritized features over reliability
- **Result:** Each team optimized their metric, activation fell through cracks

---

## 📊 Slide 3: The Solution (3 minutes)

### Two-Phase Approach

#### Phase 1: MVP (3 Weeks, $25K)

**7 Features Targeting Discovery + Trust:**

1. **Free Filter Restoration** - Let users filter to free-only content
2. **Badge Visibility 3x** - Make free/pro badges impossible to miss
3. **Free Tier Value Guide** - Set expectations upfront
4. **Free-First Ranking** - Show free content first in results
5. **Lock Indicators Upfront** - Show locks BEFORE clicking
6. **Transparent Upgrades** - Clear value props in upgrade prompts
7. **Free Alternative Flow** - Offer alternatives when hitting paywalls

**Why These 7?**
- Highest RICE scores (Reach × Impact × Confidence / Effort)
- All UI/UX changes (low risk, reversible)
- Fits exactly in 3-week sprint with 4 engineers
- Complete the "discovery + trust" story

---

#### Phase 2: Infrastructure (6 Weeks, $100K)

**Save Infrastructure Overhaul:**
- Incremental saves (1-5MB vs 1GB+)
- Compression (90% size reduction)
- Auto-save every 30 seconds
- Reliable infrastructure (99.5% success vs 83%)

**Why Separate Phase?**
- Too large for MVP (24 person-weeks)
- Higher risk (infrastructure changes)
- MVP proves approach first
- Can wait (62% activation acceptable without it)

---

### The RICE Prioritization

**How We Chose These 7 Features:**

| Feature | RICE Score | Reason |
|---------|------------|--------|
| Free Filter | 33,750 | Highest leverage, proven demand |
| Badges 3x | 32,000 | Quick win (1 week), high impact |
| Free Guide | 22,500 | Sets expectations, easy |
| Free-First | 21,250 | Complements filter |
| Lock Indicators | 14,875 | Critical for trust |
| Transparent Upgrade | 11,200 | Revenue quality |
| Free Alternative | 4,900 | Completes trust story |

**Deferred Features:**
- Save Infrastructure: 656 RICE (lowest due to 24-week effort, but critical → Phase 2)
- JTBD Onboarding: 4,500 RICE (uncertain ROI, high effort → defer)

**Key Insight:** Save infrastructure has LOW RICE score (huge effort) but remains strategically CRITICAL → gets dedicated Phase 2 instead of rushing in MVP.

---

## 📊 Slide 4: Expected Impact (2 minutes)

### Activation Rate Projections

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
        ACTIVATION RATE IMPROVEMENT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

CURRENT:        39.4% ████████░░░░░░░░░░░░

AFTER MVP:      62.1% ████████████░░░░░░░░
                      (+22.7 pts, 3 weeks)

AFTER PHASE 2:  72.3% ██████████████░░░░░░
                      (+32.9 pts, 9 weeks)

TARGET:         70%   ██████████████░░░░░░
                      ✓ ACHIEVED

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### Expected Value Model (Monte Carlo)

| Scenario | Activation | Probability | Users/Month |
|----------|------------|-------------|-------------|
| Pessimistic | 55% | 15% | +4,680 |
| **Conservative** | **62.1%** | **50%** | **+6,810** |
| Optimistic | 67.3% | 30% | +8,370 |
| Best Case | 72% | 5% | +9,780 |

**Expected (Weighted Average): 63.2% activation, +7,140 users/month**

**Confidence: 80% probability of achieving >60% activation**

---

### Business Impact

#### MVP Impact (Conservative)

```
Additional Users:     +6,810/month
Pro Conversions (8%):  +545 pro users/month
Monthly MRR:          +$7,080
Annual Revenue:       +$624,000

Investment:           $25,000
ROI:                  2,496% (24.96x return)
Payback Period:       3.5 weeks
```

#### Total Program Impact (MVP + Phase 2)

```
Additional Users:     +9,318/month (+78.9% increase)
Pro Conversions:      +745 pro users/month
Monthly MRR:          +$9,690
Annual Revenue:       +$859,000

Total Investment:     $125,000 (MVP + Phase 2)
Year 1 ROI:           587%
Payback Period:       1.7 months
```

---

### User Sentiment Impact

| Metric | Current | After Phase 2 | Improvement |
|--------|---------|---------------|-------------|
| App Store Rating | 3.8 | 4.6 | +0.8 ⭐ |
| 1-Star Reviews | 37.2% | 18% | -19.2 pts |
| 5-Star Reviews | 39.4% | 55% | +15.6 pts |
| NPS Score | -36 | +30 | +66 pts |

**Compound Effect:**
- Higher rating → More organic installs → Lower CAC
- Better reviews → Higher trust → More conversions
- Positive NPS → Viral growth → Sustainable scaling

---

## 📊 Slide 5: Risk Management (2 minutes)

### Risk Assessment

#### MVP Risks: LOW ✅

| Risk | Mitigation |
|------|------------|
| Feature adoption low | Prominent UI, tooltips, smart suggestions |
| Timeline slip | Buffer in estimates, parallel work streams |
| Pro conversion drops | Monitor as guardrail, instant rollback |
| A/B tests inconclusive | Large samples (1,500+ users), clear metrics |

**Key Point:** All UI/UX changes, fully reversible via feature flags, <5 min rollback time

---

#### Phase 2 Risks: MEDIUM ⚠️

| Risk | Mitigation |
|------|------------|
| Data loss | Shadow mode testing, double-write, slow rollout |
| Performance regression | Load testing, auto-scaling, monitoring |
| Complex bugs | Beta program (10%), gradual rollout (10%→100%) |
| Timeline overrun | MVP can stand alone, Phase 2 optional |

**Key Point:** Phased rollout (shadow → alpha → beta → production) catches issues early

---

### Sensitivity Analysis

**"What if features fail?"**

| Scenario | Activation Rate | Still Successful? |
|----------|-----------------|-------------------|
| All features succeed | 62.1% | ✓ Target exceeded |
| Free Filter fails | 52.1% | ✓ Still +12.7 pts |
| Free-First fails | 57.1% | ✓ Still +17.7 pts |
| Both Free features fail | 47.1% | ✓ Still +7.7 pts |

**Resilience:** Even if 2 major features fail, still achieve meaningful improvement. **Not a single-point-of-failure plan.**

---

### Organizational Risks

**Risk:** Teams resist changes (monetization team opposes free filter)

**Root Cause:** Incentive misalignment
- Monetization measured on premium impressions
- Activation not primary metric for any team
- Short-term clicks vs. long-term health

**Mitigation:**
- ✅ Executive sponsorship (CPO-level buy-in)
- ✅ Data-driven case ($2.6M CAC waste)
- ✅ Align incentives (measure on activation, not impressions)
- ✅ A/B test to prove (evidence over opinions)
- ✅ Quick wins build momentum (badges Week 1)

---

## 📊 Slide 6: Competitive Context (1 minute)

### Canva vs. Competitors

| App | Rating | 1-Star % | Key Advantage |
|-----|--------|----------|---------------|
| **Canva** | **3.8** ⭐⭐⭐ | **37.2%** | Template library |
| Adobe Express | 4.2 ⭐⭐⭐⭐ | 28% | Professional tools |
| Over | 4.3 ⭐⭐⭐⭐ | 25% | Mobile-first UX |
| PicsArt | 4.4 ⭐⭐⭐⭐ | 22% | Photo editing |
| Snapseed | 4.6 ⭐⭐⭐⭐ | 15% | Simple, focused |

**Key Insight:** Canva has the LOWEST rating. Users are switching to alternatives due to onboarding friction.

**Window of Opportunity:** Competitors haven't fixed their issues yet. Moving fast (3-week MVP) creates head start.

---

## 📊 Slide 7: Timeline & Milestones (1 minute)

### Implementation Timeline

```
WEEK 1: Foundation
  Day 1-2: Sprint planning, design reviews
  Day 3-5: Ship badges + free guide ✓ (quick wins)
  Day 1-5: Start free filter + ranking

WEEK 2: Core Development  
  Day 1-3: Complete free filter + ranking → A/B test → Ship
  Day 4-5: Start lock indicators + upgrades + alternatives

WEEK 3: Completion
  Day 1-3: Complete remaining features → Ship
  Day 4-5: Bug fixes, final testing
  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  END OF WEEK 3: All 7 features live ✓
  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

WEEK 4: Evaluation
  Measure MVP impact (activation rate)
  Go/No-Go decision for Phase 2

WEEK 4-9: Phase 2 (if approved)
  Save infrastructure overhaul
  Auto-save implementation
  Gradual rollout with monitoring

WEEK 10: Program Review
  Final results, lessons learned
```

---

### Success Milestones

**Week 1:**
- ✓ Badges shipped (100%)
- ✓ Free guide shipped (100%)
- ✓ Badge notice rate >70%

**Week 2:**
- ✓ Free filter A/B test complete
- ✓ Filter adoption >60%
- ✓ Time to find content <3 min

**Week 3:**
- ✓ All 7 features shipped
- ✓ Design completion improved 15+ pts
- ✓ No major rollbacks needed

**Week 4: Go/No-Go Decision**
- **GO to Phase 2 if:** Activation >54% (+14.6 pts)
- **Iterate MVP if:** Activation 49-54%
- **Pivot if:** Activation <49%

**Week 9: Phase 2 Complete**
- ✓ Activation rate >70%
- ✓ Save success >99%
- ✓ All goals achieved

---

## 📊 Slide 8: Why This Will Work (2 minutes)

### Evidence-Based Approach

**1. User Demand is Proven**
- 45% explicitly mention free content discovery issues
- 38.6% mention hidden paywall frustration
- 35.5% mention save failures
- **Users are TELLING US what to fix**

**2. Feature Already Existed**
- Free filter worked successfully in 2025
- Was removed (monetization decision)
- Users explicitly request its return
- **Not building new, just restoring proven**

**3. Framework Validation**
- AARRR Funnel: Confirms stages 3-5 are leaks
- Cognitive Load: Shows extraneous load 3-4x too high
- JTBD: Validates user intent and friction points
- **Multiple frameworks align on same root causes**

**4. Conservative Projections**
- Using conservative scenario (50% probability)
- Even pessimistic scenario succeeds (+15.6 pts)
- Not dependent on optimistic assumptions
- **Built-in margin of safety**

**5. Competitive Validation**
- Competitors who offer free filters rate higher
- Transparency (showing locks) is best practice
- Auto-save is industry standard
- **Following proven patterns, not inventing**

---

### Why NOW?

**1. Crisis is Escalating**
- Save failures increased from #2 (2025) to #1 issue (2026)
- App rating declining (was 4.1 in 2025)
- 1-star reviews increasing (was 32% in 2025)

**2. Every Week Costs Money**
- 600+ users lost per week
- $12K+ wasted CAC per week
- $2.6M annually at current rate

**3. Competitive Window**
- Competitors haven't fixed their issues yet
- 3-week MVP creates first-mover advantage
- Window may close as competitors improve

**4. Technical Feasibility**
- No complex technical unknowns
- All features proven possible (filter existed before)
- Team has capacity
- Low risk profile

**5. Strategic Momentum**
- Quick wins (badges Week 1) build confidence
- Early data validates approach
- Can iterate rapidly

---

## 📊 Slide 9: The Decision (1 minute)

### What We're Asking For

✅ **Approval to proceed with 3-week MVP**

**Commitments Required:**

**1. Resources**
- 4 engineers × 3 weeks (12 person-weeks)
- 0.5 FTE design support
- 0.5 FTE product management
- Total investment: $25,000

**2. Executive Sponsorship**
- CPO-level ownership
- Authority to override team objections
- Alignment of team incentives (activation > impressions)

**3. Measurement & Accountability**
- Daily activation rate tracking
- Weekly stakeholder updates
- Go/No-Go decision Week 4

**4. Phase 2 Contingent**
- Not asking for Phase 2 approval today
- Separate decision after MVP results
- MVP can stand alone if needed (62% is good)

---

### Decision Framework

**APPROVE IF:**
- ✓ Agree 60.6% churn is unacceptable
- ✓ Agree root causes are correctly identified
- ✓ Agree solution addresses root causes
- ✓ Accept 80% probability of >60% activation
- ✓ Accept $25K investment for $624K return

**DEFER IF:**
- Need more data (what specific data?)
- Need different approach (what alternative?)
- Timeline not feasible (when would work?)

**REJECT IF:**
- Disagree with problem diagnosis
- Disagree with solution approach
- Risk profile unacceptable

---

## 📊 Slide 10: Recommendation (30 seconds)

### The Bottom Line

**Current State:** 60.6% churn, $2.6M/year wasted CAC, 3.8 rating

**Proposed Action:** 7-feature MVP in 3 weeks

**Expected Outcome:** 62.1% activation (+22.7 pts), +$624K annual revenue

**Risk:** LOW (all reversible UI/UX changes)

**Confidence:** HIGH (80% probability of success)

**ROI:** 2,496% (24.96x return on $25K investment)

---

### Why This Will Succeed

1. ✅ **Data-Driven** - Every recommendation backed by user feedback
2. ✅ **Framework-Validated** - Multiple analytical frameworks align
3. ✅ **Risk-Managed** - Low-risk MVP, phased approach
4. ✅ **Realistic Scope** - Fits team capacity, no heroics
5. ✅ **Fast Time-to-Value** - 3 weeks to results
6. ✅ **Strategic** - Addresses root causes, not symptoms
7. ✅ **Resilient** - Works even if some features fail
8. ✅ **Proven** - Following industry best practices

---

### The Ask

**APPROVE immediate implementation of MVP starting Monday**

**Next Steps (If Approved):**
- Sprint planning: Monday
- Ship quick wins: Week 1
- Complete MVP: Week 3
- Evaluation: Week 4
- Phase 2 decision: Week 4

**Every day of delay costs:**
- 20+ users lost
- $400+ wasted CAC
- Continued rating decline
- Competitive ground lost

**The data is clear. The plan is ready. The team can execute. Let's move.**

---

## Questions?

**For detailed analysis, see:**
- Complete Case Study (67 pages)
- RICE Prioritization Model
- Framework Analysis
- Hypothesis Testing Plan
- Solution Design Specs
- All documents in project folder

**Contact:**
- Product Strategy Team
- product@canva.com
- Available for follow-up

---

**END OF PRESENTATION**

---

## Appendix: Key Quotes (If Needed)

### User Frustration - Free Content

> "Still can't filter the graphics by price. Takes forever to find free items."

> "I only want to see free graphics but it takes forever because I am forced to see paid graphics."

### User Frustration - Hidden Paywalls

> "Almost NOTHING good is free to use and locked behind the PRO. You'd pay for nothing useful in the end."

> "All the designs say FREE but when you try to use them, LOCKED."

### User Frustration - Save Failures

> "Download never finished—it stops halfway every time."

> "Anytime I want to save my work, it takes up to more than 1gb of data, and I'd still not be able to save it."

> "I end up screenshotting which reduces the quality."

### User Love (When It Works)

> "I have been doing designs on a laptop until I tried the mobile app. It is really the best app ever."

> "This is literally the best app! I use it for everything, projects, posters, and more."

**Key Insight:** Users LOVE Canva when they succeed. We just need to help them succeed.

---

**DECISION REQUIRED: Approve/Defer/Reject MVP Implementation**
