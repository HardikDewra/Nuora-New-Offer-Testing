# Nuora Gummies PDP Offer Report - Omre-Style Offer (V2)

**Test URL:** `https://mynuora.com/products/nuora-vaginal-probiotic-super-package`

**Product:** Nuora Vaginal Probiotic Gummies (60 gummies / 30 servings)

**Status:** Tested variant - CONTROL WON

**Inspiration:** Omre PDP (`https://omre.co/products/nmn-resveratrol`)

**Change from V1:** Simplified rounded pricing ($40, $100 vs $39.99, $79.99)

---

## A/B Test Results

### Test Configuration
- **Test Name:** Highest PDP (Control) VS Omre Offer V2
- **Test Date:** Jan 30, 2026
- **Duration:** 15 hours
- **Total Visitors:** 1,600
- **Split:** 50/50
- **Targeting:** Mobile + United States only

### Performance Comparison

| Metric | Control | Omre Variant (V2) | Difference |
|--------|---------|-------------------|------------|
| Visitors | 795 | 805 | +10 |
| Revenue | $3,157.50 | $2,685.08 | -$472.42 |
| Rev/Visitor | $3.97 | $3.34 | -$0.63 |
| Conv. Rate | 7.42% | 5.47% | -1.95% |
| Orders | 59 | 44 | -15 |
| AOV | $52.63 | $61.02 | +$8.39 |
| Profit | $1,933.50 | $2,370.08 | +$436.58 |
| Profit/Visitor | $2.43 | $2.94 | +$0.51 |
| Ship. Rev | $0.00 | $84.15 | +$84.15 |

### Funnel Conversion Rates

| Stage | Control | Omre Variant (V2) |
|-------|---------|-------------------|
| Add to Cart | 15.7% | 10.6% |
| Reached Checkout | 10.2% | 7.5% |
| Checkout Completed | 7.42% | 5.47% |

### Session Duration

| Metric | Control | Omre Variant (V2) | Change |
|--------|---------|-------------------|--------|
| Avg Session | 41 sec | 34 sec | -17.1% |

### Purchase Type Breakdown

| Type | Control | Omre Variant (V2) |
|------|---------|-------------------|
| One-Time Purchases | 8 | 14 |
| Subscription Purchases | 51 | 30 |

### Probability to Win

| Variant | Probability |
|---------|-------------|
| Control | 83.02% |
| Omre V2 | 15.98% |

### Test Outcome

**RESULT: CONTROL WINS (83.02% probability)**

- Control had higher conversion rate (7.42% vs 5.47%)
- Control had higher revenue ($3,157 vs $2,685)
- Control had more orders (59 vs 44)
- Omre V2 increased OTP orders (8 -> 14) while dropping subscriptions (51 -> 30)
- Omre V2 had higher AOV ($61.02 vs $52.63) and profit
- Session duration dropped (-17.1%)
- Side-by-side toggle continues to cannibalize subscriptions

---

## V1 vs V2 Comparison

| Metric | V1 Result | V2 Result | Change |
|--------|-----------|-----------|--------|
| Variant Conv. Rate | 5.41% | 5.47% | +0.06% |
| Control Conv. Rate | 7.91% | 7.42% | -0.49% |
| Variant OTP Orders | 37 | 14 | -23 |
| Variant Sub Orders | 44 | 30 | -14 |
| Variant Sub % | 54% | 68% | +14% |
| Session Duration | 33 sec | 34 sec | +1 sec |
| Prob. to Win | ~6% | 15.98% | +10% |

**V2 Changes Made:**
- Simplified rounded pricing ($40.00, $100.00 instead of $39.99, $79.99)
- Cleaner "SAVE X%" badge design
- Same side-by-side Sub/OTP toggle
- Subscription info inside selected card (same as V1)

**V2 Result:**
- Slightly improved probability to win (15.98% vs ~6%)
- Better subscription ratio (68% vs 54%)
- Still significantly underperforms control
- Side-by-side toggle still hurts subscription rate vs control's checkbox

---

## Offer Structure

This variant uses **dynamic pricing** with rounded numbers based on subscription status.

### Subscribe and Save Pricing

| Supply | Sale Price | Compare Price | Discount | Per Pack | Per Day |
|--------|-----------|---------------|----------|----------|---------|
| 1-month | $40.00 | $60.00 | 33% | $40.00 | $1.33 |
| 3-month | $100.00 | $180.00 | 44% | $33.33 | $1.11 |

### One-Time Purchase Pricing

| Supply | Price | Per Pack |
|--------|-------|----------|
| 1-month | $60.00 | $60.00 |
| 3-month | $180.00 | $60.00 |

---

## Key UI Elements

### Card Design
- "1-month supply" and "3-month supply" naming
- "SAVE X%" badge on each card (gold/yellow background)
- "Most popular" badge on 3-month card
- Per pack and per day pricing shown
- Subscription info appears inside selected card when Sub toggle is active

### Subscription Info Display (Inside 3-month Card)

- [Lightning] Free shipping included
- [Calendar] A 3-month supply every 3 months
- [Clock] Swap, skip or cancel anytime

### Sub/OTP Toggle
- Side-by-side buttons: "Subscribe & Save" | "One-time purchase"
- Selected state: Yellow/cream background
- Unselected state: White background with border

### CTA
- "ADD TO CART" (brown button)
- "Swap, skip or cancel anytime" below CTA

---

## Key Design Differences from Control

| Element | Control | Omre-Style V2 |
|---------|---------|---------------|
| Bundle naming | "1 Pack / 2 Packs / 3 Packs" | "1-month supply / 3-month supply" |
| Quantity options | 3 options | 2 options only |
| Sub/OTP toggle | Checkbox below bundles | Side-by-side buttons |
| Pricing style | $34.99, $49.99, $58.99 | $40.00, $100.00 (rounded) |
| Savings display | None on cards | "SAVE X%" badge |
| Best deal badge | None | "Most popular" on 3-month |
| Per day price | Not shown | Shown on cards |
| Subscription info | In checkbox module | Inside selected supply card |

---

## Key Learnings

1. **Rounded pricing did not significantly improve conversion** - V2 performed similar to V1
2. Side-by-side toggle continues to cannibalize subscriptions (51 -> 30)
3. Subscription ratio improved vs V1 (68% vs 54%) but still worse than control (86%)
4. Higher AOV ($61.02) suggests larger bundle purchases but fewer total orders
5. Probability to win improved (15.98% vs ~6%) but still not competitive
6. CRITICAL INSIGHT: The side-by-side Sub/OTP toggle design is fundamentally flawed for Nuora
7. Giving OTP equal visual weight to subscription always hurts subscription rate
8. Control's checkbox-style toggle with subscription pre-selected remains optimal
9. Even with cleaner design and rounded numbers, the toggle pattern doesn't work
