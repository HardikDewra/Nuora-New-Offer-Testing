# Nuora Gummies PDP Offer Report - Omre-Style Offer (V1)

**Test URL:** `https://mynuora.com/products/nuora-vaginal-probiotic-super-package`

**Product:** Nuora Vaginal Probiotic Gummies (60 gummies / 30 servings)

**Status:** Tested variant - CONTROL WON

**Inspiration:** Omre PDP (`https://omre.co/products/nmn-resveratrol`)

---

## A/B Test Results

### Test Configuration
- **Test Name:** Highest PDP vs Omre Offer
- **Test Date:** Jan 21, 2026
- **Duration:** 13 hours
- **Total Visitors:** 2,927
- **Split:** 50/50
- **Targeting:** Mobile + United States only

### Performance Comparison

| Metric | Control | Omre Variant (V1) | Difference |
|--------|---------|-------------------|------------|
| Visitors | 1,429 | 1,498 | +69 |
| Revenue | $6,173.05 | $5,122.25 | -$1,050.80 |
| Rev/Visitor | $4.32 | $3.42 | -$0.90 |
| Conv. Rate | 7.91% | 5.41% | -2.50% |
| Orders | 113 | 81 | -32 |
| AOV | $54.63 | $63.24 | +$8.61 |
| Profit | $3,833.05 | $4,834.25 | +$1,001.20 |
| Profit/Visitor | $2.68 | $3.23 | +$0.55 |
| Ship. Rev | $9.90 | $207.90 | +$198.00 |

### Funnel Conversion Rates

| Stage | Control | Omre Variant (V1) |
|-------|---------|-------------------|
| Add to Cart | 15.9% | ~7% |
| Reached Checkout | 9.2% | 5.4% |
| Checkout Completed | 7.91% | 5.41% |

### Session Duration

| Metric | Control | Omre Variant (V1) | Change |
|--------|---------|-------------------|--------|
| Avg Session | 47 sec | 33 sec | -29.8% |

### Purchase Type Breakdown

| Type | Control | Omre Variant (V1) |
|------|---------|-------------------|
| One-Time Purchases | 23 | 37 |
| Subscription Purchases | 90 | 44 |

### Test Outcome

**RESULT: CONTROL WINS**

- Control had significantly higher conversion rate (7.91% vs 5.41%)
- Control had higher revenue ($6,173 vs $5,122)
- Control had more orders (113 vs 81)
- Omre variant had higher AOV ($63.24 vs $54.63)
- Omre variant had higher profit but fewer subscriptions
- Omre variant significantly reduced session duration (-29.8%)
- CRITICAL: Omre variant flipped subscription ratio - more OTP than subscriptions (37 OTP vs 44 Sub)

---

## Offer Structure

This variant uses a **dynamic pricing system** where prices change based on both the quantity selected AND the purchase type (Subscribe vs One-time).

### Subscribe and Save Pricing

| Supply | Sale Price | Compare Price | Discount | Per Pack | Per Day | Refill Frequency |
|--------|-----------|---------------|----------|----------|---------|------------------|
| 1-month | $39.99 | $52.30 | 30% | $39.99 | $1.33 | Every month |
| 3-month | $79.99 | $139.45 | 40% | $26.66 | $0.89 | Every 3 months |

### One-Time Purchase Pricing

| Supply | Sale Price | Compare Price | Discount | Per Pack | Per Day |
|--------|-----------|---------------|----------|----------|---------|
| 1-month | $39.99 | $55.20 | 30% | $39.99 | $1.33 |
| 3-month | $119.97 | $165.60 | 40% | $39.99 | $1.33 |

---

## Key UI Behavior

### Dynamic Elements That Change Based on Selection

| State | Subscribe and Save Shows | One-time Shows | CTA Button |
|-------|-------------------------|----------------|------------|
| 1-month + Subscribe | $39.99 | $39.99 | "GET STARTED" |
| 1-month + One-time | $39.99 | $39.99 | "ADD TO CART" |
| 3-month + Subscribe | $79.99 | $119.97 | "GET STARTED" |
| 3-month + One-time | $79.99 | $119.97 | "ADD TO CART" |

### Subscription Info Display (Inside Selected Card)

When **Subscribe and Save** is selected, subscription details appear inside the selected supply card:

**1-month selected:**
- [Calendar] A 1-month supply each month
- [Clock] Swap, skip or cancel anytime

**3-month selected:**
- [Lightning] Free shipping included
- [Calendar] A 3-month supply every 3 months
- [Clock] Swap, skip or cancel anytime

---

## Key Design Differences from Control

| Element | Control | Omre-Style Variant |
|---------|---------|-------------------|
| Bundle naming | "1 Pack / 2 Packs / 3 Packs" | "1-month supply / 3-month supply" |
| Quantity options | 3 options (1, 2, 3 packs) | 2 options only (1-month, 3-month) |
| Sub/OTP toggle | Checkbox below bundles | Side-by-side buttons below bundles |
| Toggle style | Dashed border checkbox | Two equal-width buttons |
| Selected toggle | Orange fill + cream background | Yellow/cream background |
| Savings display | None on cards | "SAVE X%" badge on each card |
| Best deal badge | None | "Most popular" on 3-month |
| Per day price | Not shown | Shown on each card |
| Subscription info | In checkbox module | Inside the selected supply card |
| CTA copy (Sub) | "ADD TO CART" | "GET STARTED" |
| CTA copy (OTP) | "ADD TO CART" | "ADD TO CART" |
| Section header | "FINAL SUPERSAVINGS" | "New Year Offer" |
| Price anchoring | Strikethrough only | Strikethrough + "SAVE X%" badge |
| Free shipping indicator | None on cards | [Lightning] inside 3-month sub card |

---

## Omre Reference (Inspiration Source)

**URL:** `https://omre.co/products/nmn-resveratrol`

### Their Offer Structure

**Subscribe and Save:**

| Supply | Sale Price | Compare Price | Discount | Per Each | Per Day |
|--------|-----------|---------------|----------|----------|---------|
| 1-month | $62.10 | $69.00 | 10% | $62.10 | $2.07 |
| 3-month | $165.60 | $207.00 | 20% | $55.20 | $1.84 |

**One-Time Purchase:**

| Supply | Price |
|--------|-------|
| 1-month | $69.00 |
| 3-month | $207.00 |

### Their UI Elements

- **Section Header (Sub):** "Subscribe and Save"
- **Section Header (OTP):** "Onetime"
- **CTA Button (Sub):** "GET STARTED - $X.XX ~~$XX.XX~~" (shows both prices)
- **CTA Button (OTP):** "ADD ONETIME - $X.XX"
- **Toggle Style:** Side-by-side buttons with radio circles
- **Selected Sub Toggle:** Filled circle, no background change
- **Selected OTP Toggle:** Filled circle, orange/blue border
- **Most Popular Badge:** On 3-month supply
- **Subscription Info:** Inside selected card with icons
- **Free Shipping:** [Lightning] indicator inside 3-month sub card

### Notable Omre CTA Feature

Omre's CTA button dynamically shows both the sale price AND strikethrough compare price:
- "GET STARTED - $62.10 ~~$69.00~~"
- "GET STARTED - $165.60 ~~$207.00~~"

This reinforces the savings at the final action point.

---

## Key Learnings

1. Making one-time purchase equally visible significantly increased OTP orders (23 -> 37)
2. Subscription orders dropped dramatically (90 -> 44) - nearly half
3. This variant effectively cannibalized subscriptions in favor of one-time purchases
4. Higher AOV ($63.24 vs $54.63) suggests people buying larger bundles, but as OTP
5. Conversion rate dropped significantly (-2.50%) indicating the UI may have confused or deterred buyers
6. Reduced session duration (-29.8%) similar to Ryze variant
7. CRITICAL INSIGHT: Side-by-side Sub/OTP toggle with equal visual weight hurts subscription rate
8. The dynamic pricing showing OTP as a clear option likely made customers choose the "safer" one-time option
