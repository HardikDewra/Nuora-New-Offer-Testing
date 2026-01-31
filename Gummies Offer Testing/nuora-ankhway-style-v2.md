# Nuora Gummies PDP Offer Report - Ankhway-Style Offer (V2)

**Test URL:** `https://mynuora.com/products/nuora-vaginal-probiotic-super-sale`

**Product:** Nuora Vaginal Probiotic Gummies (60 gummies / 30 servings)

**Status:** Tested variant - CONTROL WON

**Inspiration:** Ankhway PDP (`https://ankhway.com/products/mushroom-gummies`)

**Change from V1:** Simplified rounded pricing + "Buy 2 Get 1 Free" messaging on 90-day supply

---

## A/B Test Results

### Test Configuration
- **Test Name:** Highest PDP (Control) VS Ankhway Offer v2
- **Test Date:** Jan 30-31, 2026
- **Duration:** 1 day 6 hours
- **Total Visitors:** 4,143
- **Split:** 50/50
- **Targeting:** Mobile + United States only

### Performance Comparison

| Metric | Control | Ankhway Variant (V2) | Difference |
|--------|---------|----------------------|------------|
| Visitors | 2,091 | 2,052 | -39 |
| Revenue | $10,726.85 | $8,880.20 | -$1,846.65 |
| Rev/Visitor | $5.13 | $4.33 | -$0.80 |
| Conv. Rate | 8.23% | 7.16% | -1.07% |
| Orders | 193 | 147 | -46 |
| AOV | $55.58 | $60.00 | +$4.42 |
| Profit | $6,667.85 | $8,007.20 | +$1,339.35 |
| Profit/Visitor | $3.19 | $3.90 | +$0.71 |
| Ship. Rev | $0.00 | $301.95 | +$301.95 |

### Funnel Conversion Rates

| Stage | Control | Ankhway Variant (V2) |
|-------|---------|----------------------|
| Add to Cart | 17.3% | 11.8% |
| Reached Checkout | 10.3% | 9.2% |
| Checkout Completed | 8.23% | 7.16% |

### Session Duration

| Metric | Control | Ankhway Variant (V2) | Change |
|--------|---------|----------------------|--------|
| Avg Session | 50 sec | 34 sec | -32.0% |

### Purchase Type Breakdown

| Type | Control | Ankhway Variant (V2) |
|------|---------|----------------------|
| One-Time Purchases | 40 | 29 |
| Subscription Purchases | 153 | 119 |

### Probability to Win

| Variant | Probability |
|---------|-------------|
| Control | 94.52% |
| Ankhway V2 | 5.49% |

### Test Outcome

**RESULT: CONTROL WINS (94.52% probability)**

- Control had higher conversion rate (8.23% vs 7.16%)
- Control had higher revenue ($10,726 vs $8,880)
- Control had more orders (193 vs 147)
- Ankhway V2 had higher AOV ($60.00 vs $55.58) and higher profit
- Session duration dropped significantly (-32.0%)
- OTP as visible separate card continues to hurt conversion
- Subscription ratio: Control 79% vs Ankhway V2 80% (similar)

---

## V1 vs V2 Comparison

| Metric | V1 Result | V2 Result | Change |
|--------|-----------|-----------|--------|
| Variant Conv. Rate | 4.82% | 7.16% | +2.34% |
| Control Conv. Rate | 6.98% | 8.23% | +1.25% |
| Variant Orders | 39 | 147 | +108 |
| Variant Sub Orders | 24 | 119 | +95 |
| Variant OTP Orders | 15 | 29 | +14 |
| Variant Sub % | 62% | 80% | +18% |
| Prob. to Win | ~10% | 5.49% | -4.5% |

**V2 Changes Made:**
- Rounded pricing ($40.00, $50.00, $99.99 instead of $37.99, $39.99, $75.99)
- Added "Buy 2 Get 1 Free!" messaging on 90-day supply
- Subscription info inside selected card (expanded detail)
- Dynamic CTA showing both strikethrough and sale price

**V2 Result:**
- Conversion improved significantly vs V1 (7.16% vs 4.82%)
- Subscription ratio improved (80% vs 62%)
- Still underperforms control
- OTP as visible card continues to be a weakness

---

## Offer Structure

This variant uses **vertically stacked cards** with subscription options separate from one-time purchase.

### Subscription Options

| Supply | Sale Price | Compare Price | Per Pack | Per Day | Delivery | Badge |
|--------|-----------|---------------|----------|---------|----------|-------|
| 30-day | $40.00 | $50.00 | $40.00 | $1.27 | Monthly | "Most Popular - Save 20%" |
| 90-day | $99.99 | $150.00 | $33.33 | $0.84 | Quarterly | "Best Value! Buy 2 Get 1 Free!" |

### One-Time Purchase

| Supply | Price | Per Pack | Description |
|--------|-------|----------|-------------|
| 1 Pack | $50.00 | $50.00 | N/A |

---

## Key UI Elements

### Card Layout (Vertical Stack)

1. **30-day supply** (Subscription)
   - Header: "Most Popular - Save 20%" (olive/gold background)
   - Subscription info inside card when selected:
     - [Checkmark] Only $1.27 per day
     - [Checkmark] 1x bag (30 days supply) delivered monthly
     - [Checkmark] Delay, pause or cancel anytime

2. **90-day supply** (Subscription)
   - Header: "Best Value! Buy 2 Get 1 Free!" (teal background)
   - Subscription info inside card when selected:
     - [Checkmark] Free Shipping
     - [Checkmark] Only $0.84 per day
     - [Checkmark] 3x bags (3 months supply) delivered quarterly
     - [Checkmark] Delay, pause or cancel anytime

3. **One time purchase** (OTP)
   - No header badge
   - Simple card at bottom, always visible
   - $50.00 per pack

### CTA Button Behavior

| Selected Option | CTA Text |
|-----------------|----------|
| 30-day sub | "BUY NOW \| ~~$50.00~~ $40.00" |
| 90-day sub | "BUY NOW \| ~~$150.00~~ $99.99" |
| One-time | "BUY NOW \| $50.00" |

---

## Key Design Differences from V1

| Element | V1 | V2 |
|---------|-----|-----|
| 30-day price | $37.99 | $40.00 |
| 90-day price | $75.99 | $99.99 |
| 90-day messaging | None | "Buy 2 Get 1 Free!" |
| OTP price | $39.99 | $50.00 |
| CTA style | "BUY NOW" | "BUY NOW \| ~~$X~~ $Y" |
| Subscription info | Minimal | Expanded with checkmarks |

---

## Key Learnings

1. **V2 significantly outperformed V1** - conversion jumped from 4.82% to 7.16%
2. "Buy 2 Get 1 Free" messaging improved subscription ratio (62% -> 80%)
3. Rounded pricing appears to perform better than $X.99 pricing
4. Higher AOV ($60) suggests customers buying larger bundles
5. Still underperforms control - OTP as visible card remains problematic
6. Session duration dropped 32% - consistent with other vertical layouts
7. CRITICAL INSIGHT: Even with improvements, the vertical card layout with visible OTP still loses to control's horizontal cards + checkbox toggle
8. The fundamental issue is not pricing or copy - it's the OTP visibility pattern
9. Control's 79% subscription rate vs V2's 80% shows similar subscription capture, but control converts more total customers
