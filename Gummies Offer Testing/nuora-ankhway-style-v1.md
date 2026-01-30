# Nuora Gummies PDP Offer Report - Ankhway-Style Offer (V1)

**Test URL:** `https://mynuora.com/products/nuora-vaginal-probiotic-super-sale`

**Product:** Nuora Vaginal Probiotic Gummies (60 gummies / 30 servings)

**Status:** Tested variant - CONTROL WON

**Inspiration:** Ankhway PDP (`https://ankhway.com/products/mushroom-gummies`)

---

## A/B Test Results

### Test Configuration
- **Test Name:** Current Best Offer vs New Ankway Offer (Super Sale)
- **Test Date:** Jan 17, 2026
- **Duration:** 8 hours
- **Total Visitors:** 1,597
- **Split:** 50/50
- **Targeting:** Mobile + United States only

### Performance Comparison

| Metric | Control | Ankhway Variant (V1) | Difference |
|--------|---------|----------------------|------------|
| Visitors | 788 | 809 | +21 |
| Revenue | $2,941.07 | $2,104.39 | -$836.68 |
| Rev/Visitor | $3.73 | $2.60 | -$1.13 |
| Conv. Rate | 6.98% | 4.82% | -2.16% |
| Orders | 55 | 39 | -16 |
| AOV | $53.47 | $53.96 | +$0.49 |
| Profit | $1,870.07 | $1,996.39 | +$126.32 |
| Profit/Visitor | $2.37 | $2.47 | +$0.10 |
| Ship. Rev | $0.00 | $113.85 | +$113.85 |

### Funnel Conversion Rates

| Stage | Control | Ankhway Variant (V1) |
|-------|---------|----------------------|
| Add to Cart | 15.1% | ~10% |
| Reached Checkout | 9.8% | 7.5% |
| Checkout Completed | 6.98% | 4.82% |

### Session Duration

| Metric | Control | Ankhway Variant (V1) | Change |
|--------|---------|----------------------|--------|
| Avg Session | ~41 sec | 29 sec | -31.8% |

### Purchase Type Breakdown

| Type | Control | Ankhway Variant (V1) |
|------|---------|----------------------|
| One-Time Purchases | 6 | 15 |
| Subscription Purchases | 49 | 24 |

### Test Outcome

**RESULT: CONTROL WINS**

- Control had significantly higher conversion rate (6.98% vs 4.82%)
- Control had higher revenue ($2,941 vs $2,104)
- Control had more orders (55 vs 39)
- AOV was nearly identical
- CRITICAL: Ankhway variant drastically reduced subscription orders (49 -> 24) while increasing OTP (6 -> 15)
- Session duration dropped significantly (-31.8%)
- Subscription ratio flipped from 89% sub to 62% sub

---

## Offer Structure

This variant uses **vertically stacked cards** with subscription options separate from one-time purchase.

### Subscription Options

| Supply | Sale Price | Compare Price | Discount | Per Pack | Per Day | Delivery |
|--------|-----------|---------------|----------|----------|---------|----------|
| 30-day | $37.99 | $47.49 | 20% | $37.99 | $1.27 | Monthly |
| 90-day | $75.99 | $79.99 | N/A | $25.33 | $0.84 | Quarterly |

### One-Time Purchase

| Supply | Price | Per Pack | Description |
|--------|-------|----------|-------------|
| 1 Pack | $39.99 | $39.99 | 1x bag delivered once |

---

## Key UI Behavior

### Card Layout (Vertical Stack)

1. **30-day supply** (Subscription)
   - Header: "Most Popular - Save 20%" (olive/brown background)
   - Shows per day cost and delivery frequency inside card when selected

2. **90-day supply** (Subscription)
   - Header: "Best Value! Buy 2 Get 1 Free!" (teal background)
   - Shows free shipping, per day cost, delivery frequency inside card when selected

3. **One time purchase** (OTP)
   - No header badge
   - Simple card with "1x bag delivered once" description
   - White background, border highlight when selected

### CTA Button Behavior

| Selected Option | CTA Text |
|-----------------|----------|
| 30-day sub | "BUY NOW" |
| 90-day sub | "BUY NOW | ~~$79.99~~ $59.98" |
| One-time | "BUY NOW | $29.99" |

---

## Key Design Differences from Control

| Element | Control | Ankhway-Style Variant |
|---------|---------|----------------------|
| Layout | Horizontal cards + checkbox toggle | Vertical stacked cards |
| Bundle naming | "1 Pack / 2 Packs / 3 Packs" | "30-day supply / 90-day supply" |
| OTP handling | Checkbox toggle (Sub vs OTP) | Separate card at bottom |
| OTP visibility | Hidden behind toggle | Always visible as third option |
| Savings display | None on cards | "Save 20%" in header |
| Best deal badge | None | "Best Value! Buy 2 Get 1 Free!" |
| Header style | None | Colored banner headers on cards |
| Per day price | Not shown | Shown inside selected card |
| Subscription info | In checkbox module | Inside each subscription card |
| Free shipping | None on cards | Inside 90-day card |
| CTA copy | "ADD TO CART" | "BUY NOW" with price |
| Card selection | Radio buttons on horizontal cards | Full card highlight with border |

---

## Subscription Info Display (Inside Selected Card)

**30-day supply selected:**
- [Checkmark] Only $1.27 per day
- [Checkmark] 1x bag (30 days supply) delivered monthly
- [Checkmark] Delay, pause or cancel anytime

**90-day supply selected:**
- [Checkmark] Free Shipping
- [Checkmark] Only $0.84 per day
- [Checkmark] 3x bags (3 months supply) delivered quarterly
- [Checkmark] Delay, pause or cancel anytime

---

## Ankhway Reference (Inspiration Source)

**URL:** `https://ankhway.com/products/mushroom-gummies`

### Their Offer Structure (GBP)

| Option | Sale Price | Compare Price | Per Pack | Badge |
|--------|-----------|---------------|----------|-------|
| 30-day supply (Sub) | £23.99 | £29.99 | £23.99 | "Most Popular - Save 20%" |
| 90-day supply (Sub) | £59.97 | £89.97 | £19.99 | "Best Value! Buy 2 Get 1 Free!" |
| One time purchase | £29.99 | - | £29.99 | None |

### Their UI Elements

- **Layout:** Vertical stacked cards
- **Card Headers:** Colored banners ("Most Popular" = olive, "Best Value" = teal)
- **CTA Button:** "BUY NOW | ~~£89.97~~ £59.98" (shows strikethrough + sale price)
- **Subscription Info:** Checkmarks inside selected card
- **OTP Card:** Simple white card at bottom, always visible
- **Free Shipping:** Listed inside 90-day card
- **Per Day Cost:** Shown inside card (e.g., "Only £0.66 per day")

---

## Key Learnings

1. Making OTP a visible separate card (not a toggle) increased OTP orders significantly (6 -> 15)
2. Subscription orders dropped dramatically (49 -> 24) - cut in half
3. Vertical stacking may create more visual weight for OTP option
4. Conversion rate dropped significantly (-2.16%) - worst performing variant so far
5. Session duration dropped (-31.8%) - consistent with other variants
6. CRITICAL INSIGHT: Having OTP as a visible third card makes it a "safer" choice for commitment-averse customers
7. The "Buy 2 Get 1 Free" messaging didn't drive enough subscription value to offset OTP increase
8. Vertical layout may increase cognitive load compared to horizontal cards
